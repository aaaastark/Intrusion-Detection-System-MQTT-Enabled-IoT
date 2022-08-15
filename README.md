# Research Paper: A Deep Learning-Based Intrusion Detection System for MQTT Enabled IoT

###  In this thesis, we proposed a Artificial Neural Network (ANN) for intrusion detection in the MQTT-based protocol and also compared its performance with other traditional machine learning (ML) algorithms, such as a Deep Neural Network (DNN), Naive Bayes (NB), Random Forest (RF), k-Nearest Neighbour (kNN), Decision Tree (DT), Long Short-Term Memory (LSTM), and Gated Recurrent Units (GRUs). The performance is proved using publicly available datasets, including MQTT-IoTIDS2020. The MQTT-IoT-IDS2020 contains three abstract-level features, including Uni-Flow, Bi-Flow, and Packet-Flow. The results for the first dataset and binary classification show that the ANN-based model achieved 99.79%, 99.85%, and 94.36% accuracies for Uni-flow, Bi-flow, and Packet-flow, respectively. However, in the case of multi-label classification, these accuracies reduced to 99.71%, 99.70%, and 92.86%, respectively.

#### Research Paper: A Deep Learning-Based Intrusion Detection System for MQTT Enabled IoT
- Website Link to Paper: <https://www.researchgate.net/publication/355478103_A_Deep_Learning-Based_Intrusion_Detection_System_for_MQTT_Enabled_IoT>.

#### Loading the dataset IEEE DataPort (MQTT-IOT-IDS2020)
- Website Link to Dataset: <https://ieee-dataport.org/open-access/mqtt-iot-ids2020-mqtt-internet-things-intrusion-detection-dataset>.
#### MQTT INTERNET OF THINGS INTRUSION DETECTION DATASET

#### API that are used in this Project
- tensorflow
- sklearn
- keras
- matplotlib
- numpy
- pandas
- warnings

## Paper vs Proposed Results: DNN vs ANN netowrks

#### Binary Class Classification

- Bi-flow Features Paper: 99.75%
- Bi-flow Features Proposed: 99.85%
- ![image](https://user-images.githubusercontent.com/74346775/184626036-9cdf59cf-fde2-46cc-9af3-844d0fe70723.png)
- ![image](https://user-images.githubusercontent.com/74346775/184626150-9a6f98db-b45c-40d7-b3cb-579c8ab9f6f2.png)
- ![image](https://user-images.githubusercontent.com/74346775/184626300-7e0a63dc-4b8b-4ff0-bac8-1d6cb492c8c0.png)

- Ui-flow Features Paper: 99.92%
- Ui-flow Features Paper: 99.79%
- ![image](https://user-images.githubusercontent.com/74346775/184626355-958488e9-64c9-404b-a2ff-732f42b84fb7.png)
- ![image](https://user-images.githubusercontent.com/74346775/184626386-9de5528e-f7f6-4a0a-96a8-7abdf0f139eb.png)
- ![image](https://user-images.githubusercontent.com/74346775/184626451-21232b91-0cac-4dfe-aa69-b5738ba7426e.png)

- Packet-flow Features Paper: 94.94%
- Packet-flow Features Paper: 94.36%
- ![image](https://user-images.githubusercontent.com/74346775/184626492-1f96dc18-475d-45ac-8878-153a475cc84c.png)
- ![image](https://user-images.githubusercontent.com/74346775/184626549-c1b197c4-ae54-49b1-afbd-779ef947f6d9.png)
- ![image](https://user-images.githubusercontent.com/74346775/184626596-94a59fac-d84a-4e50-bd96-3d2aecc557ef.png)

#### Multi Class Classification

- Bi-flow Features Paper: 98.12%
- Bi-flow Features Proposed: 99.70%

- Ui-flow Features Paper: 97.08%
- Ui-flow Features Paper: 99.71%

- Packet-flow Features Paper: 90.79%
- Packet-flow Features Paper: 92.86%


