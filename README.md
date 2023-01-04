# clg-nodejs-7
CLG Node JS Lesson 7

*   Create a database in MongDB Compass called StudentTracker

*   Add a collection to the database called Student
 
*   Create a JSON file with the following contents and import it into the collection

        *   used Mongosh db.Student.insert

        ([
            {
                "firstName": "John",
                "lastName": "Doe"
        }
        {
                "firstName": "Adam",
                "lastName": "Smith"

        }
        ])

*   Add an item to the collection - used Mongosh db.Student.insert

*   Delete "John" from the collection - used Mongosh db.Student.findOneAndDelete({"firstName": "John"}) 
    which has deleted the entire record not just the first name

*   Delete entire collection - not executed for the purposes of assessment and record keeping, 
    however using Mongosh db.Student.drop() should remove the specified collection from the database

*   Reference - https://www.mongodb.com/docs/mongodb-shell/reference/methods/#collection-methods

