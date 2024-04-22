# Digital Filter Design Tool

Welcome to the Digital Filter Design Tool repository! This web-based application allows users to design custom digital filters through an interactive and intuitive interface. Users can place zeros and poles on the z-plane, modify their attributes, and instantly visualize the resulting filter's frequency response.

## Features

- **Interactive Z-Plane Visualization**: Users can place, drag, and remove zeros and poles on the z-plane. The unit circle is displayed for reference, assisting in the design of stable filters.
- **Dynamic Frequency Response Graphs**: The application provides real-time magnitude and phase response graphs based on the current zero-pole configuration.
- **Real-time Signal Processing**: Apply the custom filter to a signal (min 10,000 points) and observe the filtering process in real-time with adjustable speed controls.
- **Phase Correction with All-Pass Filters**: Incorporates a library of all-pass filters to correct phase issues, with the capability for users to add custom all-pass filters.
- **User-Friendly Interface**: Designed with usability in mind, the tool includes visual aids such as sliders and interactive graphs to enhance user experience.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager)
- A modern web browser that supports ES6 (Chrome, Firefox, Edge, Safari)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/digital-filter-design.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd digital-filter-design
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```

### Running the Application

1. **Start the server:**
   ```bash
   npm start
   ```
2. **Open a web browser and navigate to:**
   ```
   http://localhost:3000
   ```

## Usage

- **Designing Filters:**
  - Click on the z-plane to add zeros or poles.
  - Drag zeros or poles to modify their locations.
  - Right-click (or long-press) on a zero or pole to delete it.
  - Use the control panel to add conjugates, clear elements, or adjust filter processing speed.

- **Applying Filters to Signals:**
  - Load a signal by using the upload functionality.
  - Adjust the slider to control the speed of the real-time filtering process.
  - Observe the original and filtered signals on the corresponding graphs.

## Images
![IMG-20240422-WA0033](https://github.com/omarelansary/Digital-Filter-Design-website/assets/73857229/e43cb276-03a3-4d51-872e-b2f3a62cb08b)
![IMG-20240422-WA0032](https://github.com/omarelansary/Digital-Filter-Design-website/assets/73857229/32b3f7db-5b7c-4887-bf64-f37475232871)
![IMG-20240422-WA0031](https://github.com/omarelansary/Digital-Filter-Design-website/assets/73857229/69badd31-7423-42b2-9a8a-ea43e3c1791d)
![IMG-20240422-WA0034](https://github.com/omarelansary/Digital-Filter-Design-website/assets/73857229/da67c463-ee67-4113-99b5-f422a476d55b)
![IMG-20240422-WA0035](https://github.com/omarelansary/Digital-Filter-Design-website/assets/73857229/c9135346-a336-462e-9508-fffb6fddcce5)

