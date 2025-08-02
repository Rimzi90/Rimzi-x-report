# 🚨 Rimzi-X Report Tool

**Rimzi-X Report** is a Python-based Instagram Mass Reporting Simulation Tool — created only for **educational and ethical testing purposes**. It simulates mass reports using fake IPs, emails, reasons, and user agents, and generates log files for analysis.

## 📦 Features

- 🔀 Random report reasons and messages
- 🕵️ Fake emails, IPs, and user-agents using `Faker`
- 🌈 Colorful terminal output using `Colorama` and `Termcolor`
- 🔁 Multi-threaded reporting simulation
- 📁 JSON logs saved in `Red-X_logs/`

---

## 📲 Installation (Termux Compatible ✅)

### 🔧 Step-by-step Setup:

```bash
# 1. Update Termux packages
pkg update && pkg upgrade

# 2. Install Python & Git
pkg install python git -y

# 3. Clone this repository
git clone https://github.com/Rimzi90/Rimzi-x-report.git
cd Rimzi-x-report

# 4. Install required Python libraries (Method 1)
pip install -r requirements.txt

# --- OR ---

# Install libraries manually (Method 2)
pip install faker colorama termcolor pyfiglet tqdm

# 5. Run the tool
python main.py
