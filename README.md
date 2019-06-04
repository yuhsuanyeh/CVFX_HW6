# CVFX_HW6
- [x]  5%  (Take videos by yourselves)
- [x]  10% (Make these visual effects with ORB-SLAM2)
- [x]  10% (Make these visual effects with any post-production software)
- [x]  10% (Compare above methods)
- [x]  10% (Make some special effects based on the pose information, such as rotating, zooming in or out)
- [x]  5%  (Insert a 3D model to your video)
- [x]  30% (Assistant) 
- [x]  20% (Mutual evaluation)
- [ ] 10%  (Bonus- Make visual effects with other SLAM methods.)

## 1.Take videos by ourselves and Make these visual effects with ORB-SLAM2
After we record a video, we have to calibrate camera and calculate our camera intrinsic. Next, we use orb-slam2 to get the keypoint camera pose and the video trajectory. When we have camera pose, we can accurately project our object (Image or GIF) to the world coordinate and get the final results. <br>

### Here we show our video trajectory and point cloud and camera pose <br>
|Video1|
|:------:|
|Trajectory & Point Cloud & Camera Pose|
|<img src='pts1.gif'>|
|Added our object to video|
|<img src='gg.gif'>|

### Here we add visual effects with post-production software (After Effects) and compare with ORB-SLAM2<br>
| ORB-SLAM2 | After Effects |
|---------------|---------------|
|<img src="og.gif" alt="drawing" width="500"/>|<img src="ae.gif" alt="drawing" width="500"/>|
