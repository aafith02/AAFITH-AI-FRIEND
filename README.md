# 🎙️ AI Voice Friend Assistant

A real-time AI voice assistant that feels like a trusted friend — helping with legal-style advice, teaching step-by-step, emotional support, coding help, or even playful roleplay like bargaining for discounts.

Built with LiveKit for seamless audio/video streaming and Google Gemini for intelligent, context-aware conversations.

---

## 🌟 Features
- 🤝 Friend-Like Personality – Warm, witty, supportive, and adaptable
- 🎭 Multiple Modes – Legal help, learning aid, emotional support, coding guide, and playful roleplay
- ⚡ Real-Time Interaction – Powered by LiveKit for low-latency streaming
- 🔇 Noise Cancellation – Clear voice with BVC noise reduction
- 🧠 Google Gemini Integration – Fast and intelligent responses
- 🎯 Custom Prompt Design – Personality & behavior defined in `prompts.py`

---

## 🛠 Tech Stack
- Python
- LiveKit Agents SDK
- Google Gemini API
- Noise Cancellation Plugin
- dotenv for environment configuration

---

## ⚙️ How It Works
1. LiveKit creates a real-time audio link between user and assistant.
2. Google Gemini API handles natural language processing and response generation.
3. Custom prompts in `prompts.py` define personality and communication style.
4. Noise cancellation ensures crystal-clear voice input.
5. Session management keeps conversations smooth and natural.

---

## 💡 Why Use Existing Resources?
Building a real-time voice AI from scratch means:
- Developing speech-to-text
- Training a large language model
- Implementing audio streaming protocols
- Adding noise suppression

These are massive engineering efforts already solved by companies like Google and LiveKit.

By leveraging trusted APIs:
- Deliver features faster
- Ensure stability from day one
- Focus on user experience, not reinventing the wheel

Smart engineering: Like building a house — you don’t make your own bricks; you design how they come together into something unique.

---

Setting up your env
Google_API_KEY=your_google_api_key
LIVEKIT_URL=wss://your-livekit-url
LIVEKIT_API_KEY=your_livekit_key
LIVEKIT_API_SECRET=your_livekit_secret

python ai.py
