# mqtt
read json object via mqtt

regarding mosquitto:
reference https://mosquitto.org/man/mosquitto_sub-1.html
from the terminal run 

mosquitto_sub -h test.mosquitto.org -t Moti_IoTTest/#
or 
mosquitto_sub -h test.mosquitto.org -t Moti_IoTTest/'BECKHOFF OFFICE'/TcIotCommunicator/Json/Tx/Data

