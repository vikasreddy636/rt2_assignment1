## Assignment of the Research Track 2 course 
# GINNE VIKAS REDDY (matricola 5061211)

# ACTION SERVER 
The ActionClient and ActionServer communicate via a "ROS Action Protocol", which is built on top of ROS messages. The client and server then provide a simple API for users to request goals (on the client side) or to execute goals (on the server side) via function calls and callbacks

# Topics list

    ├── cmdvel                  
    ├── odom                  
    ├── tf                    
    ├── clock                    

# nodes list

    ├── gotopoint                  
    ├── Position server                  
    ├── UserInterface       
    ├── statemachine
    ├── Gazebo





The package contains the nodes and the simulation environment for controlling a mobile robot in the Gazebo simulation environment.
To launch the node, please run:
```
roslaunch rt2_assignment1 sim.launch
```