



Terminal commands to start container

```bash
 287  docker run -d -it -p 1883:1883 -p 9001:9001 --name mosquitto --listener 1883 0.0.0.0 --allow_anonymous true --restart always --network="host" -v /root/mosquitto/mosquitto.conf:/mosquitto/config/mosquitto.conf eclipse-mosquitto
  288  docker run -d -it -p 1883:1883 -p 9001:9001 --name mosquitto --allow_anonymous true --restart always --network="host" -v /root/mosquitto/mosquitto.conf:/mosquitto/config/mosquitto.conf eclipse-mosquitto
  289  ocker run -d -it -p 1883:1883 -p 9001:9001 --name mosquitto --restart always --network="host" -v /root/mosquitto/mosquitto.conf:/mosquitto/config/mosquitto.conf eclipse-mosquitto
  290  docker run -d -it -p 1883:1883 -p 9001:9001 --name mosquitto --restart always --network="host" -v /root/mosquitto/mosquitto.conf:/mosquitto/config/mosquitto.conf eclipse-mosquitto
```