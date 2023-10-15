# object-detection-and-super-resolution-on-license-plate-
* This project consists of two distinct sections, each addressing a specific area of focus. The first section involves object detection, which aims to identify and locate objects within an image or video. The second section focuses on super-resolution, a technique used to enhance the resolution and quality of low-resolution images or videos. By splitting the project into these two sections, we can explore and develop advancements in both object detection and super-resolution techniques independently, thereby maximizing the potential for improvements in each respective area.
***

# Dataset
* Dataset will be provided on the basis of request.
***

# Preprocessing
*  To preprocess the data for this project, the first step involved collecting vehicle images. Once the images were gathered, the dataset was split into train and test sets, ensuring that both subsets represent a diverse range of vehicle images.
*  For the annotation of license plate regions in the images, the labelme tool was utilized. This tool enabled the manual annotation of license plate areas within the vehicle images. The result of this annotation process is a JSON file containing the annotated regions of interest (license plate areas) within each image.
*  With the completion of these preprocessing steps, the dataset is now ready for training. The annotated images and corresponding JSON files can be used as input for training the object detection model to recognize and locate license plates accurately.
***

# utilization of the models
* In this project, we have employed different architectures to address the two main objectives. For the super-resolution part, we have utilized a Generative Adversarial Network (GAN) architecture. GANs are known for their ability to generate high-resolution and realistic images by training a generator network to generate visually similar images to the training data, while a discriminator network evaluates the authenticity of these generated images.

On the other hand, for the object detection section, we have implemented the YOLO v5 architecture. YOLO (You Only Look Once) is a popular real-time object detection algorithm that divides the input image into a grid and predicts bounding boxes and class probabilities directly from this grid. YOLO v5 is an improved version of the YOLO algorithm, known for its accuracy and efficiency in detecting objects in various scenes.

By utilizing GAN architecture for super-resolution and YOLO v5 for object detection, we can leverage the strengths of each model to achieve state-of-the-art results in their respective domains within this project.
