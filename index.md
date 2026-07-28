# Automated Cat Laser
To help my cats stay active, lose weight, and remain mentally stimulated while I am away from home, I designed and built an **Automated Cat Laser**. The system consists of a two-degree-of-freedom pan-and-tilt mechanism driven by two SG90 servo motors, allowing a laser module to rotate independently along the X and Y axes. An Arduino Nano controls the servos by generating PWM (Pulse Width Modulation) signals, causing the laser to move through a series of randomized positions and timed pauses that simulate the unpredictable movement of prey. The mechanical assembly was designed in CAD and fabricated using 3D-printed components that securely mount the servos and laser while maintaining proper alignment. By integrating mechanical design, embedded programming, electronics, and additive manufacturing, the project creates an autonomous laser system that encourages exercise and provides environmental enrichment for indoor cats.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Eason Z | Challenger Almaden | Mechanical Engineering | Incoming 8th Grader |

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)

# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Description
For my third and final milestone, I focused on transforming the working prototype into a polished and reliable finished product. While the previous milestone successfully demonstrated that the automated cat laser could function, several components still needed improvement. Some of the 3D-printed parts required sanding before assembly, the electronics were exposed, and the laser module lacked a secure enclosure. Rather than simply leaving the prototype as it was, I redesigned multiple components to improve the system's durability, appearance, and overall reliability.
One of the biggest improvements was creating a custom enclosure for the electronics. Earlier versions of the project had the Arduino Nano, soldered PCB, wiring, and battery connector exposed, making the electronics vulnerable to accidental damage and making the project look unfinished. To solve this problem, I designed a protective case in CAD that completely enclosed the electronics while still allowing access to the USB port for uploading code and openings for the battery cable and servo wires.
Designing the enclosure required much more planning than simply drawing a box around the electronics. I carefully measured the dimensions of every component, including the Arduino Nano, PCB, jumper wires, battery connector, and mounting hardware. The case also had to provide enough clearance for solder joints and wire bends while remaining compact. After completing the CAD model, I printed several prototypes and adjusted the dimensions until every component fit securely without excessive force.
I also designed a dedicated enclosure for the laser module. Earlier in the project, the laser was attached directly to the servo mount, leaving it exposed and allowing small amounts of movement during operation. To improve both stability and appearance, I created a custom housing that held the laser tightly while keeping it precisely aligned with the servo horn. The enclosure reduced unwanted vibration, protected the laser from accidental impacts, and produced a cleaner overall design.
Another major improvement involved redesigning the second servo mount. Earlier versions of the mount functioned correctly but often required sanding before assembly because the tolerances were too tight. Instead of making small adjustments to the existing design, I completely remodeled the part using more accurate measurements of the SG90 servo horn and spline geometry. I adjusted the wall thickness, mounting clearances, and overall dimensions to improve both strength and fit.
While redesigning the mount, I also reinforced several areas that experienced the greatest mechanical stress during operation. Because the upper servo and laser assembly are constantly accelerating and changing direction, these areas experience repeated loading that can eventually weaken printed plastic. By adding additional material around the mounting platform and support structure, I increased the rigidity of the assembly and reduced unwanted flexing while the servos were moving.
As a finishing touch, I incorporated a custom logo directly into the CAD model. Although this modification did not affect the performance of the project, it gave the final assembly a much more professional appearance and allowed me to practice more advanced CAD modeling techniques.
After completing all of the redesigned parts, I assembled the entire system and performed final testing. I verified that both servos moved smoothly across their full operating range, confirmed that the laser remained securely aligned throughout operation, and ensured that the electronics stayed safely enclosed while the project was running. By the end of the milestone, the automated cat laser had evolved from an early prototype into a durable and polished engineering project that combined mechanical design, electronics, programming, and additive manufacturing into one complete system.
## Challenges
### Redesigning Parts for Proper Fit
The biggest challenge during this milestone was redesigning components until they fit correctly. Although the CAD models appeared accurate on the computer, small dimensional differences introduced during 3D printing often prevented the printed parts from fitting together properly. In many cases, errors of only a few tenths of a millimeter were enough to prevent a servo from sliding into its mount or a screw from aligning with its hole.
Rather than forcing the components together, I repeatedly measured the printed parts, modified the CAD files, and printed new versions. This iterative design process required patience, but it taught me that engineering design rarely succeeds on the first attempt. Every prototype revealed small improvements that could be made before producing the next version.
### Balancing Strength and Size
Another challenge involved balancing structural strength with overall size. If the walls of the printed parts were too thin, they flexed slightly as the servos accelerated and changed direction. However, increasing the wall thickness too much made the components heavier and increased printing time.
I experimented with different wall thicknesses, support structures, and reinforcement features until I found a design that was both lightweight and rigid. This helped me understand the trade-offs engineers often make between weight, strength, material usage, and manufacturing time.
### Designing the Electronics Enclosure
Creating the electronics enclosure also presented several challenges. The Arduino Nano, PCB, battery connector, jumper wires, and servo cables all occupied different amounts of space, and I had to account for each of them while designing the case. Even though the electronics themselves fit inside the enclosure, I also had to leave room for wire routing so that cables would not become pinched when the lid was attached.
Several early versions of the enclosure either left too little clearance or blocked access to important connectors. Each revision required careful measurements, modifications to the CAD model, and another print before arriving at a design that both protected the electronics and remained easy to assemble.
### Improving Overall Appearance
The final challenge was making the project look as polished as it functioned. Throughout earlier milestones, my focus had been getting everything to work correctly. During this milestone, I shifted my attention toward presentation by improving cable management, enclosing exposed components, refining the printed parts, and incorporating a custom logo into the design.
Although these improvements did not change how the laser operated, they made the final project appear much more professional and demonstrated the importance of considering aesthetics alongside functionality in engineering design.
## Conclusion
Completing the final milestone marked the successful completion of the Automated Cat Laser project. By combining CAD design, 3D printing, electronics, embedded programming, soldering, and mechanical assembly, I built an autonomous system capable of providing exercise and mental stimulation for indoor cats through realistic, randomized laser movement.
The project required constant testing, redesigning, troubleshooting, and refinement. Each obstacle, from designing servo mounts and troubleshooting Arduino hardware to creating custom enclosures and improving printed components, strengthened my understanding of the engineering design process. Instead of viewing failures as setbacks, I learned to treat each one as an opportunity to improve the design through careful analysis and iteration.
Looking back, one of the most rewarding aspects of the project was seeing a collection of individually designed components come together into a fully functioning system. Every redesign, every successful print, and every debugging session contributed to the final product. The experience not only improved my technical skills but also increased my confidence in approaching future engineering projects that combine mechanical design, electronics, and programming.

# What I Learned at BlueStamp Engineering
Throughout my time at BlueStamp Engineering, I learned that engineering is much more than simply building a project that works. Every successful design requires planning, testing, troubleshooting, redesigning, and continual improvement. While my original goal was to build an automated laser toy for my cats, the project ultimately became an opportunity to develop practical engineering skills across multiple disciplines, including mechanical design, electronics, programming, manufacturing, and problem solving.
One of the most valuable skills I developed was computer-aided design (CAD). Before beginning this project, I had only limited experience designing mechanical components. Throughout the program, I learned how to create accurate 3D models while considering real-world manufacturing constraints such as material thickness, assembly clearances, screw placement, and structural strength. I also discovered that designing a part on a computer is only the beginning of the engineering process. Even carefully measured CAD models often required multiple revisions because of manufacturing tolerances introduced during 3D printing. By repeatedly measuring printed parts, identifying dimensional errors, and modifying my designs, I gained a much stronger understanding of iterative engineering design.
I also learned a great deal about additive manufacturing through 3D printing. At first, I assumed that once a model was finished, printing it would produce a perfect part. Instead, I discovered that print orientation, tolerances, wall thickness, and material properties all influence the final result. Many of my parts required multiple prototypes before they fit correctly, teaching me that rapid prototyping is an essential part of modern engineering rather than a sign of failure.
Another important area of growth was electronics and soldering. Building the circuit required connecting the Arduino Nano, servo motors, laser module, power supply, and battery into a reliable electrical system. Throughout the project, I practiced soldering and desoldering components while learning how to create strong electrical and mechanical connections. Although my first solder joints were inconsistent, repeated practice significantly improved both the quality and reliability of my work. I also became much more comfortable reading wiring diagrams, routing electrical connections, and identifying problems caused by poor electrical contact.
Programming the Arduino introduced me to embedded systems and hardware control. Using C++, I learned how software directly interacts with physical devices through digital outputs and Pulse Width Modulation (PWM). Rather than writing programs that only display information on a screen, I wrote code that controlled motors, generated randomized motion, and coordinated multiple hardware components simultaneously. This experience helped me understand how programming can be used to solve real engineering problems by controlling physical systems.
Perhaps the greatest lesson I learned was the importance of troubleshooting. Nearly every stage of the project presented unexpected obstacles, including incompatible servo mounts, defective power modules, Arduino driver issues, incorrect soldering, and mechanical tolerances that prevented printed parts from fitting together. Instead of becoming discouraged, I learned to isolate problems, test one subsystem at a time, and systematically eliminate possible causes until I found the correct solution. This logical approach allowed me to solve problems much more efficiently and showed me that debugging is one of the most important skills an engineer can develop.
One of my proudest accomplishments was successfully integrating every subsystem into a single working project. The finished automated cat laser combined mechanical engineering, electrical engineering, programming, and manufacturing into one autonomous device capable of operating without user input. Seeing the completed project function reliably after weeks of designing, printing, wiring, programming, and troubleshooting was one of the most rewarding experiences of the program.
Beyond the technical skills, BlueStamp Engineering also strengthened my confidence as an engineer. At the beginning of the program, many of the tools and technologies were unfamiliar to me. By the end, I had independently designed custom mechanical parts, assembled electronic circuits, programmed a microcontroller, solved numerous hardware and software problems, and produced a finished engineering project that successfully met its design goals. The experience taught me that persistence, careful observation, and continual improvement are just as important as technical knowledge.
In the future, I hope to continue expanding my engineering skills by learning more advanced CAD techniques, improving my programming abilities in C++ and Python, and exploring more powerful embedded systems such as the Raspberry Pi. I am also interested in designing more mechanically complex projects that combine sensors, motors, computer vision, and artificial intelligence. BlueStamp Engineering has given me a strong foundation in the engineering design process and has inspired me to pursue increasingly ambitious projects in the future.

# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Description
For my second milestone, I focused on bringing the project to life by programming the Arduino Nano and integrating all of the electronic components into a fully functional automated system. While the first milestone concentrated on designing and assembling the mechanical structure, this stage centered on making the servos move automatically so the laser could simulate the unpredictable movements of prey. This milestone required combining embedded programming, electrical wiring, power management, and hardware troubleshooting before the system could operate reliably.
To begin, I uploaded code to the Arduino Nano that controlled two SG90 servo motors using the Arduino Servo library. Rather than moving the servos in a fixed pattern, the program continuously generated random X and Y coordinates within preset limits. These coordinates represented the next location where the laser would move. To make the movement appear natural, the code calculated intermediate positions between the current and target coordinates instead of instantly jumping from one location to another. This produced smooth, continuous motion that more closely resembled the movements of insects or small animals.
Another important feature of the program was its use of randomized pause times. After each movement, the laser remained stationary for a random amount of time before moving again. This prevented the laser from moving at a constant speed or rhythm, making its behavior much less predictable. Because cats are naturally attracted to sudden, irregular movement, these pauses helped make the toy more engaging.
After confirming that the software functioned correctly, I connected both servos to the Arduino Nano and soldered the components onto a solderable PCB. The Arduino generated Pulse Width Modulation (PWM) signals on two digital output pins, while a separate power supply provided enough current for the servos to operate. During testing, I repeatedly adjusted the servo angle limits stored in the program so the laser stayed within the desired play area while avoiding mechanical interference between the servos.
One of the most useful parts of this milestone was learning how software and hardware affect one another. Small adjustments in the code could completely change the behavior of the mechanism, while wiring problems or insufficient power could cause the software to appear broken even when the code itself was correct. This milestone helped me understand that successful engineering projects require every subsystem to function together rather than independently.
By the end of the milestone, the Arduino successfully controlled both servos, allowing the laser to move automatically through randomized positions without user input. Although the project still needed cosmetic improvements and better mounting hardware, the core functionality of the automated cat laser had been completed.
## How It Works
### Arduino Nano
The Arduino Nano serves as the "brain" of the project. It is a compact microcontroller board based on the ATmega328P that executes the uploaded C++ program and controls all of the electronic components.
After the program starts, the Arduino continuously generates random target positions for both servos. It then calculates a series of smaller movements that gradually rotate each servo toward the target angle. Instead of instantly jumping to a new position, the Arduino updates the servo positions many times per second, producing smooth motion.
The Arduino also controls how long the laser pauses between movements. Using the built-in random() function, it selects both a new destination and a random delay before repeating the process. This allows the laser to behave differently every time the project runs.
### Pulse Width Modulation (PWM)
The servos are controlled using Pulse Width Modulation, commonly known as PWM. Rather than changing the voltage supplied to the servo, the Arduino repeatedly sends electrical pulses. The width of each pulse tells the servo what angle it should rotate to.
The Servo library automatically generates these pulses approximately every 20 milliseconds. As the pulse width changes, the servo's internal electronics rotate the output shaft until it reaches the requested position. Because each servo continuously compares its current position with the commanded position, it can accurately hold its angle while supporting the weight of the laser assembly.
### Randomized Motion Algorithm
One of the most important parts of the project is the algorithm that determines where the laser moves. Instead of choosing completely unrestricted positions, the code limits movement to predefined X and Y angle ranges. These limits prevent the servos from rotating beyond their safe operating range or causing the laser to point outside the intended play area.
The program also checks that each new position is far enough away from the previous one. If the new target is too close, it automatically adjusts the coordinates to create a larger movement. This prevents tiny repetitive motions that would be less interesting for a cat and produces more noticeable, prey-like behavior.
## Challenges
### Uploading Code to the Arduino Nano
The biggest challenge I encountered during this milestone was uploading code to the Arduino Nano. My board was a clone rather than an official Arduino, so my computer initially failed to recognize it. Every attempt to upload the program resulted in communication errors, preventing the project from progressing.
I first checked the Arduino IDE settings to verify that the correct board and processor had been selected. When this did not solve the issue, I researched the problem and learned that many clone Arduino boards use a different USB-to-serial chip than official boards. Because of this difference, the board required an additional driver before the computer could communicate with it.
After installing the correct driver, the Arduino appeared correctly in the IDE, and I was finally able to upload my code successfully. This experience taught me that software installation can be just as important as hardware assembly when working with embedded systems.
### Power Supply Problems
Another major challenge involved supplying enough power for the servos. While the Arduino Nano could generate the PWM control signals, it could not safely provide enough current for two servos moving simultaneously.
To solve this problem, I added a dedicated 5V power module. Unfortunately, the module malfunctioned shortly after installation and prevented the servos from operating correctly. I initially believed the issue was caused by my wiring, so I spent time checking every connection with a multimeter before realizing the power module itself was defective.
### Repairing the Circuit Board
Once I determined the power module had failed, I attempted to remove it from the solderable breadboard by desoldering every connection. Because I was still developing my soldering skills, removing the large solder joints proved much more difficult than expected. Some joints refused to melt evenly, making it impossible to completely remove the module.
I then attempted to cut away the damaged section of the board so I could replace only the faulty component. Although this initially seemed like a reasonable solution, I realized halfway through that rebuilding the circuit on a different board would be easier than repairing the damaged one.
After transferring the components to a new solderable board, I accidentally soldered the Arduino Nano onto the wrong side of the PCB. This made routing the remaining wires significantly more difficult and complicated future soldering.
Rather than continuing with an awkward layout, I returned to the original board, which still functioned despite being partially cut. I finished assembling the circuit there instead and soldered a 9V battery connector so the project could operate independently from a computer. Although this process required considerably more time than expected, it greatly improved my soldering and troubleshooting skills.
## Learning Through Debugging
Throughout this milestone, I discovered that solving engineering problems often involves eliminating possibilities one at a time. Whenever something stopped working, I tested each subsystem individually, including the Arduino, servos, wiring, power supply, and software. Breaking the project into smaller sections made it much easier to isolate the true cause of each issue instead of guessing.
This systematic approach became one of the most valuable engineering skills I developed during the project.
## Next Step
For my final milestone, I plan to improve the overall quality and appearance of the project by redesigning several of the 3D-printed components. I will create protective enclosures for the electronics and laser module, redesign the second servo mount to improve its fit and strength, and add cosmetic improvements that make the project look more polished while increasing its durability. After completing these improvements, I will perform final testing to ensure the automated cat laser operates reliably over extended periods.

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Description
For my first milestone, I designed and built the mechanical structure that allows the laser to move in two degrees of freedom. The system uses two SG90 micro servo motors arranged in a pan-and-tilt configuration, allowing one servo to rotate the laser horizontally (X-axis) while the second servo, mounted on top of the first, rotates it vertically (Y-axis). This mechanism forms the foundation of the entire project because every later improvement depends on the laser being able to move smoothly and accurately.
The first step of this milestone was designing custom servo mounts using CAD software. Since commercially available brackets did not fit my design requirements, I created my own parts that would securely hold the servos while allowing them to rotate freely without interference. I designed one mount that attached directly to the base and another that connected the second servo to the horn of the first servo. Because the SG90 servo horn has a unique spline pattern and dimensions, I had to carefully measure its diameter, thickness, and mounting holes so the printed parts would fit correctly.
After completing the CAD models, I exported them as STL files and printed them on a 3D printer. Once the parts were finished printing, I assembled the mechanism by mounting the bottom servo to the base and attaching the second servo to the rotating horn of the first servo. This allowed the second servo to rotate together with the first, creating independent motion in both the horizontal and vertical directions.
The next step was attaching the laser module. Rather than gluing it directly onto the servo, I designed a mounting platform that allowed the laser to be secured using screws. This created a much stronger attachment while also making it easier to replace or adjust the laser if necessary. I carefully aligned the laser so that its beam remained centered as the servos rotated through their range of motion.
After assembling the mechanical system, I connected both servos to a solderable breadboard using male-to-male jumper wires. The Arduino Nano generated PWM (Pulse Width Modulation) signals that controlled each servo's angular position. Because two servos require more current than the Arduino can safely supply, I added an external 5V power module powered by a USB wall adapter. The Arduino still generated the control signals, while the external supply provided enough current for both servos to operate smoothly.
By the end of this milestone, I had successfully built a complete two-axis pan-and-tilt mechanism capable of moving the laser throughout a wide area. Although the laser was not yet moving automatically, the mechanical platform was complete and ready for programming during the next milestone.
## How It Works
### SG90 Servo Motors
The primary components of this milestone are the two SG90 micro servo motors. Unlike ordinary DC motors, servo motors rotate to a specific angle instead of spinning continuously. Each servo contains a DC motor, a gear reduction system, a position sensor (potentiometer), and an internal control circuit. The Arduino controls the servo by sending Pulse Width Modulation (PWM) signals, where the width of each pulse determines the desired angle.
Whenever the Arduino changes the PWM signal, the servo compares its current position to the commanded position using its internal potentiometer. If the positions do not match, the internal motor rotates until the error becomes zero. This closed-loop feedback system allows the servo to move accurately and hold its position even when supporting the weight of another servo or the laser module.
By mounting one servo on top of another, the system gains two independent axes of rotation. The lower servo controls left and right movement, while the upper servo controls up and down movement. Together, these allow the laser to point almost anywhere within the operating range.
### Laser Module
The project uses a KY-008 laser module to project a visible red laser beam. The module contains a semiconductor laser diode that emits coherent light when electrical current passes through it. Since the laser itself remains fixed to the second servo, every movement of the servo directly changes the direction of the laser beam.
Unlike a traditional laser pointer operated by hand, this system automatically changes the laser's position using software, allowing it to simulate the unpredictable movement of small animals or insects. These random movements encourage cats to chase the laser, providing both physical exercise and mental stimulation.
## Challenges
### Designing Accurate Servo Mounts
One of the first challenges I encountered was designing the servo mounts with the proper dimensions. Although CAD software allows extremely precise measurements, the printed parts often differed slightly from the digital model because of manufacturing tolerances in the 3D printer. Even an error of less than one millimeter could prevent the servo from fitting correctly.
The first version of my lower servo mount included an opening for the servo wires, but the hole was too small. Rather than redesigning it immediately, I attempted to cut the servo wires, thread them through the opening, and solder them back together afterward. Although this initially solved the problem, the repaired wires became unreliable and occasionally caused the servo to stop working correctly. I ultimately redesigned the mount with a much larger opening and reprinted the part, eliminating the need to modify the wires.
### Mounting the Second Servo
Attaching the second servo to the horn of the first servo proved to be much more difficult than expected. My original design placed the servo on a flat platform above the horn, but I accidentally modeled the mount using measurements from a different servo horn. As a result, the parts could not be assembled.
Rather than forcing the pieces together, I redesigned the mount so that the servo horn fit into a recessed pocket instead of sitting underneath a flat platform. This increased the contact area between the parts, making the assembly both stronger and easier to align. Even after redesigning it, the fit was still slightly too tight, so I carefully sanded the printed part until it rotated freely while remaining securely attached.
### Providing Enough Power
Another challenge appeared when testing the servos. Initially, I attempted to power everything directly from the Arduino Nano. Although the Arduino could control the servos, it could not provide enough current for both motors to move at the same time. Whenever both servos accelerated together, they behaved inconsistently and occasionally stalled.
To solve this problem, I added a dedicated 5V power module powered by a USB charger. The Arduino continued generating the PWM control signals, while the external supply delivered sufficient current for both servos. This greatly improved the reliability of the system and allowed smooth movement across both axes.
### Servo Compatibility
Toward the end of the milestone, I discovered that one of my original servos, an ES08MA, used a different spline pattern and horn geometry than the SG90 servos I had designed around. Because the mounting hole and gear pattern were different, the printed parts were incompatible.
Instead of redesigning every component, I replaced the ES08MA with another SG90 servo. This ensured that both servos used identical mounting hardware and allowed the printed parts to fit exactly as intended.
## Next Step
For the next milestone, I will begin programming the Arduino Nano to control both servos automatically. Instead of manually positioning the laser, I will upload code that generates randomized movements and timed pauses, allowing the laser to imitate the unpredictable behavior of prey. I will also complete the electrical wiring, troubleshoot the Arduino Nano, and test the entire system as an integrated autonomous cat toy.


# Schematic
The schematic illustrates the complete electrical system used to operate the Automated Cat Laser. The Arduino Nano serves as the central controller, generating the Pulse Width Modulation (PWM) signals that position the two SG90 servo motors while simultaneously powering the laser module. Together, these components create a two-axis pan-and-tilt mechanism capable of directing the laser beam to randomized locations.

The **Arduino Nano**, represented by the large blue rectangle, functions as the brain of the system. It continuously executes the uploaded C++ program, calculates new target positions for the laser, and outputs PWM signals through two digital pins connected to the servo motors. These PWM signals determine the angular position of each servo, allowing the Arduino to control both the horizontal (X-axis) and vertical (Y-axis) movement of the laser.

The two **SG90 servo motors**, shown as the blue rectangles with white crosses, provide the mechanical movement of the system. The lower servo rotates the entire upper assembly left and right, controlling horizontal movement. Mounted on top of the first servo, the second servo controls vertical movement by rotating the laser module up and down. Working together, the servos allow the laser to point throughout the designated play area.

The **laser module** is connected to one of the Arduino's digital output pins and emits a continuous red laser beam throughout operation. As the servos change position, the orientation of the laser changes as well, creating the appearance of a moving target for the cat to chase.

The orange wires in the schematic represent the signal wires. These wires carry the PWM control signals generated by the Arduino Nano to each servo. Because these signals contain only control information, they draw very little current while precisely commanding each servo's position.

The red wires represent the positive power connections, while the black wires represent the ground connections. Sharing a common ground between the Arduino, servo motors, laser module, and external power supply is essential because it provides a common voltage reference for all of the control signals. Without a shared ground, the PWM signals could not be interpreted correctly by the servos.

The project is powered by a **9V battery**, shown in the schematic as the component labeled "9V." The battery supplies electrical energy to the system, allowing the Automated Cat Laser to operate independently without remaining connected to a computer. During development, the Arduino was powered through its USB connection while code was uploaded and tested. After programming was complete, the battery became the primary power source, allowing the project to function as a completely portable autonomous device.


<p align="center">
  <img src="https://github.com/user-attachments/assets/ad3ee41e-f111-4976-8eee-59be2ddbfe92" alt="Grid Measurement Screen Shot" width="80%">
</p>




# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
#include <Servo.h>

/* YOU CAN CUSTOM THESE VARIABLES IF YOU WANT TO ALTER THE TOWER BEHAVIOUR */

// X servo angle will stay in [min_x, max_x] range
// Y servo angle will stay in [min_y, max_y] range
// to be ajsuted to the size of your living room

float min_x = 5;
float max_x = 50;
float min_y = 5;
float max_y = 50;
int min_freeze = 600;
int max_freeze = 3000;
float minimal_movement = 5;
int LaserValue = 180; // 0 =0V and 255 =5V lower the value if you want to dim the laser, higher it if you want to brighten it, higher the value to max 255
/* YOU SHOULD NOT HAVE TO MODIFY THE CODE BELOW THIS LINE */

// finding center of square for starting point
int random_delay;
float x_position = min_x + (max_x - min_x)/2;
float y_position = min_y + (max_y - min_y)/2; 
float x_old_position = x_position;
float y_old_position = y_position;
float x_new_position;
float y_new_position;
float x_speed;
float y_speed;
int movement_time;

// Instantiating two servos
Servo x_servo;  
Servo y_servo;
int pos = 0;

void setup() {
  y_servo.attach(6);  // attaches the y servo on pin 6 to the servo object
  x_servo.attach(9);  // attaches the x servo on pin 9 to the servo object
  
  pinMode (3, OUTPUT);
  analogWrite(3,LaserValue);  // switch on  the laser
  
  //Place the servos in the center at the beginning 
  y_servo.write(y_position); 
  x_servo.write(x_position);     

}

void loop() {
  movement_time = random(10,40);
  random_delay = random(min_freeze, max_freeze);
  x_new_position = random(min_x+minimal_movement, max_x-minimal_movement);
  y_new_position = random(min_y+minimal_movement, max_y-minimal_movement);
  
  if( (y_new_position > y_old_position) && (abs(y_new_position - y_old_position) < 5 )) {
    y_new_position = y_new_position + minimal_movement;
  }  else if ( (y_new_position < y_old_position) && (abs(y_new_position - y_old_position) < 5 )) {
    y_new_position = y_new_position - minimal_movement;
  }
  
  if( (x_new_position > x_old_position) && (abs(x_new_position - x_old_position) < 5 )) {
    x_new_position = x_new_position + minimal_movement;
  }  else if ( (x_new_position < x_old_position) && (abs(x_new_position - x_old_position) < 5 )) {
    x_new_position = x_new_position - minimal_movement;
  }
  
  x_speed = (x_new_position - x_old_position)/movement_time;
  y_speed = (y_new_position - y_old_position)/movement_time;  
  for (pos = 0; pos < movement_time; pos += 1) { 
      x_position = x_position + x_speed;
      y_position = y_position + y_speed;
      x_servo.write(x_position);  
      y_servo.write(y_position);                    
    delay(10); 
  }
  x_old_position = x_new_position;
  y_old_position = y_new_position;
  delay(random_delay);

}



```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| SG90 9g Micro Servo Motor Steering Gear Fixed-Wing RC Airplane 90 °-180 °/360 ° | Rotates the first motor, mounted to bottom | $7.02 (x2) | [here](https://homediyer.com/products/sg90-micro-servo-motor-9g?variant=51231808225554&country=US&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&pv2=eyJhbGciOiJFUzI1NiIsInR5cCI6IkpXVCJ9.eyJjIjoiVVNEIiwiZXhwIjoxNzgyMzM4MDc5LCJtIjoiNTUyNzA0NDk5MSIsIm8iOiJzaG9waWZ5X1VTXzEwMTI0MTg0MTI1NzE0XzUxMjMxODA4MjI1NTU0IiwicCI6Mi45OTAwMDAwMDAwMDAwMDAyfQ.liaWn4RFwgIdoOO498OfPPG8a9vWdpwTbD4GaJqmdrD1kdubD3su9XQFXOIPjSxbXARM5qCX950CPtNPZGNARQ&gad_source=1&gad_campaignid=23226721648&gbraid=0AAAAAq5GleiDmwmhwx4Jexek5riRiGsQt&gclid=CjwKCAjwgO7RBhBKEiwAZNP85nouSNXotBf_31OLzfR-8ZrI_dIpQvXJbJYsuUZNy5ciuvNdldRO7RoCj9cQAvD_BwE) |
| 5V Laser Head Sensor Module Laser Tube KY-008 Laser Module | Emits the laser | $0.24 | [here](https://www.alibaba.com/pla/5V-Laser-Head-Sensor-Module-Laser_1601724953188.html?mark=google_shopping&biz=pla&searchText=electronic+modules+and+kits&product_id=1601724953188&pcy=us_en&src=sem_ggl&field=UG&from=sem_ggl&cmpgn=22635874527&adgrp=177485315221&fditm=&tgt=pla-2412849993011&locintrst=&locphyscl=9032171&mtchtyp=&ntwrk=g&device=c&dvcmdl=&creative=756472634791&plcmnt=&plcmntcat=&aceid=&position=&gad_source=1&gad_campaignid=22635874527&gbraid=0AAAAAD8m77pOB0VFl9hzvVeqhSYXTvZzV&gclid=Cj0KCQjwxvjRBhC2ARIsAI7KJa3-HEY2k5_xR4pY9nn0LJoM9fBqMnMk6Me_NNiXPrJs_i2JHCHmn2EaAgewEALw_wcB) |
| ElectroCookie Solderable Breadboard PCB Board for Electronics Projects Compatible for DIY Arduino Soldering Projects, Gold-Plated | PCB Board for base | $1.47 | [here](https://www.amazon.com/ElectroCookie-Solderable-Breadboard-Electronics-Gold-Plated/dp/B07ZV8FWM4/ref=sr_1_2?crid=1AKFYY6TW48F6&dib=eyJ2IjoiMSJ9.-Z3EIkICsmQqOZayKZj-sxr2b2px1dmwnQYryLDkP2WCIIrYCcmXlfpNChGD5Lpmozl-TgWCiYy8ztX28zWdgCKLZncjgyW89JUUBzIGVKfaAbanRMWGOmoUT9wN4JOe4fUBQRPv2yaU5V6Jioa1TI4AV4WlS-zp4hMkG162Z9c5oGxXVCwtBHozOn8gs9nnHkS4JWIYKFd20PvWWRnkg90gMROcZR6uERbi_kLHDEg.hB2l8Q1fpR2Je-K7qx37c8sUpfsbVx-0fq0YhYcFK7o&dib_tag=se&keywords=electrocookie%2B1%2F2%2Bbreadboard&qid=1783027075&sprefix=electrocookie1%2F2%2Bbreadboard%2Caps%2C134&sr=8-2&th=1) |
| Amazon Basics 4-Pack 9V Long-Lasting Alkaline Batteries for Smoke Detector, Electronics & Audio, 5-Year Shelf Life | Supplies power | $2.45 | [here](https://www.amazon.com/Amazon-Basics-Performance-All-Purpose-Batteries/dp/B0774D64LT/ref=sr_1_5?crid=2VY649SH5OMG4&dib=eyJ2IjoiMSJ9.-AcdD3NT04C-Iki0Uv9JZ3tENzk8bHGpzCVKJ6DLz1YAu4TKWUXWdQiQkVqI38fETl2mnbSMzzmkI5Lw4tFzbgG41fRpf9pMA4u5EV2BMlEDFAA5-dRLrRBVWONBsksfAtKtN7PBtFznzHatDpucITrsWbKPsOq87SroZ25lQ5GtBoyRdkrHc_tQD7ERj5FWYv-J1DsLdwbyjfSji_P7MwkrQH6IU8mnb20k60_hR5l6GE0fdkEnbKkNCzBf2MUxzUgJbERt_Mmb3GEo_05nRXv9exBQty-AHzvHQ5M7rzg.gulnZY_emkIevhImWBLrt5RgvNn2pXWBuYKp5N5ZzLQ&dib_tag=se&keywords=9V%2Bbattery%2Bamazon&qid=1784251402&rdc=1&sprefix=9v%2Bbattery%2Bamaz%2Caps%2C375&sr=8-5&th=1) |

