# Wawa

These repository contain notes and source code used to implement a baby monitoring infrastructure. 
It represents a basic guideline that contains the following features:

1. Visual monitoring using a camera
2. Plot a graph to observe the values collected from temperature and humity sensors.

# Hardware used

Figure 1 presents the infrastructure used for this case.


From this picture, we used a:

- Raspberry pi 3 with and Raspdebian OS on a SD card
- DHT11 temperature and humidity sensor
- Raspberry camera

# Software

Once the Raspberry is power ON, you can start all processes by running

```bash
$ cd /home/pi/app/wawa
$ sh startAll.sh
```

# Monitoring links

- To watch throught the camera:  

	http://192.168.1.24/hls/indes.u3m8

- To observe the temperature and humidity graphs

	http://192.168.1.24:3000

 

