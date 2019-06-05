
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

## Take videos by ourselves and Make these visual effects with ORB-SLAM2
After we record a video, we have to calibrate camera and calculate our camera intrinsic. Next, we use orb-slam2 to get the keypoint camera pose and the video trajectory. When we have camera pose, we can accurately project our object (Image or GIF) to the world coordinate and get the final results. <br>

**Video trajectory, Point cloud, and 3D visual effect : Case 1**

|Video1|
|:------:|
|Trajectory and Point Cloud|
|<img src='pts1.gif'>|
|3D Visual Effect|
|<img src='gg.gif'>|

**Video trajectory, Point cloud, and 3D visual effect : Case 2**

|Video2|
|:------:|
|Trajectory and Point Cloud|
|<img src='pts2.gif'>|
|3D Visual Effect-version1|
|<img src='gg2.gif'>|
|3D Visual Effect-version2|
|<img src='bb.gif'>|

**Comparison between ORB-SLAM2 and After Effect**  <br>
As we first apply SLAM to obtain camera pose, we can assume a real object in the world coordinate and project it onto camera plane. In this way, we can feel like there is a real object in somewhere. However, using After Effect cannot use 3D information and the result will be just like a 2D image on the screen.

| ORB-SLAM2 | After Effects |
|---------------|---------------|
|<img src="og.gif" alt="drawing" width="500"/>|<img src="ae.gif" alt="drawing" width="500"/>|


**Special Effect**
Here we add rotation effect of a image.

