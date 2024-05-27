mosquitto_pub -t 'outTopic' -m 'hello MQTT'

ON
mosquitto_pub -t 'inTopic' -m '1'

OFF
mosquitto_pub -t 'inTopic' -m '0'