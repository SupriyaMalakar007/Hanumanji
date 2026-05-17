# Hanumanji
# HanumanJi-in-Python
Drawing Hanuman Ji by using Python Turtle.

## Run Locally (Windows/Linux/macOS)
1. Download or clone this code.
2. Open terminal in the project folder.
3. Install required libraries:
   `pip install svgpathtools svg.path tqdm opencv-python`
4. Run:
   `python hanumanji.py`

## Run on Server (Linux/VPS)
This script uses `turtle`, which needs a graphical display. On a server, run it with a virtual display.

1. Install system packages:
   `sudo apt update && sudo apt install -y python3-pip xvfb python3-tk`
2. Install Python libraries:
   `pip3 install svgpathtools svg.path tqdm opencv-python`
3. Run with virtual display:
   `xvfb-run -a python3 hanumanji.py`

If you use a GUI-enabled server, you can run normally with:
`python3 hanumanji.py`

Follow us on Instagram: https://www.instagram.com/code_with_aavi/
