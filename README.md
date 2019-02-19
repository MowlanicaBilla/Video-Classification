# Video-Classification

## Introduction to Video Classification 

Ever heard of a flip book? If you haven’t, you’re missing out! Check out the one below:

![Source:Giphy.com](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTFv8M37eMPaPl0m9qupKPpKHWEdA2W_W3GT_NS7-PJhFf0W_dU)

We have a different image on each page of the book, and as we flip these pages, we get an animation of a shark dancing. You could even call it a kind of video. The visualization gets better the  faster we flip the pages. In other words, this visual is a collection of different images arranged in a particular order.

Similarly, videos are nothing but a collection of a set of images. These images are called frames and can be combined to get the original video. So, a problem related to video data is not that different from an image classification or an object detection problem. There is just one extra step of extracting frames from the video.

Remember, our challenge here is to calculate the screen time of both Tom and Jerry from a given video. Let me first summarize the steps we will follow in this article to crack this problem:

1. Import and read the video, extract frames from it, and save them as images
2. Label a few images for training the model (Don’t worry, I have done it for you)
3. Build our model on training data
4. Make predictions for the remaining images
5. Calculate the screen time of both TOM and JERRY


References :
1. https://www.analyticsvidhya.com/blog/2018/09/deep-learning-video-classification-python/
2. https://towardsdatascience.com/introduction-to-video-classification-6c6acbc57356
