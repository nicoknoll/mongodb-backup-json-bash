# Backup for MongoDB Collections as JSON
A bash script for exporting/importing collections as .json files from/to mongoDB.

## Usage

```bash

Usage: ./backup.sh [opts] <export|import>

OPTIONS:
    -h      Show this help.

    -p      Set Path
    -c      Set Collection

    -U      Mongo Username
    -P      Mongo Password
    -D      Mongo Database
    -H      Mongo Host String (ex. localhost:27017)

    -a      As JSON Array
    -b      Pretty Print
 
```
