Anomaly Detection Edge AI - Arduino UNO QAn Edge AI-powered anomaly detection system deployed on the Arduino UNO Q using Edge Impulse. 
This project runs a machine learning model directly on the device to detect anomalies locally without requiring a continuous cloud connection, ensuring minimal latency and low power consumption.
📌 Project OverviewModel Name: Bowl Anomaly Detector (Personal)Deployment Target: Arduino UNO Q (Qualcomm QRB2210 CPU)Protocol: Edge Impulse Linux protocol
🚀 Performance BenchmarksThe model has been built and optimized for the Arduino UNO Q deployment target. Below is a summary of the performance metrics for the available build options:Optimization LevelTotal LatencyRAM UsageFlash UsageAccuracyQuantized (int8) (Recommended)525 ms (Image: 1 ms, Object Detection: 524 ms)4.0 KB3.3 MB75.00%Unoptimized (float32)340 ms (Image: 1 ms, Object Detection: 339 ms)4.0 KB11.0 MB100.00%🛠️ Getting Started & DeploymentClone the Repository:

<img width="413" height="392" alt="image" src="https://github.com/user-attachments/assets/c0fbb898-79bc-4ef3-b19f-385f2238610b" />


<img width="737" height="355" alt="image" src="https://github.com/user-attachments/assets/b17da263-22f3-4180-b5c9-b17319df18d7" />
