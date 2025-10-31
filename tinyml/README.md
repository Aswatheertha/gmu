TinyML for Plant Growth Monitoring

In our Seed Incubator project, TinyML is used to monitor the growth stages of plants using the ESP32-CAM.  
The goal is to make the system capable of identifying and classifying plant growth stages automatically without depending on external servers.

🌱 Purpose
The TinyML model helps the system recognize different growth stages of a plant (for example, seedling, vegetative, and mature) by analyzing images captured by the ESP32-CAM.

⚙️ How It Works
1. The ESP32-CAM captures plant images at regular intervals.  
2. These images are added to a dataset and labeled according to the growth stage.  
3. A lightweight machine learning model (trained using TensorFlow Lite or Edge Impulse) is created using this dataset.  
4. The optimized model is deployed onto the ESP32-CAM.  
5. The ESP32-CAM runs the TinyML model locally to identify the current growth stage.

📊 Expected Output
- The system can classify each plant image into stages such as:  
  - Stage 1: Germination  
  - Stage 2: Early Growth  
  - Stage 3: Mature  
- This information can be displayed in the mobile app or web dashboard.

💡 Advantages
- Growth can be monitored automatically without manual checking.  
- Works offline, even without internet access.  
- Helps optimize light, watering, and temperature settings based on the detected stage.  

Project: Seed Incubator with Environmental Control  
Feature: TinyML-based Plant Growth Monitoring   
Repository: [gmu](https://github.com/Aswatheertha/gmu)
