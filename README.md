# GrapherV1.0
Grapher is the standalone application python based one, making the work of drawing graphs accurately  looks as using traditional manual format 

# Professional Lab Graph Tool (GrapherV1.0)

A Python-based professional graph plotting tool designed for university laboratory work.

## Features
- Multiple graphs in one workspace
- Grid toggle (small & big grid)
- Point customization (shape, size, color)
- Curve fitting (Cubic Spline)
- Line style and darkness control
- PNG and PDF export with margins
- A4 lab-graph style layout



## Requirements
- Python 3.8+
- PyQt5
- NumPy
- SciPy

## Installation
```bash
pip install -r requirements.txt
python grapher.py

## macOS Users

If the app does not open after downloading:

1. **Right-click → Open**  
   - For the first launch only, this allows macOS to run the app.

2. **If macOS still blocks the app**:  
   - Open **Terminal** (Cmd + Space → type `Terminal`).  
   - Make the app executable:  
     ```bash
     chmod +x
     ```  
     Then **drag the Grapher1.0.app** icon into the Terminal window and press **Enter**.  
   - Remove the quarantine flag:  
     ```bash
     sudo xattr -rd com.apple.quarantine
     ```  
     Then **drag the Grapher1.0.app** into Terminal and press **Enter**.  
     Enter your Mac password if prompted.

3. **Open the app again**  
   - It should now run normally.
