# KeyMV - gRPC microservices in Golang
**Repos provded as-is, and are unmaintained at this point in time.**

This project is a very basic demonstration for multi microservices commuinication using gRPC, imlpemented in Golang.
I'm not even sure this is how it's done, this was just something i've done to learn some basics in golang and gRPC.
 
## Repositories
### keymv
This repository. contains links to the relevant microservices.  

### keymv-proto
https://github.com/ilyatbn/keymv-proto  
Shared repository for all gRPC protocol buffers. all other microservices use this repo.  

### keymv-core  
https://github.com/ilyatbn/keymv-core  
Main microservice. Let's call it the gateway for the clients to perform requests.  
Obviously in a normal implementation there would probably be an API Gateway in front of it exposing REST or something.

### keymv-authengine
https://github.com/ilyatbn/keymv-authengine  
Authentication microservice.  

### keymv-dbengine
https://github.com/ilyatbn/keymv-dbengine  
Database query microservice.  
