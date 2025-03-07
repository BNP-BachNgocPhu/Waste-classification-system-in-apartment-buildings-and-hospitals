# Waste-classification-system-in-apartment-buildings-and-hospitals
This is the project that helped my team and I win the National Runner-up prize at the Mitsubishi Electric Cup 2024 Automation Competition (MECA2024).

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/2cc6d9f1-0359-41a6-b870-71d34724f87c" alt="Project Overview">
  <br>
  <em>Figure 1: We received the prize of the competition </em>
</p>

## **1. Introduction**
The issue of waste pollution worldwide, particularly in Vietnam, is becoming increasingly severe. 
Hazardous waste from hospitals, residential areas, and apartment complexes contributes significantly to 
this crisis. In Ho Chi Minh City alone, around **10,000 tons** of waste need to be processed daily, putting 
immense pressure on waste collection and disposal systems. Current treatment technologies are insufficient
, leading to an increase in illegal dumping sites and waste scattered across rivers and oceans. Waste pollution 
severely impacts the environment by contaminating soil, water, and air while also ruining urban aesthetics. Plastic 
waste and hazardous materials, which decompose slowly and contain harmful microplastics, pose serious health risks, 
including cancer, and threaten ecosystems.

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/147b6ad5-3378-4737-a9e1-1956f580354e" alt="Project Overview">
  <br>
  <em>Figure 2: Spontaneous garbage dumps in Duy Tan street area, Cau Giay district </em>
</p>

Waste brings countless unpredictable consequences, such as polluting the soil, water, and air while also ruining urban 
aesthetics. Moreover, waste contributes to the death of rivers and oceans. Particularly dangerous are plastic and hazardous 
waste, which decompose slowly and contain large amounts of microplastics. These pose serious health risks, including cancer
, and severely impact both human health and the ecosystem as a whole.

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/2f8cd737-6d5a-43f4-974d-f886cf8f31f9" alt="Project Overview">
  <br>
  <em>Figure 3: Plastic waste drifts on the coast of Quang Nam </em>
</p>

Currently, about 60 tons of household waste are discharged into the environment every day, of which large cities 
account for 60%.

Of these, about 70% are treated by traditional methods: buried in layers; but only 20% are buried in layers in a sanitary manner. 
The amount of unsanitary buried waste is increasingly polluting the soil, water and air environments. This problem is becoming 
especially serious in large cities. In addition, of the 30% treated by non-burial methods, up to 2/3 are burned in manual incinerators, 
causing smoke and dust to pollute the air.

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/51aab1f7-1bfe-4c27-83f6-f7d630716be0" alt="Project Overview">
  <br>
  <em>Figure 4: Rate of collection of urban solid waste in some localities (2019) </em>
</p>

Hanoi and Ho Chi Minh City (HCMC) are the two cities with the largest amount of domestic waste in the country, serving 
more than 17.5 million people and the need for development in both culture and infrastructure has caused the amount of 
waste in both cities to exceed the overload level (17,000 tons/day). Although there have been many actions calling for 
investment in waste treatment for decades, the main method is still burial. Most of these landfills are about to be overloaded 
and are increasingly causing serious environmental pollution such as Nam Son landfill, Soc Son (Hanoi), Tay Bac waste treatment 
area (HCMC).

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/9a54b0e3-8355-40bc-95a9-f2261e69b612" alt="Project Overview">
  <br>
  <img src="https://github.com/user-attachments/assets/5bb8cd06-83b7-40b6-8beb-2e662ec21166" alt="Project Overview">
  <br>
  <em>Figure 5, 6: Nam Son waste treatment area is overloaded and often has to stop receiving waste. </em>
</p>

With the scenario of having to deal with up to **15,000 tons** of waste per day by 2030, treating waste using traditional methods will 
cause significant consequences for the environment, especially in densely populated urban areas like Ho Chi Minh City. However, 
to date, waste treatment plants using modern technology have not appeared in Ho Chi Minh City, and it will not be until 2025 that 
the first waste-to-energy plant will officially come into operation in Cu Chi district.

This is also a common alarming situation in many other provinces and cities, when the problem of waste and environmental pollution 
has not improved. Waste treatment areas such as Khanh Son (Da Nang), Quang Trung landfill (Dong Nai), or the collection point in Ben
 Tre are all overloaded, seriously affecting people's lives, eco-tourism, and urban aesthetics.

Faced with this situation, the project “Automatic waste sorting system for apartment buildings and hospitals” was implemented with
 the hope of bringing positive impacts to social life and the ecosystem. Applying the pre-treatment stage can help reduce labor 
 resources and save costs in the process of collecting and processing waste. At the same time, this model can also be easily upgraded 
 and adjusted to classify waste according to needs thanks to the AI training mechanism.

 ## **2. System details**

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/e42df8c0-7bfe-4930-8e56-2e88e8bff077" alt="Project Overview">
  <br>
  <em>Figure 7: Complete system </em>
</p>

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/2fc79b6c-6f52-4a3e-a09a-1ae94aa0a689" alt="Project Overview">
  <br>
  <em>Figure 8: System Overview Flowchart</em>
</p>

 ### **2.1.  Vibrating system, classifying garbage of many sizes**
The first step in the process is the vibrating screen, where the waste is introduced to screen large and small waste. The vibrating screen is a device that uses a vibrating motor as a power source to make the material on the screen surface vibrate and perform the purpose of screening, depending on the size of the material, they are retained on the surface or passed through the screen mesh surface. The vibrating screen is widely used in applications of separating rock particles in the mining industry, screening sand, screening gravel in construction, etc.
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/36271719-ab50-4177-8fbb-5be2ed08c294" alt="Project Overview">
  <br>
  <img src="https://github.com/user-attachments/assets/4fda79ad-0412-443f-911b-6a300f1b77a3" alt="Project Overview">
  <br>
  <img src="https://github.com/user-attachments/assets/760e955d-6c7f-4851-9ac6-ed8043244ca8" alt="Project Overview">
  <br>
  <em>Figure 9, 10, 11: Details of the vibrating system </em>
</p>

The vibrating screen has a size of **0.4 m x 1.4 m x 0.8 m**. The screen surface is inclined at **16 degrees**, made of iron to increase durability and load-bearing capacity.
**Design and division of compartments**
Including 3 main screening compartments, classifying waste by size.
- **Top compartment**: Screening large-sized waste (plastic bottles, metal cans). Waste is transferred to a separate container.
- **Middle compartment**: Screening medium-sized waste (pieces of paper, boxes). Waste is retained and transferred to the conveyor belt.
- **Bottom compartment**:Screening small-sized waste (dust, sand, debris). Waste is transferred to a separate container for later processing.

Use a **120W** vibrating motor to create suitable vibrations. The motor is firmly attached to the frame of the vibrating screen. The vibration force is calibrated through experimentation to ensure effective separation of waste and reduce the risk of clogging.

 ### **2.2. Middle classification system, using vision**

 <br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/f5383779-b439-464d-a9ab-3458d1eee193" alt="Project Overview">
  <br>
  <em>Figure 12: Middle classification system </em>
</p>

Classify waste into four corresponding bins. 
- Use two **HG-KR23 Servo motors** with iron blades to push waste from the conveyor belt into the bin. Each motor is responsible for classifying two different types of waste.  
- The camera is mounted on the classification frame, connected to the **YOLOv5 network**. The camera identifies waste based on shape, color and size.

The program processes the signal from the camera to correctly classify the four types of waste into the corresponding bins.

### **2.3. Electrical cabinet**

 <br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/d99557b7-dbfa-4c68-80df-10567f114074" alt="Project Overview">
  <br>
  <em>Figure 13: Electrical cabinet</em>
</p>

**Safety standards:**

- The design of the electrical cabinet must meet standards such as IEC 61439, NFPA 70, ISO/IEC 17025.
- Ensure electrical safety, fire prevention and other risks.  

**Technical requirements:**  
- Install the correct voltage and current ratings.
- Arrange safety devices such as circuit breakers, protective relays, and grounding.

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/32cd2119-e370-4d4e-bf69-ad787722fcef" alt="Project Overview">
  <br>
  <img src="https://github.com/user-attachments/assets/7b9e2baa-ca83-44a2-aea8-fa6a00779bd1" alt="Project Overview">
  <br>
  <img src="https://github.com/user-attachments/assets/a68bf173-1d02-4e47-9075-7ceac036008c" alt="Project Overview">
  <br>
  <em>Figure 14, 15, 16: Wiring diagram drawing is done on EPLAN software </em>
</p>

### **2.4 Smart Automation Solutions - I do this part**

**YOLOv5 Network**  
YOLO is a CNN model for object detection, which has the advantage of being much faster than previous models. It can even run well on embedded devices with limited resources like raspberry pi. YOLO can also be understood as “You only look once”, which means we only need to look once to detect an object. It can be seen that this is a very fast and powerful algorithm.

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/d5e4fc19-8003-4c26-8e1c-b9b2a9023f1b" alt="Project Overview">
  <br>
  <em>Figure 17: Basic structure of YOLOv5 network</em>
</p>

- Backbone: is the main part of the network, responsible for extracting features from the input image. Backbone often uses convolutional neural networks that are pre-trained on a large dataset such as ImageNet, to achieve high representation. Some popular backbones are Darknet, ResNet, CSPDarknet, EfficientNet, etc.
- Neck (PANet): is the part connecting the backbone and the output, responsible for combining features at different levels, creating feature maps that increase the scale for object detection. Neck often uses techniques such as feature pyramid network (FPN), path aggregation network (PAN) or cross-stage partial network (CSP) to enhance the representation and detection capabilities of the network.
- Output: is the final operation of the YOLO module. The output applies anchor boxes and convolution layers and fully connected layers to classify objects to process the final output including: object type, accuracy scale, and bounding boxes.

In the modern context, the problem of environmental waste classification is becoming increasingly important, especially in environmental protection and sustainable development. With the advancement of artificial intelligence technology, the use of deep learning models such as CNN and YOLO has opened up new directions in solving the problem of waste classification.
YOLO network is one of the most advanced models in the field of object recognition and detection. With the ability to process quickly and with high accuracy, YOLO has been widely applied in many different fields, from security monitoring, industrial automation to object detection in medical images. Therefore, in this project, the team will focus on researching the theoretical basis of YOLO network and its application in building a waste classification model in apartment buildings and hospitals.

**Object recognition system**  
The key to this process is the **MELIPC (Mitsubishi Electric Industrial Computer)**, a line of industrial computers from Mitsubishi Electric, designed to meet the demanding needs of industrial applications. MELIPC combines powerful computing capabilities with connectivity and automation features to optimize production processes and data management.  
MELIPC is equipped with a powerful processor and advanced data analysis tools, allowing for fast and accurate processing and analysis of image data from cameras. This is important in identifying objects of different shapes and sizes in the waste sorting system. In addition, MELIPC has the ability to connect and integrate with other automation systems (in this model, the Robot arm), through standard industrial communication protocols. This helps optimize the sorting process through real-time control and monitoring devices.

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/1d293704-9baa-441d-8bd2-97a21944dc13" alt="Project Overview">
  <br>
  <em>Figure 18: MELIPC (Mitsubishi Electric Industrial Computer)</em>
</p>

In terms of operating principles, MELIPC receives image data from the Camera and performs pre-processing steps (resizing, color, etc.). Then, the computer continues to send data to the trained AI model (YOLOV5n) to be able to perform the task of recognizing and classifying waste. At the same time, the computer also plays a major role, used to connect to the PLC via Mx Component software to send control signals, affecting the classification actuator.  
The following code is executed on Visual Studio Code software, which has the function of looping through the detected objects in a frame, checking certain conditions and then drawing a box around the object, adding a label with the object name and reliability, as well as sending the object name via **TCP/IP connection**.

The protocols in the waste identification model are implemented as follows:
- Connection protocol from Camera to MELIPC via USB2.0 port.
- Connection protocol from Camera running application (Python) to monitoring and connection application (C#) via TCP/IP protocol.
- Connection protocol from monitoring and connection application (C#) to PLC via Mx Component

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/cf05d69e-4d11-4c57-a69a-537ac4fa2b79" alt="Project Overview">
  <br>
  <em>Figure 19: The recognition results are displayed on the computer screen</em>
</p>

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/fb22de46-b60e-4704-9840-f444ca3f2797" alt="Project Overview">
  <br>
  <em>Figure 20: MX Component software interface</em>
</p>

In this project, YOLOv5n was carefully chosen as the main AI model for object recognition. The training images were some common types of waste labeled in order 1 (Paper), 2 (Plastic), 3 (Aluminum), 4 (Styrofoam). The training dataset consisted of 10,000 images, labeled on Roboflow software with more than 1,000 different types of waste. During the training process, the team applied data augmentation methods such as flipping horizontally and vertically (Flip), adjusting brightness (Brightness Adjustment), and blurring images (Blur). This process helps the model learn more features from the data. According to a 2017 study in Germany, applying Augmentation can increase the accuracy of the model by up to 12% and perform better when encountering waste types that the system has never seen during training. This is especially important in automatic waste sorting systems, where having a large and diverse amount of data can significantly improve the accuracy and thus increase the reliability of the model.

After completing the training process, the AI ​​model has achieved high accuracy and is integrated into a Python application. This application uses a Camera to collect images on the conveyor belt and recognize each type of waste according to the trained labels. Thanks to the fast processing ability of YOLOv5n, the system can operate effectively with a recognition speed of up to 20-30 FPS on MELIPC (using Intel i7 CPU), ensuring the ability to classify waste in real time.  
When the system is operating, the Camera will continuously send image data to MELIPC, then the computer will continuously recognize and classify each type of waste and send the results via the C# interface application via TCP/IP protocol with MELIPC as the host.  
The **C# application** will continuously receive data from MELIPC, then send it to the PLC via the Mx Component software and store the corresponding values ​​in temporary variables (1: Paper, 2: Plastic, 3: Aluminum, 4: Styrofoam, 5: No Sorting), then with the pre-programmed program in the PLC, it will process this data to output appropriate control signals.

<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/51cc707b-b1d5-4a1e-b594-3f3336790987" alt="Project Overview">
  <br>
  <em>Figure 21: Actual image from the system's Camera</em>
</p>

## **Model accuracy and stability in operation**
During the process of perfecting and calibrating the system, the research team applied testing and evaluation methods to ensure that the model achieved optimal accuracy and stability.  
Specifically, the model was used to classify many different garbage cases, from theoretical to practical situations, for the purpose of calibrating and optimizing technical parameters. This process is very important, as it helps the research team identify and eliminate potential factors that may affect the accuracy and stability of the system.  
The results of 1000 experimental runs showed that the model achieved an accuracy of up to 82%. This is an extremely impressive number, showing the effectiveness and reliability of the system when deployed in real applications.  
More notably, during the testing process, the model did not encounter any errors or problems such as short circuits. This confirms the high stability of the system, an extremely important factor, especially in applications requiring high continuity and reliability.

<h3 align="center">Table: Classification Results of the Model</h3>

<div align="center">

| **No.** | **Type of Waste** | **Quantity of Waste** | **Correct Classification (%)** |
|--------|--------------------|------------------------|--------------------------------|
| 1      | Plastic            | 250                    | 86%                            |
| 2      | Carton             | 300                    | 92%                            |
| 3      | Aluminum           | 200                    | 85%                            |
| 4      | Styrofoam          | 200                    | 82%                            |
| 5      | Others             | 50                     | 64%                            |

</div>

With these impressive results, the research and development team has enough basis to believe in the model's ability to operate well in practice. The criteria of accuracy and stability have been perfectly met, opening up positive prospects for the widespread deployment of the system in the near future, contributing to improving the efficiency and quality of related applications.

---

## Contact Information

If you have any questions or need further information, feel free to reach out:

- 📧 Email: [bachngocphu.work@gmail.com](mailto:bachngocphu.work@gmail.com)  
- 💼 LinkedIn: [Bach Ngoc Phu](www.linkedin.com/in/bachngocphu)  

