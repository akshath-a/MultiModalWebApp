# MultiModalWebApp

An end-to-end AI application built to showcase interactions across multiple modalities: Text, Image, Audio, and Video utilizing state-of-the-art models via Groq, Google Gemini, Open AI and Huggingface.

## 🚀 Features & Modalities Covered

### 1. ✍️ Text ➔ Text
* **Engine:** `Llama-3.3-70b-versatile` via **Groq Cloud API**
* **Capability:** Hyper-fast contextual content generation, text transformation, and complex logical reasoning utilizing Groq's hardware acceleration for near-instantaneous token-per-second output.

### 2. 🎨 Text ➔ Image
* **Engine:** Modern OpenAI Image Generation Architecture (`gpt-image-2` / DALL-E)
* **Capability:** Transforms descriptive textual prompts into high-fidelity 1024x1024 creative illustrations or concept art, featuring an automated base64 inline decoding stream to bypass standard temporary download link dependencies.

### 3. 👁️ Image ➔ Text
* **Engine:** `Gemini-2.5-flash` via **Google AI**
* **Capability:** Native computer vision and structural understanding. Accepts image uploads to perform object detection, document OCR, visual data extraction, or detailed scene evaluation.

### 4. 🗣️ Text ➔ Audio
* **Engine:** `tts-1` (Alloy/Echo voices) via **OpenAI API**
* **Capability:** High-fidelity, low-latency Text-to-Speech (TTS) synthesis. Converts raw textual blocks or articles into natural-sounding spoken audio streams downloadable right from the dashboard UI.

### 5. 🎙️ Audio ➔ Text
* **Engine:** `Whisper-Large-v3` via **Groq Cloud API**
* **Capability:** Sub-second speech-to-text transcriptions. Bypasses standard latency boundaries to decode spoken audio waveforms into highly accurate, structured text.

### 6. 🎬 Text ➔ Video
* **Engine:** Huggingface
* **Capability:** Synthesizes temporal, coherent short video sequences or motion clips entirely from descriptive textual scenes, establishing a direct pipeline for prompt-to-cinema rendering.

### 7. 📹 Video ➔ Text
* **Engine:** `Gemini-2.5-flash` via **Google AI**
* **Capability:** Complex spatial-temporal understanding. Leverages a specialized native processing wait-loop architecture to securely monitor file compilation states on the cloud backend, delivering scene-by-scene contextual analysis, action logging, and summaries.

### 8. 🖼️ Image ➔ Image
* **Engine:** Modern OpenAI Image Generation Architecture (`gpt-image-2` / DALL-E)
* **Capability:** Executes guided image variations and transformations. Utilizes explicit binary tuple MIME-type encoding (`image/png`) to feed source imagery and textual modification directions directly to the generative model.

### 9. 🔊 Audio ➔ Audio
* **Engine:** Hybrid **Gemini-2.5-flash** + **OpenAI TTS** Pipeline
* **Capability:** A cross-API conversation mirroring loop. Uses Gemini to ingest, analyze, and resolve intent directly from an uploaded voice clip, then immediately hands the textual resolution to OpenAI's speech engine to vocalize a hands-free, automated audio response.

---

## 🛠️ Tech Stack & Model Architecture

* **Frontend/Backend App framework**: Streamlit (Python)
* **Inference APIs**: Groq Cloud SDK, Google GenAI SDK, Open AI, Huggingface
* **Prototyping**: Jupyter/Google Colab Notebook

---
