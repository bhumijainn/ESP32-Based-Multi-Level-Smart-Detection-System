# ESP32-Based-Multi-Level-Smart-Detection-System
ORBITS
Optimized Reliable Blind-aid with Intelligent Travel Stick

Affordable Smart Mobility Solution for the Visually Impaired (< ₹3,000)

 **IDEA TITLE**

Development of a Smart Blind Stick for Enhanced Mobility and Safety of Visually Impaired Person

 Problem Statement

Traditional white canes only detect ground-level obstacles, leaving users vulnerable to:

Head-level injuries from overhanging objects

Mid-level collisions with people or objects

Falls due to steps or potholes

Advanced smart canes exist, but at approximately ₹70,000, they are unaffordable for most users.

**The ORBITS Solution**

ORBITS is an intelligent, low-cost (< ₹3,000) smart blind stick designed to provide:

Three-level obstacle detection

Intuitive haptic feedback guidance

Built-in emergency assistance system

It aims to transform mobility anxiety into confidence.

 **Core Innovations**
 1. Smart Multi-Level Sensing (Sensor Fusion)

ORBITS scans surroundings across three safety zones:

Zone Level	Sensor Used	Purpose
Head Level	ToF Sensor	Detect overhead obstacles
Mid Level	Ultrasonic Sensor	Identify people & objects ahead
Ground Level	IR Sensor	Detect steps, potholes, edges

All sensors are integrated using Sensor Fusion for reliable environmental perception.

TinyML Integration

Processes sensor data intelligently

Filters environmental noise

Classifies genuine threats in real-time

Reduces false positives

2️. Touch-Based Guidance System

Instead of confusing audio alerts, ORBITS uses a Haptic Wristband:

Left motor → Obstacle on left

Right motor → Obstacle on right

Center motor → Obstacle ahead

Stronger vibration → Closer obstacle

This enables intuitive, distraction-free navigation.

3️. Emergency SOS System

Safety is critical.

Dedicated SOS button

Integrated GSM module

GPS location tracking

Sends emergency SMS with live coordinates

No smartphone app required

 **System Architecture**
Controller

ESP32 Microcontroller (Core processing unit)

Sensors

ToF (Head-level detection)

Ultrasonic (Mid-level detection)

IR sensor (Ground detection)

Communication

GSM module for SMS alerts

GPS module for live location tracking

Output

Haptic motors (Directional wristband feedback)

 **Working Principle**

Sensors continuously scan the environment.

ESP32 collects multi-zone sensor data.

TinyML processes and classifies obstacles.

Wristband provides directional vibration feedback.

In emergency situations, SOS triggers GPS-based SMS alert.

**Key Features**

16-bit embedded intelligence via ESP32

Multi-zone obstacle detection

Real-time haptic feedback

Intelligent noise filtering using TinyML

Emergency SOS with location

Fully standalone system

Cost under ₹3,000

**Impact**

ORBITS addresses the “invisible obstacle” problem by:

Reducing risk of head and chest injuries

Increasing navigation confidence

Enhancing independent mobility

Making smart assistive technology affordable

This solution bridges the affordability gap and provides dignity, safety, and independence to visually impaired users.

**Cost Advantage**
Product Type	Approx. Cost
Traditional Smart Cane	₹70,000
ORBITS	< ₹3,000
 **Future Improvements**

Object classification refinement

Rechargeable battery optimization

Waterproof casing

Mobile app companion (optional enhancement)

AI-based route learning

**Contribution**

Contributions, improvements, and feedback are welcome.
Please fork the repository and submit a pull request.
