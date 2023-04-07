## Run Locally

Clone the project in a WSL console 

Go to the project directory

```bash
  cd blogStefan
```
Start the ddev server

```bash
  ddev start
```

Install the dependencies

```bash
    ddev composer install
```

Export the database 

```bash
    ddev export-db --file=/tmp/db.sql.gz
```

Import the database

https://ddev.readthedocs.io/en/latest/users/usage/commands/#import-db

Ids 
admin/Qwf5WUyp4dB8dET