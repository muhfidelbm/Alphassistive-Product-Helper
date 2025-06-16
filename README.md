# Alphassistive Product Helper

An assistive system that helps visually impaired users get product information in real-time, using Alphaasistive Robot. This application uses computer vision and a multimodal AI to identify a product, listen to a user's spoken question, and provide an audio answer about allergens, ingredients, and vegan status.

This project was developed as the core implementation for my thesis: *"Pengembangan Sistem Pemahaman Deskripsi Produk Secara Interaktif Menggunakan LLM untuk Robot AlphAsisstive"* at Universitas Airlangga.

---

### Tech Stack

*   **Computer Vision:** OpenCV, Ultralytics (YOLOv8)
*   **AI/LLM:** Google Gemini API (`google.genai`)
*   **Audio Input:** PyAudio, Silero VAD
*   **Text-to-Speech (TTS):** Coqui TTS
*   **Core Libraries:** PyTorch, NumPy, Torchaudio
*   **Model:** A custom-trained YOLOv8 model (`detection_model_02.pt`) for product detection.

### Writer's Setup

*   AMD Ryzen™ 5 5600H with Radeon™ Graphics
*   NVIDIA GeForce RTX™ 3060 Laptop GPU 6 GB VRAM
*   24 GB DDR4 RAM
*   Fedora Linux 42 (Workstation Edition)
*   Redmi Note 7 as Camera, with [Scrcpy](https://github.com/Genymobile/scrcpy)
