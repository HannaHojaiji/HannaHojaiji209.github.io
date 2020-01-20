# EE-209AS 
## ****Project proposal for Security and Privacy for Embedded Systems, Cyber-Physical Systems, and Internet of Things****
**Team members: Hannaneh Hojaiji, Mark Chen, Riyya Iyer**

In this project, we propose the "same-body" authentication for a set of sensor networks. 

![System flowchart](https://github.com/HannaHojaiji/EE-209AS/blob/master/System%20flowchart.png)

Here, through daily and one-time authentication of the sensor network and the mobile device trough NFC key, we pair the devices for a single user. 
![established communication setup with smartwatch](https://github.com/HannaHojaiji/EE-209AS/blob/master/watch%20communication.png)
Then, throughout the day, periodic authentication for localized connection is needed. 
This was an IP address of the shared WiFi connection and a secret key is sent over short distance communication, which ensures that the sensor network is locally activated on the same individual user.
The data communication will be encrypted to ensure security of the pins shared between the sensor network and the smartphone. 
![established communication with the watch](https://github.com/HannaHojaiji/EE-209AS/blob/master/established%20communication.png)


## References
###### [1] Zhang, Jiansong, et al. "Proximity based IoT device authentication." IEEE INFOCOM 2017-IEEE Conference on Computer Communications. IEEE, 2017.
###### [2] Cornelius, Cory T., and David F. Kotz. "Recognizing whether sensors are on the same body." Pervasive and Mobile Computing 8.6 (2012): 822-836.
###### [3] Han, Jun, et al. "Do you feel what I hear? Enabling autonomous IoT device pairing using different sensor types." 2018 IEEE Symposium on Security and Privacy (SP). IEEE, 2018.
###### [4] Anand, S. Abhishek, and Nitesh Saxena. "Noisy Vibrational Pairing of IoT Devices." IEEE Transactions on Dependable and Secure Computing 16.3 (2018): 530-545.








