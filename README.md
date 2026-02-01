# 🛍️ Shoplifting Detection Using YOLOv8

This project presents a real-time shoplifting detection system built using the YOLOv8 object detection model. The system analyzes retail surveillance footage to detect suspicious activities related to shoplifting, such as item concealment and abnormal human behavior. The goal is to support retail security by providing an automated and efficient monitoring solution.

## 📌 About the Project

Shoplifting is a significant issue in retail environments, leading to substantial financial losses every year. Traditional CCTV monitoring requires continuous human attention and is prone to errors. This project leverages deep learning and computer vision techniques to automatically identify potential shoplifting activities, reducing dependency on manual monitoring and improving response time.

## 🚀 Key Features

- Real-time shoplifting detection using YOLOv8  
- High-speed and accurate object detection  
- Works with surveillance videos, recorded footage, and webcam input  
- Supports training with a custom dataset  
- Easy implementation using Google Colab  

## 🛠️ Technologies Used

- Python  
- YOLOv8 (Ultralytics)
- OpenCV  
- PyTorch  
- Google Colab  

## 📊 Dataset Information

The dataset used in this project was sourced from **Roboflow**. It contains annotated images representing shoplifting-related activities and normal in-store behavior. The dataset is formatted in YOLO annotation style and includes labeled bounding boxes for relevant objects and actions. Roboflow was used for dataset management, preprocessing, and augmentation to improve model performance.

## ▶️ How It Works

1. Input surveillance video or image data is provided to the system  
2. The YOLOv8 model processes each frame  
3. Objects and suspicious activities are detected in real time  
4. Bounding boxes and labels are displayed on the output  
5. Results are saved for further analysis

## 📈 Results

- Accurate detection of shoplifting-related activities  
- Real-time performance suitable for surveillance systems  
- Visual output with labeled bounding boxes  

## 🔮 Future Scope

- Action-based behavior recognition for higher accuracy  
- Integration with real-time alert and alarm systems  
- Deployment on edge devices for live store monitoring  
- Support for multiple camera feeds  

## 📜 License

This project is licensed under the **MIT License**.  
Refer to the `LICENSE` file for more details.
