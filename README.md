# rf_jamming_detection
Project Overview
This repository focuses on detecting RF jamming attacks in Vehicular Ad-hoc Networks (VANETs) using machine learning techniques. The project leverages the "RF Jamming Dataset for Vehicular Wireless Networks," which contains comprehensive data for evaluating RF jamming detection algorithms.

The dataset and methodology are inspired by the research paper:
"RF Jamming Classification Using Relative Speed Estimation in Vehicular Wireless Networks."

This project aims to develop and deploy a robust detection system to identify and classify RF jamming attacks, improving the security and reliability of VANETs.

Dataset
The dataset includes diverse scenarios of RF jamming attacks, along with ground truth labels. It is specifically tailored for advancing RF jamming detection techniques in VANETs.

Key Features in the Dataset
Variations of Relative Speed (VRS): Measures the changes in the relative speed between vehicles.
Received Signal Strength Indicator (RSSI): Indicates the strength of the received signal.
Signal-to-Interference-and-Noise Ratio (SINR): Represents the signal quality amidst interference and noise.
Packet Delivery Ratio (PDR): Measures the reliability of data transmission.
The dataset is an essential tool for researchers and practitioners in wireless communication security to enhance VANETs' robustness against malicious interference.

Project Components
1. Data Preprocessing
Cleaned and normalized the dataset to ensure consistent scaling of features.
Handled missing values by filling them with appropriate measures (e.g., mean).
2. Feature Selection
Focused on the most relevant features: VRS, RSSI, SINR, PDR, and others.
Analyzed correlations to understand feature importance for detecting RF jamming.
3. Machine Learning Model
Trained a Random Forest Classifier for multi-class classification:
Class 1: No Jamming.
Class 2: Reactive Jamming Attack.
Class 3: Constant Jamming Attack.
Achieved high accuracy in predicting the type of RF jamming attack using the dataset.
4. Edge Deployment
Optimized the trained model for deployment on edge devices such as Raspberry Pi.
Implemented real-time prediction using live or simulated RF signal data.
5. Visualization
Developed a user-friendly interface to display predictions and visualize key metrics:
Real-time updates of detected jamming types.
Alerts and notifications for identified attacks.


Contributions
Contributions are welcome! Feel free to:

Fork this repository.
Submit issues or suggestions.
Create pull requests for improvements.
Acknowledgments
We acknowledge the researchers and contributors of the RF Jamming Dataset for Vehicular Wireless Networks, which serves as the foundation for this project. Special thanks to the authors of the paper "RF Jamming Classification Using Relative Speed Estimation in Vehicular Wireless Networks" for their insights and efforts in advancing wireless communication security.

License
This project is licensed under the MIT License. You are free to use, modify, and distribute this software in compliance with the license.

For questions or support, feel free to open an issue or contact the maintainer!







