# los_led

## LED点滅
0 → LEDを消灯

1 → LEDを点灯

2 → LEDが５秒点灯し１秒消灯を３回繰り返す。
デモ　→ https://youtu.be/tlezvTLKG80


## Dependency
C

## Setup
ハードウェア：Rasberry Pi 3 Model B V1.2

ソフトウェア：Raspbian　3.2.1

## Usage

Rasberry Piの2２番ピンと３９番ピンにLEDを接続

cd ~/catkin_ws/src

$ git clone https://github.com/EnosawaAyana/led_ros.git

$ cd ..

$ catkin_make

$ cd src/led_ros/LED

$ bash setup.bash

$ roslaunch led_ros LEDlaunch

$ 0

$ 1

$ 2

## License
This software is released under the GENERAL PUBLIC LICENSE , see LICENSE.
## References
https://github.com/ryuichiueda/robosys2019.git
