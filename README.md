# Smart Sales Manager - Ecommerce  Web Apps

Smart Sales Manager is React and Node.js based eCommerce platform.

Built with:
* Node.js v10.15.3
* NPM 6.4.1
* Angular 7.
* Express
* Babel
* WebPack 4
* Mysql 7.2

## Dashboard
Client-side dashboard use JSON Web Token (JWT) to access REST API.


## Installation


### Requirements
* Node.js v10.15.3
* NPM 6.4.1
* Angular 7.
* Express
* Babel
* WebPack 4
* Mysql >= MariaDb.10.1.31

Please check the video related to the work has been completed till now.
https://drive.google.com/file/d/1ud4gok7mqli7_zMxw1Eo-zJjYad-BRIB/view?usp=sharing

[![Please check the video related to the work has been completed till now.](https://drive.google.com/file/d/1ud4gok7mqli7_zMxw1Eo-zJjYad-BRIB/view?usp=sharing)](https://drive.google.com/file/d/1ud4gok7mqli7_zMxw1Eo-zJjYad-BRIB/view?usp=sharing)
### Set-up MySql database

Create data base having name "ssm" on mysql console and import database sql file located in database folder.
=======


### Requirements
* Node.js >= 10.15.3
* Mysql >= MariaDb.10.1.31


And change the database connection config parameter as per your database setting by going server/routes/authentication.js file

### Set-up server and client.

```shell 
git clone https://github.com/kamleshgorasiya/ssm-public.git ssm-public
```
### install dependencies for server

```shell
cd ssm-public/server
npm install
```
### Start node server

```shell
node server
```
### Now need to start SSM client so please go to the root of the client folder(myApp) then install dependencies
and start Angular client

```shell
npm install
ng server -o
```


### Contributing

If you can, please contribute by reporting issues, discussing ideas, or submitting pull requests with patches and new features. We do our best to respond to all issues and pull requests within a day or two, and make patch releases to npm regularly.


## Licence

This software is provided free of charge and without restriction under the MIT License
