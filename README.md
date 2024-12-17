### streaming pipeline using **flink**, **kafka** and **Docker**

#### approach: examining IP addreses which comes into kafka topic and determining where the traffic is comming from using [ip2location](https://www.ip2location.io)

##### features:
- this repo contains credentials. ( which you may not have. *Sorry*)
- routing data from HTTP Inceptors to kafka topics
- getting data from kafka topic with flink and enrich it(with 'country', 'city' and 'state' extracted from the IP address), then pass it forward.