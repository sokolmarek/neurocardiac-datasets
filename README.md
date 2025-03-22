# ECG (Multimodal) Datasets for Cognitive Load, Stress, and Emotion Research

This list provides a comprehensive collection of publicly available and restricted datasets used for research especially on **cognitive load**, **stress**, and **emotions**, with a particular focus on **Electrocardiogram (ECG)** data. The emphasis on ECG reflects the importance of heart activity in understanding autonomic nervous system responses and psychophysiological states.

These datasets are valuable for developing machine learning models, conducting psychological and physiological analysis, and advancing human-computer interaction research. Alongside ECG, many datasets include other modalities such as **EEG**, **EDA**, **PPG**, **EMG**, **respiration**, and more, enabling multimodal data fusion and deeper insights into human states.

To contribute a new resource, open an issue mentioning it, or a pull request with it.

---

## Table of Contents
So far, the datasets are categorized into five main types:

1. [Cognitive Load](#cognitive-load) – Includes datasets for assessing mental workload during  cognitive tasks.
2. [Stress](#stress) – Includes datasets focused on stress responses under different conditions.  
3. [Emotions](#emotions) – Includes datasets for analyzing emotional states from physiological and behavioral signals.
4. [Drivers](#drivers) – Includes datasets collected from drivers in real-world driving scenarios.
5. [Virtual reality](#virtual-reality) – Includes datasets collected in virtual reality environments.
6. [Mixed](#mixed) – Includes datasets that capture both cognitive and emotional responses.   
7. [Stimulation](#stimulation) – Includes datasets focused on physiological responses to various stimuli.   
8. [Non-ECG Multimodal](#non-ecg-multimodal) – Includes datasets with multimodal physiological data excluding ECG.
 
## Cognitive Load

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [WAUC (Workload Assessment Under Physical Activity)](https://doi.org/10.3389/fnins.2020.549524) | 48 | NASA Multi-Attribute Task Battery (MATB-II), physical exercise (bike/treadmill) | ECG, EEG, EDA, Respiration, PPG, Temperature, Accelerometer |
| [MAUS (Mental Workload Assessment on N-Back)](https://dx.doi.org/10.21227/q4td-yd35) | 22 | N-back tasks (0-back, 2-back, 3-back) | ECG, EDA, PPG |
| [CLARE (Cognitive Load Assessment in Real-time)](https://arxiv.org/abs/2404.17098) | 24 | Multi-Attribute Task Battery (MATB-II) | ECG, EEG, EDA, Eye Tracking |
| [MMOD-COG (Multimodal Cognitive Load Classification)](https://doi.org/10.1109/ISPA.2019.8868678) | 40 | Reading comprehension, mental arithmetic | ECG, EDA, Speech |
| [Simultaneous Physiological Measurements](https://physionet.org/content/simultaneous-measurements/1.0.2/) | 13 | Baseline, treadmill walking, cognitive audio test, uphill walking | ECG, PPG, HR, HRV, Respiration, Oxygen Saturation, Accelerometry |

---

## Stress

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [WESAD (Wearable Stress and Affect Detection)](https://dl.acm.org/doi/10.1145/3242969.3242985) | 15 | Trier Social Stress Test (public speaking, mental arithmetic), watching amusing/neutral videos | ECG, EMG, Respiration, EDA, PPG, Accelerometer |
| [SWELL-KW (Stress and User Modeling at Work)](https://cs.ru.nl/~skoldijk/SWELL-KW/Dataset.html) | 25 | Office work tasks with interruptions and time pressure | ECG, EDA, Body Posture (Kinect), Facial Video |
| [cStress](https://pmc.ncbi.nlm.nih.gov/articles/PMC4631393/) | 41 | Trier social stress test, cold pressor, mental arithmetic | ECG, Respiration, Accelerometer |

---

## Emotions

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [DREAMER](https://zenodo.org/records/546113) | 23 | Watching 18 film clips | EEG, ECG |
| [AMIGOS (A Dataset for Affect, Personality and Mood Research on Individuals and Groups)](https://www.eecs.qmul.ac.uk/mmv/datasets/amigos/) | 40 | Watching short and long videos individually and in groups | EEG, ECG, GSR, Facial Videos |
| [CASE (Continuously Annotated Signals of Emotion)](https://gitlab.com/karan-shr/case_dataset) | 30 | Watching various videos | ECG, BVP, EMG, GSR, Respiration, Skin Temperature |
| [Emognition](https://www.nature.com/articles/s41597-022-01262-0) | 43 | Watching short film clips eliciting nine discrete emotions | EEG, BVP, HR, EDA, SKT, ACC, GYRO, Upper-body Videos |
| [EmoWear](https://www.nature.com/articles/s41597-024-03429-3) | 49 | Watching emotionally stimulating video clips | ECG, BVP, EDA, Respiration, Skin Temperature, Accelerometer, Gyroscope |
| [ECG and GSR Data for Emotion Recognition](https://data.mendeley.com/datasets/g2p7vwxyn2/2) | 25 | Watching stimulus videos designed to elicit specific emotions | ECG, GSR |
| [A2ES (Asian Affective and Emotional State)](https://www.mdpi.com/1999-4893/16/3/130) | 47 | Emotion elicitation tasks | ECG, PPG |

---

## Drivers
| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [AffectiveROAD](https://www.media.mit.edu/tools/affectiveroad/) | 10 | Real-world driving on city and highway routes | ECG, EDA (wrists), HR, BR, Skin Temp, In-car Temp, Humidity, Sound levels, GPS, Interior/Exterior Video |
| [Stress Recognition in Automobile Drivers](https://physionet.org/content/drivedb/1.0.0/) | 17 | Real-world driving (city and highway) | ECG, EMG, GSR, Respiration |
| [MIT Driver Stress](https://doi.org/10.1109/TITS.2005.848368) | 17 | Real-world driving in city (high stress) vs. highway (low stress) | ECG, EMG, EDA, Respiration |
| [ADABase (Autonomous Driving Cognitive Load Assessment)](https://adabase-dataset.github.io/) | 51 | Driving simulation with secondary cognitive tasks (e.g., mental arithmetic) | ECG, EDA, EMG, Respiration, PPG, Eye Tracking, Video |
| [manD](https://www.nature.com/articles/s41597-024-03137-y) | 50 | Driving through five scenarios designed to elicit emotions like neutral, anger, fear, sadness, and surprise | ECG, EEG, EDA |

---

## Virtual reality
| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [Multilevel Stress Assessment from ECG in a Virtual Reality Environment Using Multimodal Fusion](https://doi.org/10.1109/JSEN.2023.3323290) | 19 | Virtual reality tasks designed to induce stress | ECG, additional modalities not specified |
| [VREED: Virtual Reality Emotion Recognition Dataset Using Eye Tracking, ECG, and GSR](https://www.kaggle.com/datasets/lumaatabbaa/vr-eyes-emotions-dataset-vreed) | 34 | Immersive 360° video-based virtual environments | Eye tracking, ECG, GSR |

---

## Mixed

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [CLAS (Cognitive Load, Affect and Stress)](https://dx.doi.org/10.21227/ybsw-yr53) | 62 | Math problems, logic puzzles, Stroop test, emotional images, audio/video stimuli | ECG, PPG, EDA, Accelerometer |
| [ECSMP (Emotion, Cognition, Sleep, and Multi-Model Physiological Signals)](https://doi.org/10.1016/j.dib.2021.107660) | 20 | Cognitive tasks, emotional stimuli, sleep monitoring | EEG, ECG, PPG, EOG, EMG, Respiration, GSR, Temperature |
| [StressID (Multimodal Stress Identification Dataset)](https://project.inria.fr/stressid/) | 65 | Emotional video clips, mental arithmetic, reading, public speaking | ECG, EDA, Respiration, Video, Audio |
| [SenseCobot](https://zenodo.org/records/8363762) | 21 | Collaborative robotics programming tasks | ECG, EDA, EEG, Body Temperature, BVP, Facial Emotions, NASA-TLX Questionnaires |

---

## Stimulation

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [Concurrent EEG, ECG, and Behavior with tES](https://github.com/ngebodh/GX_tES_EEG_Physio_Behavior#i-want-to-look-at-individual-stimulation-trials) | 62 | tES (9 types), cognitive vigilance task | EEG, ECG, EOG, Behavioral |

## Non-ECG Multimodal

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [DEAP](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/) | 32 | 40 music video clips | EEG, EDA, BVP, Respiration, Skin Temp |
| [EEVR](https://melangelabiiitd.github.io/EEVR/) | 37 | Immersive 360° VR videos | BVP, EDA, PPG |


