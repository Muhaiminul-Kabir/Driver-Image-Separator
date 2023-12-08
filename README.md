# Driver-Image-Separator
## Overview:
This project stands as a significant contribution to our ongoing thesis, concentrating on the precise isolation of drivers within vehicles through a two-step process employing YOLOv8. Our project focuses on isolating the driver from vehicles, considering diverse angles and scenarios.
## Methodology:
**Vehicle Segmentation**: Utilizing YOLOv8, the system detects multiple cars/trucks within an image, discerning the largest vehicle by analyzing segment points. This facilitates the extraction of the largest vehicle, eliminating other objects from the image with OpenCV.
**Driver Identification**: Once the largest vehicle is isolated, the system uses YOLOv8 again to detect individuals within the vehicle. In a side-view scenario, the driver is identified as the person with the maximum bounding box area, emphasizing the person covering the most substantial area within the vehicle.
## Workflow:
**Vehicle Detection & Cropping**: Analyzing images containing multiple vehicles, the system identifies and extracts the largest vehicle using segment point analysis.
**Driver Identification**: Within the isolated vehicle, the system employs YOLOv8 to detect individuals, emphasizing the individual covering the most significant area within the bounding box, assuming a side-view of the vehicle.
Technologies Used:
**YOLOv8 Framework**: Utilized for both vehicle and driver detection.
**Image Processing Libraries**: Employed **OpenCV** for cropping and isolating specific segments within images.
## Objectives:
+ Accurately isolate the driver within vehicles from diverse angles and scenarios.
+ Enhance the functionality of driver-assist technologies by precisely identifying drivers in varying vehicle environments.
## Impact:
The successful implementation of this project aims to contribute significantly to driver-assist technologies and autonomous vehicle functionalities. By accurately identifying and isolating the driver, the system can enhance safety measures and improve overall driving experiences.
## Challenges & Innovations:
Addressing challenges related to diverse vehicle orientations, varied lighting conditions, and occlusion scenarios are key aspects. The innovation lies in utilizing segment point analysis and area-based driver identification to precisely isolate the driver within complex vehicle images.
## Screenshots
![](github.com/Muhaiminul-Kabir/Driver-Image-Separator/Untitled.png)
## Contributor:
### **Md. Muhaiminul Kabir**<br>
Bachelors of Science in Computer Science and Engineering **(Ongoing)**<br>
Ahsanullah University of Science and Technology<br>
Dhaka, Bangladesh<br>

