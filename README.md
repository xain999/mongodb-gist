# mongodb-gist
This repository is one stop shop for using mongodb shell

---

### Connect shell to mongodb instance
`$ mongo "mongodb://localhost/my_app_development:28015"`

### List databases
`$ show dbs`

### Use databases
`$ use {myDB}`

### List tables
`$ show collections`

### Show all entries
`$ db.{table}.find({})`

### Remove all entries
`$ db.{table}.deleteMany({})`