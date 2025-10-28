# 🍎FruitEye-XAI

# Fruit Freshness Detection using MobileNetV2 + Grad-CAM

- A deep learning system that detects whether fruits are fresh or rotten using transfer learning with MobileNetV2. The project also includes Explainable AI (Grad-CAM) to visually highlight the regions the model     focuses on while predicting fruit quality.

# ✅ Features

- Automated data loading and augmentation

- Transfer learning using MobileNetV2

- Multi-class fruit freshness classification

- Real-time prediction with confidence scores

- Grad-CAM visual explanation for transparency

- Performance evaluation with metrics and reports

# 🧠 Model Architecture

| Component     | Details                                            |
| ------------- | -------------------------------------------------- |
| Base Model    | MobileNetV2 (pretrained on ImageNet)               |
| Layers Added  | Global Average Pooling + Dense + Dropout + Softmax |
| Loss Function | Categorical Crossentropy                           |
| Optimizer     | Adam                                               |
| Input Size    | 224 × 224 × 3                                      |

# 🚀 How It Works

1️⃣ Load and preprocess images

2️⃣ Train the model with Image Augmentation

3️⃣ Predict fruit freshness from test images

4️⃣ Use Grad-CAM heatmaps to explain predictions

# 📊 Evaluation

- Accuracy displayed after testing

- Detailed classification report per fruit class

- Grad-CAM highlights core fruit regions → reliable understanding
