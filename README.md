# Mealinfo project in python using mangoDB
### required modules 
*  import json
* import pprint
* import warnings
*   warnings.filterwarnings("ignore")
### Client connection with mongoDB
* import pymongo
* client = pymongo.MongoClient('localhost',27017)
### create database 
db = client['mealinfo']
use some MONGODB commands like find(),find_many(),insert_one(),insert_many(),sort(),limit(),update_many(),drop()
