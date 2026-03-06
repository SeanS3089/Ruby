# Ruby – Lightweight Python Market Scanner  
Ruby is a clean, simple, Windows‑native market scanner built entirely in Python.  
It focuses on clarity, stability, and a minimal interface that still allows deep customization of the chart view.

Ruby is not AI‑powered. It is a lightweight, reliable tool designed for traders who want fast charting, clean visuals, and a distraction‑free workflow.

---

## Features

### Clean, Responsive Charting
- Lightweight candlestick renderer  
- Last‑N‑candles display for clarity  
- Adjustable chart view and indicator visibility  
- Smooth resizing and stable layout  

### Minimal Tkinter Interface
- Simple, clean control panel  
- Customizable chart settings  
- Light/Dark theme support  
- No clutter, no unnecessary UI elements  

### Windows Desktop Application
- Packaged as a Windows installer  
- Creates a proper Start Menu entry  
- Stores configuration in a local folder  
- No command‑line knowledge required  

### Licensing & Activation
Ruby uses a simple, local licensing system:

- Alpha Vantage API key (free tier works for testing)  
- Email address (license is locked to this)  
- License key (provided by Oly Bee Co LLC)  

Activation happens during installation and requires no server connection.

---

## Tech Stack
- **Python 3**  
- **Tkinter** (GUI)  
- **Matplotlib** (chart rendering)  
- **JSON config system**  
- **Local license verification**  

No external frameworks. No AI. No cloud dependencies.

---

## Installation

Ruby is distributed as a Windows installer.

During installation, you will be prompted for:

1. **Alpha Vantage API Key**  
   - Free to obtain with an email address  
   - Works on the free tier for testing  

2. **Email Address**  
   - Used to lock your license  

3. **License Key**  
   - Provided by Oly Bee Co LLC  

Once activated, Ruby launches normally from the Start Menu.

---

+-----------------------------------------------------------+
|                         Ruby GUI                          |
|                 (Tkinter Application Layer)               |
+---------------------------+-------------------------------+
                            |
                            v
+-----------------------------------------------------------+
|                   Chart Rendering Engine                  |
|            (Matplotlib + Overlay Modules)                 |
+---------------------------+-------------------------------+
                            |
                            v
+-----------------------------------------------------------+
|                     Market Data Layer                     |
|              (Alpha Vantage Fetch + Parsing)              |
+---------------------------+-------------------------------+
                            |
                            v
+-----------------------------------------------------------+
|                Licensing & Activation Layer               |
|     (config.json, license.lock, trial.lock, machine ID)   |
+---------------------------+-------------------------------+
                            |
                            v
+-----------------------------------------------------------+
|               File & Configuration Management             |
|            (%APPDATA% storage, theme, settings)           |
+-----------------------------------------------------------+


## 🔒 Licensing

Ruby is **proprietary software**.  
All rights reserved.  
See `LICENSE.txt` for full terms.

Redistribution, modification, reverse engineering, and commercial use are prohibited without written permission.

---

Purpose of This Repository

This repository exists to:

- Demonstrate clean, lightweight Python engineering  
- Showcase GUI layout, chart rendering, and modular structure  
- Provide a recruiter‑ready example of a real Windows application  
- Document the architecture of a simple, stable trading tool  

The full commercial version of Ruby is available through Sean Scott.

---

About the Author

Ruby is developed by **Oly Bee Co LLC**, specializing in:

- Python development  
- Data and charting tools  
- GUI applications  
- Lightweight, user‑friendly software
- RL based machine learning aimed at future prediction, specialized currently in financial markets  
 
Ruby and its sister project Scarlet reflect a focus on clarity, stability, and narratable workflows.

---

Contact

For licensing or collaboration inquiries:

**Oly Bee Co LLC**  
Email: scarletprogramming@outlook.com
