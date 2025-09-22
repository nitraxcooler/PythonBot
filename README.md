# 🐍 PythonBot

PythonBot is a lightweight AI chatbot powered by Hugging Face Transformers and PyTorch.  
This project lets you chat with a locally running model and experiment with conversational AI.

---

## ✨ Features
- 🤖 Chat with a pre-trained model (LoRA fine-tuned for better responses).  
- ⚡ Runs locally—no API keys required once downloaded.  
- 🖥️ Can be converted to a portable `.exe` using PyInstaller.  
- 🧰 Easy to modify and retrain.

---

## 📥 Installation

### 1️⃣ Clone the repository
git clone https://github.com/your-username/PythonBot.git
cd PythonBot

### 2️⃣ Create and activate a virtual environment
python -m venv venv
# Windows
.\pybot-venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

### 3️⃣ Install dependencies
pip install -r requirements.txt

▶️ Usage

Run the bot:

python pythonbot_local.py


To build a portable .exe:

pyinstaller --onefile --noconsole --add-data "pythonbot-lora;pythonbot-lora" pythonbot_local.py


Your executable will appear in the dist folder.

📂 Project Structure
PythonBot/
├─ pythonbot_local.py     # Main chatbot script
├─ pythonbot-lora/        # Model weights or LoRA files
├─ requirements.txt       # Dependencies
└─ README.md              # This file

📜 License

This project is released under the MIT License. See LICENSE
for details.

🤝 Contributing

Pull requests and suggestions are welcome! Fork the repo and submit a PR.
