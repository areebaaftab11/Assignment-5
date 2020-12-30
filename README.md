# Assignment-5



Name: Areeba Aftab
Student ID: 2338751

#Instructions

In this assignment,you will push your C++skills to the limit by implementing a simple database system using binary searchtrees.  Though the end product will be a far cry from Oracleor MySQL, your DB will allow the user to insert, delete, and query data.  The data itself will be persistent (stored on disk), so that you may process it over several sessions.The DB itself will contain data that would be commonly found in a university’s computer system.  In our case, this information consists of student and faculty records.  The information for each will be stored in its own tree (or “table” in DB terminology).Though I will provide you with a general outline of the program, many of the implementation details will be up to you.  In the same spirit, I will give you a point in the right direction as far as some of the C++techniques go, but it will also be your responsibility toresearch the techniques in more detail.DetailsTablesThe tables that store the records in your DB will be binary search trees.  The nodes will consist of Student or Faculty objects, depending on the tree.  The tree will be sorted on the primary key value of the nodes, which in our case will be faculty and student Ids.Your first job will be to build a BST implementation supporting the usual operations (including delete).  This should not be difficult in and of itself.  Just be sure to use templates tomake your implementation generic, and overload operators as required.Student RecordsStudent records will be stored in a Student class.  Student records contain a unique student ID (an integer), a String name field, a string level field (Freshman, Sophomore, etc), a String major field, a double GPA field, and an integer advisor field, which will contain the Faculty ID of their advisor.  These are the only fields the class contains.The Student class must overload equality
