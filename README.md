# Motion Planning and Decision Making for Autonomous Vehicles

<img width="953" alt="image" src="https://user-images.githubusercontent.com/74157573/194764242-f472d861-50c9-491a-9612-94461bdec8b8.png">

<img width="953" alt="image" src="https://user-images.githubusercontent.com/74157573/194764317-85f2fc1e-4276-4599-af36-ae9ba9eedd81.png">

<img width="953" alt="image" src="https://user-images.githubusercontent.com/74157573/194764330-ba53567a-5c43-4eff-a7dc-ac90f78d05a5.png">



Cubic Spiral Path Planner Integration
========================================

This example creates a C++ server that connects to a python Carla API client.
The output is visualizing the cubic spirals form the motion planner inside Carla

Compile
---------------

'cd project/solution_cubic_spirals_integrated'
'cmake .'
'make'

Run
------------
launch Carla simulator in new window


'cd project/solution_cubic_spirals_integrated'
'./spiral_planner'

Open new window

'cd project'
'python3 simulatorAPI.py'

Camera Control for spectator window from carla server script

key listener is from python script window, then use arrow keys to change camera angle
and use w/s to change camera zoom

IF rpclib is not a populated folder can get the source files with
git clone https://github.com/carla-simulator/rpclib.git
