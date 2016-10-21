# mqtt-elasticSearch

this file stores data published on MQTT in elasticSearch

#dependencies

Paho-mqtt-library
elasticSearch client library
ElasticSearch mush be running on the same server on port 9200

#use

modify the header lines in the file to include the http or ip address and port of your mqtt server
modify if required the topics (default $SYS topic)
run as python mqtt-elasticSearch from terminal on the same machine where elasticSearch is running

