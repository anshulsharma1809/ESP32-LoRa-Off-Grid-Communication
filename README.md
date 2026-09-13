# ESP32 LoRa Off-Grid Communication System

## 📡 Project Overview

This project demonstrates a wireless off-grid communication system using **ESP32 and LoRa technology**.

The system is designed to allow multiple nodes to exchange messages over LoRa without relying on Wi-Fi or cellular networks.

The project was developed as an academic project during my B.Tech in Electronics & Communication Engineering.

## 🎯 Objectives

- Understand LoRa-based wireless communication
- Interface a LoRa module with ESP32
- Implement communication between multiple nodes
- Display received and transmitted messages
- Understand basic addressing and message handling
- Explore communication in situations where conventional internet connectivity is unavailable

## 🧩 Hardware Used

- ESP32 development board
- LoRa module
- TFT ST7735 display
- Keypad
- Buzzer
- Battery/power source
- Connecting wires

## ⚙️ Main Features

- Wireless communication using LoRa
- ESP32-based control
- Multi-node communication
- Message transmission and reception
- Device identification
- Broadcast messaging
- TFT display for user interface
- Buzzer indication for received messages

## 🔌 Communication Interfaces

The project involved interfacing different peripherals with the ESP32, including:

- SPI
- GPIO
- Display interface
- Keypad input
- Buzzer output

## 🏗️ System Architecture

```text
        ┌───────────────┐
        │    ESP32      │
        └───────┬───────┘
                │
        ┌───────▼───────┐
        │  LoRa Module  │
        └───────┬───────┘
                │
         Wireless LoRa
          Communication
                │
       ┌────────▼────────┐
       │   Other Nodes   │
       │ Node 1 / 2 / 3  │
       └─────────────────┘
