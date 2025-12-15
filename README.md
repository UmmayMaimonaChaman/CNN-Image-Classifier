# CNN Vision 🚀

A professional Deep Learning Workbench running entirely in the browser using TensorFlow.js. Train custom models, run batch inference, and visualize model decisions with Grad-CAM.

## Features ✨

### 1. 🔍 Inference Engine
- **Multi-Model Support**: Switch between MobileNet v2, ResNet-50, EfficientNet, and InceptionV3.
- **Real-Time Classification**: Drag & drop images or use **Webcam Capture** for instant predictions.
- **Privacy First**: All processing happens locally in your browser. No images are uploaded.

### 2. 📂 Batch Processing
- **Batch Mode**: Upload multiple images at once to the dashboard.
- **Data Table**: View top predictions, confidence scores, and inference latency (`ms`) for each image.

### 3. 🧠 Training Workbench
- **Custom Training**: Train a Convolutional Neural Network (CNN) from scratch in the browser.
- **Dataset Support**: Load the default MNIST dataset or upload your own CSV (`label, pixel1...pixel784`).
- **Live Visualization**: Real-time Accuracy and Loss curves using Chart.js.

### 4. 🎨 Explainability (Grad-CAM)
- **Heatmap Overlay**: Visualize *where* the model is looking with a dynamic Saliency Map overlay.
- **Interactive**: Toggle heatmaps on/off for any classification result.

## Tech Stack 🛠️
- **Core**: HTML5, Vanilla JavaScript, CSS3 (Modern Dark Theme)
- **ML Engine**: TensorFlow.js (In-browser training & inference)
- **Visualization**: Chart.js (Training curves)
- **Icons**: Lucide Icons

## How to Run 🏃‍♂️
1. Clone the repository.
2. Navigate to the `CNN update` folder.
3. Open `index.html` in any modern browser (Chrome/Edge/Firefox).
   - *Note: For Webcam access, browsers may require serving via localhost (e.g., VS Code Live Server) rather than `file://` protocol.*

## License 📄
© 2025 CNN Vision. All rights reserved. | Created by **Ummay Maimona Chaman**.
