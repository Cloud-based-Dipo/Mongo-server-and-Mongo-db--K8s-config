# Mongo-server-and-Mongo-db--K8s-config
K8s config files for Mongo server and Mongo db deployment 
mongo.yaml contains the config of mongo express server and the external service created for access to the server.
mongodb.yaml contains the config file of the mongo database and the internal service for connection from the mongo server to the database.
mongodb-secret.yaml contains the encoded credentials for connection between the mongo server and db.
mongo-configmap.yaml contains configuration details for reference from the mongo server
