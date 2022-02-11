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




# Excuting the package(individual)

create a workspace in root repositories

```cd```

```mkdir "name of the workspace" ```

```cd "name of the package"```

```mkdir src```

Build the package

```catkin_make```

clone the repository 

```git clone -b action https://github.com/vikasreddy636/rt2_assignment1.git```

Refresh the workspace using

```rospack profile```


The package contains the nodes and the simulation environment for controlling a mobile robot in the Gazebo simulation environment.

To launch the node, please run:
`````````
roslaunch rt2_assignment1 sim.launch
`````````