# telinfo-pihat
Design for  Raspberry Pi hat with Telinfo interface

Based on [PiTInfo V1.2](https://hallard.me/pitinfov12/) by Charles and the [Raspberry Pi HAT KiCAD template](https://www.hackster.io/jonbuford/raspberry-pi-hat-kicad-template-c9d6e7) by Jon Buford. 

However, due to issues getting the KiCad template feature to work, I ended up cloning the [Github kicad_libary](https://github.com/KiCad/kicad-library) and then manually copying Jon's files from the kicad_library/template directory. 

The reason behind this project is that I'm interested using Raspberry Pis for home automation and I'm learning how to use Kicad to make PCBs. 

Ideas include:
- [ ] Interface to the telinfo terminals on (French) electricity meters
- [ ] LED Mains voltage indicator on Teleinfo terminal block
- [ ] RGB LED to indicate status of Teleinfo data receptoion
- [ ] RGB LED to indicate status of sending data to remote server
- [ ] Button to shutdown the Pi
- [ ] Button to restart the Pi
- [ ] Swith to detect that enclosure has been opened (tamper detection)
- [ ] I2C Temperature sensor (within enclosure) to proactively and safely shutdown RPi if needed
- [ ] I2C Temperature & humidity sensor (outside enclosure) to log environment data with consumtion data
- [ ] 3D printing design for box to house the Pi
- [ ] LCD/OLED display to show fault information / electrical consomption information
- [ ] Real time clock
- [ ] PCB fabrication files and Bill of Materials on example PCB fabricator / component supplier for one-stop shopping 



