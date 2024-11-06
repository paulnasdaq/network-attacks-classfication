# Multiclass Classifier: Identification of malicious network traffic

## Dataset
The raw network packets of the UNSW-NB15 dataset was created by the IXIA PerfectStorm tool in the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS) for generating
a hybrid of real modern normal activities and synthetic contemporary attack behaviours. Tcpdump tool used to capture 100 GB of the raw traffic (e.g., Pcap files). This data set has the following
nine types of attacks, namely, 
- Fuzzers 
- Analysis, 
- Backdoors
- DoS
- Exploits
- Generic
- Reconnaissance
- Shellcode
- Worms

The Argus and Bro-IDS tools are used and twelve
algorithms are developed to generate totally 49 features with the class label.

## Goal
The goal is to create a classifier to classify the data into the either normal or malicious traffic, and the exact type of attack each entry belongs to.