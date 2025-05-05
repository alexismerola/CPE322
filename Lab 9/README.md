# Lab 9 - YANG
#### In this lab, we explored YANG (Yet Another Next Generation), a data modeling language used for network configuration protocols like NETCONF. The goal was to process a YANG module by converting it into YIN (an XML-based format) and UML (for visual modeling). We then used PlantUML to generate a graphical representation of the model. This hands-on process helped reinforce how YANG models can be transformed and visualized for better understanding and system design.

### Install pyang and PlantUML
#### Installed the required tools pyang and PlantUML using pip3. Both installations completed without any issues.
![alt text](install.jpg)

### copy ~/iot/lesson9/intrusiondetection.yang to ~/demo
#### Copied the provided intrusiondetection.yang file from the lesson directory to the working ~/demo folder for further processing.
![alt text](cp.jpg)

### Run pyang to generate intrusiondetection.yin and intrusiondetection.uml
#### Ran pyang to convert the YANG model into two formats:
#### - .yin for XML-based representation
#### - .uml for visual modeling
#### Both files were generated and verified in the ~/demo directory.
![alt text](pyang1.jpg)
![alt text](pyang2.jpg)

### Run PlantUML to generate intrusiondetection.png
#### Processed the .uml file with PlantUML to produce a .png diagram. The image was created successfully and clearly represents the structure of the intrusion detection model.
![alt text](py-intrusiondetection.jpg)
![alt text](intrusiondetection.jpg)

#### The lab successfully demonstrated the complete workflow from YANG source code to a visual UML diagram. All tools were installed and functioned as expected, and each transformation step produced the correct output. The final PNG image clearly displays the structure of the intrusion detection model, making it easier to interpret the system’s design. This process is useful for documenting and managing network configurations in real-world applications.
