# ROS_Navigation
![image](https://github.com/glitter2626/ROS_Navigation/blob/master/4_17.png)

# Error
[WARN]Costmap2DROS transform timeout. Current time: 1465910131.3043, global_pose stamp: 1465910127.6785, tolerance: 1.0000
Ans: 需要修改global和/或local的tranform tolerance参数的值，比如0.5，也可能是需要同步时钟：$ sudo ntpdate ntp.ubuntu.com
