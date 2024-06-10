# Telepathy: Interactive Parkour Game Controlled by EMG Signals

## Overview
This project, "Telepathy," demonstrates the integration of neuroscience, embedded systems, and interactive technology by using Electromyography (EMG) to control a parkour game displayed on a 16x2 LCD screen. The project aims to make complex scientific concepts in neuroscience and bio-engineering accessible through hands-on learning experiences.

## Group Members
- [Matin Huseynzade](https://github.com/chillmatin)
- [Fahrettin Çetin](https://github.com/fhricetin)
- Berkan Gönülsever

## Project Description
This project explores the practical applications of neural communication and control using EMG, which captures electrical activity produced by skeletal muscles to detect and interpret muscle movements. The data is processed using an Arduino microcontroller to control an interactive parkour game on an LCD screen.

### Objectives
- **Educational Engagement:** Make sophisticated scientific concepts accessible through practical demonstrations.
- **Practical Demonstration:** Showcase the real-time control of digital interfaces using muscle activation.
- **Interdisciplinary Integration:** Combine hardware and software components to create interactive applications.
- **Innovation Inspiration:** Inspire future developments in human-machine interaction and assistive technologies.

## Hardware Requirements
- Arduino UNO
- Electromyography (EMG) Sensor
- 16x2 Arduino LCD Screen
- 10k Potentiometers (2x)
- 9V Batteries (3x)
- Electronics Breadboard
- Jumper Wires
- Resistors

## Software Requirements
- Arduino IDE
- LiquidCrystal Library for Arduino

## Setup and Configuration

1. **Hardware Integration:**
    - Connect the EMG sensor to the Arduino UNO.
    - Connect the 16x2 LCD screen to the Arduino.
    - Use potentiometers to control the contrast and brightness of the LCD screen.
    - Power the Arduino and EMG sensor with 9V batteries.

2. **Software Setup:**
    - Install the Arduino IDE.
    - Include the LiquidCrystal library in your Arduino sketch.

3. **Code Implementation:**
    - Copy the provided Arduino code into the Arduino IDE.
    - Upload the code to your Arduino UNO.

## Usage
1. **Initialize Graphics:**
   - The custom characters for the game elements are created using the LiquidCrystal library and displayed on the LCD screen.

2. **Read EMG Sensor Values:**
   - The Arduino reads the EMG sensor values, processes the data to calculate a moving average, and determines muscle activation based on a predefined threshold.

3. **Control the Game:**
   - When muscle activation is detected, the game character jumps, simulating an interactive game control mechanism.

4. **Play the Game:**
   - The game logic updates the terrain and character positions based on the EMG signal. When muscle activation is detected, the character jumps, creating a continuous parkour challenge on the LCD screen.

## Demonstration
Watch the video demonstration of the "Telepathy" project:

[![Telepathy Project Demonstration](https://img.youtube.com/vi/s6AagdaxEYI/0.jpg)](https://www.youtube.com/watch?v=s6AagdaxEYI)

## Results
- The project successfully demonstrates the integration of EMG signal processing with an interactive digital application, providing a tangible demonstration of how biological signals can control digital interfaces.

## Future Work
- **Enhanced Signal Processing Algorithms:** Develop more sophisticated signal processing algorithms to improve accuracy and reliability.
- **Integration with Additional Educational Content:** Combine real-time physiological data with virtual reality environments for immersive learning experiences.
- **Expansion to Assistive Technologies:** Extend the project to develop intuitive and effective prosthetic devices or rehabilitation tools.
- **Gym and Physiotherapy Applications:** Adapt the technology for gym and physiotherapy settings to monitor and enhance physical training and rehabilitation exercises, providing real-time feedback and personalized workout plans.

## Report
For detailed information, please refer to our project report: [Telepathy Term Project Report](https://github.com/chillmatin/Telepathy/blob/main/TermProjectReport.pdf)

## References
- Brooks, J. (2020). About backyard brains. [Link](https://www.instructables.com/Arduino-LCD-Game/)
- Gage, G. (2015). How to control someone else’s arm with your brain. [Link](https://www.youtube.com/watch?v=rSQNi5sAwuc&t=1s)
- Mindhe, A. (2021). Parkour game using Arduino. [Link](https://www.hackster.io/mindhe_aniket/parkour-game-using-arduino-c66275)
