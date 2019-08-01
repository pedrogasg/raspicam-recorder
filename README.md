# raspicam-recorder

Utility launch file for record the picam output

## Install

```bash
sudo apt-get install python-catkin-tools python-rosinstall-generator -y

mkdir -p catkin_ws_cr/src

cd catkin_ws_cr/src

git clone https://github.com/pedrogasg/raspicam-recorder.git

cd ..

catkin init

catkin build

source ~/catkin_ws_cr/devel/setup.bash --extend

```


## Usage

```bash
roslaunch raspicam_recorder record.launch node_name:=<node_name> bag_location:=<folder>
```
