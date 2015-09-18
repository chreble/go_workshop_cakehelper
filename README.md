# go_workshop_cakehelper
Project for the Go Worrkshop from @ceble and @jgautheron. Will use it if well realize to manage the fridge cake content and providers :)

## What is the project suppose to do 
This is an API using a Go based server and a angular front end. I hope to make use of the BoltDB project for the database (if had some time to do so). Else will have to do it in SQL or MongoDB.
This project will allow Nexway group to know what's still in the fridge and who will help me (if some one is up) to take some cakes back on the Tuesday.

FrontEnd : request the output of the go function and print it emphasised

## Manage fridge content
First part of the API (on the top of the page) : print the list of the cakes still in and allow one to remove the cake he just eat.
### List
Go : have a read only function on the BoldDB database to show what's still on

### Remove
Go : have an update function in the database to delete the cake from the list or decrease the number still in

## Help me
### List
Go : have a read only function on the database to show who's going to help on the XX-XX-XXXX

### Remove
Go : have an update function in the database to add the helper for the XX-XX-XXXX
