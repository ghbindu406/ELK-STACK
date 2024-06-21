# ELK-STACK
ELK STACK ELASTICSEARCH, LOGSTASH, KIBANA

1. what is ELK STACK?
   ELK stack is nothing but the elasticsearch, logstash, kibana combined together called as ELK stack , which is used as centralised logging for applicastion,
2. ELK FLOW OR Arch?
   elk where the 3 tools involved
   elastisearch which is used to search data from any format
   logstash it is used as data processing it has built 200 filters and plugins which can process the diferent data type to single format
   kibana: which is used as visulizasing stong gi tool where the data collected can be easily read wiht this kibana where it support different type od graph tbales, pie charts adn also geological part also
  Beats : this are know data transfers where beats are downloaddedd as plugins where it used to collecte the data from the server adn transfor it to logstash in which the data is processed and send to elaassticsearch adn then kibana for visulizing
Storage -- data which is collected is stored in different format
1. staoge --elasticsearch
2. archiving -s3/ google storage
3. monitoring -we can go with nagios / graphite
   Where does Elasticsearch store data?

3. You can locate where Elasticsearch stores data under its default paths.
   For Debian/Unbuntu this will be located at /var/lib/elasticsearch/data & for RHEL/CentOS this will be located at 
   /var/lib/elasticsearch.

4. What database does Elasticsearch use?
   Elasticsearch is a NoSQL database
5. How can you forward logs from Kubernetes to Logstash?

   By using a log shipper such as Filebeat, as illustrated on our integration page for sending Kubernetes logs to Logstash.
6. Where are Kibana dashboards stored?
    Kibana dashboards are stored in Elasticsearch under the default index kibana-int which can be edited within the 
   config.js file if you wish to store your dashboards in a different location.
7. Few examples for Beats?
   Filebeat, Metricsbeat, Winlogbeat, Pakcketbeat, Auditbeat etc
8. 
