FROM confluentinc/cp-kafka-connect:5.4.1

RUN confluent-hub install debezium/debezium-connector-postgresql:1.1.0 --no-prompt
RUN confluent-hub install --no-prompt debezium/debezium-connector-mysql:1.2.2
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-elasticsearch:10.0.1
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-twitter:0.3.34
RUN confluent-hub install --no-prompt mongodb/kafka-connect-mongodb:1.5.0