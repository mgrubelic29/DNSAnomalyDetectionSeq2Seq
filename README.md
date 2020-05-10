# DNS Anomaly Detection using a Sequence-to-Sequence Model  
## **Authors:** Matthew Grubelic, Chris Saliby, Anthony Saldana, Luke Turbert, Andrew Rittenhouse  
## Advisors: Vahid Behzadan, Ph.D., Liberty Page 
### Sponsor: Secure and Assured Intelligent Lab (SAIL)  
**Abstract:**
The risk of crippling cyber attacks on computer systems is increasing rapidly each day. Current software and techniques used to defend against these malicious attacks are showing their limitations and are being completely overwhelmed in some cases. As a result, a more modern and forwardthinking solution is becoming increasingly necessary. The team is implementing one such software solution using a sequence to sequence neural network in Python3 with the Pytorch library to observe malicious events and predict when the next attack might happen. In this project, a deep learning sequence to sequence model, modeled after behavior of predictive typing technologies, was implemented on the CICIDS 2017 dataset to detect malicious DNS traffic and determine the probability of another attack in the future. The model functions by observing sequences of network packets, using them to predict upcoming sequences of packets, and comparing the actual observed data to the prediction. Since the amount of notable research and experimentation done in this area so far is lacking, the results yielded by this network traffic anomaly detection approach further demonstrate that the use of a sequence to sequence model is a viable, though still emerging, solution for modern intrusion detection systems.  

**Goal:** _To leverage machine learning techniques to automatically detect anomalous traffic using the DNS protocol. The project seeks to eliminate the need for manual examination of suspicious log files by allowing a machine learning algorithm to make decisions. The machine learning algorithm will use an unsurpervised learning model that is trained off of known data and then compares this data to unknown, live DNS data._


## What is in this README.md? 

In this README.md, a quick instructional guide will be given to help in the setup and execution of the code associated with this projcet.

The project has **three main pieces of code:** The "DARPADatatsetParser.ipynb", the "Seq2SeqTraining.ipynb" and the "Seq2SeqTesting.ipynb"

