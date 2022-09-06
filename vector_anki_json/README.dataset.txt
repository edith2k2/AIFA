# Anki Vector Robot Dataset > raw
https://public.roboflow.ai/object-detection/robot

Provided by [Amitabha Banerjee](https://robotics.thinkific.com)
License: CC BY 4.0

**Background**

The Anki Vector robot (assets currently owned by Digital Dream Labs LLC which bought Anki assets in 2019) which was first introduced in 2018. In my opinion, the Vector robot has been the cheapest fully functional autonomous robot that has ever been built, The Vector robot can be trained to recognize people; however Vector does not have the ability to recognize another Vector. This dataset has been designed to allow one to train a model which can detect a Vector robot in the camera feed of another Vector robot.

**Details**
Pictures were taken with Vector’s camera with another Vector facing it and had this other Vector could move freely. This allowed pictures to be captured from different angles. These pictures were then labeled  by marking the rectangular regions around Vector in all the images with the help of a free Linux utility called labelImg. Different backgrounds and lighting conditions were used to take the pictures. There is also a collection of pictures without Vector.

**Example**
An example use case is available in my Google Colab notebook, a version of which can be found in my [Git](https://).

**More**
More details are available in [this ](https://medium.com/towards-artificial-intelligence/teaching-the-vector-robot-to-detect-another-vector-robot-a04bf88603c9)Medium article.
If you are new to Computer Vision/ Deep Learning/ AI, you can consider my course on '[Learn AI with a Robot](https://robotics.thinkific.com/courses/aiwitharobot)' which attempts to teach AI based on the AI4K12.org curriculum. There are more details available in [this](https://medium.com/programming-robots/learn-ai-with-a-robot-8de7c5779972) post.
