# Camera-Calibration

Determining the intrinsic and extrinsic parameters of a your mobile phone camera using camera calibration techniques.

Choose an appropriate 3D calibration object (i.e. a nonplanar object, a rubiks cube for example) so that the world points on that object span a 3-dimensional space, and the image points are easy to mark. Place the calibration object on a horizontal plane, such as a tabletop, or floor, to take the image. Mark at least 20 image points as carefully as possible and establish their world coordinates in millimeters.

![44270246-ff78-4869-b103-f57928ac5578](https://user-images.githubusercontent.com/46634351/104126719-f3baf500-537f-11eb-8c39-58ef9ad1a675.jpg)

From this data, compute the camera matrix P. Show the original points and the back-projected camera points on a single image and compute the average re-projection error.

Implementing QR decomposition of a matrix because we are using direct linear transformation

