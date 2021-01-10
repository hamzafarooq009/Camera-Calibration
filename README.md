# Camera-Calibration

Determining the intrinsic and extrinsic parameters of a your mobile phone camera using camera calibration techniques.

Choose an appropriate 3D calibration object (i.e. a nonplanar object, a rubiks cube for example) so that the world points on that object span a 3-dimensional space, and the image points are easy to mark. Place the calibration object on a horizontal plane, such as a tabletop, or floor, to take the image. Mark at least 20 image points as carefully as possible and establish their world coordinates in millimeters.

![44270246-ff78-4869-b103-f57928ac5578](https://user-images.githubusercontent.com/46634351/104126719-f3baf500-537f-11eb-8c39-58ef9ad1a675.jpg)

From this data, compute the camera matrix P. Show the original points and the back-projected camera points on a single image and compute the average re-projection error.

Implementing QR decomposition of a matrix because we are using direct linear transformation

![14e9aa0b-2755-4bb1-86a5-fa2352cb235e](https://user-images.githubusercontent.com/46634351/104126791-5e6c3080-5380-11eb-91b8-ec733d90282f.jpg)

Computing camera center C, intrinsic matrix K and Rotation matrix R. Generate a 3D figure which shows the calibration points, the camera center and the orientation of the camera in 3D (You also have to plot the points for 3d calibration object as well)

Search for the sensor information of your camera on the web. From this information, compute the focal length in mm. The following link may be useful to look up sensor sizes in mm(since most smartphone sensor sizes will be quoted in inches):
https://www.digicamdb.com/sensor-sizes/
