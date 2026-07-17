# Automated Cat Laser
To help my cats stay active, lose weight, and remain mentally stimulated while I am away from home, I designed and built an **Automated Cat Laser**. The system consists of a two-degree-of-freedom pan-and-tilt mechanism driven by two SG90 servo motors, allowing a laser module to rotate independently along the X and Y axes. An Arduino Nano controls the servos by generating PWM (Pulse Width Modulation) signals, causing the laser to move through a series of randomized positions and timed pauses that simulate the unpredictable movement of prey. The mechanical assembly was designed in CAD and fabricated using 3D-printed components that securely mount the servos and laser while maintaining proper alignment. By integrating mechanical design, embedded programming, electronics, and additive manufacturing, the project creates an autonomous laser system that encourages exercise and provides environmental enrichment for indoor cats.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Eason Z | Challenger | Mechanical Engineering | Incoming 8th

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)

# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Description

For my third and final milestone, I focused on refining the project by improving its appearance, durability, and overall functionality. Rather than adding completely new features, I concentrated on redesigning existing components to create a more reliable and polished final product.

One of my main improvements was designing and 3D printing a protective enclosure for the electronics. I created a custom case that housed the Arduino Nano, power circuitry, and wiring, protecting the components from accidental damage while also making the project easier to transport. While designing the enclosure in CAD, I had to consider the dimensions of every component, including the Arduino, power connections, jumper wires, and battery leads. I also designed openings for the USB port, power cable, and wiring so the system could still be programmed and powered without removing it from the enclosure. Multiple test prints were required to adjust the tolerances so every component fit securely without excessive force.

I also designed and printed a dedicated case for the laser module. Instead of leaving the laser exposed, the enclosure held it firmly in place while keeping it aligned with the servo horn. This reduced unwanted movement and made the laser more stable as the servos changed position. The housing also protected the laser from being bumped or knocked out of alignment during operation.

Another major improvement was redesigning the second servo mount. Earlier versions fit the servo horn loosely and required sanding before they could be assembled. For the final version, I completely remodeled the mount using more accurate measurements of the servo horn and spline dimensions. I adjusted the clearances and wall thickness to improve the strength of the printed part while maintaining a tight fit. I also reinforced the mounting platform with additional material around the high-stress areas to reduce flexing as the servo accelerated and changed direction. As a finishing touch, I incorporated a custom logo directly into the CAD model, giving the mount a more professional appearance while demonstrating more advanced CAD techniques. The final design fit much more precisely than previous versions and required significantly less post-processing before assembly.

After assembling all of the redesigned parts, I tested the complete system to ensure the laser moved smoothly in both the X and Y axes while the electronics remained securely mounted inside their enclosures. These improvements made the final project much cleaner, sturdier, and more reliable than the earlier prototypes.

# Challenges

The biggest challenge during this milestone was the amount of redesigning and reprinting required before the parts fit correctly. Even small measurement errors in the CAD model could prevent components from fitting together, especially around the servo gears and mounting holes. Because 3D printers also have slight dimensional inaccuracies, I often had to adjust tolerances by only a few tenths of a millimeter before printing another prototype.

Several versions of the servo cases did not fit properly onto the servo gear because the center opening was either too tight or slightly misaligned. Each failed print required measuring the part, modifying the CAD model, and printing another revision. This iterative design process took a significant amount of time, but it allowed me to better understand manufacturing tolerances and the importance of designing for real-world assembly rather than relying only on CAD dimensions.

Although repeatedly redesigning parts was frustrating, each iteration improved the quality of the final product and helped me develop a more efficient design process.

# What I Learned at BlueStamp Engineering

During my time at BlueStamp Engineering, I learned much more than simply how to build a working project. I developed practical engineering skills by repeatedly designing, building, testing, troubleshooting, and improving my work.

The biggest challenges I overcame were uploading code to a clone Arduino Nano, redesigning and reprinting 3D models until they fit correctly, and learning proper soldering techniques. Each of these required patience and careful troubleshooting. I learned that engineering projects rarely work perfectly on the first attempt, and that solving problems is an essential part of the design process.

My biggest accomplishments were successfully assembling all of the custom 3D-printed parts into a functional mechanism, getting the Arduino code working correctly with both servos, and producing clean, reliable solder joints. Through practice, I learned how to heat both the pad and the component lead evenly so the solder flowed correctly, creating strong electrical and mechanical connections instead of cold solder joints. Seeing the completed system operate smoothly after solving so many problems was one of the most rewarding parts of the project.

Throughout the program, I gained experience with a wide variety of technical skills, including CAD design, 3D printing, soldering and desoldering, drilling, sanding, hot gluing, electrical wiring, and programming in C++. I also learned how to measure components accurately, account for manufacturing tolerances, and improve designs through repeated testing and iteration.

In the future, I would like to continue developing my CAD skills so I can design more detailed and mechanically complex parts. I also want to expand my programming knowledge in C++, learn how to use Raspberry Pi computers for more advanced projects, and become familiar with additional engineering tools and manufacturing techniques. Overall, this project gave me a much stronger understanding of the engineering design process and increased my confidence in tackling challenging technical problems independently.

# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Description

For my second milestone, I focused on programming the laser toy and getting the electronics working together. I uploaded code from an online DIY laser toy project to an Arduino Nano and used it as the foundation for my project. The code controls two servo motors that move the laser in both the X and Y axes. Instead of moving in a predictable pattern, the laser pauses briefly in one location before moving to another point. This creates random, bug-like movements that are designed to stimulate a cat's hunting instincts and encourage it to chase the laser.

This milestone also involved connecting the Arduino to the two servos and making sure they responded correctly to the program. I tested the movement several times and adjusted the wiring and power supply so the servos could move smoothly without resetting the Arduino. By the end of this milestone, I had a working system that could control the laser's movement in two dimensions.

One thing that surprised me during this project was how much time 3D printing takes, especially when parts need to be redesigned and reprinted after testing. Even small design changes can require several hours of printing. I also learned that there are important differences between genuine Arduino boards and clone Arduino boards. Although they perform the same basic functions, the clone Arduino required additional drivers before I could upload code, which was something I had not expected.

# Challenges

One of the biggest challenges I faced was uploading the code to the Arduino Nano. Since I was using a clone Arduino instead of an official Arduino board, my computer could not recognize it at first. After researching the problem, I discovered that I needed to install the correct driver for the USB-to-serial chip on the board. Once the driver was installed, I was able to successfully upload the program.

Another challenge was supplying enough power for the servos. The Arduino could not provide enough current on its own, so I added a separate power module. Unfortunately, the power module malfunctioned, preventing the servos from operating correctly. I first attempted to remove it by desoldering it from the board, but my solder joints were difficult to remove and the repair was unsuccessful. I then tried cutting away part of the board to replace the damaged section, but halfway through I decided it would be easier to transfer the components to another board instead.

After soldering the Arduino onto the new board, I realized I had accidentally soldered it onto the wrong side, making it difficult to complete the wiring. Rather than starting over again, I went back to the original board, which still functioned even though it had been partially cut. I finished the wiring on that board and soldered a 9V battery connection so the project could operate without being plugged into a computer. Although these setbacks took extra time, they helped me improve my soldering skills and taught me how to troubleshoot hardware problems more effectively.

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Description

For my first milestone, I built the arm that moves the laser in two dimensions. I started by designing custom mounts for both servos that securely attached either to a breadboard or to a servo horn. After printing the mounts, I assembled the arm and attached the laser to the servo horn using screws. Finally, I connected the servos to the breadboard with male-to-male jumper wires and added a 5V power supply module powered by a USB charger adapter.

One of the most important parts of this milestone was designing the screw holes with the correct dimensions. The screws needed to fit securely while remaining short enough not to interfere with the servo. I also had to carefully measure the dimensions of the second servo mount. After several failed prints that were either too large, too long, or designed for the wrong servo horn, I modified the mount by sanding the opening until it fit properly.

# Challenges

One challenge I faced was designing the servo mounts. The bottom mount needed an opening for the servo wires to pass through, but the hole was too small. I initially cut and stripped the wires to make them fit, but after soldering them back together, the connection was unreliable, causing the servo to move inconsistently. To solve this problem, I redesigned and reprinted the mount with greater tolerance and more space for the wires.

Another challenge was mounting the second servo onto the first servo's horn. My initial design placed a platform above the servo horn, but I accidentally used the wrong servo horn model, so the parts did not fit together and had to be reprinted. I then redesigned the mount so the servo horn fit into a recessed pocket, making the structure stronger. Although the new design was much closer, it still required sanding before it fit correctly.

During testing, I also discovered that powering the servos directly was insufficient, so I added a dedicated 5V power module. This required rewiring the circuit to provide enough current for both servos. Finally, I realized that my original ES08MA servo used a different gear and horn pattern than expected, making it incompatible with my design. I replaced it with an SG90 servo, which fit the printed parts correctly.


# Schematic

This schematic illustrates the wiring for my project. The **orange wires** are the signal wires and connect to the Arduino's digital output pins, which generate the PWM signals used to control the servo motors. The **red wires** are connected to the positive power rail (+), while the **black wires** are connected to the ground rail (-).

The **9V battery** is represented by the box labeled **"9V"** and provides power to the circuit. The **Arduino**, shown as the long blue rectangle labeled **"Arduino,"** serves as the microcontroller that controls the system. The **two blue rectangles with white crosses on top** represent the servo motors, which rotate along the X and Y axes to position the laser.


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
float max_y = 35;
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

