# GoStack Challenge 02

![GymPoint](https://raw.githubusercontent.com/Rocketseat/bootcamp-gostack-desafio-03/master/.github/logo.png)

![GitHub language count](https://img.shields.io/github/languages/count/GiovaniCuenca/GoStack-Challenge02)    ![GitHub issues](https://img.shields.io/github/issues/GiovaniCuenca/GoStack-Challenge02)          ![GitHub](https://img.shields.io/github/license/GiovaniCuenca/GoStack-Challenge02)


## About the Challenge

Start the development of the application backend which will be used for the Bootcamp certification final challenge.
[Oficial challenge README](https://github.com/Rocketseat/bootcamp-gostack-desafio-02/blob/master/README.md)

## Technologies

 - **Engine**: NodeJS
 - **Microservices**: Express
 - **Utility**: Sucrase / Nodemon
 - **DB**: Docker / Sequelize / Postgres SQL
 - **Package Manager**: Yarn
 - **Programs**: VScode / Insomnia / Postbird

## Features

 - API development

## Installation
Requirements:
Docker;
Node.JS v10.15 or higher,
Yarn v1.12 or higher,

Clone or download the zip file. At the project folder run the following at your terminal:

    # Install Dependencies:
    $ yarn
    
    # Start Postgres:
    $ docker run --name postgresgympoint -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres:11
    
    # Create a new Database named 'gympoint' and run the following:
    $ yarn sequelize db:migrate 
    $ yarn sequelize db:seed:all
    
    # Run the Server:
    $ yarn dev
    

## License
This project is under the MIT license. See the [LICENSE](https://github.com/GiovaniCuenca/GoStack-Challenge02/blob/master/LICENSE) for more information.
