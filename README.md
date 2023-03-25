# Scalable-Facial-Recognition

This repository contains two similar projects that leverage Amazon Web Services to build scalable face recognition services.

## Project 1: Elastic Face Recognition Service
In this project, we built an elastic application that can automatically scale out and in on demand and cost-effectively by using IaaS cloud resources from Amazon Web Services (AWS). The AWS infrastructure is used to build a scalable face recognition service on the cloud that has all the software components loosely coupled. Every component of AWS used is elastic and hence, the project can be scaled up and down as per the number of requests coming in.

### Features
Our cloud application performs face recognition on user-provided images using the provided deep learning model, which then returns the recognition result as output to the users.
Each image input through the website is a request to our application and our application can handle multiple requests concurrently.
It automatically scales out when the request demand increases, and automatically scales in when the demand drops.
The application should handle all the requests as fast as possible, and it should not miss any requests. In addition, the recognition requests should all be correct.

## Project 2: Real-time Face Recognition on Raspberry Pi IoT Devices
In this project, we built a distributed application that utilizes PaaS services and IoT devices to perform real-time face recognition on real videos recorded by the device. Specifically, we developed this application using Amazon’s Lambda based PaaS and Raspberry Pi based IoT. Lambda is the first and the most widely used Function as a Service PaaS. Raspberry Pi is the most widely used IoT development platform. This project is crucial as it provides experience in developing real-world, IoT data-driven cloud applications like helping find missing people/criminals, improved medical treatment, etc.

### Features
Our distributed application performs real-time face recognition on real videos recorded by Raspberry Pi based IoT devices.
We use Amazon's Lambda based PaaS to develop the application.
This project provides experience in developing real-world, IoT data-driven cloud applications like helping find missing people/criminals, improved medical treatment, etc.
