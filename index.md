---
title: Home
---

# Information

EGR314 Spring 2023  
Professor Aukes  
Team 204  
Members:  
Nicholas C. Dunn  
Eduardo Lopez  
Richard Green

# Table of Contents
* [Introduction](https://egr314-team204.github.io/#introduction-team-204-semester-project)
* [Team Organization](https://egr314-team204.github.io/#team-organization)
* [User Needs, Benchmarking and Requirements](https://egr314-team204.github.io/#user-needs-benchmarking-and-requirements)
* [Design Ideation](https://egr314-team204.github.io/#design-ideation)
* [Presentation](https://egr314-team204.github.io/#presentation)
* [Selecting Our Design](https://egr314-team204.github.io/#selecting-our-design)
* [Block Diagram](https://egr314-team204.github.io/#block-diagram)
* [Component and Microcontroller Selection](https://egr314-team204.github.io/#component-and-microcontroller-selection)
* [Software and Hardware Proposal](https://egr314-team204.github.io/#hardware-and-software-proposal)



## Introduction: Team 204 Semester Project  
Our team has been tasked with creating a weather station that can sense the environment around us with the implementation of a controlled response. We decided on the idea to create a product that will sense the environment of a terrarium to control the climate inside. We will be utilizing a temperature sensor and motor with a fan balde connected that will be turned on and off based on the temperature inside utilizing a PIC microcontroller. As a team, we will use our knowledge gained from this semester to plan, design, and manufacture a printed circuit board that will combine our individual subsystems to work together. As we move along further in the semester we will document our work on how we came up with our design and every piece of information we have pertaining to our project. As of right now, we are currently working on individual PCBs for our subsystems to make sure they work and if they don’t we can fix any mistakes before we design our team board.  
  
  
## Team Organization
Our team recognizes the value of this product design and development class as an opportunity to gain hands-on experience in product design, development, and teamwork. Therefore, we agreed to develop a team charter that outlines our goals and objectives for this class. Our team charter includes the following elements:  
* Developing a product that meets the needs of our target market.
* Gaining hands-on experience in the product design process.
* Leveraging our skills and knowledge in embedded systems to design and develop a cutting-edge product that satisfies user needs.
* earning how to work effectively as a team and communicate effectively with team members and stakeholders.  
  
We also recognize that success in this project and product design process can take many forms, such as eventually selling units of a product, better demonstrating our knowledge to others, developing a new, mind-blowing addition to our portfolio of engineering expertise, furthering our passions, and making new professional connections. Our primary goal is to gain valuable skills and knowledge through this product design experience, which we can apply to our future careers.  
  
To agree on our team charter, we held a meeting where we discussed our individual goals and objectives for this class. We then synthesized our individual goals and objectives to create a comprehensive team charter that aligned with the course requirements and our personal aspirations.  
  
To guide our team through the product design process, we developed a mission statement that outlines the purpose of our project. Our mission statement is as follows:
"The mission of our team is to successfully brainstorm and develop a product that can measure an aspect of the environment around us and communicate the data received through the internet to the end-user."  
  
We developed our mission statement through a brainstorming session where we discussed the purpose and objectives of our product. We identified the need for a product that can measure environmental aspects and communicate the data to the end-user. Therefore, we developed our mission statement to reflect this purpose.  
  
* [Link to Team Organization Page](/TeamOrg)
  
  
## User Needs, Benchmarking, and Requirements  

We started to gather user needs based on how we want our product to perform when in use. We generated about 60 user needs that include ease of use, replaceable parts, custom alerts and notifications just name a few. We continued our research by using keywords related to our product to find similar products on the market and gather reviews from users of that product. From those reviews we found that the consumers really like a sturdy reliable product with a large display and easy to use software. We then grouped our list of user needs together based on user preferences, system preferences, safety, durability, and marketing. This gave us a good idea of what the customer values in a product and we reflected that by prioritizing safety measures in our product.  
  
We strive to reach every aspect we defined through this research. We are prioritizing safety because that is always most important when dealing with electronics. For the hardware design we want to have a compact design that can withstand the elements while being cost efficient for the customer. The functionality and software of the product should be compatible with an application on a smart phone to monitor the sensors accompanied by a physical display that clearly shows the data received. Ideally we want to create a user experience that is stress free with clear and concise instructions that allow the user to use and maintain the product easily. We also want the user to be able to customize their device to meet their specific needs and the ability for the device to be used anywhere. The materials used in manufacturing should be cost effective without compromising quality but also can be recycled if need be. Finally safety is our number 1 priority. We want to avoid risk to the user by taking the precautions in manufacturing but also adding warning labels and instructions on how to operate the device safely.  
  
* [Link to User Needs, Benchmarking, and Requirements Page](/UserNeed)
  
  
## Design Ideation
When designing our project, we needed to take into consideration many more ideas than the required project parameters. For instance, the product would be worthless if it caused harm to the user. With this in mind, we proceeded to create Jamboards. Jamboards are an online version of a wall of sticky notes, a place where we throw every conceivable point, idea, requirement and thought onto a page.  
  
After doing this, our team member Richie went through the hundreds of notes and compiled them together. Removing repeated statements and combining very similar ones, he reduced the absurd number of notes into a manageable amount.  
  
Once Richie was done with compiling, it was Eddie’s turn to work. He sorted through each of the notes and stacked them based on a subject that each needed to go with. An example of this would be when he put anything to do with safety in the pile labeled “safety”.  
  
When Eddie was finished, Nick went through and ranked each pile depending on how prevalent, necessary or required it was. Needless to say, project requirements and safety of the user/maker were among the highest ranked.  
  
After we had finished this process, we each generated our own concepts. Richie made a weather system helmet, Eddie thought of an irrigation system, and Nick created a reptile habitat monitoring system. Through a few hours of discussion, we decided to go with the reptile habitat, as it seemed to be the most feasible of the ideas generated for us to work on.  
  
* [Link to Ideation Page](/Ideation)

## Presentation
 
* [External Link here](https://www.youtube.com/watch?v=ebKb8as0qI8)  
  
  
  
# Our Design

## Selecting Our Design  
<img src="./media/media/image1.png" style="width:6.5in;height:3.28611in" alt="Diagram Description automatically generated" />    

## Block Diagram
  
With a team of 3 members, our project requirements were reduced to a single motor subsystem, a single weather related sensor, and the primary microcontroller. Each member took a subsystem, and constant communication between us has been crucial in deciding steps for each.  
  
Richie took the temperature sensor. This satisfies the project requirements as it will be able to detect changes in the outside world, and then relay changing data to the microcontroller to be displayed.  
  
Eddie has the hardest subsystem of all: the microcontroller. This is the primary brain of our device and is essential for the other 2 subsystems to work. It will read the data produced by the above sensor and display it.  
  
Nick defaulted to the final available subsystem, the motor. In order to satisfy project requirements a motor controller was needed to control it. This communicates with the microcontroller, and will change it’s speed depending on the variables received from the temperature sensor through the microcontroller.
  
<PINGE.png>

  
  
## Component and Microcontroller Selection  
Temperature Sensor: The LM90CIMM/NOPB temperature sensor was chosen for our design due to its high accuracy, low power consumption, and small form factor. With an accuracy of ±0.5°C over a temperature range of -55°C to +150°C, this sensor meets our requirements for precise temperature measurement. Its low power consumption also makes it ideal for power management, and its small form factor allows for easy integration into our product design. Additionally, the LM90CIMM/NOPB has a digital output that makes communication with our microcontroller possible, simplifying our design process. Overall, the LM90CIMM/NOPB temperature sensor is a reliable and efficient choice for our environment sensing needs.  
  
Motor Driver: The IFX9201SG motor driver was selected for our design due to its high efficiency, low power consumption, and compact size. This motor driver is capable of driving a single DC motor or two DC motors in parallel, making it versatile for our needs. Its advanced MOSFET technology allows for high efficiency, reducing power consumption and heat dissipation. Additionally, the IFX9201SG motor driver has built-in protection features such as overcurrent and overtemperature protection, ensuring the safety and longevity of our motor and driver. Its small form factor also allows for easy integration into our product design. Overall, the IFX9201SG motor driver is a reliable and efficient choice for driving our DC motor(s).  
  
Motor: The DC motor kit that includes 6 motors was selected for our design due to its high quality, durability, and compatibility with our motor driver. These motors have a rated voltage of 3-12V, making them compatible with our switching power source. Their high torque and low noise make them suitable for a variety of applications, including robotics and automation. The motors also have a long lifespan, reducing the need for frequent replacement. Additionally, the motors in this kit are compatible with the IFX9201SG motor driver we selected, allowing for easy integration into our design. Overall, the DC motor kit is a reliable and versatile choice for our motor needs.  
  
Microcontroller: The PIC18F27J53 microcontroller was chosen for our design due to its high processing power, versatility, and low power consumption. With a clock speed of up to 48 MHz, this microcontroller can handle complex tasks and algorithms with ease. Its versatile architecture and large memory capacity make it suitable for a wide range of applications, including control systems, data acquisition, and communication interfaces. It also has built-in communication interfaces, including modules for SPI, I2C, UART, USB and Ethernet, which simplify our design process. Additionally, this PIC has 28-pins which leaves plenty of GPIO's after our serial communication channels are already connected. Overall, the PIC18F27J53 microcontroller is a reliable and efficient choice for our embedded system needs. 
  
* [Link to Component Selection](/ComponentSelect)
  
* [Link to Microcontroller Selection](/MicroSelect)

## Hardware and Software Proposal

* [Link to Hardware Proposal](/Schem)
  
* [Link to Software Proposal](/Software)




# Other website format resources
  
## Background

![image caption]
<img src="./media/media/image1.png" style="width:5.51299in;height:9.62264in" />

[link to background](/background)

## Results

1. Numbered Point 1
1. Numbered Point 2
1. Numbered Point 3

## Conclusions and Future Work

## External Links

* [example link to idealab](https://idealab.asu.edu)


## References
