# Skincare.AI – NeuralNexus Web App

Welcome to the web application repository for **Team NeuralNexus's Skincare.AI**, developed as part of **Smart India Hackathon 2023 (SIH'23)**. Skincare.AI is an innovative AI-powered platform aimed at simplifying and accelerating the diagnosis of skin diseases and dermatological conditions through deep learning and intelligent image analysis.

---

## 🧠 About the AI

Skincare.AI leverages cutting-edge **deep learning models** trained on dermatological datasets to classify and detect a wide range of skin conditions. Our backend architecture integrates:

- **Convolutional Neural Networks (CNNs)** for image feature extraction
- **EfficientNet** and **ResNet** variants for robust classification performance
- **Vision Transformers (ViT)** for leveraging attention mechanisms on high-resolution dermatological images
- Transfer learning from pre-trained models on ImageNet and dermatology-specific datasets to improve accuracy and generalization

These models are optimized for both speed and diagnostic precision, making the system suitable for real-world clinical and teledermatology applications.

---

## 🧰 Tech Stack

This web application is built using a modern and scalable tech stack:

- **Frontend Framework:** [Next.js](https://nextjs.org/) – React-based framework for server-side rendering and optimized performance
- **Language:** [TypeScript](https://www.typescriptlang.org/) – for type safety and better development tooling
- **Styling:** Tailwind CSS (or specify if you're using another framework)
- **Backend & APIs:** Node.js-based API integration with the trained AI models
- **Model Serving:** TensorFlow Serving / FastAPI (depending on your actual deployment setup) for deploying the trained DL models
- **Deployment Ready:** Compatible with Vercel, Docker, or cloud platforms

---

## 🚀 Getting Started

To launch the development server locally, use one of the following commands:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Then open your browser and navigate to: [http://localhost:3000](http://localhost:3000)
