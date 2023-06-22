# 13 E-Commerce Back End

## Task

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

The task is to build the back end for an e-commerce site. goal is to configure a working Express.js API to use Sequelize to interact with a MySQL database.

This will not be a visible website like normal, this will run on the backend using mysql workbench and insomina

## Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
## Links and references
[Recording 1 Beginning](https://watch.screencastify.com/v/Ujh9HwU6mSUOts4kNpFd)
[Recording 2 Delete in Insomina](https://watch.screencastify.com/v/QgTe5PFwkJ4wamyfOsKH)

[npm detenv package](https://www.npmjs.com/package/dotenv)
[npm express package](https://www.npmjs.com/package/express)
[npm mysql2 package](https://www.npmjs.com/package/mysql2)
[npm sequelize package](https://www.npmjs.com/package/sequelize)