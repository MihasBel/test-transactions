# test-transactions

A test task for the implementation of a transaction system. It accepts requests to deposit or withdraw money and enters them into the database. It also gives transaction data from the database when requesting information on any transaction.
## Architecture schema in [miro](https://miro.com/app/board/uXjVPvwzV6U=/?share_link_id=797824750985)

## REST part
[REST repo](https://github.com/MihasBel/test-transactions-rest)
REST-full API to create and get transactions

## Service part

[Srevice repo](https://github.com/MihasBel/test-transactions-service) 
Service to consume and save transactions to DB and read transactions from DB

## broker/model
contains common models for kafka

## docker-compose.yaml 
Uses to up and running all infrastructure 

TODO:
- setup jwt token. 
- add to compose file API and service. 
- create tests. 
- realise slicing of balances.
