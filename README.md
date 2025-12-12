📡 Signal Architect: ML Operations Simulator

A gamified educational experience demystifying Machine Learning for the Telecommunications industry.

📖 About The Project

Signal Architect is an interactive browser-based game designed to teach the fundamental concepts of Applied Machine Learning to non-technical stakeholders and students.

Set in the world of Telecommunications, the player acts as a Network Architect. The goal is to balance Network Integrity (preventing dropped calls) with Cost Efficiency (preventing wasted electricity) by using ML models to forecast user demand.

Key Learning Outcomes:

Data Patterns: Understanding Linear trends vs. Seasonality vs. Chaotic anomalies.

Model Selection: Why we choose different algorithms (Linear Regression vs. Random Forest vs. Neural Nets) for different problems.

Underfitting/Overfitting: Visually experiencing what happens when a model is too simple for complex data.

Capacity Planning: The business impact of ML predictions.

🎮 Game Features

📱 Mobile-First Design: Vertical layout optimized for smartphones and tablets.

🗣️ AI Voice Guidance: Features "Aria," a text-to-speech assistant that guides the player (requires audio enabled).

📊 Real-Time Simulation: Watch traffic hit your network in real-time to see if your predictions hold up.

🎨 Visual Storytelling: CSS animations bring the scenarios to life (Constructing buildings, Day/Night cycles, Viral smartphone notifications).

⚡ Single-File Architecture: The entire game runs from a single index.html file with no backend 

🕹️ How to Play

Analyze Phase: Look at the historical data points (Blue Line). Is it going up steadily? Waving up and down? Or spiking randomly?

Select Model: Choose the ML algorithm that best fits the visual pattern.

Linear Regression: Good for straight lines.
Random Forest: Good for repeating waves.
Deep Neural Net: Good for chaos and noise.

Configure Capacity: Use the slider to set your Server Capacity (Green Line) based on the model's forecast (Purple Line).

Deploy: Watch the simulation. If traffic exceeds capacity, you lose integrity!

🚀 How to Run Locally
You don't need to install Node.js, NPM, or any complex servers.
Download the index.html file from this repository.
Double-click index.html to open it in Chrome, Safari, or Edge.
Enjoy!

🌐 How to Deploy (GitHub Pages)

This game is designed to be hosted for free on GitHub Pages.
Fork/Clone this repository.
Go to Settings > Pages.
Under Source, select Deploy from a branch.
Select your main branch and click Save.
Wait about 60 seconds, and GitHub will provide your live URL.
🛠️ Built With
HTML5
React 18 (via CDN)
Tailwind CSS (via CDN for styling)
Lucide React (for Icons)
Web Speech API (for Voice Synthesis)
📄 License
Distributed under the MIT License. See LICENSE for more information.
Designed for educational purposes to illustrate ML solutions in real-world scenarios.
