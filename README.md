# raspberry-pi

* Latest rasberry-pi is 4
* Operating systems
    * Raspberry Pi OS (official)
    * [Other](https://www.ubuntupit.com/best-raspberry-pi-os-available/)

    [Change OS](https://www.mbtechworks.com/how-to/change-raspberry-pi-operating-system.html)

    [MagPi Magazine](https://magpi.raspberrypi.org/)

* Terminology
    * __SBC__ (__S__ mall __B__ oard __C__ omputer)
    * __NOOBS__  (__N__ ew __O__ ut __O__ f __B__ ox __S__ oftware is an easy operating system installation manager for the Raspberry Pi) [doc](https://www.raspberrypi.org/documentation/installation/noobs.md)

Canakit

[youtube](https://www.youtube.com/watch?v=BpJCAafw2qE)

[Minimum Required](https://itsfoss.com/things-you-need-to-get-your-raspberry-pi-working/)

[Simulator](https://devblogs.microsoft.com/python/iot-exploration-with-vs-code-python-and-the-device-simulator-express/)
[Projects](https://magpi.raspberrypi.org/books/projects-5)
[Raspberry Pi — First Boot](https://medium.com/jungletronics/how-to-set-up-a-headless-raspberry-pi-9edcbc3597c2)

## To upgrade throug terminal
```cmd
    sudo apt update
    sudo apt upgrade
```

## Connecting remotely
* Using SSH
    * Enable SSH 
    * Findout ip address (through **ipconfig** in terminal)
    * On host machine(windows/mac)
        * ssh yourusername@198.51.100.0  (use the actual ip address here )
* Using Virtual Network Computing
    * [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/)
    * One can connect from anywhere in the world using real VNC account and registrering
* Programming
    * Node-Red
        * Run Node-Red console
        * http://localhost:1880
        * [more](http://nodered.org)
    * Thonny for Python
    * Sonic Pi (music)
    * GreenFoot for java
    * Geany (for C,HTML,Java, PHP)
* Resources
    * [Begineers Book](https://store.rpipress.cc/products/the-official-raspberry-pi-beginners-guide-3rd-edition)
    * [Documentation](http://rpf.io/docs)
    * [Electronics Project](http://rpf.io/gpiozero)
    * [Magpi issues](http://magpi.cc/issues)
    * [Command Line](http://magpi.cc/clibook)
    * [Making Minecrart](http://magpi.cc/MCBook)
    * [Python Games](http://magpi.cc/rtfkvd)
