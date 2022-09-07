# ERC-Automated-Vacuum-Cleaner-electronics

'Line following bot'[https://www.tinkercad.com/things/bgIEer8z0oY]




'Mode Setter and differential drive'[https://www.tinkercad.com/things/4bE99C3nQTb]
(Short description)
The mode setter:
  LCD desplays the current mode and the respective DC motor turns on.
  There is a prompt for the user to select the mode of his/her preference on the serial monitor.
  
The wheel-motor controller:
  Serial monitor takes an input of linear and angular velocities from the user and returns-
  the speeds and rpms of of each of the two wheels using the differential drive model of a robot.
  The respective motors named MotorL and MotorR turn according to these rpms.
  (Special cases of rectilinear motion with Wz=0 and motion with negative velocities have been taken into account)
