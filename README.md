# MIGRATIONS-SIDDERS-MODELS
Migrations - Migrations are basically for keep track of changes to the database.
To create an empty project,I have used this command - npx sequelize-cli init
For creating the models, I have used this command -  npx sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string
    It creates the user model in 'models' directory and create a migration file in migration folder.
For creating the tables into the database i used this commmand - npx sequelize-cli db:migrate this command creates a table into the database and also create a 
   sequelizeMeta table.
For inserting the some default records into the table then we will use the seeders.
   Creating the first seed we have to first initialize the seed with this command - npx sequelize-cli seed:generate --name demo-user
   this command creates a seed file and update it our require fields.
   inserting the recordss in databse table we have to used this command - npx sequelize-cli db:seed:all
   
