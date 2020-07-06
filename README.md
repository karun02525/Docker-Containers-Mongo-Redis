# Services Multiple Contianers MongoDb,Spsring Boot,Redis and Elastic Search

##Create multiple container 

  docker run -p 6379:6379 --name sum-redis redis
  docker run -p 27017:27017 --name sum-mongo mongo
  docker run -p 9200:9200 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.7.1

##Show runing port
  docker ps
