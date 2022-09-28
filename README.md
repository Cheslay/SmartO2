# SmartOxygen

## Table of contents
* [Introduction](#introduction)
* [Features](#Features)
<!-- * [Technologies](#technologies) -->
* [Setup](#setup)

## Introduction
The purpose of this project is to make the oxygen dispensing of patients in need of oxygen easier for the healthcare personel.

## Features
The device should be able to detect the patients oxygen saturation
The device should be able to detect if the patient has chronic obstructive lung disease, to decide the target saturation
The device should dispence oxygen to the patient, to reach the patients optimal saturation

### Controller
Prior to beginning this project, the controller has already been chosen. The project will be using a Particle Argon development board kit, this microcontroller is 3V3 logic and has input for a LiPo battery as well as an onboard LiPo charger module.

### Sensor for soil moisture
Before researching sensors, let's specify a list of requirements
- **Supply voltage**: preferably 3V3 to avoid further switching losses
- **Range**: should be able to read in the range of completely dry to completely soaked soil (or just plain water)
- **Operating temperatures**: Outside temperatures during the summer, let's say 10°C to 40°C
- **Response time**: the sensor should be kept at a minimum to lower the power consumption during reads
- **Cost**: Low, this filters out any industrial-grade sensors
<!-- To do: Research and select sensor -->

### Power source
This project is going to be placed outside. For it to be mobile, we require a wireless power source. This could be anything from wind to solar or a button cell battery to a super capacitor.
As a starting point, this project will be using a LiPo battery. The reason behind this is because it's easy. I have a few laying around with capacities between 400 and 800 mAh and the microcontroller supports easy connection and charging of them. I will, however, like to set up a requirement which will later be determined if these batteries can fulfill it.
- **Capacity**: Should be able to supply the setup with power for at least two months
- **Replacable**: Definitely, this will allow you to keep it running, simply switch out with a fully charged battery

## Setup
TBD
