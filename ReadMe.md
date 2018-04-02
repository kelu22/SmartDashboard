# Abstract

The idea is to design and develop a Smart Home manager interface as an Android application. The application would first have a login screen, and then a dashboard that contains information about the sensors in a smart home (temperature, humidity, noise level...) and a section with buttons that interact with the home: turn on/off certain lights, lock the door, close windows...

The application would be just an interface that would send HTTP requests to a very simple API server (developed by Pacoard)that will respond to these requests, making the application think that the Smart Home actually exists. 