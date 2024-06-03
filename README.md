git clone https://github.com/NAGOYASHACHIHOKO/auto_aim

catkin build --this

1つ目のターミナル(roscoreの起動)
roscore
2つ目のターミナル(bagの再生)
cd ~
rosbag play -l redbag.bag
3つめのターミナル
rosrun armor_detection view_rgb
