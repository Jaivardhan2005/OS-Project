# 🔄 Page Replacement Algorithm Simulator

An interactive web-based simulator for visualizing and comparing various page replacement algorithms used in Operating Systems memory management.

![Page Replacement Simulator](https://img.shields.io/badge/OS-Project-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Overview

This simulator provides a visual and educational tool to understand how different page replacement algorithms work in operating systems. It allows users to input custom page reference strings, specify the number of memory frames, and observe step-by-step execution of each algorithm.

## ✨ Features

- **7 Page Replacement Algorithms**
  - FIFO (First In First Out)
  - LRU (Least Recently Used)
  - Optimal (OPT)
  - LFU (Least Frequently Used)
  - MFU (Most Frequently Used)
  - NRU (Not Recently Used)
  - LIFO (Last In First Out)

- **Interactive Visualization**
  - Step-by-step execution with play/pause controls
  - Visual indication of page hits (green) and page faults (red)
  - Adjustable animation speed
  - Frame state visualization at each step

- **Comparison Mode**
  - Side-by-side comparison of all algorithms
  - Bar charts for page faults and hit ratios
  - Performance metrics for each algorithm

- **User-Friendly Interface**
  - Modern, responsive dark theme design
  - Custom page reference string input
  - Random sequence generator
  - Configurable number of frames (1-10)

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)

### Installation

1. Clone or download the repository
2. Open `project2.html` in your web browser

```bash
# No additional setup required!
# Simply open the HTML file in a browser
```

## 📖 How to Use

1. **Enter Page Reference String**: Input a comma-separated sequence of page numbers (e.g., `7,0,1,2,0,3,0,4,2,3,0,3,2`)

2. **Set Number of Frames**: Choose the number of memory frames (1-10)

3. **Select Algorithm**: Choose a specific algorithm or "All Algorithms" to compare

4. **Run Simulation**: Click "Run Simulation" to see the results

5. **Control Animation**: Use the step controls to navigate through each step:
   - ⏮️ **Prev**: Go to previous step
   - ⏭️ **Next**: Go to next step
   - ▶️ **Play**: Auto-play animation
   - ⏸️ **Pause**: Pause animation
   - **Speed Slider**: Adjust animation speed

6. **Compare Algorithms**: Click "Compare All" to see a visual comparison of all algorithms

## 📊 Algorithms Explained

| Algorithm | Description | Complexity |
|-----------|-------------|------------|
| **FIFO** | Replaces the oldest page in memory | O(1) |
| **LRU** | Replaces the least recently used page | O(n) |
| **Optimal** | Replaces the page not needed for longest time (theoretical) | O(n²) |
| **LFU** | Replaces the least frequently accessed page | O(n) |
| **MFU** | Replaces the most frequently accessed page | O(n) |
| **NRU** | Uses reference bits to approximate LRU | O(n) |
| **LIFO** | Replaces the most recently added page | O(1) |

## 📈 Metrics Displayed

- **Page Faults**: Number of times a requested page was not in memory
- **Page Hits**: Number of times a requested page was found in memory
- **Hit Ratio**: Percentage of page hits (higher is better)
- **Fault Ratio**: Percentage of page faults (lower is better)

## 🎨 Visual Indicators

| Color | Meaning |
|-------|---------|
| 🟢 Green | Page Hit - Page found in memory |
| 🔴 Red | Page Fault - Page not in memory |
| 🟣 Purple | New page entry |
| 🔵 Blue | Existing page in frame |

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No external dependencies
- **Responsive Design** - Works on desktop and mobile devices
- **Modern UI** - Glassmorphism design with gradient accents
- **Smooth Animations** - CSS transitions and keyframe animations

## 📁 Project Structure

```
OS-Project/
├── project2.html    # Main application file (HTML, CSS, JS combined)
└── README.md        # Project documentation
```

## 🎓 Educational Use

This simulator is perfect for:
- Operating Systems coursework
- Understanding memory management concepts
- Comparing algorithm efficiency
- Preparing for OS exams
- Teaching page replacement concepts

## 🔮 Future Enhancements

- [ ] Export simulation results to CSV/PDF
- [ ] Add more algorithms (Clock, Second Chance)
- [ ] Belady's Anomaly demonstration
- [ ] Working set analysis
- [ ] Custom theme options

## 📜 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to improve the simulator.

---

<p align="center">
  Made with ❤️ for Operating Systems Education
</p>
