---
date: '2'
title: 'BMS - Electric Vehicle'
cover: './GUI.png'
#github: 'https://github.com/bchiang7/spotify-profile'
external: 'https://ieeexplore.ieee.org/document/9008088'
tech:
  - C++
  - GTK+
  - Controller Area Network
---

A custom Battery Management System was designed and developed end to end. This involves the pcb designing, cell data logging and telemetry. The system/cells data is wirelessly transferred using a CAN protocol to a PC using BeagleBone black processor where a real time GUI using GTK+ dashboard is created to display all the cell statistics and their criticality statuses. The work was later extended to predict the State of Charge (SoC) with the help of neural networks.
