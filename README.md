 # Parkinson-s-Tremor-Detection-via-Smartphone-IMU
 - Parkinson's Disease (PD):
  - Neurological disease affecting about 1% of the population above 60 years old
  - Symptoms include tremor, rigidity, and bradykinesia
  - Early detection crucial for improving clinical outcomes

** Automated Detection of PD Symptoms: **
  - Utilizes widely available sensors to measure and quantify symptoms
  - Current methods mostly operate under controlled settings, limiting applicability in free-living conditions
  - Proposed method focuses on identifying tremorous episodes using smartphone IMU signals

- Methodology:
  - Multiple-Instance Learning approach used
  - Subject represented as unordered bag of accelerometer signal segments
  - Combines deep feature learning with learnable pooling stage for identifying key instances
  - End-to-end trainable

- Validation:
  - Tested on dataset of 45 subjects with accelerometer signals collected in-the-wild
  - Good classification performance observed in experiments

- Introduction to Parkinson's Disease:
  - Long-term neurodegenerative condition affecting central nervous system
  - Symptomatology includes motor and non-motor symptoms
  - Early diagnosis beneficial for efficient symptom management

- Previous Research:
  - Various methods proposed for automated detection of PD symptoms using sensor data
  - Examples include speech signals analysis, keyboard interaction analysis, and IMU sensors for gait analysis and tremor detection

- i-PROGNOSIS Program:
  - Utilizes sensors in commercial off-the-shelf devices for early Parkinson's diagnosis
  - Collects data unobtrusively and in-the-wild
  - Focuses on detecting PD onset by examining multiple symptoms and their longitudinal evolution

- Focus of the Paper:
  - Automatic detection of PD tremor from IMU data collected in-the-wild
