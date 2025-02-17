# RT-IoT2022-CyberThreat-Detection  

The **RT-IoT2022-CyberThreat-Detection** project focuses on analyzing real-time IoT network traffic to detect cybersecurity threats and anomalies. This project utilizes the **RT-IoT2022 dataset**, which integrates a diverse range of IoT devices and sophisticated network attack methodologies. By capturing both normal and adversarial network behaviors, this dataset helps in identifying malicious activities and improving Intrusion Detection Systems (IDS) for IoT environments.  

### **Dataset Overview**  
The RT-IoT2022 dataset includes various features extracted from IoT network traffic, offering valuable insights into cybersecurity threats. The data was collected using the **Zeek network monitoring tool** and the **Flowmeter plugin** to ensure accurate bidirectional traffic analysis.  

Key features in the dataset include:  
- **Proto**: Protocol used in the network communication.  
- **Service**: Type of service associated with the network connection.  
- **Flow Duration**: Duration of the network flow in milliseconds.  
- **Forward & Backward Packets**: Number of packets in both directions of communication.  
- **Payload Size**: Data payload transferred in the network flow.  
- **Attack Type**: Label indicating the type of network attack (e.g., Brute-Force SSH, DDoS, Slowloris, Nmap).  

### **Project Goals**  
The primary objectives of this project are to:  
1. Detect and classify cyber threats in real-time IoT networks.  
2. Enhance Intrusion Detection Systems (IDS) for IoT security.  
3. Analyze IoT network traffic patterns to identify malicious behaviors.  

### **Technologies Used**  
- **Python**: For data processing, analysis, and machine learning modeling.  
- **Pandas & NumPy**: For
