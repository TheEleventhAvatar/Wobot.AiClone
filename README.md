# Wobot.Ai Clone – Face Mask Detection

This project replicates a simplified version of Wobot.ai, focusing solely on detecting **face mask violations** from video input using YOLOv8.

## 🔍 Features

* 🎥 Accepts video input (e.g., CCTV footage).
* 🧠 Uses YOLOv8 for real-time face mask detection.
* 🧾 Annotated output with bounding boxes showing violations.
* 💾 Saves violation logs and processed videos.

## 🧠 Model & Dataset

* **Model**: YOLOv8 (Ultralytics, PyTorch-based)
* **Dataset Used**:
  [Face Mask Detection (Kaggle)](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)

## 🛠 Tech Stack

* Python
* PyTorch
* YOLOv8
* OpenCV
* NumPy
* Pandas

## 🚀 Getting Started

1. **Clone the repo**:

   ```bash
   git clone https://github.com/TheEleventhAvatar/Wobot.AiClone.git
   cd Wobot.AiClone
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run detection**:

   ```bash
   python detect.py --source path/to/video.mp4
   ```

4. **Output** will be saved in `runs/detect/`.

## 📄 License

Apache 2.0 License — feel free to use and modify.

---
