# GameStoreMicroServices
## Introduction
Microservice Project built for learning purposes written in dotnet core 3.1 using an event driven approach to asynchronously integrate between the microservices, with the help of RabbitMQ and Masstransit
## Used technologies and tools
+ Docker
+ DDD + clean architecture
+ ASP.NET Core 3
+ MediatR for in-Process communication
+ Sql and noSql Databases :
  + MongoDB
  + PostgreSQL
+ Redis for caching
+ Consul for service Discovery
+ RabbitMQ with Masstransit (a dotNet Abstraction for Message Brokers like RabbitMQ).
+ Ocelot for api gateway
## Services
+ [Items Service](https://github.com/zawette/GameStore.Services.Items)
+ [Stock Service](https://github.com/zawette/GameStore.Services.Stock)
+ [Inventory Service](https://github.com/zawette/GameStore.Services.Inventory)
+ [Order Service](https://github.com/zawette/GameStore.Services.Order)
+ [Identity Service](https://github.com/zawette/GameStore.Services.Identity)
## FrontEnd
+ [React FrontEnd](https://github.com/zawette/GameStore.ReactFrontEnd)

