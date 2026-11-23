# BEE 5224 – Wireless Communications II Laboratory Repository

**Strathmore University**  
**Department of Electrical and Electronic Engineering**

Welcome to the official laboratory repository for **BEE 5224 – Wireless Communications II**.

This repository contains laboratory exercises, simulated telecommunications datasets, Python programming notebooks, practical instructions and supporting learning resources for students undertaking Wireless Communications II.

The laboratory activities are designed to develop practical engineering skills in telecommunications traffic analysis, cellular network capacity planning, radio frequency optimisation and the performance analysis of wireless communication systems.

---

## 1. Course laboratory approach

The laboratory exercises complement the theoretical material covered during lectures.

Students will use Python-based engineering tools to analyse telecommunications systems, perform numerical calculations, interpret measured or simulated data, and communicate engineering findings.

The main software tools are:

- Python 3
- Jupyter Notebook
- Google Colab
- pandas
- NumPy
- Matplotlib
- Git and GitHub

**Google Colab is the recommended environment** because it allows students to execute Python notebooks through a web browser without requiring a full local software installation.

Python is used as an engineering analysis tool. The emphasis is on understanding telecommunications concepts and interpreting engineering results rather than learning software programming as an independent subject.

---

## 2. Repository organisation

The repository is organised as follows:

```text
strathmore_wireless_communication_ii_labs/
│
├── README.md
│
├── data/
│   └── traffic_measurements.csv
│
├── notebooks/
│   └── LAB1_Traffic_Measurement_Analysis.ipynb
│
├── docs/
│   ├── LAB1_Student_Setup_and_GitHub_Guide.docx
│   └── LAB1_Lecturer_Implementation_Notes.docx
│
├── requirements.txt
│
└── .gitignore
```

### data/

Contains datasets used in the laboratory exercises.

The datasets may be simulated or lecturer-provided datasets. Each dataset should be accompanied by an explanation of its fields, units and intended use.

### notebooks/

Contains Jupyter notebooks used for calculations, analysis, visualisation and interpretation.

Students should execute the notebooks, understand the calculations and complete the assigned practical activities.

### docs/

Contains laboratory handouts, software installation instructions, supplementary reading materials and other supporting documents.

---

## 3. Laboratory exercises

The repository will be expanded progressively as the course advances.

### LAB 1 – Telecommunications Traffic Measurement and Analysis

**Week 3**

This laboratory introduces telecommunications traffic measurement and the interpretation of call activity in cellular networks.

Students will:

1. Inspect and prepare a simulated call-record dataset.
2. Calculate call arrival rate and mean call holding time.
3. Calculate traffic volume and traffic intensity in Erlangs.
4. Analyse traffic variation over a 24-hour period.
5. Plot hourly traffic intensity using Matplotlib.
6. Identify busy-hour and low-demand periods.
7. Explain how traffic measurements inform GSM traffic-channel planning.

The laboratory provides the foundation for subsequent work on blocking probability and network dimensioning.

**Main resources:**

- Dataset: `data/traffic_measurements.csv`
- Notebook: `notebooks/LAB1_Traffic_Measurement_Analysis.ipynb`
- Student guide: `docs/LAB1_Student_Setup_and_GitHub_Guide.docx`

### Future laboratory exercises

Additional laboratory exercises will be published in this repository as they are introduced during the semester.

These will progressively address traffic engineering, queuing models, network dimensioning, radio resource management and cellular network optimisation.

---

## 4. Software installation and access

Students are encouraged to use Google Colab.

Open:

https://colab.research.google.com/

To access a laboratory notebook:

1. Open the relevant notebook in the `notebooks/` directory.
2. Download the notebook or open it through Google Colab using the GitHub option.
3. Upload the associated dataset from the `data/` directory when required.
4. Execute the notebook cells in sequence.
5. Study the outputs, graphs and calculations.
6. Complete the questions and practical activities.

Students who prefer to work locally may install Python, Git and Jupyter Notebook. Refer to the software installation guide in the `docs/` directory.

---

## 5. Student GitHub workflow and submissions

The lecturer's repository is the central source of laboratory materials. Students should maintain their own repositories for laboratory work and assessment submissions.

Each student should create a separate private GitHub repository using the admission number as the repository name, following the lecturer's instructions.

The recommended workflow is:

1. Obtain the laboratory materials from the lecturer's repository.
2. Create or update the student's private repository.
3. Clone the laboratory materials to the student's working environment.
4. Complete the assigned notebook and practical activities.
5. Save the completed notebook, generated datasets, graphs and laboratory report.
6. Commit and push the completed work to the student's private repository.
7. Submit the private repository URL as instructed by the lecturer.

Students should not push their completed work directly into the lecturer's original repository.

Where instructed, students will generate individual simulated datasets using a reproducible random seed derived from their admission numbers. This will enable each student to analyse a distinct dataset while following the same laboratory procedure.

---

## 6. Laboratory submission requirements

Unless otherwise specified in an individual laboratory handout, submissions should include:

- Completed Jupyter notebook (`.ipynb`).
- Relevant datasets or generated results.
- Graphs and visualisations.
- Laboratory report explaining the methodology, calculations and findings.
- Engineering interpretation and conclusions.
- GitHub repository link.

Students should ensure that their notebooks can be executed and that their calculations are clearly explained.

---

## 7. Academic integrity and responsible data use

All students are expected to:

- Complete their own analysis and explain their results.
- Acknowledge external references and resources.
- Avoid presenting simulated data as real operator measurements.
- Avoid uploading confidential, personal or subscriber information.
- Never commit passwords, API keys or GitHub access tokens.
- Maintain appropriate version control of their work.

Sharing laboratory instructions and discussing concepts is encouraged. However, submitted calculations, interpretations and reports must reflect each student's own understanding and work.

---

## 8. Repository maintenance

This repository is maintained by the course lecturer and will be updated as laboratory exercises and supporting resources are introduced.

Students should periodically check the repository for new laboratory materials and instructions.

**Course:** BEE 5224 – Wireless Communications II  
**Institution:** Strathmore University  
**Repository:** `strathmore_wireless_communication_ii_labs`

**End of README**
