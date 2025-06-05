# OpenCV Projects Repository

Welcome to the **OpenCV Projects Repository**! This repository contains a collection of small, easy-to-understand projects that demonstrate key concepts and techniques in OpenCV, the popular computer vision library. Each project focuses on a specific OpenCV feature and provides code examples with explanations.

---

## 📚 What You Will Learn

This repository covers a broad range of OpenCV topics, including:

- Image Processing Basics  
  - Reading, displaying, and saving images  
  - Image resizing, cropping, and color space conversions  
- Drawing and Annotation  
  - Drawing shapes (circles, rectangles, lines)  
  - Adding text to images  
- Image Filtering and Enhancement  
  - Blurring, smoothing, sharpening  
  - Edge detection (Canny, Sobel)  
- Feature Detection  
  - Harris corner detection  
  - Good features to track  
- Object Detection  
  - Haar cascades for face, car, and full body detection  
- Video Processing  
  - Capturing video from file and webcam  
  - Background subtraction using MOG2 and KNN  
  - Tracking objects with CamShift  
- Geometric Transformations  
  - Image rotation, translation, scaling, affine and perspective transforms  
- Contour Detection and Shape Analysis  
- Morphological Operations  
- Masking and Segmentations  
  - GrabCut algorithm  
- Event Handling  
  - Mouse callbacks for interactive image annotation  

---

## 🚀 Projects Overview

| Project Name               | Description                                            | OpenCV Concepts Covered                   |
|---------------------------|--------------------------------------------------------|-------------------------------------------|
| **Image Basics**           | Load, display, resize, and save images                  | `cv2.imread`, `cv2.imshow`, `cv2.resize` |
| **Drawing Shapes**         | Draw circles, rectangles, and text on images            | Drawing functions: `cv2.circle`, `cv2.rectangle`, `cv2.putText` |
| **Corner Detection**       | Detect corners using Harris and Shi-Tomasi methods      | `cv2.cornerHarris`, `cv2.goodFeaturesToTrack` |
| **Face & Object Detection**| Detect faces, cars, and full bodies in images/videos    | Haar cascades, `detectMultiScale`        |
| **Background Subtraction** | Segment moving objects from video backgrounds            | `cv2.createBackgroundSubtractorMOG2`, `cv2.createBackgroundSubtractorKNN` |
| **Object Tracking**        | Track a running person in video using CamShift          | Histogram backprojection, `cv2.CamShift`  |
| **Image Masking**          | Segment objects using GrabCut algorithm                  | `cv2.grabCut`, mask operations            |
| **Interactive Annotation** | Click on image to display coordinates                     | Mouse callback functions                   |

---

## 📦 Installation

Make sure you have Python installed (preferably 3.6+). Then install OpenCV and numpy:

```bash
pip install opencv-python numpy
