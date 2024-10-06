# **Spiking Neural Networks for Auditory Signal Processing**

This repository contains the code and experiments related to my Data Science master's dissertation, titled **"Exploring Spiking Neural Networks for Auditory Signal Processing: A Neuromorphic Approach to Speech Recognition and Sound Classification."** The project leverages the biological principles of Spiking Neural Networks (SNNs) to address the challenges of auditory processing tasks such as speech recognition and sound classification, offering improved energy efficiency and temporal precision.

## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## **Overview**
Traditional artificial neural networks (ANNs) have shown success in auditory processing tasks, but they often struggle with efficiency, particularly in resource-constrained environments. This project explores the application of SNNs, which more closely mimic biological neurons, to improve temporal information processing and energy efficiency in auditory tasks.

The main goals of this project are:
- Developing Spiking Neural Networks to process auditory data.
- Implementing SNN models for speech recognition and sound classification.
- Comparing the performance of SNNs with traditional ANN models in terms of accuracy and energy efficiency.


## **Features**
- **Spiking Neural Networks (SNNs)**: Modeled using biologically inspired neurons such as the Leaky Integrate-and-Fire (LIF) and Refractory LIF (RLIF) neurons.
- **Temporal Coding**: Explored temporal encoding mechanisms that allow for precise processing of time-sensitive data such as auditory signals.
- **Surrogate Gradient Learning**: Implemented surrogate gradients to enable backpropagation through time (BPTT) in the non-differentiable SNN framework.
- **Comparative Evaluation**: Compared the performance of SNNs against traditional ANNs in speech recognition and sound classification tasks.
- **Auditory Signal Preprocessing**: Converted continuous auditory signals into spike trains using an auditory front-end suitable for SNNs.

## **Datasets**
The experiments in this project utilize the following spiking datasets:
1. **Heidelberg Spiking Datasets (SHD)**: A collection of auditory recordings encoded as spike trains.
2. **Speech Commands Dataset (SSC)**: Another dataset used for evaluating speech recognition tasks.

Both datasets provide temporal structure and phase-coded spike outputs, which are ideal for spiking neural networks.

## **Installation**
To run the code in this repository, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yassine99ab/SNN-Auditory-Processing.git
    cd SNN-Auditory-Processing
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## **Usage**
Once the environment is set up, you can run the notebooks to reproduce the experiments:

1. Open the notebooks using Jupyter:
    ```bash
    jupyter notebook RLIF_ssc_model.ipynb
    jupyter notebook RLIF_shd_model.ipynb
    ```

2. Follow the instructions in the notebooks to train and evaluate the SNN models. Make sure to adjust paths for datasets if needed.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Contact**
For any inquiries or further questions, feel free to reach out:

- **Author**: Yassine Abdallas
- **Email**: yassine.abdallas1@gmail.com
