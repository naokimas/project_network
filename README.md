# project_network
Project activity network data.
Please cite the following paper when you use the data.

[Christos Ellinas, Christos Nicolaides, Naoki Masuda.  
Mitigation strategies against cascading failures within a project activity network.  
Journal of Computational Social Science, 5, 383-400 (2022)](https://doi.org/10.1007/s42001-021-00123-x)

This paper is open access.

The data set includes the temporal and structural properties of the activity network and comprises the following two files.

File 'nodes.csv' is composed of five columns.
There are 723 nodes.
Note that the node index starts from 1.  
- 1st column contains the task ID.
- 2nd column contains the start date of each task ('YYYY-MM-DD').
- 3rd column contains the end date of each task ('YYYY-MM-DD').
- 4th column contains the start date of each task since the start of the project. Note that an entry of 0 indicates that the task started on day 1.
- 5th column contains the end date of each task since the start of the project. 

File 'edges.csv' is composed of two columns.
There are 1,220 directed edges.  
- 1st column has the origin node of an edge.
- 2nd column has the destination of that edge.
