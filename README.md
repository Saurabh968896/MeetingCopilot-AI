**🧠 MeetingCopilot AI
Real-Time Voice-to-Insight Assistant for Meetings**

**🚧 Project Status: Actively Under Development**
Core real-time pipeline is functional. Performance optimization, streaming mode, and advanced intelligence features are currently being enhanced.
MeetingCopilot AI is a real-time, voice-driven meeting intelligence system that captures live system audio, transcribes speech using Faster-Whisper, and generates structured insights using a local Large Language Model (LLM).
Designed for low-latency performance and full offline execution, it transforms meeting conversations into actionable AI-powered responses within seconds.

**🚀 Features**
🎤 System Audio Capture (WASAPI Loopback – Windows)
🗣️ Real-Time Speech-to-Text (Faster-Whisper)
🧠 Local LLM-Based Insight Generation
⚡ 2–4 Second Target Response Time (16GB i7 Optimized)
🔐 Fully Offline & Privacy-Focused
🔁 Continuous Listening Mode
🖥️ CPU-Optimized Architecture

**🏗️ Architecture Overview**
Meeting Speaker Audio
        ↓
System Audio Capture (Loopback)
        ↓
Faster-Whisper (Speech-to-Text)
        ↓
Local LLM (Instruction-Tuned Model)
        ↓
Structured Insight Output


**The system runs entirely on-device with no external API calls.**

**🛠️ Tech Stack**

Python
Faster-Whisper
Hugging Face Transformers
PyTorch
SoundDevice (WASAPI)
SciPy

**⚙️ System Requirements**

**Recommended:**
16GB RAM
Intel i7 (or equivalent)
Windows (for WASAPI loopback support)
Python 3.10+

**📦 Installation**
**1️⃣ Clone Repository**
git clone https://github.com/yourusername/MeetingCopilot-AI.git
cd MeetingCopilot-AI

**2️⃣ Create Virtual Environment**
python -m venv venv
venv\Scripts\activate

**3️⃣ Install Dependencies**
pip install faster-whisper transformers torch sounddevice scipy

**▶️ Run the System**
python main.py


**The system will:**
Capture live meeting audio
Transcribe speech
Generate structured AI insights
Print responses in real time

**⚡ Current Performance (Development Phase)**
On a 16GB i7 system:
Transcription: ~1–2 sec
LLM Response: ~2–4 sec
Fully local execution
Performance and response quality are actively being optimized.

**🎯 Use Cases**
Real-time meeting assistance
Technical discussion support
Concept clarification during calls
AI-powered productivity enhancement
Intelligent meeting companion

**🔮 Upcoming Enhancements**
Streaming real-time inference
Meeting summarization mode
Action item extraction
Vector-based meeting memory
Lightweight overlay UI
Multi-speaker differentiation
Latency reduction via quantized inference

**🧩 Project Status**

**Version 1 – Functional Prototype**
Actively evolving toward a low-latency, production-grade meeting intelligence system.
