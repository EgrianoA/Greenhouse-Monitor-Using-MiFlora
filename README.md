In this system I'm using :
1. Xiaomi MiFlora as sensing device. This device can sensing air temprature, soil moisture, light intesity and soil fertility
2. ESP32 to get data from MiFlora using BLE then publish it to cloud using MQTT
3. CloudMQTT as the cloud
4. Node-Red in server to subscribe data from CloudMQTT and display the dashboard

For the workflow of the system I'll describe using image below
![Screen 1](Preview/Scheme.JPG)
