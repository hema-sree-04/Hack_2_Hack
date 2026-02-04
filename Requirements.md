# Requirements Document – AI-Powered Air Drawing System (Zillion Minds)

## 1. Introduction

This document defines the functional and non-functional requirements for the AI-Powered Air Drawing System designed to enable touchless digital teaching using hand gestures.

## 2. Stakeholders

* Teachers
* Students
* School Administration
* Education Technology Providers

## 3. Functional Requirements

### FR1: Hand Detection

* The system shall detect teacher hand movements using a camera.

### FR2: Gesture Recognition

* The system shall recognize predefined gestures for drawing.

### FR3: Air Drawing

* The system shall convert hand movements into digital drawings on a virtual whiteboard.

### FR4: Real-Time Display

* The system shall display drawings in real time without noticeable delay.

### FR5: Touchless Operation

* The system shall operate without physical contact with any device or board.

### FR6: Classroom Compatibility

* The system shall work with basic computers and standard cameras.

## 4. Non-Functional Requirements

### NFR1: Performance

* The system should process video frames in real time (minimum 20 FPS).

### NFR2: Usability

* The system should be easy for teachers to learn and use.

### NFR3: Reliability

* The system should operate continuously during a class session without crashing.

### NFR4: Scalability

* The system should support future feature expansion.

### NFR5: Affordability

* The system should not require expensive hardware.

## 5. Hardware Requirements

* Basic computer or laptop
* Standard webcam
* Display screen or projector

## 6. Software Requirements

* Python 3.x
* OpenCV
* MediaPipe
* Operating System: Windows / Linux

## 7. Assumptions & Constraints

* Adequate lighting is available
* Camera positioned correctly
* Internet connection optional

## 8. Use Case

**Actor:** Teacher

**Scenario:**

1. Teacher stands in front of the camera
2. System detects hand gestures
3. Teacher draws in the air
4. Drawings appear on virtual board

---

Prepared for Hackathon & AI for Bharat submissions
