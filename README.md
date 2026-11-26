# Lab8-AlgonquinPetStore-onSteroids

## Demo Video
[YoutubeLink](https://youtu.be/LjPURLOG6C8) 

All eight application repositories were forked, and their Docker images were built and pushed to Docker Hub using the L8 tag.
The Kubernetes deployment manifests were updated to use my custom Docker images
 
[Docker Hub Repositories](https://hub.docker.com/u/zubaird25)


### Azure Managed Services
For Mongo DB, I believe it would be best to replace it with Azure Cosmos DB for MongoDB. It is a managed document database that of course supports MongoDB compatible data and API's. This will reduce the responsibility of managing the database infrastructure. 

As mentioned in previous labs, Azure Service Bus can be a good replacement for RabbitMQ as it is a managed messaging services that supports publish and subscribe messaging between applications. This would allow services to communicate without having to maintain a message broker inside the Kubernetes Cluster.
