# Patent Summary

## Title

**Low-Cost Underwater Wireless Communication System Using Li-Fi**

## Technical Field

This invention relates to underwater wireless optical communication systems and, more particularly, to a low-cost visible-light-based system for short-range underwater data transmission.

## Problem Addressed

Conventional underwater communication methods such as acoustic communication can involve higher cost, complexity, and limitations for short-range applications.

This project explores visible light as an alternative communication medium for short-range underwater data transmission.

## Proposed System

The proposed system consists of separate transmitter and receiver modules.

### Transmitter

* Arduino Uno
* High-brightness LED
* MT3608 boost converter
* 3.7V Li-ion battery

The Arduino generates and modulates the communication signal, which is transmitted through the high-brightness LED using visible light.

### Receiver

* BPW34 photodiode
* OPA380 precision amplifier
* ADS1115 ADC
* Arduino Uno

The BPW34 photodiode detects the transmitted optical signal. The OPA380 amplifies the received signal, and the ADS1115 converts the analog signal into digital data for processing by the Arduino.

## Key Technical Features

* Visible-light-based underwater communication
* Low-cost electronic components
* Separate transmitter and receiver modules
* Portable battery-powered operation
* Optical signal detection and amplification
* Digital signal processing using Arduino
* Short-range underwater communication

## Prototype Performance

The prototype was designed for short-range communication in clean, shallow-water conditions.

**Test message:** `HELLO`

**Approximate communication range:** 20–50 cm

## Potential Applications

* Underwater robotics
* Underwater sensing
* Marine data collection
* Aquaculture
* Diver communication
* Educational optical communication systems

## Project Status

Academic prototype developed and tested for short-range underwater optical communication.

## Patent Status

**Patent application filed. Publication is currently pending.**

The application is expected to be published by the Patent Office in the coming months.

> This file provides a high-level technical summary only. It does not contain the complete patent specification, claims, inventor information, or other confidential filing details.
