# 🧠 Brain Tumor Classification Using Pretrained CNNs

This project uses **transfer learning** and **fine-tuning** with popular pretrained models (VGG16, MobileNetV2, EfficientNetB3) to classify brain MRI images as either containing a tumor or not.

---

## 📂 Dataset

- Total Images: **253**  
  - `Yes Tumor`: 155 images  
  - `No Tumor`: 100 images
- Split using `image_dataset_from_directory()` with:
  - **80%** for training
  - **20%** for validation

---

## 📦 Models Used

| Model            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **VGG16**     | Classic CNN model with deep but simple architecture |
| **MobileNetV2**  | Lightweight and optimized for mobile usage |
| **EfficientNetB3** | Scales depth, width, and resolution efficiently |

---




