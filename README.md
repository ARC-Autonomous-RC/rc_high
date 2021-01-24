# rc_high

## launch the file in Rviz

define the RC car by an urdf file. it includes the ZED camera and the lidar.
to launch the launch file, use:

roslaunch rc_high RC_car_display.launch

and set the fix frame to ARC_car_base_link to view the car model (robot model)

## Generating tf tree 

rosrunn tf view_frames
evince frames.pdf
