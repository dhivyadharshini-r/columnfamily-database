 Railway Ticket Reservation using HBase

  HBase is a distributed column-oriented database
 built on top of the Hadoop file system. It is an
open-source project and is horizontally scalable.
In this application, we are creating a column
family database using HBase for Railway ticket 
reservation.

         TABLE NAME:  Ticket _Reservation

   The table contains the attributes like,
         Passenger_details( name,gender,age,mobile no)
         Train( name, class)
         Station(starting point, leaving point)
 
OPERATIONS USED:
     In the application the operations like 
INSERT, UPDATE and DELETE are used.

KEYWORDS USED:
   1.put - it is used to put  the data in the table
   2.get - it is used to retrieve the values in the 
table.

SYNTAX:
    1. INSERT - put 'table_name', 'row_key','column_family:column_name','value'
    2. GET - get 'table_name', 'row_key'.
    3. DELETE -  'table_name', 'row_key'.
