+++ 
draft = true
date = "2019-07-01"
title = "Bio-inspired motor control learning"
slug = "bioinspired-motor-control-learning"
+++

  ![bio-inspired locomotion](/img/bio-inspired-locomotion.gif)


We developed a new bio-inspired control system for robots based on the human cerebellum. The cerebellum controls our movements and adjusts them to the surroundings, both in relation to activating the right muscles and in relation to making the necessary adjustments to enable us to walk in dynamic environments. We utilized the ability of the cerebellum to learn from its mistakes so that it achieves the desired action.

To emulate the cerebellum, we used a real-time learning algorithm ([Locally Weighted Projected Regression](https://homepages.inf.ed.ac.uk/svijayak/publications/vijayakumar-ICML2000.pdf)) which learned the change in phases for each hindlimb during walking. The learning algorithm learnt the specific optimal phases for specific limb configurations. This motor learning technique was used for motor control.

The experiments involved a musculoskeletal mouse robot which was simulated in Gazebo and controlled using ROS. It was made to walk on two rolling belts, one for each hindlimb. The speed of one of the belt was then increased, and the robot automatically adjusted the walking parameters to stabilize the movement. These provisional findings confirm the results achieved under similar tests with real mice and humans. 


In the [news](https://www.dtu.dk/english/news/nyhed?id=%7BB28DBED6-5DFC-4815-8BD4-4416130F635D%7D)