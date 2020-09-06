[Got rasberry pi from Amazon](https://www.amazon.com/CanaKit-Raspberry-4GB-Starter-MAX/dp/B07XPHWPRB)
[Install Visual studio Code](curl -L https://raw.githubusercontent.com/headmelted/codebuilds/master/docs/installers/apt.sh | sudo bash)
### [Enabled SSH](https://www.raspberrypi.org/documentation/remote-access/)
* Preferences => Rasberry Pi configuration => Interfaces => Enabled SSH
* Get Ip adress
    ```cmd
        hostname -I
    ```
 * Connecting through [windows 10](https://www.raspberrypi.org/documentation/remote-access/ssh/windows10.md)
    * ssh pi@192.168.1.24


### [Enabled VNC](https://www.raspberrypi.org/documentation/remote-access/)
* Preferences => Rasberry Pi configuration => Interfaces => Enabled VNC
* Downloaded vnc [viewer](https://www.realvnc.com/en/connect/download/viewer/windows/)
* Used VNCViewr to connect.