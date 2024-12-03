# **Fine-tuning-YOLOv8-for-Licence-Plate-Detection**

![anpr](https://github.com/user-attachments/assets/6350f00b-17ee-4cf1-b209-310e6a899068)
## **Project Overview**  
This project leverages the power of **YOLOv8**, a state-of-the-art object detection model known for its speed and accuracy, to detect license plates from images. YOLO (You Only Look Once) is trained to detect various objects using datasets like **COCO**, but it needs fine-tuning for specialized tasks such as license plate detection.

---

## **Why YOLOv8?**  
**YOLOv8** is designed for real-time object detection, balancing high accuracy with fast processing speeds. It excels at detecting objects in images, making it ideal for applications requiring quick and efficient processing. However, since YOLO models are typically trained on general datasets like **COCO**, additional training on specific data is essential for specialized tasks like license plate detection.

---

## **Project Details**  
The model used for this project is **YOLOv8n**, a lightweight version of YOLOv8 that provides a balance between computational efficiency and performance. The training involves fine-tuning the model using a labeled dataset specifically for license plate detection, allowing it to achieve high precision and reliability.

---

## **Training Strategy**  
- **Model Used:** `yolov8n.pt` (pre-trained YOLOv8 model).  
- **Dataset Configuration:** Data is structured using a `data.yaml` file specifying paths and labels for training and validation sets.  
- **Training Epochs:** 100 epochs to ensure thorough model learning.  

---

## **Key Features**  
- **Real-Time Detection:** Capable of detecting license plates in live or recorded video feeds.  
- **High Accuracy:** Fine-tuning improves precision and adaptability to specific use cases.  
- **Scalability:** Can be adapted for larger models or integrated into larger systems for complex applications.  

---

## **Future Directions**  
- **Dataset Expansion:** Incorporating more varied samples to enhance model generalization.  
- **Hyperparameter Tuning:** Experimenting with different learning rates and batch sizes for improved performance.  
- **Model Optimization:** Exploring model compression techniques for faster inference.  

---
## **Project Enhancement**  

This project has been further developed, where the license plate detected using the fine-tuned YOLOv8 model is processed by EasyOCR to extract the license plate number. The extracted number is then saved in a CSV file for further analysis. To know more [check this repository.](https://github.com/Sourudra/Fine-tuning-YOLOv8-for-Licence-Plate-Detection)

---
