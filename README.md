<h1>Database and Containers</h1>


<h2>Description</h2>
Through this project, you will be able to manage a database and visualize its data with tools installed inside containers.
<br />

<h2>AWS Cloud Map</h2>
<p align="center">
<img src="https://i.imgur.com/xXY2o9H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<h2>Services Used</h2>

- <b>VPC & Subnets</b> 
- <b>Amazon RDS</b>
- <b>Amazon EC2</b>
- <b>Amazon EBS</b>
- <b>Amazon ECS</b>
- <b>Amazon EFS</b>

<h2>Environments Used </h2>

- <b>AWS Management Console</b>
- <b>Docker</b>
- <b>AWS Management Console</b>
- <b>Metabase</b>

<h2>Database and Containers walk-through:</h2>

- <b>Create a VPC within the AWS Management Console and use "VPC,subnets,etc."</b>
- <b>Choose 2 Availablity Zones and 2 public subnets</b>
- <b>Create a RDS MySQL database within Amazon RDS</b>
- <b>Within Amazon EC2 create a ECS Cluster in a EC2 instance</b>
- <b>Check the resources available for the creation of the container</b>
- <b>Create a Task definition which contains the image used, the size of the container, the enviroment variables etc. in order to create the container</b>
- <b>"Add container" to the Task Definition/b>
- <b>Import an image from Docker Hub and install it into the container</b>
- <b>Create limits for each image so they do not sabotage each other</b>
- <b>Select EC2 Launch type and select the prevoisuly created Task Definition to run the task</b>
- <b>Connect the EC2 instance containing the ECS Cluster using its IP address</b>
- <b>Create a Task Definition for Metabase</b>
- <b>Configure the Metabase</b>
- <b>Add the EFS file system to the Metabase container</b>
- <b>Create your database struture with multiple tables;use SQL query to create these tables</b>
- <b>Add your data to each table</b>
- <b>Add the newly created database to Metabase in order to create a dashboard to view the statistcis of your added database</b>




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
