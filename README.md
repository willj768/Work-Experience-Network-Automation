# Work Experience Network Automation

A motion-triggered power management system that automatically controls network device port power states to reduce energy consumption and carbon emissions.

## Overview

This project combines IoT motion detection with network automation to intelligently manage power usage on Cisco network devices. When motion is detected in an area, the system activates a network port. When no motion is detected for a specified period, it automatically powers down the port, reducing unnecessary energy consumption and associated carbon emissions.

**Key Metrics Tracked:**
- Time saved (hours) from port shutdown periods
- Power consumption (kW) during active periods
- Carbon emissions (grams) based on electricity consumption
- Motion detection events with timestamps

## Features

- **Motion-Triggered Control**: Automatically enables/disables network ports based on PIR (Passive Infrared) sensor input
- **Energy Monitoring**: Real-time tracking of power consumption and carbon emissions
- **Configurable Scheduling**: Optional time-based monitoring to disable during weekends and after-hours
- **Web Dashboard**: Flask-based interface to visualize power usage statistics and historical logs
- **Cisco Device Integration**: Direct SSH communication with Cisco switches using Netmiko
- **Data Persistence**: CSV-based logging for motion events and power metrics

## Project Structure
