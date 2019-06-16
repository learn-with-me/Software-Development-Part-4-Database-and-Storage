# Databases

> Just because you can do it with a language/framework, does not mean you should.

#### JSON

Before we dive into databases, let's understand JSON, as this will drive a lot of decisions on what database to choose and why. Javascript Object Notation \(JSON\) is unstructured, flexible and readable by humans. Basically, you can dump data into the database however it comes, without having to adapt it to any specialized database language \(like SQL\). You can nest fields in a data record, or add different fields to individual data records as and when you need.

All of this makes an important step towards user-friendly computing. Today many prefer JSON over XML. JSON data format is used by a number of NoSQL data stores.

JSON does, however, lack indexing - and JSONB format was created to tackle this problem. JSONB stores data in binary format, instead of a simple JSON blob. Data input is a bit slower, but processing becomes a lot faster since the data doesn't need to be reparsed. 

#### Postgres

Able to handle SQL and NoSQL data. Now offers enhanced JSON storage capabilities.

#### MongoDB

Designed as a native JSON database

