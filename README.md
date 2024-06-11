# NanoPwn #
 The NanoPwn is a handsized device capable of Wifi, Bluetooth, Sub-Ghz, Infared and 13.56Mhz RFID. The RFID feature is detachable to save space unless needed. For around $40 you can create a device which competes with the Flipper zero.

 Features: 

 # WIFI #
Wifi is powered by a ESP32-S3R8 which features a average Wifi speed of 150Mpbs. The powerfull chip specs out at IEEE 802.11b and a Fine timing measurement of 802.11mc FTM. Wifi Multi-Media aswell.

- Evil portal 
- SSID Spam
- Deauth
- Handshake capture
- PMKID Attack
- Karma Attack
- Custom MAC Address
- Hidden SSID Revealer
- Evil twin 
- Fake access point 
- DNS Spoofing
- Association flood


# Bluetooth # 
Bluetooth is powered by the same powerfull ESP32-S3R8, the chip features BLE, Bluetooth mesh and  Bluetooth 5 at 2mbps. On high power it will transmit at 20dBm.

- Bluetooth Honeypot
- Bluetooth PIN Brute Force
- Bruteforce speaker + Play Audio + 100% volume
- Info about all devices 
- Bluetooth BadUSB


# Sub-Ghz #
 Using a CC1101 v2.00, you could open garage doors up to 900 meters away. It has a transmitting power of 10dBm and has interchangable attenas with an SMA connection.
 
 - Jammer
 - Replay Attack
 - Traffic Recorder ( RAW )
 - Traffic Analysis
 - Transmit RAW
 - Roll jam
 - Roll Back
 - DeBruijn
 - JukeBox
 - Transmit raw from SD card


# Infared #
For transmitting IR the NanoPwn uses 3x Infrared LED TSAL6400 and a TSOP4838 as the receiver, but don't forget a 2N4401 transistor.

 - Learn IR signal 
 - Send IR signal ( Signals found in folders in subfolders etc ) 
 - Update IR signal database
 - Read IR signals from SD card


# RFID #
For 13.56Mhz RFID cards, the device uses the extremly cheap PN532. The PN532 is a compact device capable of read and write of Mifare and Iso 14443A cards. The RFID compoments are detachable and has a 3d-printed box with external GPIO ports to connect it.

 - Read 13.56Mhz RFID cards 
 - Write 13.56Mhz RFID cards
 - Save clone to SD card 
 - Write from SD card (
 - Show UID from SD card
 - Write last cloned RFID
