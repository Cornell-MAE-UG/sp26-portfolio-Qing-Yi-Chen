---
layout: project
title: MAE 3780 Robot Project
description: MAE 3780 - Mechatronics Autonomous Cube-Collecting Competitive Robot Final Project
technologies: [Arduino, C++, Circuits, Autodesk Fusion 360, 3D-Printing, Rendering]
image: /assets/images/robot.jpg
---

For MAE 3780: Mechatronics, we had to design, prototype, test, and run an autonomous cube-collecting robot made with Arduino in class-wide competitive with 61 teams total. Our robot design ended up winning us 2nd place out of the 61 teams total. We also successfully beat the TA team's robot.

We opted to go for a Roomba-inspired, four wheel drive (high torque, lower speed), and wide-mouthed design within a $40 budget and 8" x 8" bounding box. This overall design proved to be very successful as it as able to push other robots off the playing field with its pure torque. Our robot would then resume going back to the board to collect the remaining blocks while the opponents was stuck off the field. AT the end of nearly all our rounds we would end up with more blocks than the opponents because we pushed them off the board, which allowed us to win the round and advance.

![Photo of rendering]({{ "/assets/images/render.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

My personal contribution to this group robot project was being responsible for modeling the chassis for the robot in Autodesk Fusion 360 CAD, sending the file to be printed at the RPL (Rapid Prototyping Lab) in a timely manner during a busy printing season, drawing up the flowchart for the robot's Arduino code structure, debugging the code so the robot could successful border detect, and helping connect the wires.

The CAD was the biggest contribution out of all my efforts because the role included having to come up with a strong yet lightweight chassis design that could fit all our moving components in the tight bounding box without any of them bumping into each other. The spinning straws in the front should not hit the wheels and the wheels should not touch other wheels. The border-detecting QTI sensors had to be mounted at a specific height away from the floor where its sensor was just barely above the ground for it to be able to properly differentiate between the colored playing field and black borders around the square field. We also had to severely cut down on volume and sparse density infill during printing due to high 3D-printing costs based on grams of PLA plastic used, which made us balance structural integrity with mass reduction. This overall made a very challenging task of building a chassis able to meet all these demands, but I successfully made up with a CAD design able to meet all those requirements. I was even able to add most of the real life components to the CAD assembly, which allowed me to make a render of the robot in Fusion 360.

Here is the flowchart:

![Photo of flowchart]({{ "/assets/images/flowchart.jpg" | relative_url }}){: .inline-image-l}

Overall, I believe our robot was highly successful because we came in 2nd place out of 61 whole teams, finished all our milestones (design proposal, movement, color and line detection, and cube collection) successfully and on time, worked synergistically as a team, were able to debug the code, stayed within the budget, and fit into the bounding box on competition day.

I believe I contributed my fair part to this winning Mechatronics final project as well as my other two teammates who contributed their fair parts.

Here is the final report PDF for viewing: [MAE 3780 Final Report]({{ "/assets/Mecha-Final-Report.pdf" | relative_url }})
