# MERN Curd
Mongo Express React Node

### 1. Install the all dependencies for Express & React(client)

cd Root-Folder && npm install && cd client && npm install && cd.. && npm start

###2. Build Docker
build docker images and push to your repos so we can later use it with kuberneties

###3. Create Mongo Stateful sets form kuberconfig mongo-rs.yaml
so your connection staring would be
mongodb://mongo-0.mongo.botnext,mongo-1.mongo.botnext,mongo-2.mongo.botnext,mongo-3.mongo.botnext:27017/mydb?replicaSet=rs0

###use service for exposing api and front end
here is a great blog for mongo "https://stefanprodan.com/2018/mgob-kubernetes-gke-guide/"
