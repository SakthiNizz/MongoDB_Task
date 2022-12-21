# MongoDB_Task

In this Task had a two categories 

1. Curd Operation 

2. Aggregate function along with json dataset.

The Task Discription is given below and also in .ipynb file

Note : For Task 2 make sure that "students.json" file and "Student Database.ipynb" in same folder, Otherwise you have to declare the path.

#Discription:
1. Telephone Directory CRUD Operation

        Telephone directory: Perform CRUD operation using mongodb and python.

        You need to

        Import necessary modules.

        Perform CRUD operations to manipulate data in MongoDB. Create, retrieve, update, and delete (CRUD)

        Create a database using attribute style on a MongoClient instance. Declare a variable db and assign the new database as an attribute of the client.

        Create a collection.

        For CRUD operation, create a directory which has fields like Name, Phone number, Place etc.,

        Insert the record into the collection.

        Make a query to find records you just created.

        Modify the records, use the update_one() method. The update_one() method requires two arguments, query and update.

        Delete the record, use delete_one() method. delete_one() requires a query parameter which specifies the document to delete.

2.  Student Database (MongoDB)
        Here is the student dataset in the JSON format.
        
        Perform the following operation:
        
        1)    First create a database and then load the student.json dataset.
        
        2)    Insert the students record into the collection.
        
        Queries need to answer:
        1)     Find the student name who scored maximum scores in all (exam, quiz and homework)?
        
        2)     Find students who scored below average in the exam and pass mark is 40%?
        
        3)     Find students who scored below pass mark and assigned them as fail, and above pass mark as pass in all the categories.
        
        4)     Find the total and average of the exam, quiz and homework and store them in a separate collection.
        
        5)     Create a new collection which consists of students who scored below average and above 40% in all the categories.
        
        6)     Create a new collection which consists of students who scored below the fail mark in all the categories.
        
        7)     Create a new collection which consists of students who scored above pass mark in all the categories.
