Create Db
use bookAPI
https://www.tutorialspoint.com/mongodb/mongodb_create_database.htm

Creat collection
db.createCollection('books')
https://www.tutorialspoint.com/mongodb/mongodb_create_collection.htm

insert document
db.books.insert([json])
https://www.tutorialspoint.com/mongodb/mongodb_insert_document.htm


or use this way
To import Book data into your mongoDB database. 
Make sure MongoDB is running then run 'mongo bookAPI < booksJson.js' from the command line.