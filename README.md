# FaceFrame 👓
### AI-Powered Real-Time Glasses Try-On

> Find frames that fit — instantly, accurately, no store visit required.

**🌐 [Try it live → faceframeai.com](https://faceframeai.com)**

## What It Does

FaceFrame uses computer vision and machine learning to analyze your face in real time and recommend eyeglass frames that suit your unique face shape — all directly in your browser, no upload required.

1. **Detect** — MediaPipe maps 468 facial landmarks from your live camera feed
2. **Classify** — A custom-trained CNN identifies your face shape (oval, round, square, heart, or oblong)
3. **Recommend** — Frames are matched and overlaid in real time based on your shape profile

---

## Tech Stack

| Layer | Technology |
|---|---|
| Face Detection | MediaPipe Face Mesh (468 landmarks) |
| Shape Classification | TensorFlow / Keras CNN |
| Feature Engineering | scikit-learn, NumPy |
| Computer Vision | OpenCV |
| Frontend | React.js |

---

## Architecture


Camera Feed
    │
    ▼
MediaPipe Face Mesh
(468-point landmark detection)
    │
    ▼
Landmark Feature Extraction
(facial ratios, geometry)
    │
    ▼
CNN Face Shape Classifier
(5 categories)
    │
    ▼
Frame Recommendation Engine
    │
    ▼
Real-Time AR Overlay


---

## Key Technical Highlights

- **Sub-50ms inference latency** — landmark detection and classification run in a single pass, fast enough for smooth real-time overlay
- **Custom CNN trained on labeled face shape dataset** — 5-class classifier with data augmentation for robustness across lighting and angles
- **No backend required for inference** — model runs client-side, keeping user video data fully private
- **Cross-disciplinary team** — built by 4+ students spanning Computer Science and Business at The Ohio State University

---

## Team

Built by a multidisciplinary student team at **The Ohio State University**.

| Role | Focus |
|---|---|
| CEO & CV Lead | Computer vision pipeline, ML model, product strategy |
| Engineering | React frontend, system integration |
| Business | Market research, partnerships, go-to-market |

---

## Status

🟢 **Live** — [faceframeai.com](https://faceframeai.com)

> Source code is private as FaceFrame is an active product under development.
> For technical inquiries or collaboration, reach out via [rsinghvi7891@gmail.com](mailto:rsinghvi7891@gmail.com)

---

## Contact

**Rishi Singhvi** — Owner & Co-Founder
[LinkedIn](https://www.linkedin.com/in/rishi-singhvi) · [rsinghvi7891@gmail.com](mailto:rsinghvi7891@gmail.com) · [faceframeai.com](https://faceframeai.com)
