# Banka-3-Infrastructure

## Step 1
Install [docker desktop](https://www.docker.com/products/docker-desktop/)

## Step 2
Create file `.env` and copy content of `.env.example` into `.env`
For each variable in `.env` file add full path to directories

## Step 3 
Open terminal in current directory and run `docker-compose up -d` command


## Run With Monitoring

`docker-compose --profile user-service --profile bank-service --profile all up -d`
