# CVFX_HW6
10% (Compare above methods)
10% (Make some special effects based on the pose information, such as rotating, zooming in or out)
5% (Insert a 3D model to your video)
30% (Assistant)
20% (Mutual evaluation)
10% (Bonus- Make visual effects with other SLAM methods.)
##Take videos by yourselves and Make these visual effects with any post-production software


## 1.Take videos by ourselves and Make these visual effects with ORB-SLAM2
After we record a video, we have to calibrate camera and calculate our camera intrinsic. Next, we use orb-slam2 to get the keypoint camera pose and the video trajectory. When we have camera pose, we can accurately project our object (Image or GIF) to the world coordinate and get the final results. <br>

### Here we show our video trajectory and point cloud and camera pose <br>
|Video1|
|:------:|
|Trajectory & Point Cloud & Camera Pose|
|<img src='pts1.gif'>|
|Added our object to video|
|<img src='gg.gif'>|
