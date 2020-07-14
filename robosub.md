---
layout: landing
title: RoboSub Team
description: Advanced autonomous underwater robotics.
image: assets/images/robosubbanner.JPEG
nav-menu: true
show_tile: true
rank: 2
---

<!-- Spotlights -->
<section id="two" class="spotlights">
	<section>
		<div class="content-noimage">
			<div class="inner">
				<p>
          RoboSub is R3’s most advanced project to date, the primary objective of which is to design and manufacture a submarine capable of participating at a high level in the RoboSub competition. The sub, or Felix as we call it, features some of the most involved design work ever completed for an R3 project.
				</p>
			</div>
		</div>
	</section>
	<section>
		<div class="image">
			<img src="assets/images/sub1.jpg" alt="Felix on a Bench" />
		</div>
		<div class="content">
			<div class="inner">
        <p>
          Felix comes from a common design philosophy within the robotic submarine community; a holonomic thruster configuration for yaw maneuvers and translations in the XY plane and, coupled Z facing thrusters for upward translations as well as roll and pitch maneuvers. The large aluminum wings serve two purposes: to hold the thrusters in place and to provide drag during roll and pitch maneuvers. A lot of time was devoted to designing a small, symmetric, and maneuverable submarine.
        </p>
			</div>
		</div>
	</section>
	<section>
		<div class="image">
			<img src="assets/images/sub2.jpg" alt="RoboSub Team at Competition" />
		</div>
		<div class="content">
			<div class="inner">
        <p>
          Felix’s control system is one of the most advanced that R3 has developed. Felix runs its navigation and object detection on a Nvidia Jetson TX2, paired with STM32 microcontrollers for high speed I/O for sensor data collection and thruster control. The microcontrollers are mounted onto custom shield boards with the power, signal processing, and low-level communication hardware. It also features a very sophisticated control algorithm, responsible for handling tasks such as generating inputs for the cascaded PID to output to the thrusters or running the YOLO V3 neural network which we trained to detect the gate, buoys, and other competitions objectives.
        </p>
			</div>
		</div>
	</section>
	<section>
		<div class="content-noimage">
			<div class="inner">
				<p>
          We are very happy to announce that all of our work went into achieving a score of 18th in our first year at the RoboNation RoboSub competition.
				</p>
			</div>
		</div>
	</section>
</section>

<div class="videoWrapper">
  <iframe src="https://www.youtube.com/embed/4EaoVBWqIN8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
