# project_network
Project activity network data used in Ellinas and Masuda (2018).
Please cite the following paper when you use the data.

Christos Ellinas and Naoki Masuda.
TITLE NOT FIXED.
arXiv:181x.xxxxx (2018).

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
