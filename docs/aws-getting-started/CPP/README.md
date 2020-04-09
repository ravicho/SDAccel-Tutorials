# Getting Started on AWS F1 with SDAccel and C/C++ Kernels

This getting started guide is intended for developers looking to create SDAccel applications on AWS F1 using acceleration kernels created from C/C++ or OpenCL™ functions.


>**IMPORTANT:**  For SDAccel based labs, Makes sure to use the “FPGA Developer AMI - 1.7.0” and Xilinx Tools: 2019.1 to run these labs.
For Vitis based labs, Make sure to use “FPGA Developer AMI - 1.8.1” and these labs can be accessed  [here](https://github.com/Xilinx/AWS-F1-Developer-Labs)


## Prerequisites
A number of preparation steps are required before being able to connect to an F1 instance. This module will show you how to:
- Create an AWS account
- Create an S3 bucket
- Prepare your private connection keys
- Request access to AWS F1 instances

[**FOLLOW THE INSTRUCTIONS**](../PREREQUISITES/README.md)

<hr/>

## 1. Create, configure and test an AWS F1 instance
This module will show you how to:
- Launch and configure an AWS F1 instance
- Connect to the instance, and run a simple test
- Close the session

[**FOLLOW THE INSTRUCTIONS**](STEP1.md)

<hr/>

## 2. Run your first SDAccel program on AWS F1
This module will show you how to:
- Create and configure a new SDAccel project
- Compile, profile, and accelerate your test application

[**FOLLOW THE INSTRUCTIONS**](STEP2.md)

<hr/>

## 3. Learn more about AWS F1 and the SDAccel C/OpenCL flow
This module provides online training videos on the following topics:
- Introduction to AWS F1 and the SDAccel Development Environment
- AWS F1 hardware specifications and requirements
- Fundamental Concepts of Application Host Code
- OpenCL Memory Architecture

[**FOLLOW THE INSTRUCTIONS**](STEP3.md)

<hr/>

## 4. Practice and experiment with C/C++ kernels
This module will show you how to:
- Run additional labs and examples on F1
- Learn more about SDAccel
- Get support and troubleshoot issues

[**FOLLOW THE INSTRUCTIONS**](STEP4.md)

<hr/>

## 5. Install and run SDAccel on your own machine
The AWS F1 instances loaded with the FPGA developer AMI provide all the necessary tools to develop, compile, execute and debug your application in the Amazon cloud. Optionally, it is also possible to develop and compile your application on your own machine and upload it to AWS for execution and debug in the cloud.

This optional module will show you how to:
- Install and license SDAccel locally on your machine
- Compile a simple example locally
- Upload and execute it on AWS F1

You will need the following:
- A Xilinx account — create one [here](https://www.xilinx.com/registration/create-account.html)
- A Linux computer running either:
  - Ubuntu 16.04.5 LTS, 18.04.1 LTS
  - CentOS 7.4, 7.5, 7.6
  - RHEL 7.4, 7.5, 7.6

[**FOLLOW THE INSTRUCTIONS**](STEP5.md)
<br>
<hr/>
<p align="center"><sup>Copyright&copy; 2019 Xilinx</sup></p>
