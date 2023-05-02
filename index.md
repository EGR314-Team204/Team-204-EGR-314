---
title: Home
---

# Information

EGR314 Spring 2023  
Professor Aukes  
Team 204  
Members:    
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
* [System Verification](https://egr314-team204.github.io/#system-verification)
* [Lessons Learned](https://egr314-team204.github.io/#lessons-learned)
* [Recommendations for future students](https://egr314-team204.github.io/#recommendations-for-future-students)

## Introduction: Team 204 Semester Project  
Our team has been tasked with creating a weather station that can sense the environment around us with the implementation of a controlled response. We decided on the idea to create a product that will sense the environment of a terrarium to control the climate inside. We will be using a temperature sensor utilizing a PIC microcontroller and ESP32. As a team, we will use our knowledge gained from this semester to plan, design, and manufacture a printed circuit board that will combine our individual subsystems to work together. As we move along further in the semester we will document our work on how we came up with our design and every piece of information we have pertaining to our project. As of right now, we are currently working on individual PCBs for our subsystems to make sure they work and if they don’t we can fix any mistakes before we design our team board.  
  
  
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
  
## Product Requirements 

Product Design-

i. Design optimizes space <br>
ii. Design will be able to withstand harsh outdoor conditions and be weather-resistant <br>
iii. Cost efficient for the consumer <br>
iv. Compact for portability <br>

Functionality/ Software-

i. Mobile app control, allows the user to adjust settings and monitor the system remotely via a mobile app or internet connection <br>
ii. System utilizes a sensor to monitor temperature <br>
iii. Data will be transmitted to internet <br>

Interactivity/ User experience-

i. Device setup is easy <br>
ii. Usage of device and interface is straight forward <br>
iii. Maintenance is basic or non existent <br>

Customization-

i. The user is able to adjust the sensitivity of the environmental sensors to match their specific needs <br>
ii. The user is able to modify the displayed outputs to visualize the data they need <br>

Manufacturing-

i. Is designed to be recycled or reused <br>
ii. Materials are cost efficient without compromising quality <br>
iii. Materials are durable and have longevity <br>
iv. Quality materials are used when necessary <br>

Safety-

i. The overall product is designed in a way that avoids risk to the user <br>
ii. Exclusion/reduction of materials that are potentially hazardous <br>
iii. Space for any warning labels/details <br>

## Design Ideation
When designing our project, we needed to take into consideration many more ideas than the required project parameters. For instance, the product would be worthless if it caused harm to the user. With this in mind, we proceeded to create Jamboards. Jamboards are an online version of a wall of sticky notes, a place where we throw every conceivable point, idea, requirement and thought onto a page.  
  
After doing this, we went through the hundreds of notes and compiled them together. Removing repeated statements and combining very similar ones, we reduced the absurd number of notes into a manageable amount.  
  
Once we were done with compiling, it was time to sort through each of the notes and stack them based on a subject that each needed to go with. An example of this would be when he put anything to do with safety in the pile labeled “safety”.  
  
When we were finished, we then went through and ranked each pile depending on how prevalent, necessary or required it was. Needless to say, project requirements and safety of the user/maker were among the highest ranked.  
  
After we had finished this process, we generated a couple concepts. Including a weather system helmet, an automated irrigation system and a reptile habitat monitoring system. Through a few hours of discussion, we decided to go with the reptile habitat, as it seemed to be the most feasible of the ideas generated for us to work on.  
  
* [Link to Ideation Page](/Ideation)

## Presentation
 *[https://www.youtube.com/watch?v=ebKb8as0qI8](https://www.youtube.com/watch?v=ebKb8as0qI8)
  

## Selecting Our Design  
![Final Concept](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/314_Concept.png?raw=true)

This Reptile Habitat idea was the most sensible choice for our project. The idea allows us to satisfy all course and user based requirements with room for addition beyond just the course requirements. The design has a variety of options that could be integrated into it like mutliple environemnt sensors, an actuator, and wifi capabilties for remote monitoring. As a proof of concept and with limited team members the temperature sensor and microcontroller were the decided susbsytems to create the base for this idea, the one thing that changed from the ideation is the motor subsystem which was dropped.

## Block Diagram
  
With a team of 2 members, our project requirements were reduced to a single weather related sensor, and the primary microcontroller. Both members took a subsystem, and constant communication between us has been crucial in deciding steps for each.  
  
Richie took the temperature sensor. This satisfies the project requirements as it will be able to detect changes in the outside world, and then relay changing data to the microcontroller to be displayed.  
  
Eddie has the microcontroller. This is the primary brain of our device and is essential for the other subsystems to work. It will read the data produced by the above sensor and display it.  

![BlockDiagram](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204BlockDiagram.png?raw=true)

  
  
## Component and Microcontroller Selection  
Temperature Sensor: The TC74A4 temperature sensor was chosen for our design due to its high accuracy, low power consumption, and small form factor. With an accuracy of ±0.5°C over a temperature range of -55°C to +150°C, this sensor meets our requirements for precise temperature measurement. Its low power consumption also makes it ideal for power management, and its small form factor allows for easy integration into our product design. Additionally, the TC74A4 has a digital output that makes communication with our microcontroller possible, simplifying our design process. Overall, this temperature sensor is a reliable and efficient choice for our environment sensing needs.  
 
Microcontroller: The PIC18F27J53 microcontroller was chosen for our design due to its high processing power, versatility, and low power consumption. With a clock speed of up to 48 MHz, this microcontroller can handle complex tasks and algorithms with ease. Its versatile architecture and large memory capacity make it suitable for a wide range of applications, including control systems, data acquisition, and communication interfaces. It also has built-in communication interfaces, including modules for SPI, I2C, UART, USB and Ethernet, which simplify our design process. Additionally, this PIC has 28-pins which leaves plenty of GPIO's after our serial communication channels are already connected. Overall, the PIC18F27J53 microcontroller is a reliable and efficient choice for our embedded system needs. 

![powerBudget](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204PowerBudget.png?raw=true)

The Power Budget was a tool we used to document and calculate our power needs. We listed our components and their current and voltage needs in their respective power rails, typically for more complex projects there can be multiple power rails, luckily for ours there is only one which is the 3.3V rail which represents our 3.3V switching voltage regulator. To ensure we are not drawing more current than the regulator can handle we calculated the max current that could be drawn from our subsytems and compared it against the max output current of the voltage regulator with a 25% safety margin. As seen in the power budget above we were well under that limit.

* [Link to Component Selection](/ComponentSelect)
  
* [Link to Microcontroller Selection](/MicroSelect)

* [Power Budget](https://docs.google.com/spreadsheets/d/1ZWJujIUSddGSwfPPaxeSsj4ZDpHQYlIZ/edit#gid=2120733341)

## Hardware and Software Implementation

![hardwareProp](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204Schematic.png?raw=true)

The above schematic is essential to satisfying user needs and product requirements. It provides a clear and concise visualization of the circuit, which is especially helpful for us to understand how the circuit works and how it can be optimized. It helps determine the function of each component and how they are connected together, which can help to ensure that the circuit meets the desired product requirements. As seen in the schematic the TC74 and ESP32 satisfy user requirements by sensing the surrounding environments temperature and relaying to the internet to be remotely monitered by the user. Which of course is made possible by the voltage regulator circuit providing adequate wall power to all components. As well as the microcontroller which runs the desired program for the design and oversees operation of the other subsystems.

![PCBDesign](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204PCBDesign.png?raw=true)

![PCBfront](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204PCB.png?raw=true)

![PCBback](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204PCBback.png?raw=true)

Version 2.0 Hardware "what if":
As we look to the future and the possibility of a version 2.0 of our hardware design, there are a few key areas that we would like to address. First and foremost, we want to ensure that all the pins are connected correctly. In the previous iteration of our design, we had to resort to using jumper wires on the final board to compensate for some pin connectivity issues. This was less than ideal, and we want to avoid it in the future. To that end, we plan to thoroughly review and test the pin connections before moving forward with any additional design work. We want to be certain that everything is in order before proceeding to avoid any unnecessary complications down the line. In addition to addressing the pin connectivity, we also want to expand the capabilities of our design by adding more peripherals. Specifically, we're interested in incorporating a fan and a humidity sensor. These additions will enable the project to more accurately simulate real-world environmental conditions, which is a key aspect of our overall objective. Lastly, we are aware that there were some footprint errors in the previous iteration of our design that were not resolved. We plan to prioritize the resolution of these errors before making any other modifications. By doing so, we can ensure that our subsequent design work is built on a solid foundation, and that any further changes or improvements are made with complete confidence in the underlying structure of the design.

![softwareProp](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204Software.png?raw=true)

The code and flow for our software is fairly simple due to utilizing only 1 sensor for our final project. The TC74 temperature sensor communicates through I2C and then transmits that data to an ESP32 over UART and finally prints to the MQTT wifi server. Unfortunately we did not get to implement an interrupt and bidirectional communication into our project due to time constraints.

5 Biggest Changes to software: 

1. Removal of our actuator subsystem
2. Initially the software included 1 interrupt but due to time constraints it was removed
3. A push button also did not get implemented into the final software 
4. Did not pursue interactivity function on MQTT(Bidirectional MQTT communication)
5. Removed one LED blinking while loop, only utilized one LED

Version 2.0 Software "what if":
If we were to create a version 2 of our software design, we would prioritize several key improvements to the existing code. Specifically, we would like to implement interrupts between a fan, temperature sensor, humidity sensor, and LEDs. Doing so would allow for more efficient and reliable communication between these different components, resulting in a more streamlined and effective system overall. In the previous iteration of our software, we were not able to implement these interrupts due to time constraints and limited resources. However, with a new version of the software, we would have the opportunity to allocate more time and resources to these critical aspects of the design. In addition to implementing interrupts, we would also like to dive into the code itself and ensure that we have robust debugging LEDs and other functions to verify that the software is working as intended. This would help us to identify any issues or errors more quickly and accurately, minimizing downtime and maximizing productivity. Another area where we see potential for improvement is in the user interface. Specifically, we would like to implement multiple pushbuttons and an LCD display to enhance the device's overall usability and functionality. By incorporating these features, we could provide users with more options and greater control over the device's operation, which would be particularly useful in more complex applications. Overall, we believe that these changes would significantly enhance the performance, reliability, and user-friendliness of our software design.

## System Verification 

![SystemVerification](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204Verification.png?raw=true)

## Lessons Learned

Throughout the term, our team learned a lot about various aspects of our project, including working with Github, surface mount soldering, microcontroller selection, I2C communication, MQTT wifi capabilities, teamwork and commitment, the ESP32 component, effective communication, testing, and time management. We found that working with Github was interesting and useful for future projects, as it allowed us to collaborate efficiently and manage our project in an organized way. Surface mount soldering was challenging but taught us the importance of patience and attention to detail. Selecting the right microcontroller and thoroughly researching project specifications before making decisions saved us time and prevented delays. Coding in I2C was initially challenging, but it allowed us to communicate between components with ease. Adding MQTT wifi capabilities was a highlight of the project and taught us the value of persistence. Effective communication was crucial for project success, and we learned to listen actively, ask questions, and share ideas openly. Testing the project thoroughly before presenting it helped us identify and fix any bugs or errors. Time management was critical, and we learned to prioritize tasks and set realistic deadlines to complete the project on time and to a high standard.

## Recommendations for future students 

1. Always visit office hours for troubleshooting or getting help with assignments, do not be afraid to ask questions until you understand<br>
2. Coordinate assignments and action plans with your team memebers well in advance to a deadline so that the quality of work is not degraded<br>
3. Familiarize yourself with cadence as much as you can and even mock up assignments early so that when it comes time to design it is easier on you and any possible fluke issues can be handled well in advance<br>
4. When it comes to team conflict always be professional and try to internally resolve problems, if that is unsuccessful approach the professor for a conflict resolution<br>
5. Be nice to Professor Aukes and the teaching team they want to help you succeed, but it is harder if you are being a jerk<br>

## Appendix A Bill of Materials

![BOM](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204BOM.png?raw=true)

## Appendix B MQTT Topic Table

![MQTT](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204MQTT.png?raw=true)

## Appendix C MPLabX main.c code 
#include "mcc_generated_files/mcc.h" <br>
#include "mcc_generated_files/examples/i2c1_master_example.h" <br>
#include <stdio.h> <br>
#include <stdlib.h> <br>
#define address 0x4C <br>
#define tempreg 0x00 <br>
 uint8_t temp; <br>
 
 

void getTemp() <br>
{ <br>
    temp = I2C1_Read1ByteRegister(address, tempreg); <br>
    printf("Temperature in Degrees Celsius = %d\r\n", temp); <br>
    //EUSART2_Write(temp); <br>
    LED2_Toggle(); <br>
    delay_ms(200); <br>
} <br>
//char str[80]; <br>
uint8_t rx1Data; <br>

void ISR1(void) <br>

{ <br>
    EUSART2_Receive_ISR(); <br>
    if (EUSART2_is_rx_ready()) <br>
    { <br>
        rx1Data = EUSART2_Read(); <br>
        printf("temp = %d\r", rx1Data); <br>
        LED1_Toggle(); <br>
    } <br>
      //  if (EUSART1_is_tx_ready()) <br>
      //  { <br>
       //     EUSART1_Write(rx1Data); <br>

        //} <br>

    } <br>
 
 
void main(void) <br>
{ <br>
    // Initialize the device <br>
    SYSTEM_Initialize(); <br>
    I2C1_Initialize(); <br>
    EUSART1_Initialize(); <br>
    //EUSART1_Initialize(); <br>

    //EUSART2_SetRxInterruptHandler(getTemp); <br>


    // Enable the Global Interrupts <br>
    INTERRUPT_GlobalInterruptEnable(); <br>
    // Enable the Peripheral Interrupts <br>
    INTERRUPT_PeripheralInterruptEnable(); <br>

    //EUSART2_SetRxInterruptHandler(EUSART2_ISR_callback); <br>
    EUSART2_SetRxInterruptHandler(ISR1); <br>


    //getTemp(); <br>
    while (1) <br>
    { <br>
        getTemp(); <br>


       // ISR1(); <br>




} <br>
} <br>





    /*while (PORTCbits.RC0 != 0) // Keep blinking LED until Jumper is low <br>
            { <br>
        LED2_SetHigh(); // Turn on LED <br>
        delay_ms(500); <br>
        LED2_SetLow(); // Turn off LED <br>
        __delay_ms(500); <br>
        } <br>
            LED2_SetLow(); // Turn off LED when Jumper is low <br>


}*/ <br>

## Appendix D MCC Configuration

![MCC](https://github.com/EGR314-Team204/egr314-team204.github.io/blob/main/media/media/Team204MCC.png?raw=true)
