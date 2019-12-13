# Softcore-Lightweight-Crypto-Performance

## Overview

This project has been done as a collaboration between California State Polytechnic University Pomona and Xilinx on developing a low power computational technology while being a cost-efficient solution. The project is aimed towards using Field Programmable Gate Array (FPGA) platforms that will use softcore processors to perform image processing, cyber security, encryption, and high-performance applications for Defense. The main benchmarking methods were performed using encryptions on the MicroBlaze platform on a Basys3 board. The encrytions consist of RSA, AES, and ASCON. All references are documented at the end of this document.


## Team Members:

- Ryan Melendez: Electrical Engineer, College of Engineering, California State Polytechnic University, Pomona.
- Burhan Alestwani: Electrical and Computer Engineer, College of Engineering, California State Polytechnic University, Pomona.


## Supervising Professor:

- Mohamed El-Hadedy: Assistant Professor in Electrical and Computer Engineering at CalPoly, Pomona

- Anas Salaheddin: Assistant Professor in Electrical and Computer Engineering at CalPoly, Pomona.


## Collaborators:

- Wen-Mei Hwu: Director of Center for Cognitive Computing Systems Research and Walter J. Sanders III-AMD Endowed Chair Professor in Elecrical and Computer Engineering at UIUC.

- Jinjun Xiong: Director of Center for Cognitive Computing Systems Research and Adjunct Research Professor at UIUC.


### Video Tutorial Link: https://youtu.be/49-BLvp7WhM

## Introduction: 
As the demand for computational power increases, the need to develop cost efficient methods for computing is constantly rising. To help solve this issue, our research is dedicated towards developing low power computational technology while being a cost-efficient solution compared to other resources. The project is aimed towards using Field Programmable Gate Array (FPGA) platforms that can be reconfigured to run applications that can be used in image processing, cyber security, encryption, and high-performance applications for Defense. 


## Ojective: 
The objective is to run an application on the FPGA board using a softcore processor (Microblaze) that will be able to efficiently run the C code. Once this objective is satisfied, our next goal is to implement the maximum units of soft-core processors working with each other efficiently on a single FPGA chip while using the minimum amount of resources. The configuration will be performed using master-slave format, which the load will be distributed across multiple cores utilized by the board. Our initial testing was performed using Discrete Fourier Transform (DFT). This was used to make sure that the Microblaze is fully functioning and exporting results. The second test we have performed was aimed towards benchmarking using various encryptions. We have used multiple encryptions on the soft core processor to generate the encryption keys.


## Future Goals:
The next objective is to design communication interfaces to connect multiple low-power FPGA platforms for rapid scalability. This allows the FPGA boards to be used at large scale projects and support the high computational demand for the power-hungry applications.


## Project Sponsors:

- Xilinx Inc.

- IBM

- IBM-Illinois Center for Cognitive Computing Systems Research
