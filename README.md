# CSC 461 Final Project


Utilizing the YOLO algorithm, a model that has a single-pass approach speeds up processing, suitable for real-time tasks. In addition, it excels in accurately detecting diverse objects within an image. Furthermore, we utilize multiple pictures somewhere in the range of 4 to 8 from the 20,000 images found within the imported dataset from Kaggle. The dataset contained multiple CSV that described the objects found within a specific by marking them within a rectangle. After creating the model we then predicted the object found within the images that range from a bus, pedestrian/person, bicycle, traffic light, etc. Our main focus will be to predict objects with their corresponding label accurately. 

During the prediction phase, our model exhibited a commendably high confidence level in its predictions. However, it is noteworthy that no single object received a 100% confidence score. The confidence scores ranged from the lower 30s to the mid-90s, indicating the model's ability to provide reasonably confident predictions across a variety of objects. This distribution of confidence scores suggests a good understanding of the objects present in the images, capturing the uncertainty inherent in complex scenes.


