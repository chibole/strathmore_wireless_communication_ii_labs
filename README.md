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

The lecturer's repository is organised as follows:

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

Students may also generate their own datasets as instructed in individual laboratory exercises.

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

The laboratory is designed to develop students' understanding of traffic engineering principles and their application to cellular network planning.

**Laboratory learning activities**

Students will:

1. Understand basic telecommunications traffic engineering concepts.
2. Calculate call arrival rate and mean call holding time.
3. Calculate traffic volume and traffic intensity in Erlangs.
4. Generate their own simulated telecommunications traffic datasets using Python.
5. Inspect and prepare call-record datasets for engineering analysis.
6. Analyse traffic variation over a 24-hour period.
7. Plot hourly traffic intensity using Matplotlib.
8. Identify busy-hour and low-demand periods.
9. Explain how traffic measurements inform GSM traffic-channel planning.
10. Apply traffic engineering principles to blocking probability and network dimensioning.

**Access the LAB 1 notebook**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chibole/strathmore_wireless_communication_ii_labs/blob/master/notebooks/LAB1_Traffic_Measurement_Analysis.ipynb)

Click the badge above to open the lecturer's LAB 1 notebook directly in Google Colab.

**Current laboratory stage**

The first stage of LAB 1 covers telecommunications traffic engineering fundamentals and the generation of individual simulated telecommunications traffic datasets.

At this stage, students are required to:

1. Access the lecturer's notebook through Google Colab.
2. Create their own copies of the notebook in their personal GitHub repositories.
3. Follow the instructions provided to generate their individual telecommunications traffic datasets.
4. Inspect the generated records.
5. Download and upload their CSV datasets to their personal GitHub repositories.

The current activity concludes with the successful generation and storage of each student's own dataset.

Further activities involving traffic analysis, visualisation, busy-hour identification and GSM capacity planning will be introduced progressively as LAB 1 continues.

**Main resources:**

- Notebook: `notebooks/LAB1_Traffic_Measurement_Analysis.ipynb`
- Dataset reference: `data/traffic_measurements.csv`
- Student setup and GitHub guide: `docs/LAB1_Student_Setup_and_GitHub_Guide.docx`

### Future laboratory exercises

Additional laboratory exercises will be published in this repository as they are introduced during the semester.

These will progressively address traffic engineering, queuing models, network dimensioning, radio resource management and cellular network optimisation.

---

## 4. Software installation and access

Students are encouraged to use Google Colab.

Open:

https://colab.research.google.com/

To access a laboratory notebook:

1. Open the relevant notebook using the link provided in this README or the `notebooks/` directory.
2. Open the notebook using Google Colab.
3. Save your own copy to your personal GitHub repository.
4. Follow the instructions provided in the notebook.
5. Execute the required Python Code cells in sequence.
6. Study the outputs and complete the assigned practical activities.
7. Save your completed notebook and generated files in your personal repository.

Students who prefer to work locally may install Python, Git and Jupyter Notebook. Refer to the software installation guide in the `docs/` directory.

---

## 5. Student GitHub workflow and submissions

The lecturer's repository is the central source of laboratory materials.

Each student must maintain an individual GitHub repository for laboratory work and assessment submissions.

### 5.1 Creating a personal GitHub repository

Each student should:

1. Create a GitHub account if they do not already have one.
2. Sign in to https://github.com/.
3. Create a new repository using their admission number as the repository name.
4. Set the repository visibility to **Private**.
5. Initialise the repository with a README file.

For example, the repository name should follow this format:

`YOUR_ADMISSION_NUMBER`

### 5.2 Working with the lecturer's notebook

For the current LAB 1 activity:

1. Open the lecturer's notebook using the **Open in Colab** badge in Section 3.
2. In Google Colab, select **File → Save a copy in GitHub**.
3. Select your personal GitHub repository.
4. Save the notebook using the following path:

   `notebooks/LAB1_Traffic_Measurement_Analysis.ipynb`

5. Follow the laboratory instructions and complete the required activities.
6. Download your generated CSV dataset.
7. Upload the dataset to the `data/` folder in your personal repository.

You do not need to fork the lecturer's repository. You should work using your own copy of the notebook.

### 5.3 Saving and updating your work

Students should ensure that their work is saved in their personal GitHub repositories.

GitHub uses version control to keep track of changes.

The following terms are important:

- **Repository:** An online project folder where you store your work.
- **Commit:** A saved version of your changes, accompanied by a short description.
- **Push:** Sending committed changes from a local computer to GitHub.
- **Fork:** Creating a copy of another person's repository under your GitHub account. Forking is not required for the current laboratory workflow.
- **Clone:** Downloading a GitHub repository to your computer.

For the current LAB 1 activity, students can use the GitHub website and Google Colab without installing Git or using command-line instructions.

**Important:** Executing a notebook cell does not automatically save the updated notebook to GitHub. Ensure that changes made after creating your initial copy are saved to your personal repository.

---

## 6. Laboratory submission requirements

Unless otherwise specified in an individual laboratory handout, submissions should include:

- Completed Jupyter notebook (`.ipynb`).
- Relevant datasets or generated results.
- Graphs and visualisations.
- Laboratory report explaining the methodology, calculations and findings.
- Engineering interpretation and conclusions.
- Personal GitHub repository link.

For the current stage of LAB 1, the required submission consists of:

1. Your personal GitHub repository link.
2. Your notebook: `LAB1_Traffic_Measurement_Analysis.ipynb`.
3. Your generated dataset: `traffic_measurements.csv`.

The notebook and dataset should be available in your personal repository.

Further submission requirements will be communicated as the laboratory activities progress.

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

Where individual datasets are required, students must generate their own datasets using the instructions provided. Students should not submit another student's dataset as their own.

---

## 8. Repository maintenance

This repository is maintained by the course lecturer and will be updated as laboratory exercises and supporting resources are introduced.

Students should periodically check the repository for new laboratory materials and instructions.

The laboratory notebooks may be expanded or updated as the course progresses. Students should therefore check for the latest instructions before beginning a new laboratory activity.

---

**Course:** BEE 5224 – Wireless Communications II  
**Institution:** Strathmore University  
**Department:** Electrical and Electronic Engineering  
**Repository:** `strathmore_wireless_communication_ii_labs`

**End of README**
