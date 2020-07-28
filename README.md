<p align="left">
<img src="/.github/finances.png" width="200" heigth="200" />
</p>

<h1 align="left" >Go Finances</h1>

<h3>Database Diagram</h3>
<p align="left">
<img src="/.github/database.PNG"  />
</p>


# :rocket: Features
- Create and Delete transactions </br>
- Import transactions from CSV file</br>


# :construction_worker: Installation
Clone this repo

```git clone https://github.com/Alissonjra/gofinances-api```


Run the following script in order to execute the application in development mode:

```yarn install  ```  

Initialize your database
```( POSTGRESQL )```

Run the transactions in order to configure the database:

```yarn typeorm migration:run```


Start the application:

```yarn dev:server```

# :hammer: Technologies

In this project i used this technologies:

- [Express](https://expressjs.com/pt-br/)
- [Multer](https://www.npmjs.com/package/multer)
- [TypeORM](https://typeorm.io/#/)
