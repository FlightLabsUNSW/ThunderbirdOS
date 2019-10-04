# ThunderbirdOS


## Compilation

Navigate to where you want to put the workspace
and clone the workspace
```sh
$ git clone https://github.com/FlightLabsUNSW/ThunderbirdOS
$ cd ThunderbirdOS
$ colcon build --symlink-install
```
and add the newly compiled workspace to you environment
```sh
$ source install/setup.bash
```

### Note
For a much greater depth in using Colcon refer to the docs:
[Colcon Documentation](https://colcon.readthedocs.io/en/released/user/quick-start.html)

Colcon can also be used for building ROS 1 packages as noted in the docs

## Running
To run a particular package after building it, use `ros2 run`
```sh
$ ros2 run package_name node_name
```
e.g:
```sh
$ ros2 run example_package sos_publisher
```
## Development

## Branches
When you make a new branch, put the name and a brief description here

* `test_branch` = a test branch to show you format
