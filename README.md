# 🎯 YOLO Object Detector

A real-time object detection tool powered by **YOLOv8** (Ultralytics). Choose to either upload an image or use your live webcam feed, and the tool detects every object in view — drawing a bounding box, label, and confidence score around each one.

## ✨ Features

- Detects **80 common object classes** out of the box, based on the COCO dataset
- Choose between analyzing a single image or a live webcam feed
- Automatically draws bounding boxes and labels around every detected object, even when multiple objects appear at once
- Uses a pre-trained YOLOv8 model — no training required

## 🧠 Model Information

| Item | Details |
|------|---------|
| **Model** | YOLOv8n (nano) |
| **Framework** | PyTorch (via Ultralytics) |
| **Dataset** | COCO (Common Objects in Context) |
| **Number of Classes** | 80 |
| **Model Size** | ~6 MB |
| **Input Size** | 640 × 640 (default) |
| **Download** | Automatic on first run |

> The YOLOv8n model is the lightest variant, designed for real-time detection. If you need higher accuracy, you can switch to `yolov8s.pt`, `yolov8m.pt`, or `yolov8l.pt` (larger sizes, slower).

## 📋 Detectable Classes (80 COCO Classes)

| # | Class | # | Class | # | Class | # | Class |
|---|-------|---|-------|---|-------|---|-------|
| 1 | person | 21 | elephant | 41 | cup | 61 | toilet |
| 2 | bicycle | 22 | bear | 42 | fork | 62 | tv |
| 3 | car | 23 | zebra | 43 | knife | 63 | laptop |
| 4 | motorcycle | 24 | giraffe | 44 | spoon | 64 | mouse |
| 5 | airplane | 25 | backpack | 45 | bowl | 65 | remote |
| 6 | bus | 26 | umbrella | 46 | banana | 66 | keyboard |
| 7 | train | 27 | handbag | 47 | apple | 67 | cell phone |
| 8 | truck | 28 | tie | 48 | sandwich | 68 | microwave |
| 9 | boat | 29 | suitcase | 49 | orange | 69 | oven |
| 10 | traffic light | 30 | frisbee | 50 | broccoli | 70 | toaster |
| 11 | fire hydrant | 31 | skis | 51 | carrot | 71 | sink |
| 12 | stop sign | 32 | snowboard | 52 | hot dog | 72 | refrigerator |
| 13 | parking meter | 33 | sports ball | 53 | pizza | 73 | book |
| 14 | bench | 34 | kite | 54 | donut | 74 | clock |
| 15 | bird | 35 | baseball bat | 55 | cake | 75 | vase |
| 16 | cat | 36 | baseball glove | 56 | chair | 76 | scissors |
| 17 | dog | 37 | skateboard | 57 | couch | 77 | teddy bear |
| 18 | horse | 38 | surfboard | 58 | potted plant | 78 | hair drier |
| 19 | sheep | 39 | tennis racket | 59 | bed | 79 | toothbrush |
| 20 | cow | 40 | bottle | 60 | dining table | 80 | — |

## 📦 Requirements

- Python 3.9 or newer
- A working webcam (only needed for the live detection mode)

## 📥 Clone the Repository

git clone https://github.com/kamandNajari/YOLO_Object_Detector.git
cd YOLO_Object_Detector

## 🚀 Installation

pip install -r requirements.txt

If you don't already have PyTorch installed, install the lightweight CPU version first:

pip install torch --index-url https://download.pytorch.org/whl/cpu

## 📓 Running the Notebook

Make sure Jupyter is installed:

pip install jupyter

Then launch it:

jupyter notebook

Open `yolo_object_detector.ipynb` from the Jupyter interface and run the cell (Shift + Enter).

The YOLOv8 model is downloaded automatically on first run — no manual setup needed.

## ▶️ How to Use

1. Run the notebook cell — a small window will ask you to choose an input mode
2. Click **Upload Image** to select any photo from your device, or **Use Webcam** for live detection
3. If you chose an image: a window opens showing the image with all detected objects boxed and labeled
4. If you chose webcam: a live window opens, continuously detecting objects in real time
5. Press **q** to close the webcam window

## 🛠️ Tech Stack

- [Ultralytics YOLOv8](https://docs.ultralytics.com/) — pre-trained object detection model
- [PyTorch](https://pytorch.org/) — deep learning framework
- [OpenCV](https://opencv.org/) — webcam capture, image handling, and display
- [Tkinter](https://docs.python.org/3/library/tkinter.html) — input mode selection and file picker

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 👥 Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/KamandNajari">
        <img src="https://avatars.githubusercontent.com/KamandNajari" width="100px;" alt="Kamand Najari"/><br />
        <sub><b>Kamand Najari</b></sub>
      </a><br />
      <a href="https://github.com/KamandNajari" title="GitHub">@KamandNajari</a>
    </td>
    <td align="center">
      <a href="https://github.com/python-is-life2022">
        <img src="https://avatars.githubusercontent.com/python-is-life2022" width="100px;" alt="python-is-life2022"/><br />
        <sub><b>python-is-life2022</b></sub>
      </a><br />
      <a href="https://github.com/python-is-life2022" title="GitHub">@python-is-life2022</a>
    </td>
  </tr>
</table>

---

Thank you for checking out this project! ✨
