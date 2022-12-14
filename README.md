# NYUSH_DURF_video-semantic-segmentation
This is the repository for NYUSH Dean's undergraduate research funding, video semantic segmentation.

Group Member: Muyang Xu, Chengyu Zhang, Qianyu Zhu

Project report @: [click here for writing](https://github.com/qianyu-zhu/NYUSH_DURF_video-semantic-segmentation/blob/main/DURF_report.pdf).

# Abstract:
In computer vision, segmentation refers to detecting and locating different image fragments at the pixel level, with application in both image and video. Based on the image segmentation, video segmentation is divided into four subjects: video semantic segmentation (VSS), video object segmentation (VOS), video instance segmentation (VIS), and video panoptic segmentation (VPS). The complexity of tasks increases along with the four approaches, and they are highly interrelated. 

To achieve these tasks, various research that utilizes deep learning models has been done. Our project will mainly focus on learning current mainstream algorithms for video object segmentation (VOS) starting from two-dimensional images, comparing the validity by cross-comparing different models, and achieving optimization concerning region similarity and contour accuracy. Furthermore, we expect to achieve an ideal VOS model, approximating its economic efficiency to the VIS model.

# Research Question and Significance:
VOS (video object segmentation) is an image processing model that learns features from static information such as the object's appearance and segments the object according to this information. Our research team would like to tackle the task of semi-supervised video object segmentation, i.e., the separation of an object from the background in a video, given the mask of the first frame. The critical ingredient of existing approaches of semi-supervised VOS, for example, OSVOS and MaskTrack. At present, this region's main research direction is to combine transparent information with motion information (the motion information is almost adopted by optical flow). Our research aims to implement a Video Object Segmentation algorithm, which would be trained and tested mainly on the DAVIS (Densely Annotated VIdeo Segmentation) dataset, as well as other legacy datasets.

Video Object/Instance Segmentation has broad application prospects. It plays a vital role in various real-life tasks, including autonomous vehicles, medical image diagnosis, augmented reality, video processing, and so on. Meanwhile, by conducting this research, we can reinforce our knowledge in machine learning, implement a video segmentation algorithm on our own, and have a better understanding and capability of video segmentation and computer vision.

# Project Design and Feasibility: 
## 1st stage: 
### Algorithm study:
During this period, our team mainly focused on learning core concepts of several basic models for semi-supervised video segmentation, including evaluation matrix and encoding/decoding fully convolutional networks (encoder, decoder, upsampling strategies), etc.

### Image object segmentation (the final project of Machine Learning): 
We decide to learn, understand and implement several basic two-dimensional models, and compare the advantages/disadvantages among different models. The primary purpose is to choose the comparatively efficient model in the attempt to construct a video segmentation model.

### Video object segmentation: 
We classified different models into three categories based on their testing performances, referring to the semi-supervised video object segmentation on the DAVIS open challenge. The elementary model with a lower level of performance, efficiency, and accuracy, such as OSVOS, the medium- level model such as OSVOS-S, OnAVOS, and MiVOS model at the advanced level.

## 2nd stage Mock Construction and Comparison:
Based on the previous study of three phases of video object segmentation, we expect to construct the mock models with respect to OSVOS, OnAVOS, MiVOS. Test our models through the DAVIS's evaluation platform, compare and analyze the potential aspects which significantly contribute to the qualities weakness among different models. At this stage, we are attempting to figure out the possible optimization derived from two- dimensional image segmentation.

## 3rd stage Integration Optimization:
### Preparation study: 
We will dig into the VIS algorithm and figure out the connection between VOS and VIS model. This preparation aims to strengthen which aspects of the model have the massive difference between VOS and VIS.
### Implementation: 
We will choose a comparatively ideal mock model from the second stage. Targeting the difference, we intend to bridge the gap between VOS and VIS, thus approaching VOS's efficiency to VIS as much as we can. We will also probe whether the VIS can thoroughly overtake all VOS models in the entire industry field. If not, how can we possibly enhance the VOS model in the attempt to reduce cost and increase benefits in some specific branches where VOS still has considerable prospects compared with VIS.

### Group Partnership Plan (if applicable):
We would collaborate to find the ideal resources and study both individually and collectively. We will also implement different parts of the model and on separate algorithms, with the division of parts acquired after systematically understanding the VOS algorithms. Constant meetings would be held for exchanging ideas, updating the process, and bug hunting.

We???ll also collaborate with Star Chen, a sophomore student majoring in Computer Science, doing independent research under our mentor Li Guo to boost our project further.

Additionally, all the team members will most likely be in the same location, so we would utilize face-to-face meeting sessions and online communication through Zoom and WeChat to push our project forward.

# Background:
We three are sophomore students majoring in science majors: Computer Science (Muyang), Math (Qianyu), Data Science concentration in AI (Chengyu). The courses we've taken for our primary requisite could help us in the completion of this research project, such as but not limited to Introduction to Computer Science, Data Structures, Probability and Statistics, and Linear Algebra. Moreover, all four of us are currently taking Machine Learning under our mentor Professor Li Guo's instruction this semester, which provides us a solid knowledge foundation for our research and grants us the project experience of working together.

# Feedback and Evaluation:

For our main datasets DAVIS and YouTube, we???ll fully utilize the official competition website Codalab, where performance score could be obtained after code submission. The evaluation metrics are also described in the DAVIS 2016 and 2017 paper. These are the direct feedback and evaluation. Moreover, this project will be monitored by the DURF association and our mentor. We will give reports of different stages weekly to our mentor according to the project schedule. Feedback and evaluation on our progress and additional guidance will be gained through weekly communication with our mentor.

# Dissemination of Knowledge:
The resources, dataset, code and result of our research project would be published open source on Github with detailed documentation and reflection of the whole process. Our research result of this project would be captured by a final paper, which will be shared on the project Github page. Our research team will exhibit the results via poster and presentation through attending the DURF Research Symposium.
