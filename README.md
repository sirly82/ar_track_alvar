# THIS FOR NOETIC-ROS
Just if you use noetic

# Open Terminal
Open the Terminal or klik (Ctrl+Alt+T) for shortcut

# Create Workspace (if you dont have it)
```
$ mkdir -p ~/catkin_ws/src
```

# Access Workspace (if you have it)
```
$ cd ~/catkin_ws/
```

# Instal Paket ``` ar_track_alvar ```
```
$ git clone https://github.com/sirly82/ar_track_alvar.git
```

If you use another version, access this 
```
$ git clone https://github.com/ros-perception/ar_track_alvar.git
```

so, checkout with your version (ex: melodic-devel)
```
$ git checkout melodic-devel
```

# Build Your Workspace
```
$ cd ~/catkin_ws
$ catkin_make
```

```
$ source ~/catkin_ws/devel/setup.bash
```

# Verification
```
$ rospack find ar_track_alvar_msgs
```
If it show your path like this, the installation is successfull
```
/home/sirly28/catkin_ws/src/ar_track_alvar/ar_track_alvar_msgs
```
