# Caredrop
Low-cost, crowd-sourced air drop solutions to quickly deliver food, water, and medicine to remote areas.

There is great need to efficiently air drop significant quantities of food, water, and medicines to distressed populations in remote locations. Numerous research groups have investigated this by using autonomous flying drones [1,2], but the solutions described so far do not scale well, Specifically, the solutions available today are limited in payload size and have a very high total solution cost. The CareDrop project is focused on what is achievable today with existing open source aircraft and autonomous guidance systems software. In addition, the concept of global and local populations crowd sourcing an air drop solution is explored so a global crowd-sourcing network can support future caredrops quickly and at much lower cost than if conducted regionally.

Introduction

The technical goal of the caredrop project is to develop easy to follow open source plans for a reusable unmanned aerial drone capable of safely delivering a 25 kg payload to a location that is 80 km away with a total drone cost of under $7K. Ease of use of this system is crtiical since technically capable teams with limited or no flight experience will need to build, deploy, and maintain these drones, potentially over many months of time.

Preliminary Solution

A practical solution to this problem is to take an existing and airworthy proven ultralight aircraft design and adapt it for this problem. Rather than carry a pilot, these aircraft can be easily adapted to drop a 25 kg payload either as a single payload drop or with multiple care packages over a designated flight plan. One of the least expensive and mature ultralight aircraft designs is the Affordaplane [3], which claims to have a total cost of between $4K and $7K and a total build time of around 250 hours. It is very likely that the construction time can be greatly reduced without sacrificing quality by using rapid construction techniques (e.g. pop-rivets instead of bolts) and modern large format 3D printers.

Rather than support a human pilot, numerous changes can be made that better supoort an autonomous air drop goal. The single pilot seat area of the aircraft can be modified to hold and release the payload. Choosing the pilot position location for the payload is advantageous as the stability of the plane is least impacted when a payload is released from near the center of gravity of the aircraft. There are also numerous other ultralight designs that are potentially lower cost to manufacture and operate with components that should be reviewed and considered for this project.

The engine of this propeller driven aircraft would ideally be fully electric with battery provided energy given the lower complexity and ease of use of electric vehicles. However, the current cost of just the batteries needed for an all electric propelled solution is between $8K and $24K. Thus the current design is focused on gasoline powered air cooled engines with at least 30 horse power (at continous use). Numerous ultralight engines are available for this and although many are too expensive, numerous persons and groups have built ultralight aircraft using motorcycle and lawnmower engines. In addition, there are reports of power generation engines (e.g. Generac, Kohler) being repuprosed for this task. However, the RPM and torque reuirements for aircraft differ enough that modifications are needed including gear boxes, which takes extra time and money to deploy.

Autonomous flight control can be provided by a combination of open source RC model aircraft control technology (Pixhawk [4], Ardupilot [5]) and large model aircraft servos and sensors. The open source flight control community has developed the ability plan missions and autonomously fly small aircraft to achieve a mission including take-off, flight tracking, and landing.

An interesting possibility is to have groups of persons around the world perform construction of parts or all of this aircraft. During the COVID-19 pandemic numerous groups around the world created cloth masks and other essential components for healthcare workers. For example, current large format 3D printers can be used to create near perfect parts with resilient materials (e.g. PLA+, PETG, ASA) that can be assembled (with strong bonding adhesives) to form large aircraft parts. 

To achieve global support for this project the designs for the aircraft have to be open, modular, and well-specified, allowing groups around the world to contribute without mismatch errors on final construction. As such it is recommended that all components are made with metric units.

Clearly at this stage we are at the brainstorming phase, exploring potential plans and ideas. Hopefully soon, with the help of the open source community, we will have some initial plans and small scale tests to validate the approach.

References

[1] Mathisen, S.G., Leira, F.S., Helgesen, H.H. et al. Autonomous ballistic airdrop of objects from a small fixed-wing unmanned aerial vehicle. Auton Robot 44, 859–875 (2020). https://doi.org/10.1007/s10514-020-09902-3.

[2] Bluman, J, Carter Vault, D, Soon, WK, Talbott, R, Willis, J, Kopeikin, A, & Prosser, E. "Autonomous Drone Delivery From Airdrop Systems (ADDAS): Aerially Deploying Folding-Wing Drones for Ground Reconnaissance." Proceedings of the ASME 2020 International Mechanical Engineering Congress and Exposition. Volume 4: Advances in Aerospace Technology. Virtual, Online. November 16–19, 2020. V004T04A018. ASME. https://doi.org/10.1115/IMECE2020-24046

[3] http://www.affordaplane.com/

[4] https://pixhawk.org/

[5] https://ardupilot.org/
