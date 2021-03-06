

<p align="center">
  <img src="https://i.imgur.com/3eMMRmW.png" height="150" alt="Gobarber" />
</p>

## Overview

Gobarber is an app built to help barbers and customers to create and manage their appointments. Barbers can manage daily and monthly availiability, and customers can create appointments with available barbers.

Gobarber 2020 is an app developed during the Rocketseat GoStack Bootcamp in 2020.

This app consists of a REST API built with NodeJS and Express, a web app built with ReactJS, and a mobile app built with React Native. You can reach these repositories following the list below:
	 
 - **Gobarber Backend:**: https://github.com/hmhallak/gobarber-2020
 - **Gobarber Web:** https://github.com/hmhallak/gobarber-2020-web
 - **Gobarber Mobile:** https://github.com/hmhallak/goabarber-2020-mobile

## Environment
 - To run the system you'll need the following docker containers running:
	 - Postgres (https://hub.docker.com/_/postgres)
	 - Redis (https://hub.docker.com/_/redis)
	 - Mongo (https://hub.docker.com/_/mongo)
   
 - Install and run these containers and then proceed to the Setup section.

## Setup (Backend)
 - Install dependencies:
<code>yarn</code>

- Copy .env.example and rename to .env, then set your environment configs in .env file

- Create your database in postgres and then run migrations:
 <code>yarn typeorm migration:run</code>

- Run server backend:
<code>yarn dev:server</code>

Ready to go! You can use the requests.json file to make api requests with Insomnia (https://insomnia.rest/) or Postman (https://www.getpostman.com/).
