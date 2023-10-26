# ros2web_turtlesim


## Dependencies
- [`ros2web`](https://github.com/ros2web/ros2web)
- [`ros2web_app`](https://github.com/ros2web/ros2web_app)
- [`launch_api`](https://github.com/ros2web/launch_api)

## Installation
```bash
mkdir -p ~/ros2_ws/src
cd ~/ros2_ws/src
git clone https://github.com/ros2web/ros2web_turtlesim.git
cd ~/ros2_ws
colcon build --symlink-install
. ./install/local_setup.bash
```

## Usage
```bash
ros2 run ros2web_turtlesim turtlesim_ctl

# Star ros2web (another terminal)
ros2 web server --no-auth
```

Access the following URL.

http://localhost:8080/turtlesim_ctl

