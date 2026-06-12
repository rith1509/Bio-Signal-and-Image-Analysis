# Bio-Signal and Image Analysis: Product-Driven Engineering

This repository contains advanced pipelines and technical evaluations for biomedical signal processing, machine learning models, and wearable-device algorithm development. The core focus is translating theoretical signal processing concepts into application-oriented solutions designed for clinical diagnostics, human-machine interfacing, and consumer health technology.

## Core Engineering Frameworks and Applications

### 1. Neuroengineering and Cognitive Computing
* **ADHD Diagnostic Classifier (`adhd_mywork.ipynb`):** An end-to-end machine learning pipeline developed to preprocess raw EEG data, extract critical spectral features, and classify ADHD tendencies with an emphasis on clinical deployability.
* **P300 Event-Related Potential (ERP) Speller (`code_for_EEG_P300_Event_Related_Potential_Analysis.ipynb`):** An implementation of a Brain-Computer Interface (BCI) paradigm. Processes time-locked EEG signals to detect P300 waves, translating neural intent into system commands.
* **Cognitive Load Quantifier ([Analysis of Cognitive Load using EEG.pdf](Analysis%20of%20Cognitive%20Load%20using%20EEG.pdf)):** A quantitative study analyzing spectral power changes across Alpha, Beta, and Theta frequency bands to objectively measure mental fatigue and cognitive strain.

### 2. Physiological Signal Processing Pipelines
* **ECG Artifact Rejection and Feature Extraction ([RithRajak_24116085_ecg.pdf](RithRajak_24116085_ecg.pdf)):** Implementation of digital filtering algorithms (Bandpass and Notch filters) to isolate clean electrocardiogram signals, followed by automated QRS complex detection.
* **EMG Neuromuscular Analysis ([RithRajak_24116085_emg_assignment.pdf](RithRajak_24116085_emg_assignment.pdf)):** Electromyogram signal processing optimized for muscle fatigue detection, prosthetics control mapping, and human-machine interfacing.

### 3. Edge-Ready Human Activity Recognition (HAR)
* **Sensor Fusion Analytics ([RithRajak_24116085_humanActivityRecognition.pdf](RithRajak_24116085_humanActivityRecognition.pdf)):** Employs tri-axial accelerometer and gyroscope data to develop wearable-ready classification models that track and identify physical activities in real time.

---

## Technical Stack and Engineering Toolkit

* **Languages:** Python (Jupyter Notebook environment)
* **Signal Processing and ML:** NumPy, SciPy (Signal Module), Scikit-Learn, MNE-Python, Matplotlib, Seaborn
* **Signal Modalities:** EEG, ECG, EMG, Audio/Speech, Inertial Sensor Data (IMU)

---

## Product and Industry Relevance

The methodologies developed in this repository address foundational engineering bottlenecks in health-tech product architecture:
* **Motion Artifact Mitigation:** Implemented robust preprocessing pipelines to handle noisy, real-world data streams ([Analysis and Preprocessing of Pure and Contaminated EEG.pdf](Analysis%20and%20Preprocessing%20of%20Pure%20and%20Contaminated%20EEG.pdf)).
* **Hardware-Agnostic Form Factors:** Evaluated trade-offs between traditional wet sensors and consumer-grade form factors ([Report on Dry-Contact and Noncontact Biopotential.pdf](Report%20on%20Dry-Contact%20and%20Noncontact%20Biopotential.pdf)) to design algorithms optimized for everyday wearable hardware.

---

## Repository Structure

```text
├── Neuroengineering/
│   ├── adhd_mywork.ipynb                       # ADHD ML Classification Pipeline
│   └── code_for_EEG_P300_Event_Related_...     # BCI P300 Speller Implementation
├── Physiological_Signals/
│   ├── RithRajak_24116085_ecg.pdf              # ECG QRS Detection
│   └── RithRajak_24116085_emg_assignment.pdf   # EMG Muscle Fatigue Analytics
├── Wearables_and_Speech/
│   ├── RithRajak_24116085_humanActivity...     # IMU-based Activity Tracker
│   └── RithRajak_24116085_speech (2).pdf       # Speech Audio Signal Processing
└── Technical_Reports/                       # Architectural and Research Frameworks
