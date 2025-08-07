# Fsociety

A no-root network stress testing tool for security professionals.
Simulate HTTP load to test the resilience of web applications. Supports Termux, Linux, Windows, and macOS. Includes real-time metrics and configurable multi-threading.


---

🚀 Key Features

No root required (Termux/Linux compatible)

Multi-threaded HTTP requests

Randomized headers for evasion

Real-time packet counter

Automatic dependency installation



---

📦 Installation

📱 Termux (Android)

pkg update && pkg upgrade -y
pkg install git python -y
git clone https://github.com/Demon33gio/Fsociety.git
cd Fsociety
python fsociety.py

🐧 Linux (Debian/Ubuntu)

sudo apt update && sudo apt install python3 python3-pip git -y
git clone https://github.com/Demon33gio/Fsociety.git
cd Fsociety
python3 fsociety.py

🐧 Linux (Arch/Manjaro)

sudo pacman -Syu python python-pip git
git clone https://github.com/Demon33gio/Fsociety.git
cd Fsociety
python fsociety.py

🪟 Windows

1. Install Python 3.7+ from python.org


2. Make sure to check "Add Python to PATH" during installation


3. Then run:



git clone https://github.com/Demon33gio/Fsociety.git
cd Fsociety
python fsociety.py

🍎 macOS

brew install python git
git clone https://github.com/Demon33gio/Fsociety.git
cd Fsociety
python3 fsociety.py


---

⚙️ Usage

python3 fsociety.py

Enter the target URL when prompted

Choose the number of threads (default: 20)

Enable verbose logging if needed (y/n)

The test will begin – press Ctrl + C to stop



---

🧠 Technical Info

Requires Python 3.7+

Dependencies: requests, httpx, colorama

No special permissions or root access required



---

⚖️ Legal Disclaimer

This tool is intended strictly for authorized testing and educational purposes.
Do not use it on networks or websites you do not own or have explicit permission to test.
Unauthorized use is illegal.


---

📄 License

Licensed under the GNU General Public License v3.0


---

> Note: This is a lightweight version focused on core functionality.
For issues or support, please open an issue in this repository.

