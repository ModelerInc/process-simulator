# Visual Business Process Simulator 🚀

A lightweight, interactive Single Page Application (SPA) designed to help Solutions Architects, Business Analysts, and Operations Managers visually model and simulate workflows. 

Unlike heavy enterprise Business Process Management (BPM) suites that require training and complex installations, this simulator runs entirely in your browser via a single HTML file. It allows you to stress-test workflows in real-time, identify hidden bottlenecks, and calculate the financial impact of broken processes.

## ✨ Key Features

* **Interactive Design Canvas:** An infinite panning and zooming grid where you can drag, drop, and connect Task Nodes and Decision Gates.
* **Live Simulation Engine:** Inject a variable rate of "work tokens" into your system and watch them route through the process tick-by-tick. Control playback speed or step through manually.
* **Dynamic Bottleneck Detection:** Nodes visually pulse red and trigger drop warnings when their queues exceed their configured maximum capacity.
* **Advanced Routing Logic:** Use Decision Nodes to split workflows based on percentage probabilities (e.g., 80% Fast-Track, 20% Manual Review).
* **Financial & Analytics Tracking:** The system calculates total processed items, maximum queue sizes, average wait times, active utilization rates, and the financial penalties of dropped items. 
* **CSV Export:** Download a complete simulation report to analyze your workflow data in Excel or Sheets.
* **Save & Load (JSON):** Export your mapped processes as `.json` files to share with your team, and rely on `localStorage` auto-saves so you never lose your work.

## 🛠️ Tech Stack

This project was built with simplicity and portability in mind. 
* **Zero Dependencies:** No React, Vue, Node.js, or external libraries required.
* **Single File Architecture:** The entire application (HTML5, CSS3, and Vanilla ES6+ JavaScript) is contained within one single `.html` file. 

*(Note: This application was rapidly prototyped and built using "vibe coding" in collaboration with Gemini AI).*

## 🚀 Getting Started

Because there is no backend or build process, using the simulator is instant:

1. Clone this repository or download the `simulator.html` file directly.
2. Double-click the `.html` file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Click **+ Task** to start building your process map!

## 📖 How to Use

1. **Build Your Map:** Use the left sidebar to add Tasks and Decisions. Use the "Draw Connection" button to link them together.
2. **Configure Nodes:** Click any node to open its configuration panel. Set its Processing Time (ticks), Capacity (concurrent items), Max Queue Limit, and Operating Costs.
3. **Set Input Rates:** In the Simulation Engine panel, set the Min and Max variable input rates. This determines how many items enter the start of your process every tick.
4. **Run the Simulation:** Hit **Play**. Watch the upper dashboard to monitor total system cost, dropped items, and queue backups in real-time. 

## 🤝 Contributing

Feel free to fork this project, submit pull requests, or open issues to suggest new features like specific probability distributions, resource-pooling logic, or new visual themes!
