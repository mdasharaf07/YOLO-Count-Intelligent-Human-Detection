# 👥 AI People Counting System (YOLOv8 + Colab)
This project is an AI-powered people counting system that runs on **Google Colab** using **YOLOv8** and **OpenCV**. It detects and counts the number of people in a video frame-by-frame using object detection.

# 🎯 Features
- 🎥 Upload and analyze any video (MP4, AVI, etc.)
- 🧠 YOLOv8-powered person detection (COCO class `person`)
- 🔢 Real-time people count overlay per frame
- 📊 Total count summary at the end
- ✅ All done inside Google Colab — no setup required

## 📄 How It Works
1. Upload a image file using the Colab uploader
2. The system processes each frame using YOLOv8
3. Detects all `person` class objects and draws bounding boxes
4. Displays each frame with a running count
5. Optionally saves the processed video for download

## 🧪 Technologies Used

- [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics)
- OpenCV for video processing
- Python (Google Colab runtime)

## ▶️ How to Run (Colab)

1. Open the Colab notebook: `YOLO Count: Intelligent Human Detection.ipynb`
2. Run all cells in order:
   - Install packages
   - Load YOLOv8 model
   - Upload a image
   - Process and count people
3. View live frame results
4. (Optional) Download the output video

## 📂 Files Included

- `YOLO Count: Intelligent Human Detection.ipynb` – Colab notebook with full code
- `README.md` – Project documentation

# 🧑‍💻 Author
**Mohamed Asharaf**
