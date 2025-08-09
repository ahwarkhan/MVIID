# Multi-Vector IoT Intrusion Classifier (MVIIC)

This project introduces a lightweight multi-vector intrusion detection framework designed to address cybersecurity vulnerabilities in Internet of Medical Things (IoMT) healthcare systems. The framework, **MVIIC**, utilizes a novel deep learning approach based on a custom **Modified Gated Recurrent Unit (MGRU)** architecture.

## Key Features

* **Dual-Classifier System:** The framework features a dual-classifier system. A **Binary Label Classifier (BLC)** provides simple attack notifications for non-technical users, while a **Multi-Label Classifier (MLC)** offers detailed attack vector identification for cybersecurity professionals.
* **GA-Enhanced Feature Selection:** A **genetic algorithm (GA)** was employed to select the most effective features from the dataset. This process reduced computational complexity and improved performance without compromising detection accuracy.
* **High Performance:** The framework was rigorously tested against the **CICIoT2023** and **CICIoMT2024** datasets, demonstrating superior performance metrics (accuracy, precision, recall, and F1-score) when compared to other existing intrusion detection systems.
* **Resource Efficiency:** The lightweight and computationally efficient nature of the MGRU layers makes the architecture suitable for real-time deployment in **resource-constrained IoMT environments**.
