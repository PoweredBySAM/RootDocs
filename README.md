# Root® Robot Documentation

The [Root® Coding Robot](https://edu.irobot.com/root) is a toy robot that teaches coding basics to kids of all ages and skill levels through hands-on programming experiences.
It is currently built and sold by [SAM Labs](https://samlabs.com/) and was previously manufactured by Root Robotics (2018-2019) and iRobot (2019-2024).

![Root drawing arcs with blue marker](images/root-drawing.jpg)

## Programming Root

Root robots can programed using the companion **SAM Root** app available on [iOS](https://apps.apple.com/us/app/sam-root/id1524652548), [Android](https://play.google.com/store/apps/details?id=com.rootrobotics.rootcoding), or [Web](https://root.samlabs.com/).

Advanced users can also use the [iRobot Education Python Web Playground](https://python.irobot.com/) or downloadable [iRobot Education Python 3 SDK](https://github.com/iRobotEducation/irobot-edu-python-sdk) for even more control over the robots.

## Turning Root On/Off

To turn the Root robot on or off, press and hold the yellow button (otherwise referred to as its “nose”) until the lights turn on/off (around 4 seconds).

![Turning Root on illustration](images/root-turn-on.png)

If Root is not responding as expected, hold the power button for 10 seconds to force the Root robot to turn off.

> [!TIP]
> The yellow nose button also acts as a "stop" button.
> Pressing it while a program is running will immediately stop the motors and tell the SAM Root app to stop the running project.

## Charging

To charge your Root robot, plug a powered USB cable into the USB-C port on the top of the robot.
For the quickest charging, we recommend using a USB charger capable of supplying 5W (5V, 1A) or greater.
We also recommend always using the USB cable supplied with the robot.

![Root charging illustration](images/root-charging.png)

While the robot is charging, a light on top of the robot will flash yellow.
Once the robot is fully charged, the light will stay green.
Please note that the robot is not able to connect over Bluetooth while it is charging.

For additional information about charging, refer to the [Product Information Guide](files/Root-Product-Info-Guide.pdf).

### Charging Contacts

The Root robot can also be charged by applying between 6.5V and 9V across the two metal charging contacts on the rear of the robot.
The robot has a special circuit to make the charging contacts reversible, so it does not matter which charging contact has the higher voltage.
However, please note that the USB-C port supports higher charging currents and typically results in faster charging.

> [!WARNING]
> Do not apply more than 9 Volts across the charging contacts.
> Excessive voltage can damage the robot.

## Bluetooth Connection

Root coding robots are controlled over a Bluetooth® Low Energy connection by a companion device, such as a laptop, tablet, phone, or Raspberry Pi.
Root robots are available to connect over Bluetooth whenever 
1. the robot is powered on (i.e. the eyes are on) 
2. it not connected to another device.

Once you connect to the robot, it will play a chime and the lights will briefly flash blue.
To disconnect, trigger a disconnection from the app or turn off the robot by holding down the yellow nose button.

To start, go to [root.samlabs.com](https://root.samlabs.com/) to use the SAM Root web app or download the SAM Root app from the [Apple App Store](https://apps.apple.com/app/id1524652548) or [Google Play Store](https://play.google.com/store/apps/details?id=com.rootrobotics.rootcoding).
To connect to robots when using the [web app](https://root.samlabs.com/), you must use a browser that supports Web Bluetooth, such as [Chrome](https://www.google.com/chrome/) or [Edge](https://www.microsoft.com/edge).
The SAM Root app features three coding levels (graphical, hybrid, and text) to support learners of all skill levels.
Once you have made a project, you can tap the robot connection button and select your robot to connect.
Then press the play button to see your project come to life!

![Root Bluetooth connection illustration](images/root-connect.png)

Advanced users can access even more capabilities using the downloadable [iRobot Education Python 3 SDK](https://github.com/iRobotEducation/irobot-edu-python-sdk) or in-browser Python coding experience within the [iRobot Education Python Web Playground](https://python.irobot.com/).
All of these coding experiences implement the openly documented [Root Bluetooth Low Energy protocol](https://github.com/iRobotEducation/root-robot-ble-protocol) used by the robots.
If you are having issues with your Bluetooth connection, please see the FAQ below.

> [!TIP]
> If you have multiple Root robots, give each one a unique name to make it easier to conenct to the right one.
> Once you have connected to a robot, simply tap the connection button again and select "Rename".
> When using the SAM Root app on iOS or Android, you can also touch the top of the robot or press the bumpers to highlight those areas on your robot in the Bluetooth connection window.

## Model Comparison

| &nbsp; | ![Root Lite model](images/root-lite.png)<br>**Root® Lite** | ![Root Pro model](images/root-pro.png)<br>**Root® Pro** |
| --- | --- | --- |
| Model number | RT0 | RT1 |
| **Software Compatibility** | | |
| Multi-level SAM Root apps ([Web](https://root.samlabs.com/), [iOS](https://apps.apple.com/app/id1524652548), [Android](https://play.google.com/store/apps/details?id=com.rootrobotics.rootcoding)) | ✓ | ✓ |
| Python Web Playground ([Web](https://python.irobot.com/)) | ✓ | ✓ |
| Downloadable Python 3 SDK ([macOS, Windows, Linux](https://github.com/iRobotEducation/irobot-edu-python-sdk)) | ✓ | ✓ |
| **Connectivity** | | |
| Wireless | Bluetooth® Low Energy | Bluetooth® Low Energy |
| Wired | USB-C (Serial) | USB-C (Serial) |
| Firmware Updates | Bluetooth® Low Energy | Bluetooth® Low Energy |
| **Power** | | |
| Battery | Integrated 9Wh Li-Ion  | Integrated 9Wh Li-Ion |
| Charging | USB-C cable (included) or<br>DC charging contacts | USB-C cable (included) or<br>DC charging contacts |
| Output | USB-C (0.2A at 5V) | USB-C (0.2A at 5V) |
| **Sensors** | | |
| Power button | ✓ | ✓ |
| Capacitive touch buttons | 4x | 4x |
| Bumper zones | 2x | 2x |
| Wheel encoders | 2x | 2x |
| Motor current feedback | ✓ | ✓ |
| Ambient light sensors | 2x | 2x |
| Cliff sensor | - | 1x |
| RGB color sensors | - | 32x |
| 3D gyroscope | ✓ | ✓ |
| 3D accelerometer | ✓ | ✓ |
| Battery level monitor | ✓ | ✓ |
| **Actuators** | | |
| Drive wheels | 2x | 2x |
| Integrated magnets to drive on vertical magnetic surfaces | - | ✓ |
| Maximum speed | 10 cm/s | 10 cm/s |
| Speaker | ✓ | ✓ |
| RGB light bars | 4x | 4x |
| Marker actuator | ✓ | ✓ |
| Actuated magnetic eraser | - | ✓ |
| **Accessories** | | |
| Included accessories | 1x Fold-up whiteboard grid<br>1x Green dry-erase marker<br>1x Reusable sticker sheet<br>1x Microfiber eraser cloth | 1x Fold-up whiteboard grid<br>1x Green dry-erase marker<br>1x Blue dry-erase marker<br>1x Reusable sticker sheet<br>1x Microfiber eraser cloth |
| Compatible with Root Brick Top | ✓ | ✓ |
| Magnetic attachment points for accessories | 10x | 10x |
| Faceplate | Transparent | Whiteboard |

## Mechanical

Root is a differential drive robot with two driven wheels and four slide points to limit tipping.
When both wheels turn the same speed in the same direction, the robot will drive straight.
When the wheels turn different speeds, the robot will turn/arc.
When the wheels are the same speed in opposite directions, the robot will turn in place.
Each wheel uses encoders to maintain the correct speed and measure the distance traveled.
The maximum speed is 10 cm/s.

### Features

![3D drawing of Root with numbered features](images/root-features-top.svg)

1. USB-C port for charging, 5V power out, and serial connection (BETA)
2. RGB LED light bars (4x)
3. Top accessory magnets (12x)
4. Capacitive touch sensors (4x)
5. Programmable marker lift/drop
6. Ambient light sensors (2x) and eye LED lights (illuminated when robot is on)
7. Power/Stop yellow "nose" button
8. Bumper sensors (2x)

![3D drawing of Root with numbered features](images/root-features-bottom.svg)

9. DC charging contacts (6.5V-9V DC input)
10. Serial number label
11. Programmable magnetic eraser (model RT1 only)
12. Magnets (2x, model RT1 only)
13. Hand grip indents (2x)
14. Drive wheels with gear motors and encoders (2x)
15. Scanning color sensors (32x, model RT1 only)
16. Cliff sensor (model RT1 only)

### Drawings

#### Top

![Dimensioned drawing of top of Root](images/drawing-top.svg)

#### Bottom

![Dimensioned drawing of bottom of Root](images/drawing-bottom.svg)

#### Side

![Dimensioned drawing of side of Root](images/drawing-side.svg)

### Top Magnets

Root has ten small magnets underneath the top surface to help with attaching accessories.
These 5mm diameter magnets are in a 32mm x 32mm grid as shown in the [top drawing](#top) of the robot.
Each magnet has the North pole facing up.
You can use these to hold accessories in place by gluing magnets to your accessory that line up with the magnets in Root.
(*Make sure the magnets are facing the right direction first!*)

## Electrical

### Battery

Root has an integrated 2500mAh 3.6V 9Wh Li-Ion battery.
The battery can be charged using a standard USB-C charger through the USB-C port on the top of the robot.
A USB-C to USB-A charging cable is included in the box.

### USB Power Output

Root robots have ability to provide power to an accessory from the USB-C port.
When the robot detects an Upwards Facing Port (UFP), e.g. a USB device, rather than a USB charger or host, it will supply 5V with a maximum of 250mA to the VBUS pin of the USB-C port.

[This cable](https://www.amazon.com/AmazonBasics-USB-Type-C-Micro-B-Cable/dp/B01LONQBDG/) has been verified to work with the robot.

[This article](https://www.embedded.com/design/power-optimization/4458380/USB-Type-C-and-power-delivery-101-----Ports-and-connections) contains more information about USB-C cable configurations.

## Frequently Asked Questions

### About

<details>
<summary><b>What are Root® coding robots?</b></summary>

Root® coding robots, software, and curriculum teach programming and STEM fundamentals in an engaging and flexible way.
They incorporate problem solving, art, math and more, with an intuitive app and versatile mobile robot to keep students engaged throughout their learning journey.
Bridging the gap between K-12 education, Root® coding robots provide a continuous learning platform that advances alongside students’ abilities.
For schools, this means more personalized classroom learning, better student engagement, and less money and time spent on single-purpose software and hardware.

</details>

<details>
<summary><b>What age(s) are the Root® coding robots designed for?</b></summary>

Root® coding robots are designed for learners who are **6 years of age and up**.
For children under the age of 6, helping hands are recommended.

</details>

<details>
<summary><b>Which model of Root® coding robot should I choose?</b></summary>

All Root® coding robot models are suitable for all skill levels, require minimal setup, are packed with programmable sensors, draw on paper or an included fold-out whiteboard, and can be expanded to do even more.
A detailed breakdown of the features of each model can be found in the [model comparison chart](#model-comparison).
In short, there are two models of Root® robots:
- The Root® Lite coding robot (model RT0) makes it easy to bring more robots into your home or learning space for less.
Designed to provide a balance of value and utility, the Root® Lite is equipped with the essential features to transform learning to code into a grand adventure.
If you’re looking for a way to bring code alive through art, music, and exploration, the Root® Lite is the choice for you.
It features bright white bumpers with a translucent top.
- The Root® Pro coding robot (model RT1) provides the ultimate interactive coding experience.
From navigating flat, horizontal surfaces to vertical, magnetic whiteboards, the Root® Pro makes the most of your space while also defying gravity.
In addition to all the features seen in the Root® Lite, the Root® Pro comes with a color sensor, an eraser, and a cliff sensor for even more ways to take STEM learning to the next level.
It features jet-black bumpers with a whiteboard top.

</details>

<details>
<summary><b>What skills will my students learn with the Root® coding robots?</b></summary>

Root® robots are designed to teach **sequencing, coding, math, science, robotics, problem solving, and more** to students of all skills and backgrounds.
From the very beginning, these tools were designed and piloted with educators to appeal to a wide range of ages, skill levels, and interests to deliver immersive, scalable, and cross-curricular learning experiences.
We encourage you to visit our [Learning Library](https://edu.irobot.com/learning-library) for many examples of ways to engage with these robots.

</details>

<details>
<summary><b>Do I need previous coding or robotics experience to use Root® coding robots?</b></summary>

No!
Root® coding robots are designed to be exceptionally easy to get started and learn!
The robots work right out of the box, without requiring any assembly.
Simply turn on the robot, connect to it from the iRobot Coding app, and use one of the three intuitive programming levels to get started.
Check out the [Learning Library](https://edu.irobot.com/learning-library) for examples of ways to learn with with these robots.

</details>

### Getting Started

<details>
<summary><b>How do I power my Root® coding robot on/off?</b></summary>

**To power your Root® coding robot on**, press and hold the robot’s yellow button (otherwise referred to as its “nose”) for three seconds until its LED lights turn on. 

**To power your Root® coding robot off**, press and hold the robot’s yellow button (otherwise referred to as its “nose”) for three seconds until its LED lights turn off.

For additional help and information on getting started, we invite you to explore the [Learning Library](https://edu.irobot.com/learning-library).

</details>

<details>
<summary><b>How do I connect to and control my Root® coding robot?</b></summary>

To connect to and control your Root® coding robot,
- Place your Root® coding robot on a flat surface, such as the fold-out whiteboard that’s included in the box.
- Power your Root® coding robot on by pressing and holding the robot’s yellow button (otherwise referred to as its “nose”) for three seconds until its LED lights turn on.
- Power on your Bluetooth® Low Energy (BLE) device and ensure its Bluetooth® settings are active.
- Open the iRobot Coding App on your BLE device ([Web](https://code.irobot.com/), [iOS](https://apps.apple.com/us/app/irobot-coding/id1524652548), or [Android](https://play.google.com/store/apps/details?id=com.rootrobotics.rootcoding)).
- Click on the plus (+) icon under the “My Projects” header in the Content Manager.
- Open the Bluetooth® connection window by clicking on the Root® coding robot icon to the right of the project title in the Project Editor.
- Select the Root® coding robot that you would like to connect with.
- Begin coding in the Project Editor!

For additional help and information on getting started, we invite you to explore the [Learning Library](https://edu.irobot.com/learning-library).

</details>

<details>
<summary><b>How do I update the firmware on my Root® coding robot?</b></summary>

Normally, the iRobot Coding apps should detect the version of the firmware running on the robot and prompt you to update when needed.
If you do not receive a prompt, you may manually update the robot by completing the following steps:
1. Power off the robot by pressing and holding the robot’s yellow button (otherwise referred to as its “nose”) for three seconds until its LED lights turn off.
2. Wait 10 seconds to make sure that the robot is fully powered off.
3. Hold down both the left and right bumpers.
4. While still holding down both bumpers, hold the robot’s yellow button (its “nose”) down for 10 seconds, or until the robot’s LED lights start flashing blue. (The robot flashes blue to indicate that it is in "update” mode).
5. Navigate to the web updater page using a Web Bluetooth compatible browser, such as Chrome or Edge.
6. Press the “Pair” button and select the "ROOT BOOT" robot from the connection list. You should only see devices that are in "update” mode as connection options on this page.
7. Press the “Update” button and wait for the update to complete.

</details>

<details>
<summary><b>How can I reset my Root® coding robot?</b></summary>

**Regular Reset**:
To regularly turn off your Root® coding robot and/or force a disconnection of the Bluetooth® Low Energy connection:
- Power your Root® coding robot off by pressing and holding the robot’s yellow button (otherwise referred to as its “nose”) for three seconds until its LED lights turn off.
- Wait for about 10 seconds to allow the robot to fully shut down.
- Power your Root® coding robot back on by pressing and holding the robot’s yellow button (otherwise referred to as its “nose”) for three seconds until its LED lights turn on. 

**Forced Reset**:
If your Root® coding robot is not responding as expected, you can perform a forced reset:
- Force reset your Root® coding robot by pressing and holding the robot’s yellow button (otherwise referred to as its “nose”) for ten seconds. This action forces the robot to turn off completely.
- Power your Root® coding robot back on by pressing and holding the robot’s yellow button (otherwise referred to as its “nose”) for three seconds until its LED lights turn on. 

**Factory Reset**:
A traditional factory reset erases the information and settings on devices. Given that Root® coding robots do not retain any user data from previous usage, users do not need to conduct a factory reset. If you have changed the robot’s name, you may choose to rename it back to the original name of “ROOT” to simulate a factory reset.

</details>

<details>
<summary><b>Are there any resources to get started with the Root® coding robot?</b></summary>

**Yes!**
Please visit our [Learning Library](https://edu.irobot.com/learning-library) for an abundance of resources to help you get started including starter tutorials, projects, and videos.
Our [Learning Library](https://edu.irobot.com/learning-library) provides an expansive collection of lessons that help teachers and integrate coding and robotics into the curriculum by exploring a wide range of topics and genres.
- Beginner content includes a curated assortment of free activities, videos, sample coding projects, and DIY coding competition kits.
- Access to premium curriculum modeled after educational standards (such as CSTA) and self-guided or custom professional development trainings are also available for purchase.

</details>

<details>
<summary><b>Is there curriculum available to help me teach with the Root® coding robot?</b></summary>

**Yes.**
Our made-for-classrooms curriculum is designed to fit seamlessly into your school year with over 75 scaffolded, hands-on, project-based activities.
This curriculum is specifically mapped to several international standards sets, such as the US Common Core Standards, CSTA, UK Key Stages, and more.

Each lesson includes 40-60+ minutes of outlined instruction with multiple engagement points, such as:
- Class discussion
- Team-based project
- Reflection activity
- Going further extensions

By utilizing the multiple programming levels in the iRobot Coding App, each lesson provides multiple opportunities for every student to feel appropriately engaged and academically challenged, regardless of their coding background.
This integrated scaffolding approach with the App and robot promotes a cohesive and inclusive classroom experience.
Additionally, embedded math, ELA, science, and arts connections create cohesive, school-wide learning opportunities.

The curriculum is available in a digital format that allows you to conveniently print a copy for each member of your teaching team and review your lesson plans inside or outside of the classroom. With prepared lessons already designed to meet their required learning objectives, teachers can spend more time teaching and less time planning.

</details>

### Programming

<details>
<summary><b>Do I need an app to control the Root® coding robots?</b></summary>

Yes. Root® coding robots are controlled over Bluetooth using the companion iRobot Coding app.

The iRobot Coding app is compatible with Bluetooth® Low Energy (BLE) devices running most major, up-to-date operating systems, including Windows, macOS, ChromeOS, Linux, iOS, iPadOS, and Android.

The iRobot Coding app can be downloaded from the [Apple App Store](https://apps.apple.com/app/id1524652548), [Google Play Store](https://play.google.com/store/apps/details?id=com.rootrobotics.rootcoding), or used online at [code.irobot.com](https://code.irobot.com/).
When connecting to your robot using the online [Web App](https://code.irobot.com/), please also ensure you are using a browser that supports Web Bluetooth, such as Chrome or Edge.

Advanced users can also use the [iRobot Education Python Web Playground](https://python.irobot.com/) or downloadable [iRobot Education Python 3 SDK](https://github.com/iRobotEducation/irobot-edu-python-sdk) for even more control over the robots. 

</details>

<details>
<summary><b>What programming languages do the Root® coding robots teach?</b></summary>

Root® coding robots are controlled by the companion learn-to-code iRobot Coding apps, which feature both an easy-to-learn block coding language and Python.
The iRobot Coding app is available for free across [Web](https://code.irobot.com/), [iOS](https://apps.apple.com/app/id1524652548), and [Android](https://play.google.com/store/apps/details?id=com.rootrobotics.rootcoding) devices.
It teaches key skills by separating learning to code into three (3) progressive Learning Levels.
These Learning Levels are designed to scaffold how students learn to code by catering to any coding ability, from pre-readers to advanced users: 
- **Learning Level 1** uses drag-and-drop, graphical blocks to teach sequencing and the fundamental logic skills.
The number of available blocks is purposefully limited and no reading skills are required for this level. 
- **Learning Level 2** builds computational fluency with hybrid blocks that feature a mixture of graphics and coding script.
- **Learning Level 3** uses full-text code to teach the structure and syntax of professional coding languages, using the powerful and intuitive Python programming language. 

For those interested in taking their learning to the next level, the iRobot Python apps (BETA) provide a direct pathway to graduate from block-based coding to entirely text-based Python coding environments.
The zero-installation Python coding environment known as the [iRobot Education Python Web Playground](https://python.irobot.com/) or a downloadable [Python 3 SDK](https://github.com/iRobotEducation/irobot-edu-python-sdk) let you unlock even more capabilies and learning.

</details>

<details>
<summary><b>Can I control the Root® coding robots from other programming environments?</b></summary>

The Root® coding robots are designed to be used with the companion iRobot Coding app.
The iRobot Coding app is compatible with devices running most major, up-to-date operating systems, including [Web](https://code.irobot.com/), [iOS](https://apps.apple.com/app/id1524652548), and [Android](https://play.google.com/store/apps/details?id=com.rootrobotics.rootcoding).
In order to connect your Root® coding robots to the iRobot Coding app, your device requires Bluetooth® Low Energy (BLE) and (for the web app) a [Web Bluetooth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API#browser_compatibility) supported browser like Chrome or Edge. 
For experienced users, there are also the iRobot Python apps (BETA), which include a zero-installation Python coding environment on the web known as the [iRobot Education Python Web Playground](https://python.irobot.com/) or a downloadable [Python 3 SDK](https://github.com/iRobotEducation/irobot-edu-python-sdk).

Advanced developers can create their own libraries and projects that work with Root by utilizing the publically avilable [Bluetooth® Low Energy (BLE) protocol](https://github.com/RootRobotics/root-robot-ble-protocol) usedy by the Root robots.
The protocol documentation should provide enough information for you to connect to and use the robot with any hardware that supports BLE using the programming language and Bluetooth® library of your choice.

Please note:
Implementation of the Bluetooth protocol requires advanced coding experience and some understanding of how Bluetooth Low Energy works.
To help you get started, we’ve included a basic sample script that runs on a Raspberry Pi® 3 to drive your Root® coding robots using arrow keys.

</details>

### Charging

<details>
<summary><b>What type of charger do Root® coding robots require?</b></summary>

For full charging speeds, Root® coding robots require a minimum 5W (5V, 1A) USB charger.
We recommend always using the charging cable provided with the robot.

</details>

<details>
<summary><b>How long do the Root® coding robots’ batteries last?</b></summary>

The Root® coding robots’ batteries will typically last for 2 hours of continuous, heavy-use, and 1 week with intermittent use.

</details>

<details>
<summary><b>How long do Root® coding robots take to charge?</b></summary>

The charging speed is dependent on the amount of current your USB adapter can provide. 
Adapters with 5W or more should charge at full speed and be and to charge completely (from empty to full) in under 3 hours.

</details>

<details>
<summary><b>How do I know that the Root® coding robots are fully charged?</b></summary>

When Root® coding robots are fully charged, the LED lights on the top of the robot will glow green.
You should unplug the charger when the battery is full.

</details>

<details>
<summary><b>Why isn’t my Root® coding robot charging?</b></summary>

The charging cable provided should always be used to charge your robot. If your Root® coding robot does not indicate that it is charging – even when using the provided charging cable and a minimum 5W USB adapter – the battery may be at too low of a voltage.

If this is the case, please follow the steps below: 
- Plug your robot in and wait 1 hour. (The robot should slowly charge even if it does not flash the LED lights.)
- After 1 hour, unplug the robot, then plug it back in again.
- If the LED light still does not light up, leave the robot plugged in and repeat these steps after an additional hour.

If your robot is still not charging after following the above instructions, please contact us. 

</details>

### Drawing

<details>
<summary><b>Do Root® coding robots require a special type of marker or pen?</b></summary>

Root® coding robots support a wide range of markers and pens, but not every brand or design will work.
To ensure proper operation, insert the marker when the holder is raised and leave a small gap between the surface and the tip of the marker.
For markers that are too narrow, you may try wrap some tape around the neck of the marker to widen the diameter until it can be held in place.

</details>

<details>
<summary><b>Why won’t my Root® Pro coding robot stick to my whiteboard?</b></summary>

**Only the Root® Pro coding robot (with the white top) is designed to attach to and navigate magnetic whiteboard surfaces.**
On some whiteboards with weak magnetic backing, the Root® Pro coding robot might slip.
Other whiteboards may not have any magnetic backing at all.
Root will also not stick to magnetic whiteboard paint.

Please note that you can still use a magnetic or non-magnetic whiteboard with either model of the Root® coding robot model as long as the whiteboard and robot are placed on a horizontal surface, such as a table or floor.

</details>

<details>
<summary><b>Why is my Root® Pro coding robot moving slowly and making additional movements on the whiteboard?</b></summary>

If your Root® Pro coding robot is moving slowly and making additional movements on a vertical magnetic whiteboard, it is likely because the robot is using its sensors and corrective algorithms to compensate for gravity and draw the most accurate shapes possible. 

</details>

<details>
<summary><b>Why does my Root® coding robot slip when it drives?</b></summary>

Root® coding robots may slip more than usual if the wheels are dirty from dust or marker ink.
To improve performance, try cleaning the wheels with some rubbing alcohol and a cloth.

</details>

<details>
<summary><b>Why won’t my Root® coding robot draw well on a flat surface?</b></summary>

If your Root® coding robots won't draw on a flat surface, such as the fold-out whiteboard that is included in the box, please check the marker holder.
The robot's marker holder can hold several different brands of dry-erase markers and pens, but these tools come in a variety of different shapes and sizes.
This means that some pencils, crayons, and pens cannot be gripped by the robot’s marker holder or are not pushed down hard enough by the springs in the marker actuator.
The marker should be just above the drawing surface when the marker holder is in the up position.
When the marker holder is programmed to go down, the marker should go down below the wheel height.
If the Root® Pro coding robot detects a cliff, the robot will automatically lift the marker to prevent it from drawing when it is placed back down.

</details>

<details>
<summary><b>Why won’t my Root® Pro coding robot erase?</b></summary>

The Root® Pro coding robot's eraser is designed to work best on magnetic whiteboard surfaces.
The eraser has an embedded magnet to hold it firmly against the smooth surface of magnetic whiteboard so that it can erase.
On the included fold-up whiteboard, the robot will typically not be able to press down hard enough to erase effectively and the eraser pad can get caught on the folds, pushing the robot off course.

</details>

<details>
<summary><b>How do I clean the eraser pad on my Root Pro?</b></summary>

Root’s eraser pad is held in place with a hook-and-loop fastener.
To service, simply peel off the eraser pad, wash and dry it, and replace it on the robot.

</details>

### Features and Accessories

<details>
<summary><b>Is the Root Brick Top accessory compatible with my robot?</b></summary>

The Root Brick Top is compatible with both Root models and attaches magnetically to the top of the robot.

</details>

<details>
<summary><b>How does the Root® Pro coding robot stick to a magnetic vertical whiteboard?</b></summary>

The Root® Pro coding robot has strong permanent magnets embedded inside its chassis to help it climb whiteboards.
There are also twelve (12) smaller magnets on the top surface to connect accessories.
Keep magnetic-sensitive objects away from the robot.

</details>

<details>
<summary><b>How do I clean off dry-erase marker from my whiteboard?</b></summary>

Dry-erase marker should be able to be wiped off non-porous whiteboard surfaces using the included microfiber cloth.
We recommend wiping clean the whole whiteboard after every use.
If the marker ink is left to dry for longer periods of time, it may get harder to clean off.
For marks that do not wipe off easily, you can trying using a damp cloth.
For more stubborn marks, you can draw over them with a fresh dry-erase marker.
Once drawn over, you should be able to wipe it clean with a cloth.
Please note that the marker you use for cleaning will pick up some of the color you are drawing over, so use a matching color or darker marker to clean if possible.

</details>

<details>
<summary><b>Can I decorate my Root® coding robots?</b></summary>

Yes. The top of the Root® Pro coding robot features a whiteboard surface that users may decorate using dry-erase markers, vinyl clings, or printable outfits from the [Learning Library](https://edu.irobot.com/learning-library). While the top of the Root Lite coding robot does not feature a whiteboard surface, users may still decorate this model using vinyl clings or printable outfits from the [Learning Library](https://edu.irobot.com/learning-library). 

</details>

<details>
<summary><b>How fast can Root® coding robots drive?</b></summary>

Root® coding robots can drive up to ****10 cm/s.**

</details>

<details>
<summary><b>Why do the wheels on my Root robot make a clicking sound?</b></summary>

Root’s drive wheels have internal clutches to prevent damage to the motors if Root is pushed or gets stuck.
The clicking sound is the clutch being activated when the there is too big of a force between the wheel and the motor.
If it keeps happening, make sure that nothing is blocking the wheel and preventing it from turning.

</details>

<details>
<summary><b>Why do the wheels stop when I pick the Root® Pro coding robot up?</b></summary>

The Root® Pro coding robot is designed to only drive on flat surfaces.
Its integrated cliff sensor allows the robot to detect when it is lifted.

</details>

<details>
<summary><b>Why does the color sensor turn off when I pick the Root® Pro coding robot up?</b></summary>

The Root® Pro coding robot only detects color when it's driving on a flat surface.
If too little light is refected back to the cliff sensor, the robot will turn off the color sensing.
You may cover the cliff sensor on the robot if you would like to see the color sensor run while picked up.

</details>

<details>
<summary><b>How do I calibrate the Root® Pro coding robot’s color sensor?</b></summary>

The Root® Pro coding robot will automatically calibrate to the reflectiveness of the surface underneath the robot.
We recommend that you leave the robot on a white surface for a few seconds before starting a color sensing program.

</details>

### Troubleshooting

<details>
<summary><b>Why won’t my Root coding robot connect to my Android device?</b></summary>

Many connection issues on Android devices are caused by incorrect Bluetooth permissions.
In Android, Bluetooth permissions are often included under “Location permissions”.
On your device, confirm that:
1. app-level Location permissions are enabled for the iRobot Coding app
2. device-level Location permissions turned on
3. Bluetooth is turned on

To turn on app-level Location permissions for the iRobot Coding app, long press the app icon and open the “App info” screen. 
From there, select “Permissions” → “Location” → “Allow only while using the app”. The app should also have requested this permission the first time it is opened.

To turn on device-level Location permissions, open the “Settings” app and select “Location” → “Use location”

To turn on Bluetooth, swipe from the top of the screen to bring up the Quick Settings menu and tap the Bluetooth icon. Alternatively, open the “Settings” app and select “Connected devices” → “Connection preferences” → “Bluetooth” → “Use Bluetooth”.

</details>

<details>
<summary><b>My Root® robot keeps stopping, beeping, and blinking red. Help?</b></summary>

The robot will flash red and beep when (1) the battery level gets too low or (2) it detects that a wheel is stuck. If your robot still flashes red, beeps twice, and stops moving when it is fully charged, then the robot is likely triggering a stuck or “stalled” motor error. 
 
Some reasons this error can be triggered include:
1. **Something is blocking the wheel or robot.** This is the most common reason for a motor stall. Please make sure nothing is stuck around the wheels and that they can rotate normally.
2. **The motor connector is unplugged from the printed circuit board in the robot.** You can often tell this is the problem by manually rotating both wheels with your fingers while the robot is ON. Because the motor brakes are applied when the robot is ON, if the stalled wheel is easier to spin than the non-stalled wheel, it may just be unplugged.
3. **If there is an issue with the motor itself.** If the robot is OFF for 10 seconds — and therefore the motor brakes are OFF — and the stuck wheel is harder to rotate than the other wheel, then there may be an issue with the motor or gearbox.
4. **If the wheel encoder has broken (e.g. because of a fall from a significant height).** This may be the issue if both motors feel the same when manually rotating them but one wheel moves faster than the other (making more noise) before the robot beeps and flashes red.
 
If you believe that you are experiencing this issue, please contact us with the serial number from the bottom of the robot (or a photo of the label on the bottom) along with a copy of your purchase confirmation to verify the robot's warranty status. If you did not purchase directly from us, please reach out to the respective provider.

</details>

<details>
<summary><b>Why are the lights on my Root® coding robot flashing blue?</b></summary>

If your Root® coding robot is flashing blue with the eyes off, then the robot is in “update” mode. This can happen if a firmware update is started but fails to complete successfully.

To troubleshoot this occurrence, you can manually restart the firmware update by following the instructions below:
1. Navigate to the [firmware updater page](https://code.irobot.com/update/index.html) using a Web Bluetooth® Low Energy (BLE) compatible browser, such as Chrome or Edge.
2. Press the “Pair” button and select the "ROOT BOOT" robot from the connection list. You should only see devices that are in "update” mode as connection options on this page.
3. Press the “Update” button and wait for the update to complete.

Alternatively, you may use the iOS or Android apps. When you connect to the robot from within the app, it should detect that the robot is in "update mode" and complete the firmware update process. Please contact us with a summary of your experience if you are not able to update your robot.

</details>

<details>
<summary><b>Why is the light on the back of my Root® coding robot flashing red on its own?</b></summary>

The rear light on the Root® coding robot will flash red when the battery is getting low.
Please plug it in to charge using the provided charging cable.

</details>

<details>
<summary><b>Why is my Root® coding robot frozen or unresponsive?</b></summary>

If your Root® coding robot is frozen or unresponsive, try to hold the yellow button (its nose) for 10 seconds until the robot turns off.
Then, turn the robot back on by pressing the yellow button a second time.

If the robot flashes red, the robot needs charging.
If the robot flashes blue, the robot needs to complete a firmware update.
If the robot does not move when you code a program and press play, ensure that Bluetooth is enabled and working and that the iRobot Coding app is properly connected to that robot.
You will need to reconnect to the robot after it is reset.

If your robot is still misbehaving after being reset, please contact us for assistance.

</details>

<details>
<summary><b>Why does my Root® coding robot keep disconnecting on its own?</b></summary>

If the Bluetooth connection with your Root® coding robot keeps disconnectiong, try charging your robot and your device.
A low battery can cause connectivity problems.
If both devices have enough charge, ensure that you are running the latest version of the iRobot Coding app and that the firmware on your Root® coding robot is up to date. 

</details>

## Trademarks

SAM Labs and Root are registered trademarks of SAM Labs Inc.

iRobot and Create are registered trademarks of iRobot Corporation.

The Bluetooth word mark and logos are registered trademarks owned by Bluetooth SIG, Inc. and any use of such marks by SAM Labs is under license.

Apple, App Store, iPadOS, and macOS are registered trademarks of Apple Inc.

Android, Google Play, Chrome, Chromebook, and ChromeOS are trademarks of Google LLC.

Microsoft, Edge, and Windows are registered trademarks of Microsoft Corporation in the United States and/or other countries.

Python is governed by the Python Software Foundation. All other trademarks mentioned are the property of their respective owners.

USB-C and USB Type-C are registered trademarks of USB Implementers Forum.

Raspberry Pi is a trademark of Raspberry Pi Ltd.

## License

Root® Robot Documenation is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.

You should have received a [copy of the license](LICENSE.txt) along with this work. If not, see <https://creativecommons.org/licenses/by-nc/4.0/>

[![CCBYNC40](images/CCBYNC40-88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)
