# Smurphy Dev setup

Instructions on how to set-up and run Smurphy locally.

## Installation and Setup

1) ```cd``` into the Smurphy root directory and run ```npm i```
```bash
cd Smurphy
npm i
```

2) Then, in *nodemon.json*, change the value of the token to match that of the bot.

## Running the Development server

The current server is a bit messy, but it can be turned on using ```npm run dev``` in the base directory. 

This runs ```npx tsc -w```, which translates the *.ts* files into *.js* files in the ```/build``` 
directory. It also runs ```npx nodemon``` in this ```/build``` directory.