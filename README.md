# Hardware-Software-Final-Project

## Sleep Monitoring Device
The purpose of this connected device is to identify the quality of sleep. To determine the quality of sleep, we use a simplified pre-trained algorithm.
![Sketch](https://github.com/gheacs/Hardware-Software-Final-Project/blob/main/picture/Sleeping%20tracker.jpg)

### Environmental and Movement Sensors

#### Humidity Sensor:
![BME280](https://github.com/gheacs/Hardware-Software-Final-Project/blob/main/picture/BME280.png)  
**Function:** A humidity sensor measures the moisture content in the air. In the context of a sleep monitoring system, it assesses the humidity level of the room where the person is sleeping.  
**Importance in Sleep Monitoring:** Humidity levels can significantly impact sleep quality. Both high and low humidity can make the sleeping environment uncomfortable, potentially disrupting sleep. High humidity can make the air feel stuffy and interfere with breathing, while low humidity can cause dryness in the throat and nasal passages. 


#### Sound Sensor:
![Microphone Amlifier](https://github.com/gheacs/Hardware-Software-Final-Project/blob/main/picture/Microphone%20Amplifier.png)  
**Function:** This sensor detects the intensity and patterns of sound in the sleeping environment. It can pick up various noises, including snoring, which is a common sleep disruptor.  
**Importance in Sleep Monitoring:** Sound levels are crucial in assessing sleep quality. Snoring, either by the person sleeping or by a partner, can indicate sleep disturbances like sleep apnea. Other ambient noises can also disrupt sleep cycles. 

#### Accelerometer:
![Accelerometer](https://github.com/gheacs/Hardware-Software-Final-Project/blob/main/picture/Accelerometer.png)  
**Function:** An accelerometer in this system measures the physical movement of the person during sleep. It can detect motions ranging from slight twitches to larger movements.  
**Importance in Sleep Monitoring:** Physical movement during sleep can be a strong indicator of sleep quality. Restless movements might suggest discomfort or interruptions in sleep stages. The accelerometer data can help in identifying patterns of restlessness or calm in sleep.

### Display Device
![Display](https://github.com/gheacs/Hardware-Software-Final-Project/blob/main/picture/display%20device.png)    
1. Display device with an OLED screen, designed to display the quality of sleep.   
2. The screen shows a sleep quality meter, similar to a speedometer, with a needle indicating the current sleep quality level.   
3. On the side of the device, there's a prominent on/off button.

### Architecture of Sleep Monitoring System
![System](https://github.com/gheacs/Hardware-Software-Final-Project/blob/main/picture/Proposed%20Flow.png)   
The proposed system:
1. Data is transferred from sensor to microcontroller.  
2. With pre-trained simplified algorithm, ESP32 can make analysis about the patient’s sleep quality.  
3. The analysis would be shown in the output visualization.  

### Decision Tree - Interpreting Sleep Environment
**Note: TBC on the threshold for each sensors**

![Decision Tree](https://github.com/gheacs/Hardware-Software-Final-Project/blob/main/picture/Decision%20tree.png)   



