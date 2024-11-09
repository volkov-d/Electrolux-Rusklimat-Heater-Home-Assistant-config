# Electrolux-Rusklimat-Heater-Home-Assistant-config

Electrolux Air Gate Transformer DI 4.0 configuration for Home Assistant mqtt integration

HOW TO USE:

Redirect all mqtt://mqtt.cloud.rusklimat.ru:8883/ requests to your local Home Assistant SSL MQTT server.  You could use your local static DNS record for that. Build in HA Mosquito mqtt server would not work. You have to use Mosquito server version 1.5 or EMQX server. Overwise local devices are not able to connect to mqtt server properly. 

Find and replace following tags with real values in the yaml configuration:

 *<DEVICE NAME>*
 *<MAC ADDRES>*
 *<TOKEN>*

Include it in configuration.yaml or just copy/past.

 Enjoy
