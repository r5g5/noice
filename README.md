# Noice

A cross-platform noise monitoring and sound therapy app for tinnitus management.  
Planned for **desktop (Windows, macOS, Linux)** and **mobile (Android, iOS)** using **JUCE** and **C++20**.

---

## Project Status
**Stage:** Planning & initial setup  
**Goal:** Build a minimal prototype that measures real-time environmental noise and provides basic alerts.

---

## Planned Features
- Real-time ambient noise level monitoring  
- Alerts when sound exceeds safe thresholds  
- Sound therapy modes (white, pink, brown noise)  
- Customizable alert and therapy settings  
- Cross-platform support for desktop and mobile  

---

## Tech Stack (Planned)
- **Language:** C++20  
- **Framework:** JUCE  
- **Build System:** CMake  
- **Targets:** Windows, macOS, Linux, Android, iOS  

---

## Development Plan
1. **Setup**
   - Configure JUCE and CMake build  
   - Create base app structure and audio input handling  

2. **Core Functionality**
   - Implement real-time decibel meter  
   - Set threshold-based alert system  

3. **Sound Therapy**
   - Add sound generation (white/pink/brown noise)  
   - Integrate playback controls  

4. **Cross-Platform Support**
   - Test and optimize for Android and iOS  
   - Ensure consistent UI and performance  

5. **UI & UX**
   - Design minimal, clean interface  
   - Add basic visualization for noise levels  

---

## Current CMake Setup
```cmake
cmake_minimum_required(VERSION 4.0)
project(noice DESCRIPTION "Cross-platform noise monitoring and sound therapy app")

set(CMAKE_CXX_STANDARD 20)
add_executable(noice main.cpp)
