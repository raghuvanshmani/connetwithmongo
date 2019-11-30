# connetwithmongo
import pymongo
uri = "mongodb://127.0.0.1:27017"
connection =pymongo.MongoClient(uri)
database = connection['manimisr']
collection = database['ramram']
data ={"name":"raghuvansh"}
collection.insert_many(data)
