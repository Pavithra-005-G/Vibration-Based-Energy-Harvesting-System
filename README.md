# ⚡ Simulation and Analysis of Vibration-Based Energy Harvesting

## Overview

This project presents the design and simulation of a Vibration-Based Energy Harvesting System using MATLAB/Simulink. The system converts ambient mechanical vibrations into usable electrical energy through rectification, filtering, and voltage regulation stages.

The harvested energy is processed using a Full-Wave Rectifier, Filter Capacitor, and PWM-Controlled DC-DC Buck Converter to provide a stable DC output suitable for low-power electronic devices.

## Objectives

* Design and simulate a vibration-based energy harvesting system.
* Convert mechanical vibration energy into electrical energy.
* Analyze voltage, current, and power characteristics.
* Study ripple reduction and voltage regulation.
* Evaluate system performance for low-power applications.

## System Architecture

```text
Mechanical Vibrations
         │
         ▼
 AC Voltage Generation
         │
         ▼
 Full-Wave Rectifier
         │
         ▼
    DC Filter
         │
         ▼
 DC-DC Buck Converter
         │
         ▼
 Regulated DC Output
```

## Simulation Parameters

| Parameter           | Value         |
| ------------------- | ------------- |
| Input Voltage       | 20 V          |
| Output Voltage      | 8.5 V         |
| Inductance          | 1.7 × 10⁻³ H  |
| Capacitance         | 5.88 × 10⁻⁶ F |
| Load Resistance     | 8.5 Ω         |
| Switching Frequency | 25 kHz        |
| Duty Ratio          | 42.5%         |

## Results

The simulation successfully demonstrates:

* Conversion of vibration-induced AC energy into DC power.
* Effective AC-to-DC rectification.
* Ripple reduction through filtering.
* Stable voltage regulation using a buck converter.
* Suitability for powering low-power electronic devices.

## Circuit Diagram

![Circuit Diagram](https://github.com/Pavithra-005-G/Vibration-Based-Energy-Harvesting-System/blob/main/simulink.jpeg)

## Input Voltage Waveform

![Input Voltage](https://github.com/Pavithra-005-G/Vibration-Based-Energy-Harvesting-System/blob/main/INPUT%20VOLTAGE.jpg.jpeg)

## Rectified Voltage Waveform

![Rectified Voltage](https://github.com/Pavithra-005-G/Vibration-Based-Energy-Harvesting-System/blob/main/OUTPUT%20CURRENT.jpg.jpeg)

## Output Voltage Waveform

![Output Voltage](output_voltage.png)


## Applications

* Wireless Sensor Networks
* Industrial Monitoring Systems
* Structural Health Monitoring
* IoT Devices
* Wearable Electronics
* Self-Powered Embedded Systems

## Software Used

* MATLAB
* Simulink

## Future Scope

* Hardware implementation using piezoelectric transducers.
* Integration with energy storage systems.
* Advanced converter control techniques.
* Real-time testing and industrial deployment.


## Institution

Department of Electrical and Electronics Engineering
NSS College of Engineering, Palakkad

## License

This project is intended for academic and educational purposes.


