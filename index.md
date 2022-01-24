<p align="center">
  <img src="https://www.di.ens.fr/willow/research/inpainting/images/new_000228/new_000228.jpg" width="175">
  <img src="https://www.di.ens.fr/willow/research/inpainting/images/new_000228/new_000228_outline.jpg" width="175">
  <img src="https://www.di.ens.fr/willow/research/inpainting/images/new_000228/new_000228_res_comb.jpg" width="175">
 <br>
  Source: <a href="https://www.di.ens.fr/willow/research/inpainting/">Willow</a>
</p>

Course webpage for the NYU Spring 2022 Course Special Topics in Data Science, DS-GA 3001.003/.004 (Introduction to Computer Vision). This course is aims to cover a broad topics in computer vision, and is *not* primarily a deep learning course. We will covert topics in traditional computer vision such as camera geometry, image formation, segmentation, object recognition, classification, and detection (see [Syllabus](#Syllabus)).


### Logistics

* DS-GA 3001.003 (Lecture) \
Thursdays 4:55pm-6:35pm  \
**Location**: Global Center for Academic & Spiritual Life, 238 Thompson Street (GCASL 361)   \
\
The class will be in-person or via Zoom (see <a href="https://brightspace.nyu.edu/d2l/le/lessons/156638/%20nits/6225595">Brightspace</a> for link). Slides will be available after the class on this webpage. (see [Schedule](#Schedule)).

* DS-GA 3001.004 (Lab) \
Tuesdays 5:55pm-6:45pm \
**Location**: Global Center for Academic & Spiritual Life, 238 Thompson Street (GCASL 361)   \
\
The labs will be in-person or via Zoom (see <a href="https://brightspace.nyu.edu/d2l/le/lessons/156638/%20nits/6225595">Brightspace</a> for link).  Labs will be used to cover additional materials or to work through practical exercises with the TA. 

* **Office Hours**: \
Office hours with each instructor will be available by appointment. 

* **Campuswire Link**: <a href="https://campuswire.com/c/G5F40373F/">Link</a>     \
Please try first to post any questions about course logistics and material, HWs and final project on Campuswire. We also highly encourage you to help each other out (but please do not reveal answers). For additional questions, please email course staff. 

### Instructors

<a href="https://www.di.ens.fr/~ponce/">Jean Ponce</a> (jean.ponce@inria.fr)  \
<a href="https://alberto.bietti.me">Alberto Bietti</a> (alberto.bietti@nyu.edu) \
<a href="https://esizikova.github.io">Elena Sizikova</a> (es5223@nyu.edu)

### TAs
Irmak Guzey (ig2283@nyu.edu)

### Grading

Four programming assignments (50% of the grade) + final project (40% of the
grade) + class participation and attendance (5%) + lab participation and attendance (5%). Assignments should be submitted using the <a href="https://brightspace.nyu.edu/d2l/le/lessons/156638/%20nits/6225595">Brightspace</a> site.

* **Excercise 1** on camera calibration. 
Due on TBA.
* **Excercise 2** on Canny edge detector. 
Due on TBA.
* **Excercise 3** on mean shift.
Due on TBA.
* **Excercise 4** on neural networks.
Due on TBA.
* **Final project:** details TBA.

### Participation and Attendance
You are expected to attend and participate in classes and labs in person or via Zoom (see <a href="https://brightspace.nyu.edu/d2l/le/lessons/156638/%20nits/6225595">NYU Brightspace</a> for link). Class attendance will count for 5% of your grade and lab attendance will count for 5% of your grade.


<a name="Syllabus"></a>
### Syllabus 
  * Introduction
  * Camera geometry and calibration
  * Filtering and feature detection
  * Radiometry and color
  * Texture and image segmentation
  * Stereopsis
  * Structure from motion and 3D models from images
  * Object recognition - historical perspective
  * CNNs for object classification and detection
  * 3D CNNs, Applications in Medical Imaging
  * Weakly-supervised and unsupervised approaches to image and video interpretation 

### References:
We do not require purchase of any textbooks and the course will be self-contained. You may wish to consult the resources below for additional material formalization. 

* D.A. Forsyth and J. Ponce, “Computer Vision: A Modern Approach”, second edition, Pearson, 2011. (<a href="https://www.pearson.com/us/higher-education/program/Forsyth-Computer-Vision-A-Modern-Approach-2nd-Edition/PGM111082.html">Link</a>)
* R. Szeliski, “Computer Vision: Algorithms and Applications”. (<a href="http://szeliski.org/Book/">PDF</a>)
* R. Hartley and A. Zisserman, “Multiple View Geometry in Computer Vision”, Cambridge University Press, 2004. (<a href="https://www.robots.ox.ac.uk/~vgg/hzbook/">Link</a>)
 

<a name="Schedule"></a>
### Schedule:

*Note*: lecture slides will be posted after each lecture.

| Date  | Lecture               | Topic | Link                                                                                          |
| ----- | ------------------------ | ------| --------------------------------------------------------------------------------------------- |
| 01/25 | Lab: Course Intro     | Introduction, Logistics       |  |
| 01/27 | Lecture 1             | Examples of vision tasks, camera geometry and calibration      | |
| 02/01 | Lab                   | A detour of sensing country, intrinsic and extrinsic parameters      |  |
| 02/03 | Lecture 2             | Linear calibration, analytic photogrammetry, filtering       |  |
| 02/08 | Lab                   | Image Stitching Exercise      | |
| 02/10 | Lecture 3             | Edge detection, keypoints and features, RANSAC, Hough transform      |  |
|  | Exercise 1 DUE        |                                                                                                |
| 02/15 | Lab                   | Edge Detection using Sobel Operator      |  |
| 02/17 | Lecture 4             | Texture, Segmentation      | |
| 03/22 | Lab                   | Radiometry and Color, Part 2      | |
| 02/24 | Lecture 5             | Radiometry and Color, Part 1     |  |
| 03/01 | Lab                   | Canny Edge Detection Skeleton Code      |  |
| 03/03 | Lecture 6             | Color      |  |
|  | Exercise 2 DUE        |                                                                                               | |
| 03/08 | Lab                   | Fundamental Matrix Esimation     |  |
| 03/10 | Lecture 7             | Stereopsis, Epipolar Geometry, Essential and Fundamental Matrices      | |
| 03/17 | No class | (spring break) | |
| 03/22 | Lab                   | Eight-point Algorithm     | |
| 03/24 | Lecture 8             | Eight-point Algorithm, Correlation-based stereo, more sophisticated methods     |  |
| 03/29 | Lab                   |      |  |
| 03/31 | Lecture 9                   | Structure from Motion     |  |
| 04/05 | Lab                   |      |  |
|  | Exercise 3 DUE        |                                                                                               | |
| 04/07 | Lecture 10                   | Affine and Projective SfM     |  |
| 04/12 | Lab                   |      |  |
| 04/14 | Lecture 11                   | SfM, Laser Scanning, Space Carving, Multiview Stereo     | |
| 04/19 | Lab                   | ICP Implementation     |   |
| 04/21 | Lecture 12                   | Visual Recognition, Intro to NN     | |
| 04/26 | Lab                   | VAE Implementation     |  |
| 04/28 | Lecture 13                   | CNN Recognition and Detection     |  |
| 05/03 | Lab                   |      |  |
|  | Exercise 4 DUE        |                         | |
| 05/05 | Lecture 14                   | CV Applications     |  |



### Acknowledgements
Much of the material for this course relies on the Computer Vision course given at ENS Paris by Mathieu Aubry, Karteek Alahari, Ivan Laptev, and Josef Sivic. Many of the slides are taken from James Hays, Svetlana Lazebnik, and Derek Hoeim. Website was originally designed by Matthew Trager.
