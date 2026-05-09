# Fire-and-Smoke-Recognition-with-YOLO

Fire and Smoke real-time recognition system (TIER 1)

Jorge Félix Peguero Solis

Problem statement: In 2024 more than 56,000 wildfires across the country were reported. These incidents affect national reserves, agriculture enterprises, and wildlife refuges.

Solution Oveview: This project addresses the recognition of wildfires and smoke in real-time to improve response times. The system will receive input data from users, security cameras, drones, etc. And apply object recognition to identify wildfires and smoke. Triggering alerts based on probabilities.

Technical Approach: CV technique: Classification with YOLO. Model: YOLOv8n-cls Frameworks: Ultralytics.

Dataset Plan: https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset Syze: Sround 2700 images. Labels: fire / nofire.

Metrics: Primary Metric: Recall. Secondary Metric: Response time.

Week By Week plan: For this project I designed a four weeks plan. 1st Week: Set up the environment and download the dataset. 2nd week: Apply and train the YOLOv8 model. 3rd week: Test the model and optimize parameters to improve its performance. 4th week: Use the Telegram API to make a bot. Supervise the final system.

Resources Needed: Compute: Google Colab and Kaggle Frameworks: Ultralytics, Requests, Matplotlib, Pillow, and OpenCV. Estimated cost: 0$

Risks & Mitigation Table:

Risk Probability Mitigation

Data Imbalance: In case of bias due to data imbalance I will use synthetic data (rotation, scaling, saturation, etc.) to balance the dataset. Latency: I would change the architecture or even the model selected to achieve a better time performance. Adversarial conditions: Add new data to teach the model how to perform in extreme weather conditions.
