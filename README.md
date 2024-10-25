# Project4_OSC-PD

## Team Members
* Juan Jose Toro
* Antonio Varona

## Project Description
This project implements an interactive DJ system using the Open Sound Control (OSC) Controller app and Pure Data (PD). The system is designed to enable electronic music creation and manipulation through a mobile interface, allowing real-time control of audio parameters through various widgets. Each interaction with the OSC Controller produces unique audio responses in Pure Data, creating an immersive DJ experience.

## How It Was Done
1. **OSC Controller Integration**: 
   * We mapped each widget in the OSC Controller layout to specific audio parameters in Pure Data.
   * All available widgets (sliders and buttons) were utilized to provide comprehensive control over the audio.
   * Real-time communication between OSC and PD enables immediate audio feedback.

2. **Pure Data Implementation**:
   * Created custom patches for audio processing and manipulation.
   * Implemented various audio effects and controls including:
     * Volume control through sliders.
     * Filter effects triggered by buttons
     * Real-time audio effect processing.

3. **System Architecture**:
   * OSC Controller provides the user interface through mobile devices.
   * Pure Data handles all audio processing and generation.
   * Network communication enables wireless control of the system.

## Requirements
- Pure Data
- OSC Controller App
- Stable network connection between devices






