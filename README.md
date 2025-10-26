# **DeepFace-Based Face Recognition System**

This repository contains a **face recognition project** built using the **DeepFace** library. It is designed to detect and recognize human faces in both images and videos, leveraging pre-trained deep learning models for high accuracy and performance.

---

## **Features**

* **Face Detection** – Detects and localizes faces in images or video frames.
* **Face Recognition** – Identifies and matches faces using state-of-the-art pre-trained models.
* **DeepFace Integration** – Uses the DeepFace library for streamlined and efficient implementation.
* **Ease of Use** – Includes ready-to-run scripts for face detection and recognition tasks.
* **Extensible Design** – Can be easily modified or extended for custom datasets and applications.

---

## **Usage**

### 1. Clone the Repository

```bash
git clone https://github.com/m-rafayali/DeepFace-Based-Face-Recognition-System.git
cd DeepFace-Based-Face-Recognition-System
```

### 2. Install Dependencies

Make sure you have Python 3.x installed, then install the required dependencies:

```bash
pip install -r requirements.txt
```

### 3. Run Face Recognition on an Image

```bash
python face_recog.py --image path_to_image.jpg
```

### 4. Run Face Recognition on a Video

```bash
python face_recog.py --video path_to_video.mp4
```

---

## **Requirements**

* Python 3.x
* DeepFace
* OpenCV
* NumPy

Example `requirements.txt`:

```
deepface>=0.0.64
opencv-python>=4.5.0
numpy>=1.19.0
```

---

## **Example**

### Recognize Faces in an Image

Detect and recognize faces from an image input:

```bash
python face_recog.py --image example.jpg
```

### Recognize Faces in a Video

Process a video stream for real-time or batch face recognition:

```bash
python face_recog.py --video example.mp4
```

---

## **Project Structure**

```
DeepFace-Based-Face-Recognition-System/
│
├── face_recog.ipynb        # Jupyter notebook for running face recognition
├── face_recog.py           # Python script for detection and recognition
├── requirements.txt        # Required dependencies
├── README.md               # Project documentation
└── LICENSE                 # License file
```

---

## **License**

This project is licensed under the [MIT License](LICENSE) – you are free to use, modify, and distribute it with attribution.
