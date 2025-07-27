This project focuses on semantic segmentation of water bodies using multi-spectral satellite imagery enriched with NDWI (Normalized Difference Water Index). Two deep learning models were explored:

- **U-Net**: A standard semantic segmentation model.
- **MobileNetV2-based U-Net**: A lightweight, encoder-decoder model using MobileNetV2 as the backbone encoder.

### Features
- 🛰️ Multi-spectral bands: [Blue, Green, Red, NIR, SWIR] + NDWI
- 🔁 Per-channel normalization
- ⚙️ Model comparison: U-Net vs MobileNetV2-U-Net
- 📏 Evaluation metric: Intersection over Union (IoU)

