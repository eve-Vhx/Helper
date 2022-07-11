# Helper

## Tutorials, guidelines and tips:

1. Setting up PX4: https://docs.px4.io/main/en/dev_setup/dev_env.html
2. Setting up QGC: https://docs.qgroundcontrol.com/master/en/getting_started/quick_start.html

# Eve Vehicles Prototype Info

## Hardware

1. Flight Controller - Pixhawk 2.1 Cube Black (trying to upgrade to cube
orange)
https://docs.px4.io/v1.12/en/flight_controller/pixhawk-2.html
2. Optical Flow Sensor - Arkflow
https://docs.px4.io/v1.12/en/uavcan/ark_flow.html
3. IR lock sensor for precision landing - Pixy Cam
https://docs.px4.io/v1.12/en/advanced_features/precland.html
4. Transmitter and telemetry module - Herelink ground and air
https://docs.cubepilot.org/user-guides/herelink/herelink-overview
5. RTK GPS
https://docs.px4.io/master/en/gps_compass/rtk_gps.html
6. Onboard computer - VOXL development board
https://www.modalai.com/pages/voxl
7. FPV Camera - Foxeer ambarella a12 (plugs into herelink to transmit
video)
https://www.foxeer.com/foxeer-4k-ambarella-a12-hd-camera-uav-
pwm-remote-control-wifi-distortionless-lens-tv-out-micro-hdmi-g-220

## Software

1. Flight firmware - px4 or ardupilot (we jump back and forth between
both)
2. MAVlink for pixhawk messages
3. MAV SDK for libraries for px4 and ardupilot
4. MAVROS for the link between pixhawk and ros

