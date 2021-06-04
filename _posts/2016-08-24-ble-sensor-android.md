---
title: 'Medical Sensor Monitoring Via BLE'
date: 2016-08-24
permalink: /posts/2016/08/ble-sensor-android/
tags:
  - BLE
  - Android
  - demos

---

Dr. Mohammad Ali Darabi is working on gum sensor for a long time, like his paper, `Gum Sensor: A Stretchable, Wearable, and Foldable Sensor Based on Carbon Nanotube/Chewing Gum Membrane`. And my job is to make the transmission wirelessly via BLE.

### Introduction

I designed the Sensor testing circuits to detect and identify the changes of our gum sensor, and forward the data to an Android-based smart phone wirelessly through the Bluetooth Low Energy (BLE) module. 

![ble-block-diagram](/files/demos/sensor_ble/ble-block-diagram.png)

As the block diagram shows, the testing procedure mainly consists of three steps. Firstly, we transformed the physical changes of the gum sensor into electrical signals by Resistance Testing Module. Then, a 10 bits Analog to Digital Convertor (ADC)  is applied to quantize the signal with the 20 Hz sampling frequency. Lastly, the digital signal is transmitted wirelessly to the smart phone through BLE links, and we can observe and study the changing properties on graphical interfaces developed by ourselves. Certainly, all the modules are powered by the Battery Module directly or by the regulated voltage. 

### Demo Presentation

<iframe width="560" height="315" src="https://www.youtube.com/embed/khnSpNPSujc" frameborder="0" allowfullscreen></iframe>

### After ...

I admire all the guys like Dr. Darabi who could be working on something that they're really interested in and something that really matters instead of just paper works. 

It was my first time to develop an android application, and also 1st time to develop the software and hardware parts at the same time on my own, and my java and engineering background help me quickly get used to android things.

### Download

Pls check BLE project on my github.