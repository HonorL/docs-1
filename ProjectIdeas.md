Driving Car
  * Controlled by app
  * Sends video feed
Two Pis
  * Pi on car in headless mode. On WIFI. Stores video
  * Centralized one, connected to ethernet
Arduino
  * On car

App
  * Authentication
  * Control car
  * View video feed
  * View car status
Camera
  * Video to android app, remote vision
  * Headlight for night vision
  * USB connection -> modular could be high end or garbage
Auxiliary
  * Temperature, Light, Camera
Actuator
  * Motors, axles of car
Feedback Loop
  * Car control
  * Automatic headlights
  * Camera feed
  
Database
  * 10 minutes of memory for video
  * logs, status, app input
Periodic timing loop
  * Checking light
  
GUI
  * Show live video and status on the app
UDP
  * Controls
  * Authentication
  * Video streaming not UDP*
