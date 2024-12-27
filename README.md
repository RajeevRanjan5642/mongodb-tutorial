# MongoDB

- NoSQL database
- Data is stored in collections which are analogous to tables in SQL databases.
- A document is a record in a MongoDB collection represented in JSON-like format (BSON) with key-value pairs.

# MongoDB Shell
- show dbs
- use <db-name>
- show collections
- db.<collection-name>.insertOne({field:value})
- db.<collection-name>.insertMany([{field:value},{field:value}])
- db.<collection-name>.find({filter})
- db.<collection-name>.findOne({field:value})
