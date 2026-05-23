## mqtt
Basic
MQTT


What is MQTT?

MQTT = Message Queuing Telemetry Transport

👉 It’s a lightweight communication protocol used in IoT.

Think of it like:

📡 “Devices send small messages through a middleman (broker)”

What is MQTT?

MQTT = Message Queuing Telemetry Transport

👉 It’s a lightweight communication protocol used in IoT.

Think of it like:

“Devices send small messages through a middleman (broker)”


There are 3 main parts:

1️⃣ Publisher (Sender)
Sends data
Example: your Pico 2W gas sensor

2️⃣ Subscriber (Receiver)
Receives data
Example: your Django app

3️⃣ Broker (Middleman)
Handles messages
Example: Mosquitto (running on your PC/server)