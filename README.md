# ECG (Multimodal) Datasets for Cognitive Load, Stress, and Emotion Research

This list provides a comprehensive collection of publicly available and restricted datasets used for research especially on **cognitive load**, **stress**, and **emotions**, with a particular focus on **Electrocardiogram (ECG)** data. The emphasis on ECG reflects the importance of heart activity in understanding autonomic nervous system responses and psychophysiological states.

These datasets are valuable for developing machine learning models, conducting psychological and physiological analysis, and advancing human-computer interaction research. Alongside ECG, many datasets include other modalities such as **EEG**, **EDA**, **PPG**, **EMG**, **respiration**, and more, enabling multimodal data fusion and deeper insights into human states.

To contribute a new resource, open an issue mentioning it, or a pull request with it.

---

## Table of Contents
So far, the datasets are categorized into the following sections:

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
| [ECG and EEG Based Detection and Multilevel Classification of Stress](https://zenodo.org/records/7782558) | 40 | Mental arithmetic task (with and without audio distraction) | ECG, EEG |  
---

## Stress

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [WESAD (Wearable Stress and Affect Detection)](https://ubi29.informatik.uni-siegen.de/usi/data_wesad.html) | 15 | Trier Social Stress Test (public speaking, mental arithmetic), watching amusing/neutral videos | ECG, EMG, Respiration, EDA, PPG, Accelerometer |
| [SWELL-KW (Stress and User Modeling at Work)](https://cs.ru.nl/~skoldijk/SWELL-KW/Dataset.html) | 25 | Office work tasks with interruptions and time pressure | ECG, EDA, Body Posture (Kinect), Facial Video |
| [cStress](https://pmc.ncbi.nlm.nih.gov/articles/PMC4631393/) | 41 | Trier social stress test, cold pressor, mental arithmetic | ECG, Respiration, Accelerometer |
| [Classification of Stress via Ambulatory ECG and GSR Data](https://github.com/ZacDair/EMBC_Release) | 45 | Self-reported stress annotations from daily life (via SMILE dataset) | ECG, GSR, Skin Temperature |
| [micro-Stress EMA: Detecting Stress in Pregnant Mothers](https://osf.io/4zajm/) | 35 | Self-reported micro-EMA stress measures during daily activities | ECG, GSR, Accelerometer, Skin Temperature |  


---

## Emotions

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [DREAMER](https://zenodo.org/records/546113) | 23 | Watching 18 film clips | EEG, ECG |
| [AMIGOS (A Dataset for Affect, Personality and Mood Research on Individuals and Groups)](https://www.eecs.qmul.ac.uk/mmv/datasets/amigos/) | 40 | Watching short and long videos individually and in groups | EEG, ECG, GSR, Facial Videos |
| [CASE (Continuously Annotated Signals of Emotion)](https://gitlab.com/karan-shr/case_dataset) | 30 | Watching various videos | ECG, BVP, EMG, GSR, Respiration, Skin Temperature |
| [EmoWear](https://www.nature.com/articles/s41597-024-03429-3) | 49 | Watching emotionally stimulating video clips | ECG, BVP, EDA, Respiration, Skin Temperature, Accelerometer, Gyroscope |
| [ECG and GSR Data for Emotion Recognition](https://data.mendeley.com/datasets/g2p7vwxyn2/2) | 25 | Watching stimulus videos designed to elicit specific emotions | ECG, GSR |
| [A2ES (Asian Affective and Emotional State)](https://www.mdpi.com/1999-4893/16/3/130) | 47 | Emotion elicitation tasks | ECG, PPG |
| [MAHNOB-HCI – Multimodal Affect Tagging](https://mahnob-db.eu/hci-tagging/) | 27 | 20 emotional video fragments + images, naturalistic viewing with self-report after each. | ECG (3-ch), EEG (32-ch), EDA/skin temperature, respiration; 6 cameras (face/body) 60 Hz, eye gaze 60 Hz, microphone 44.1 kHz. |
| [DECAF – Database for Decoding Affective Responses](https://decaf-dataset.github.io/) | 30 | 40 one-min music videos + 36 film clips, to evoke amusement, sadness, fear, etc. | ECG, MEG (brain signals), horizontal EOG, trapezius EMG, NIR facial video (all synchronized). |
| [K-EmoCon – Continuous Emotion Recognition in Naturalistic Conversations](https://www.nature.com/articles/s41597-020-00630-y) | 32 | Paired debates on social issues with real-time emotion annotation | ECG, EEG, EDA, PPG, Skin Temperature, Accelerometer, Audio-visual recordings, Self-Reports |

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
| [VR Pilots “CogPilot”](https://physionet.org/content/virtual-reality-piloting/1.0.0/) | 35 | VR flight simulator (ILS landing task) at four difficulty levels (wind, turbulence, visibility). | ECG, EMG, pupil diameter (eye-tracking). |
| [“Overview Effect” Space VR dataset](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/VBDAB4) | 40 | Immersive 360° VR space journey (SpaceBuzz) to induce awe. | ECG, EDA, respiration. |

---

## Mixed

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [CLAS (Cognitive Load, Affect and Stress)](https://dx.doi.org/10.21227/ybsw-yr53) | 62 | Math problems, logic puzzles, Stroop test, emotional images, audio/video stimuli | ECG, PPG, EDA, Accelerometer |
| [ECSMP (Emotion, Cognition, Sleep, and Multi-Model Physiological Signals)](https://doi.org/10.1016/j.dib.2021.107660) | 20 | Cognitive tasks, emotional stimuli, sleep monitoring | EEG, ECG, PPG, EOG, EMG, Respiration, GSR, Temperature |
| [StressID (Multimodal Stress Identification Dataset)](https://project.inria.fr/stressid/) | 65 | Emotional video clips, mental arithmetic, reading, public speaking | ECG, EDA, Respiration, Video, Audio |
| [SenseCobot](https://zenodo.org/records/8363762) | 21 | Collaborative robotics programming tasks | ECG, EDA, EEG, Body Temperature, BVP, Facial Emotions, NASA-TLX Questionnaires |
| [uulmMAC – Ulm Multimodal Affective Corpus](https://www.mdpi.com/1424-8220/20/8/2308) | 57 | Interactive HCI scenario with cognitive games inducing boredom/frustration. | ECG, EMG, EDA, respiration, body temperature; video & audio streams. |
| [MuSe-Stress: Multimodal Emotional Stress](https://zenodo.org/records/7920826) | 69 | Trier Social Stress Test (TSST) | ECG, Respiratory Rate, BPM, Audio, Video, Text |  

---

## Stimulation

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------|
| [Concurrent EEG, ECG, and Behavior with tES](https://github.com/ngebodh/GX_tES_EEG_Physio_Behavior#i-want-to-look-at-individual-stimulation-trials) | 62 | tES (9 types), cognitive vigilance task | EEG, ECG, EOG, Behavioral |

## Non-ECG Multimodal

| Title | N | Stimuli | Modalities |
|-------|---|---------|------------| 
| [Emognition](https://www.nature.com/articles/s41597-022-01262-0) | 43 | Watching short film clips eliciting nine discrete emotions | EEG, BVP, HR, EDA, SKT, ACC, GYRO, Upper-body Videos |
| [DEAP](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/) | 32 | 40 music video clips | EEG, EDA, BVP, Respiration, Skin Temp |
| [EEVR](https://melangelabiiitd.github.io/EEVR/) | 37 | Immersive 360° VR videos | BVP, EDA, PPG |
| [Predicting Intrinsic and Extraneous Cognitive Load with Oculo- and Bio-metric Indicators](https://zenodo.org/records/14173461) | 33 | Mental calculations (intrinsic load), visual search task (extraneous load) | Eye Tracking, HRV, GSR |  
| [Unobtrusive Measurement of Cognitive Load and Physiological Signals](https://zenodo.org/records/10371068) | 24 | Mental arithmetic, Stroop, N-Back, Sudoku (controlled); research, programming, email (uncontrolled) | EEG, PPG, EDA, Skin Temperature, Accelerometer |  


