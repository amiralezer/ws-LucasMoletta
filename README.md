# Table of contents
- [Table of contents](#table-of-contents)
  - [Introduction ](#introduction-)
  - [Memomed ](#memomed-)
  - [Compressor Monitoring ](#compressor-monitoring-)

## Introduction <a name="introduction"></a>
Repository aiming to document my projects.

## Memomed <a name="paragraph1"></a>
*This project was presented to a college subject at Universidade Tecnológica Federal do Paraná. Project developed by Lucas Moletta, Flávio Neto, Julio Tinti and Nithael Sampaio.*

In order for drug treatments to be successful it is essential that the patient follows the medical recommendations regarding drug intake, and their correct intake is known as drug adherence. Non-adherence to medication is a problem with repercussions that range from the danger to the lives of patients, to millionaire financial losses for governments and health systems. One way to tackle this problem in a smaller scope is to use automated medication organizers, but these are devices with a high acquisition cost. Thus, the main objective of the present work is to develop the prototype of a low-cost automated medication organizer to aid in medication adherence, with a main focus on the elderly public. 
The methodology used consists of the integration of different concepts for the elaboration of a functional prototype, which should allow the automated organization of medicines programmed by a user via a
Web application. The pillars of this integration will be Web programming, use of microcontrollers, 3D modeling and additive manufacturing. From these pillars, a mechanism was designed, driven by a servo motor and a stepper motor, which stores and separates the medicines previously placed in the device at the right times and doses. 
The 3D printing of the model, together with the control of the motors (movement mechanism) and integration with the Web App, which was done using an ESP32, validate the objective of the project, resulting in a proof of concept of an automated drug organizer with cost below the average market price. With the final prototype the user is able to eparate their medicines, program their doses, and receive them at the right time, in a safe way, with the appropriate alarms to remind them to take the pills. 

**Tech contributions:**

- **Python**
- **Flask**
- **AWS RDS**
- **Heroku**
- **Arduino**

## Compressor Monitoring <a name="paragraph2"></a>
*This project was presented to a college subject at Universidade Tecnológica Federal do Paraná. Project developed by Lucas Moletta, Flávio Neto, Julio Tinti and Gustavo Raimundo.*

The proposed project aimed to provide extra context to the air compressor usage at the college campus. Professor Celso Salamon pointed out that the university's air compressor was not functioning properly, consuming more energy than necessary and requiring maintenance hundreds of hours earlier than expected.
This problem is closely related to the use of data for maintenance and studying the malfunction of a machine. Therefore, this work falls within the scope of Industry 4.0 and has the ability to put machine information in the cloud for monitoring and data analytics.
After identifying the problem, the team discussed the project requirements with the professor to deliver a more suitable solution. 
**Hence, the requirements are as follows:**

- Visual signaling for problem communication.
- Sending an email to the responsible professors when an issue occurs.
- Analysis of the compressor's voltage and current data.
  
**Proposed Solution:**
Given the problem and client's requirements, the proposed solution consists of acquiring compressor data, transmitting it to a microcontroller, and using Node-RED script to store this information in a MySQL database. Additionally, if any anomalies in the compressor's operation are detected, Node-RED will send an email to the responsible professors while activating the visual signaling. Moreover, there will be a graphical display that reads the database and presents temporal information on a dashboard. This solution will help understand the issues occurring in the university's compressor.

**Tech contributions:**

- **Python**
- **Streamlit**
- **Azure**
- **Node-RED**
- **JavaScript**
- **SQL**
- **Raspberry PI**
- **ESP32**