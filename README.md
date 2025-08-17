# ⚙️ CNC 3-Axis Model using EtherCAT & TwinCAT 3
**Author:** Kaël Shelby (VTN)
## 📖 Introduction
- This project focuses on the **design and implementation of a 3-axis CNC machine model using the EtherCAT protocol**.  
- The system is built on **Beckhoff TwinCAT 3**, combined with the **EtherCAT Coupler EK1100** and extension modules for stepper motor control.

![Overview](./Images/Overview.jpg)

**Main Objectives:**
- Understand and implement the **EtherCAT protocol** in industrial applications.
- Apply algorithms for motion control and trajectory interpolation.
- Develop an intuitive **HMI interface** in TwinCAT 3.

## Overview

### 🛠️ Hardware

<p align="center">
  <img src="./Images/1.jpg" alt="Servo" width="280" height="360" style="margin-right:15px;"/>
  <img src="./Images/2.jpg" alt="Axis" width="280" height="360" style="margin-right:15px;"/>
  <img src="./Images/3.jpg" alt="Pen" width="280" height="360"/>
</p>
<p align="center">
  <img src="./Images/4.jpg" alt="Axis" width="280" height="360" style="margin-right:15px;"/>
  <img src="./Images/Circuit.jpg" alt="Circuit" width="280" height="360" style="margin-right:15px;"/>
  <img src="./Images/EtherCAT.png" alt="EtherCAT" width="280" height="360"/>
</p>

<p align="center"><em>3-Axis Motion Control System</em></p>

### 💻 Software

<img src="./Images/UI.png" alt="TwinCAT 3 HMI" style="transform: scale(0.9);"/>

<p align="center"><em>Control interface implemented in TwinCAT 3</em></p>

## 📊 Results

After completing the design and programming, the system was successfully tested.  
Key achievements include:

<img src="./Images/R2.jpg" alt="Basic trajectory interpolation" style="transform: scale(0.9);"/>
<p align="center"><em>Interpolation of basic geometric shapes</em></p>

<img src="./Images/R1.jpg" alt="UTE text interpolation" style="transform: scale(0.9);"/>
<p align="center"><em>Interpolation of text "UTE"</em></p>

## 🎥 Video Demo

👉 [Watch the demo video on TikTok](https://www.tiktok.com/@kshelbyiot/video/7531961342513712391?is_from_webapp=1&sender_device=pc&web_id=7500959777037518344)

<p align="center">
  <a href="https://www.tiktok.com/@kshelbyiot/video/7531961342513712391?is_from_webapp=1&sender_device=pc&web_id=7500959777037518344">
    <img src="./Images/Coverr.png" alt="Watch Demo Video" width="300"/>
  </a>
</p>



<p align="center"><em>Video: 3-Axis CNC Motion Control System</em></p>

## 🛠️ System Requirements

### Hardware
- Beckhoff EtherCAT Coupler **EK1100**
- Stepper motor control module **EL7041**
- Digital input module **EL1008**
- Digital output module **EL2004**
- 3 stepper motors + ball screws
- 24V DC power supply

### Software
- **TwinCAT 3** (Beckhoff)
- **Visual Studio 2017/2019** (with TwinCAT XAE integration)

## 📂 How to Open the Project
- Clone the repository to your local machine
- Open **TwinCAT 3** in Visual Studio  
- Go to `File > Open > Project/Solution`  
- Navigate to the folder **TwinCAT Project6** and open the `.tsproj` file
