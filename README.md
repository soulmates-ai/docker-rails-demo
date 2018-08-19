# README

## First, build the app
`docker-compose build`

## Create the database
`docker-compose run web scripts/wait-for-it.sh db:5432 -- "rake db:drop db:setup"`

## Run the app
`docker-compose up`


