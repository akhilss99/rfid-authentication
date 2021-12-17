# rfid-authentication
IoT and Cloud Enabled PC authentication using RFID tag with user login audit in the Client Device.
### Prerequisites: 
* IoT devices:
  * Arduino Leanardo (any Board that supports Keyboard library) - PC Authentication
  * Node MCU Esp8266 - update the real-time db & retrieve login time
  * RC522 RFID Reader
  * RFID Tags
* Cloud services: 
  * Firebase Real-Time Database - store logs
  * Firebase Cloud Messaging - notify the app
  * Pusher Beams Client - api to send push notifications using the FCM server
  * AWS EC2 - EC2 server to host the python script to automate the notifications
* Android Studio - Build & Compile the android application

Note: Instead of buying arduino Leonardo & Node mcu, can use single mcu from arduino offering both usb serial connection & wifi connectivity.

### Circuit Diagram:
<img src="circuit.jpg" width="600">
