# Flood-Detection-system
IOT  based River Flood Detection system is a system that is developed using the platform of ThingSpeak web server to get stored or retrieved which is of data from the systems. This system relies on  NodeMCU board which act as transmitter and as receiver. The ThingSpeak application acts as server. In order to find the rate of level , ultrasonic sensors were used, they send the values to ThingSpeak application. The web server stores all the data in private channel by default, but there is an option to share data to the general public by using the public channel. Along with NodeMCU consists of Buzzer and LED so that if the threshold is reached the buzzer and LED gets triggered. The results obtained tells that the system can be used at Flood prone areas.

OUTPUT

When water level is at Min/Normal level. That resembles 'Green Alert'. This means that water is at normal position and no sign about flood condition. Also green led will glow.
![image](https://user-images.githubusercontent.com/118880053/221856942-40ad8410-3204-42cb-8244-94c26705cc53.png)

When water level crosses the Max Level. That resembles 'Red Alert'. This means that water level has crossed the 80% and flood situation has occured at that place. With increase in water level the system alerts to the authority or registered user. Also red led will glow and buzzer will be triggered.
![image](https://user-images.githubusercontent.com/118880053/221859695-f7d55b43-ab65-4467-b591-f933b5de3d10.png)

