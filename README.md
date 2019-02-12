# ros_tutorials
Code used in tutorials found on ROS wiki

First, launch roscore:

```
roscore
```

Second, run the server node:

```
rosrun rospy_tutorials add_two_ints_server
```

Finally, test the service:

```
rosservice list
```

```
rosservice info add_two_ints
```

```
rosservice call /add_two_ints 245 617
```
