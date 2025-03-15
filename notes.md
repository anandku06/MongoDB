# MongoDB

## Introduction
- a general purpose document database, structure data into documents similar to JSON objects
- not using the relational database schemas of tables, columns or rows
- offers a developer-friendly way to access the data
- corresponds objects in code
- document model is easier to plan how application data will correspond to data in the databases
- model data of any shape or structure
- use one format for every language 

```javascript
    // example of a document
    {
        "id" : 1,
        "name" : {
            "first" : "Ada",
            "last" : "Lovelace"
        },
        "title" : "The First Programmer",
        "interests" : ["mathematics", "programming"]
    }
```
- **document** is the basic unit of data in MongoDB
- a **Collection** is grouping of those documents
- a **Database** is the container of collections.
- MongoDB Database is the core of Atlas