
# Gobarber 2020

Gobarber is an app built to help barbers and customers to create and manage their appointments. Barbers can manage daily and monthly availiability, and customers can create appointments with available barbers.
Gobarber 2020 is an app developed during the Rocketseat GoStack Bootcamp on 2020.

This app consists of an backend API built with NodeJS and Express, a web app built with ReactJS, and a mobile app built with React Native. You can reach these repositories following the list below:
	 
 - **Meetapp Backend:**: https://github.com/hmhallak/gobarber-2020
 - **Meetapp Web:** https://github.com/hmhallak/gobarber-2020-web
 - **Meetapp Mobile:** https://github.com/hmhallak/goabarber-2020-mobile

## Environment
 - To run the system you'll need the following docker containers running:
	 - Postgres (https://hub.docker.com/_/postgres)
	 - Redis (https://hub.docker.com/_/redis)
	 - Mongo (https://hub.docker.com/_/mongo)
   
 - Install and run these containers and then proceed to the Setup section.

## Setup
 - Install dependencies:
<code>yarn</code>

- Copy .env.example and rename to .env, then set your environment configs in .env file

- Create your database in postgres and then run migrations:
 <code>yarn typeorm migration:run</code>

- Run server backend:
<code>yarn dev:server</code>

Ready to go! You can use the requests.json file to make api requests with Insomnia (https://insomnia.rest/) or Postman (https://www.getpostman.com/).
