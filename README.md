# Driverless Car Object Detection 🚗🧍‍♂️

A deep learning computer vision project that detects humans and other objects in images, generating bounding boxes for each detected object. Built for driverless car applications, this project uses a pretrained **Faster R-CNN with ResNet50 FPN** model on the COCO dataset to demonstrate object detection in real-world scenarios.

---

## Features ✨

- Detects **humans, vehicles, and other key objects** in images.  
- Outputs **bounding boxes** with class labels and confidence scores.  
- Uses **pretrained COCO weights** for robust detection.  
- Can process **single images or batches**.  
- Includes detailed **documentation with accuracy, metrics, and sample predictions**.  

---

## Dataset 🗂️

- **Dataset:** COCO (Common Objects in Context) dataset.  
- Used to train and evaluate the Faster R-CNN model for detecting humans, cars, and other objects.  
- Sample custom images are also included for demonstration.

---


### File Descriptions:
- **`object-detection.ipynb`** → Full workflow: load COCO dataset, use Faster R-CNN ResNet50 FPN, detect objects, and visualize bounding boxes.  
- **`documentation.pdf`** → Contains accuracy, precision, recall, sample predictions, and analysis.  
- **`sample_image*.jpg`** → Images to test and visualize object detection results.  

---

## Model Architecture 🧠

- **Detection Model:** `Faster R-CNN` with `ResNet50 FPN` backbone  
- **Pretrained Weights:** COCO dataset (`weights="DEFAULT"`)  
- **Framework:** PyTorch + Torchvision  
- **Input:** Images containing humans, vehicles, and other objects  
- **Output:** Bounding boxes with class labels and confidence scores  

