# MongoDB
Our MongoClient object is not actually a dictionary, so we can't call keys() to list the names of accessible databases. The same is true for listing collections of a database. Instead, we can list database names by calling .list_database_names() on a client instance, and we can list collection names by calling .list_collection_names() on a database instance.
