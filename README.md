Q1.Describe the characteristics of Big data in detail.
A1.
Volume:
Volume is a key contributor to the problem of why traditional relational database management systems 
(RDBMS, data warehouses as we know them today) fail to handle Big Data.  Underlying that failure are more complex issues 
of cost, reliability, long query times, and their inability to handle new sources of unstructured or semi-structured data like text.

Variety: 
Variety describes different formats of data that do not lend themselves to storage in structured relational database systems. 
These include a long list of data such as documents, emails, social media text messages, video, still images, audio, graphs, and the 
output from all types of machine-generated data from sensors, devices, RFID tags, machine logs, cell phone GPS signals,
DNA analysis devices, and more.  This type of data is characterized as unstructured or semi-structured and has existed all along.

Velocity:
This is one of the major determinants of Big Data storage, retrieval, analysis, and deployment architecture that companies
must work through today. When you sign on to Amazon or Netflix and see recommended purchases or views just for you the same process 
has taken place.  The architecture of capture, analysis, and deployment must support real-time turnaround (in this case fractions of a
second) and must do this consistently over thousands of new visitors each minute.  Real Time Big Data Analytics (RTBDA) is one of the main
frontiers of development in Big Data today.

Value:
It is equally true of both big and little data that if we are making the effort to store and analyze it then it must
be perceived to have value.

Veracity:
It tells how trustworthy the data is that leads to the right direction while processing it. 

Q2.Explain the possible solutions to handle Big data. 
A2. There are two possible solutions to handle the big data,these are scale up and scale out.
1. scale up: 1.It increase the configuration of single file system like disk capacity,RAM, speed and data transfer,etc.
             2.but it is costly,complex and time consuming process.
             3.it is a monolithic system.
   scale out: 1.use multiple commodity machines and distribute the load among these machines.
   
              3. quickly implements its solution among its machines.
              4. it is not monolithic system instead increases its number of machines.
Q3. Explain the differences between scaling up and scaling out.
A3.Scale out:(Horizontal scaling)
              1.Horizontal scaling means that you scale by adding more machines into your pool of resources.
              2.It is often based on partitioning of the data i.e. each node contains only part of the data.
              3.With horizontal-scaling it is often easier to scale dynamically by adding more machines into the existing pool.
   Scale out:(vertical scaling)
              1.Vertical scaling means that you scale by adding more power (CPU, RAM) to an existing machineIn a database world.
              2.In vertical-scaling the data resides on a single node and scaling is done through multi-core.
              3.It is often limited to the capacity of a single machine, scaling beyond that capacity often involves downtime and comes with an 
               upper limit.
           
             
