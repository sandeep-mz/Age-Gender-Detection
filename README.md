
# Age and Gender Detection Using OpenCV

This project uses Python and OpenCV to detect human faces in images and predict their approximate age and gender using pre-trained deep learning models.

## Features
- Face Detection using OpenCV DNN.
- Age Prediction using a pre-trained Caffe model.
- Gender Prediction using a pre-trained Caffe model.
- Supports testing with sample images.
- Displays predicted age and gender for detected faces.

## Technologies Used
- Python
- OpenCV
- Deep Learning (Caffe Models)
- argparse

## Requirements

Install the required library:

```bash
pip install opencv-python
```

**Note:** argparse is included in Python's standard library. No separate installation is required.

## Project Structure

```text
Age-Gender-Detection/
│
├── opencv_face_detector.pbtxt
├── opencv_face_detector_uint8.pb
├── age_deploy.prototxt
├── age_net.caffemodel
├── gender_deploy.prototxt
├── gender_net.caffemodel
├── detect.py
├── images/
│   └── sample images
│
└── README.md
```

## Installation and Usage

**Step 1: Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**Step 2: Navigate to the project directory**

```bash
cd Age-Gender-Detection
```

**Step 3: Install dependencies**

```bash
pip install opencv-python
```

**Step 4: Run the project**

```bash
python detect.py
```

The program will detect faces in the input image and display the predicted age and gender.

## Required Model Files

Make sure the following pre-trained model files are available in the project directory:

- opencv_face_detector.pbtxt
- opencv_face_detector_uint8.pb
- age_deploy.prototxt
- age_net.caffemodel
- gender_deploy.prototxt
- gender_net.caffemodel

## Stop Execution

Press `Ctrl + C` in the Command Prompt or Terminal to stop program execution.

## Important Notes

- Age predictions are approximate and may not be exact.
- Gender predictions are model-based classifications and may not reflect a person's gender identity.
- Prediction accuracy depends on image quality, lighting, and face visibility.
- Ensure all required model files are present before running the project.

## Author

**Sandeep Maurya**

GitHub: [sandeep-mz](https://github.com/sandeep-mz)

---

⭐ If you find this project useful, consider giving it a star!
