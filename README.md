# E-commerce-Back-End
Object-Relational Mapping (ORM) Challenge: A interactive E-Commerce back end utlizing Object-Relational Mapping as power be Sequelize


#User Story
AS A manager at an internet retail company
`I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies`

## Github User Name
Abduler21

## Installation
please ensure you have the required NPM modules and MySQL installed installed locally 
clone this repo and install npm modules using following commands. 
Ensure your SQL Database is running 

via commandline:
`mysql -u root -p` 
when prompted enter your password 
then exit by typing 
`quit`

to run the application we need to first seed the database use the following command via gitbash Commandline:
`npm run seed`
this will build the databases we will be manipulating. 

once database is built start your server using the following command 
`npm start`  

once the server is live then you can Cycle through CRUD options via Insomnia Core / postman. 

The api endpoints are as follows:
* Categories:
http://localhost:3001/api/categories
* Tags
http://localhost:3001/api/tags
* Products 
http://localhost:3001/api/products 




## Credits
This app was built with:
* Javascript 
* express 
* Sequelize
* mysql2 
* dotenv





