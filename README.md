# Military Target and Equipment Detection

This project focuses on developing an efficient military target and equipment identification system using the YOLOv7 object detection model applied to both images and videos. Leveraging YOLOv7's speed and accuracy, the system aims to automate the detection and classification of various military targets, including vehicles, aircraft, weaponry, and infrastructure, in real-time scenarios. Through extensive training on annotated datasets and fine-tuning using transfer learning techniques, the model achieves robust performance across diverse environmental conditions and target types. By enabling rapid and accurate identification of potential threats or targets of interest, the system enhances situational awareness and facilitates timely decision-making in military operations. Its adaptability and scalability make it suitable for deployment across different platforms and operational contexts, ranging from tactical reconnaissance missions to strategic surveillance operations. Ultimately, this project represents a significant advancement in leveraging machine learning for augmenting defense and security capabilities, with potential applications in enhancing national security strategies worldwide. 

The military target and equipment detection project is a sophisticated system designed to identify various military targets and equipment in images uploaded by users. The project consists of several key components working together seamlessly to achieve this objective.

Firstly, upon accessing the web application's landing page, users are presented with an interface to upload images containing military targets. Once an image is uploaded, it is processed by the Flask backend, which serves as the central hub of the application. The Flask backend then passes the image data to the YOLOv7 model for inference.

The YOLOv7 model, trained on a custom dataset comprising eight classes including rifles, pistols, tanks, jets, soldiers, and grenades, performs object detection on the uploaded image. It identifies and localizes the military targets present in the image based on the trained classes.

Once the inference is completed, the detected classes are sent back to the Flask backend, which in turn communicates the results to the frontend for display to the user. The frontend presents the detected military targets along with any relevant visualizations, such as bounding boxes around the identified objects, providing users with real-time feedback on the detected targets.

In summary, the project leverages a combination of frontend and backend technologies, alongside the YOLOv7 object detection model, to enable users to upload images and accurately detect military targets and equipment in those images. This seamless integration of components ensures a user-friendly and efficient experience for users interacting with the web application.

We will acquire a diverse dataset of military target and equipment images from Roboflow and Kaggle. This dataset will encompass a wide range of scenarios and will be meticulously annotated with bounding boxes to create ground truth labels. Additionally, the dataset will undergo preprocessing, including image resizing and normalization, to prepare it for training. 

![image](https://github.com/KarthikPrabhu2541/Military-Target-and-Equipment-Detection/assets/91746517/3a6c4296-8ed9-4073-93a9-0dd13be4255b)

![image](https://github.com/KarthikPrabhu2541/Military-Target-and-Equipment-Detection/assets/91746517/8e7de3a1-2b50-4539-9d70-2616b2274b9d)

![image](https://github.com/KarthikPrabhu2541/Military-Target-and-Equipment-Detection/assets/91746517/2924bb76-18e1-413c-94e8-19ac844fd4a6)

Roboflow links to our project's dataset

https://app.roboflow.com/military-target-and-equipment-detection/personnel/10

https://app.roboflow.com/military-target-and-equipment-detection/tanks-ey2rh/3

https://app.roboflow.com/military-target-and-equipment-detection/fighter-jets-q3wsk/2

in case you wanna know how to work with roboflow

https://www.youtube.com/watch?v=76E6esnez8E&ab_channel=Roboflow
