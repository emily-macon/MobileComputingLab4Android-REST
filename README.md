# MobileComputingLab4Android-REST
Part of: https://github.com/allenwhitedev/Lab-4-Mobile-Computing-Ultimate-Repo

Modded Google Nearby API sample code found at https://github.com/googlesamples/android-nearby/tree/master/messages/NearbyDevices to interact with a node.js server with RESTful webservices.

Must download, configure, and run node server first found in Ultimate Repo.

In BackgroundSubscribeIntentService:
  'private static final String BASE_URL = "{CHANGE_TO_YOUR_NODE_IP_ADDR}:8080"'
  
When using this with the FRDM-K64F board, you must register your beacons with the attachment type-name as the MAC addr of the board. The value is redundent and can be anything.

The app must be open for beacons to be registered on the node server.
