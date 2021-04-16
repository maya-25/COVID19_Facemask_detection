# COVID19_Facemask_detection
It will tell whether the person wearing mask or not in order to protect nose and mouth from Corona virus
Here libraries used: 
* Tensorflow
* scikit-learn
* numpy
* Matplotlib
* imutils for video streaming and for setting up the camera frame.
* deploy.prototxt,res_ssd_300Dim - These two files required for setting the camera and detecting the face.



The sample images of dataset which can be found in datset1.zip folder.
Here MobileNetV2(weights="imagenet") transfer learning is used for traning the model initially.

Results :
Output images are shown(Output_face_mask_green.png, Output_Nomask_red.png) with the bounding box green for detecting mask and Red for detecting half mask or no mask along with percentage covered.


References:

1.M. R. Bhuiyan, S. A. Khushbu and M. S. Islam, "A Deep Learning Based Assistive System to Classify COVID-19 Face Mask for Human Safety with YOLOv3," 2020 11th International Conference on Computing, Communication and Networking Technologies (ICCCNT), Kharagpur, India, 2020, pp. 1-5, doi: 10.1109/ICCCNT49239.2020.9225384.

2.Chowdary, G. J., Punn, N. S., Sonbhadra, S. K., & Agarwal, S. (2020, December). Face mask detection using transfer learning of inceptionv3. In International Conference on Big Data Analytics (pp. 81-90). Springer, Cham.


