### MongoDB 

This repo contains the files in which data.json is the database file which will be used in order to perform the queries.

The mongo_db_queries.json is the file that contains the commands and operations done on the data.json file.


#To show databases present in the database
* show dbs

#To show collections present in the database
* show collections

#To create a collection in the database
* db.createCollection("collectionname")

#To drop the collection present in the database
* db.collectionname.drop()

#To show data present in the collection
*db.collectionname.find()

#To insert one data in the Collection
* db.collectionname.insertOne({
    : ,
    : ,
    : ,
})


* db.collectionname.insertOne({
    : ,
    : ,
    : ,
},{
    : ,
    : ,
    : ,
}
)          // by this only first one is added not both

#To insert more than one data in the Collection
* db.collectionname.insertMany([{
    : ,
    : ,
    : ,
},{
    : ,
    : ,
    : ,
}]
)



