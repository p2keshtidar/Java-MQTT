** mosquitto service should be UP

0) run the Program
1) postman
2) POST
3) url: localhost:8080/sendMessage
4) Body
5) raw
6) {
       "topic": "your topic"
       , "message" : "your message"
   }
----------------------------------------------------------------
0) run the Program
1) cd C:\Program Files\mosquitto  or the place where your mosquitto is installed
2) mosquitto_pub -t "topic" -m "massage"
