# Low-Cost Underwater Wireless Communication System Using Li-Fi

## Overview

This project presents a low-cost, portable underwater wireless communication system based on **Li-Fi (Light Fidelity)** technology.

The system uses visible light to transmit data underwater as an alternative to conventional underwater communication methods such as acoustic and RF-based communication.

The system consists of two main modules:

* **Transmitter Unit**
* **Receiver Unit**

The transmitter uses an **Arduino Uno and high-brightness LED** to transmit data through modulated visible light. The receiver uses a **BPW34 photodiode, OPA380 amplifier, ADS1115 ADC, and Arduino Uno** to detect, process, and decode the received signal.

## System Architecture

The transmitter and receiver are designed as separate modules for underwater operation.

### Transmitter Unit

* 3.7V Li-ion battery
* MT3608 boost converter
* Arduino Uno
* High-brightness LED

### Receiver Unit

* BPW34 photodiode
* OPA380 precision amplifier
* ADS1115 analog-to-digital converter
* Arduino Uno

The detailed system architecture and signal flow are available in the `diagrams/` folder.

## Working Principle

```text
Input Data
    ↓
Arduino Uno (Transmitter)
    ↓
LED Modulation
    ↓
Visible Light Transmission
    ↓
BPW34 Photodiode
    ↓
OPA380 Amplifier
    ↓
ADS1115 ADC
    ↓
Arduino Uno (Receiver)
    ↓
Decoded Data
```

The transmitter converts input data into modulated visible-light signals. The high-brightness LED transmits these signals through the water.

At the receiver, the **BPW34 photodiode** detects the transmitted light. The **OPA380** amplifies the received signal, while the **ADS1115** converts the analog signal into digital data. The receiver-side Arduino then processes and decodes the received information.

## Key Features

* Low-cost hardware implementation
* Short-range underwater wireless communication
* Visible-light-based data transmission
* Portable and battery-operated design
* Separate transmitter and receiver modules
* Modular hardware architecture
* Designed for shallow-water environments
* Uses readily available electronic components

## Performance

The system was designed and tested for short-range communication in clean, shallow-water conditions.

* **Communication range:** approximately 20–50 cm
* **Test message:** `HELLO`

## Components Used

| Component            | Purpose                             |
| -------------------- | ----------------------------------- |
| Arduino Uno          | Data generation and processing      |
| High-Brightness LED  | Visible-light transmission          |
| BPW34 Photodiode     | Optical signal detection            |
| OPA380               | Received-signal amplification       |
| ADS1115              | Analog-to-digital conversion        |
| MT3608               | Voltage boosting                    |
| 3.7V Li-ion Battery  | Portable power supply               |
| Waterproof Enclosure | Protection of electronic components |

## My Contribution

I contributed to the **overall system architecture and implementation** of the project.

My work included:

* Understanding and designing the transmitter and receiver architecture
* Working on visible-light-based underwater communication
* Arduino-based transmitter and receiver implementation
* Signal reception and processing
* Hardware integration and testing
* System-level troubleshooting
* Project documentation and technical analysis

## Applications

The proposed system can be explored for applications such as:

* Underwater robotics
* Diver communication
* Marine data logging
* Underwater sensing
* Aquaculture
* Educational optical communication systems

## Innovation

The project demonstrates a low-cost approach to underwater optical communication using readily available electronic components.

The system integrates an **Arduino-controlled LED transmitter** with a **BPW34 photodiode, OPA380 precision amplifier, and ADS1115 ADC-based receiver** into a compact communication platform.

This approach provides a simple experimental platform for exploring **visible-light communication in underwater environments**.

## Project Type

**Academic Semester Project**

## Patent

A patent application was prepared for the proposed underwater Li-Fi communication system.

The patent summary is provided separately in the `patent/` folder.

## Project Status

**Academic prototype completed and tested for short-range underwater communication.**

## Repository Structure

```text
underwater-lifi-communication/
│
├── README.md
│
├── diagrams/
│   ├── system_architecture.png
│   ├── system_flowchart.png
│   └── hardware_block_diagram.png
│
└── patent/
    └── patent_summary.md
```

