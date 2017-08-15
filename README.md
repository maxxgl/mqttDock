# Putting paho-mqtt into a Docker image

Just makin sure.

## Setup

    $ git clone https://github.com/maxxgl/mqttDock
    $ cd mqttDock
    $ docker build -t mqttdocker .
    $ docker run -p 80:1883 mqttdocker
