This project leverages Large Language Models (LLMs) to build an intelligent recommendation system capable of analyzing patient health data and medical images to provide personalized disease insights and medication suggestions. The system integrates AI-driven image analysis, speech-to-text, and text-to-speech capabilities to enable natural, multimodal interaction between patients and the system.
Using Groq Vision API, the model interprets uploaded medical images (e.g., skin rashes, X-rays, etc.) and extracts key diagnostic features. These insights are then processed by a fine-tuned LLM (such as meta-llama/llama-4-scout-17b-16e-instruct) to generate human-like, medically informed responses. The frontend is developed with Gradio, allowing users to record symptoms through voice, upload images, and receive both textual and audio-based recommendations.
Tech Stack:
Frontend: Gradio
Backend: Python
APIs: Groq Vision (for image analysis), ElevenLabs (for TTS), gTTS (for speech-to-text)
Model: meta-llama/llama-4-scout-17b-16e-instruct
