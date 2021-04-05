# Face-detection-with-Deep-Learning

A number of deep learning methods have been developeed and demonstrated for face detection.

Perhaps one of the more popular approaches is called the *"Multi-Task Cascaded Convolutional Neural Network"* **(MTCNN)** described by [Kaipeng Zhang](https://kpzhang93.github.io/) in the 2016 paper titled "[Joint Face Detection and Alignment Using Multitask Cascaded Convolutional Networks](https://arxiv.org/abs/1604.02878)"

## Why MTCNN Popular?
* Because it achieved then state-of-the-art results on a range of benchmark datasets.
* Because it is capable of also recognizing other facial features such as eyes,nose and mouth,called landmark detection.

## Working of MTCNN
The network uses a cascade structure with three networks : 
1. **Image Pyramid** - First the image is rescaled to a range of different sizes
2. **Proposal Network** - This first model proposes candidate facial regions.
3. **Refine Network** - This second model filters the bounding boxes.
4. **Output Network** - This third model proposes facial landmarks.

### Pictorial representation of above working
   ![mtcnn working](https://raw.githubusercontent.com/kuluruvineeth/Face-detection-with-Deep-Learning/main/mtcnn.webp)
   
## How to setup MTCNN ?
* [mtcnn setup](https://pypi.org/project/mtcnn/)

## Photograps I used
![pic1](https://github.com/kuluruvineeth/Face-detection-with-Deep-Learning/blob/main/test1.jpg)
![pic2](https://github.com/kuluruvineeth/Face-detection-with-Deep-Learning/blob/main/test3.jpg)
![pic3](https://github.com/kuluruvineeth/Face-detection-with-Deep-Learning/blob/main/test6.jpg)

## Resultant Photographs
![res1](https://github.com/kuluruvineeth/Face-detection-with-Deep-Learning/blob/main/pic1.jpg)
![res2](https://github.com/kuluruvineeth/Face-detection-with-Deep-Learning/blob/main/pic2.jpg)
![res3](https://github.com/kuluruvineeth/Face-detection-with-Deep-Learning/blob/main/pic3.jpg)

## Conclusion
* Face detection is a computer vision problem for identifying and localizing faces in images
* State-of-the-art face detection can be achieved using a **Multi-task Cascade CNN** via the MTCNN library



