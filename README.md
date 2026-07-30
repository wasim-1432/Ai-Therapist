# 🧠 AI Therapist 2.0

<p align="center">
  <img src="https://github.com/wasim-1432.png" alt="AI Therapist Logo" width="160"/>
</p>

<p align="center">
  <b>🤖 Your Empathetic AI Mental Wellness Companion</b><br/>
  Built with ❤️ using Python, Ollama, and MedGemma
</p>

---

## ✨ Features

* 💬 **Empathetic AI conversations**
* 🧠 **Therapist-style supportive responses**
* 🌍 **Location-aware mental health assistance**
* ⚡ **Fast local inference with Ollama**
* 🖥️ **Simple frontend interface**
* 🔒 **Runs locally for better privacy**

---

## 🛠️ Tech Stack

| Technology              | Purpose               |
| ----------------------- | --------------------- |
| 🐍 Python               | Core backend          |
| 🦙 Ollama               | Local LLM runtime     |
| 🧠 MedGemma             | AI therapist model    |
| 🎨 Frontend (Python UI) | User interaction      |
| 📍 Location Tool        | Context-aware support |

---

## 📂 Project Structure

```bash
AI-Therapist-2.0/
│
├── backend/
│   ├── ai_agent.py
│   ├── config.py
│   ├── main.py
│   ├── tools.py
│   └── test_location_tool.py
│
├── frontend.py
├── README.md
├── pyproject.toml
└── AI Therapist.pdf
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/wasim-1432/AI-Therapist.git
cd AI-Therapist
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv .venv
```

### 3️⃣ Activate Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / Mac**

```bash
source .venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install -e .
```

---

## 🦙 Setup Ollama

Install Ollama from:

👉 https://ollama.com/

Pull the MedGemma model:

```bash
ollama pull medgemma
```

Start Ollama:

```bash
ollama serve
```

---

## ▶️ Run the Application

### Start Backend

```bash
cd backend
python main.py
```

### Start Frontend

```bash
python frontend.py
```

---

## 💡 Example Conversation

```text
👤 User: I have been feeling anxious lately.

🤖 AI Therapist:
I'm sorry you're going through that. Many people experience periods of anxiety, and it can feel overwhelming. Sometimes it helps to slow down and notice what has been weighing on you recently. What has been making these feelings strongest for you?
```

---

## 🧠 Therapist Response Style

The AI is designed to provide:

* ❤️ Emotional attunement
* 🌱 Gentle normalization
* 🛠️ Practical coping guidance
* 💪 Strength-focused encouragement
* ❓ Open-ended reflective questions

---

## ⚙️ Configuration

Edit **backend/config.py** to customise:

```python
MODEL_NAME = "medgemma"
TEMPERATURE = 0.7
MAX_TOKENS = 1024
```

---

## 🧪 Testing

Run the location tool test:

```bash
python backend/test_location_tool.py
```

---

## 📸 Screenshot

<p align="center">
  <img src="docs/screenshot.png" alt="Application Screenshot" width="800"/>
</p>

---

## 🌟 Future Improvements

* 🎙️ Voice input support
* 🔊 Text-to-speech responses
* 🌐 Web deployment
* 📊 Mood tracking dashboard
* 📝 Conversation history
* 📱 Mobile-friendly UI

---

## 🤝 Contributing

Contributions are welcome!

1. 🍴 Fork the project
2. 🌿 Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. 💾 Commit your changes

```bash
git commit -m "Add some AmazingFeature"
```

4. 🚀 Push to the branch

```bash
git push origin feature/AmazingFeature
```

5. 🔁 Open a Pull Request

---

## 👨‍💻 Author

### **Mohd Wasim**

🎓 B.Tech IT | Galgotias College of Engineering & Technology

* 🔗 GitHub: https://github.com/wasim-1432
* 💻 Project: https://github.com/wasim-1432/AI-Therapist

---

## ⭐ Support

If you found this project helpful, please give it a **⭐ star** on GitHub!

<p align="center">
  ⭐ **Star this repository if you like it!** ⭐
</p>

---

## 📜 License

This project is licensed under the **MIT License**.

```text
MIT License © 2026 Mohd Wasim
```

---

<p align="center">
  Made with ❤️ by <b>Mohd Wasim</b>
</p>
