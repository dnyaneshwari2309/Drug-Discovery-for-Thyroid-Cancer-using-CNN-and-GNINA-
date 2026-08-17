# 🚀 GNINA Redocking & Cross-Docking

## 🧬 AI-Based Molecular Docking for Thyroid Cancer Drug Discovery

This project focuses on **AI-assisted molecular docking** to study potential drug-protein interactions for **BRAF inhibitors related to thyroid cancer**.

The project uses **GNINA**, an AI-based molecular docking software, to perform **redocking and cross-docking simulations** and analyze the binding behavior of different ligands with target proteins.

The main goal is to understand ligand-protein interactions, compare docking poses, analyze binding affinities, and explore the potential of computational methods in **drug discovery and cancer research**.

---

# 🎯 Project Objectives

The main objectives of this project are:

✅ Perform molecular **redocking** simulations
✅ Perform **cross-docking** experiments
✅ Analyze ligand-protein binding interactions
✅ Compare predicted binding poses
✅ Evaluate docking scores and binding affinities
✅ Study the interaction behavior of BRAF inhibitors
✅ Explore AI-based approaches for computational drug discovery

---

# 🧠 What is GNINA?

**GNINA** is an open-source molecular docking program that incorporates **deep learning techniques** into the traditional molecular docking workflow.

It can be used to:

* Predict ligand binding poses
* Estimate ligand-protein binding affinity
* Score docking configurations
* Analyze potential drug-target interactions
* Improve docking predictions using machine learning-based scoring

In this project, GNINA is used to investigate the interaction between **BRAF target proteins and inhibitor molecules**.

---

# 🔬 Redocking vs Cross-Docking

### 🔄 Redocking

Redocking involves taking a ligand whose experimentally determined binding pose is already known and docking it back into the same protein binding site.

The purpose is to evaluate how accurately the docking method can reproduce the experimentally observed pose.

### 🔁 Cross-Docking

Cross-docking involves docking ligands into **different protein structures or conformations** rather than only the structure from which the ligand originated.

This helps evaluate how well a docking method performs when the protein structure and ligand combination changes.

---

# 🧪 Project Workflow

The project follows a computational drug-discovery workflow:

### 1️⃣ Protein Preparation

* Obtain the required BRAF protein structures.
* Prepare the protein structures for docking.
* Identify the relevant binding sites.

### 2️⃣ Ligand Preparation

* Collect BRAF inhibitor ligand structures.
* Prepare ligand files for molecular docking.
* Convert structures into compatible formats when required.

### 3️⃣ Redocking

* Dock the experimentally known ligand back into its corresponding protein structure.
* Generate multiple possible binding poses.
* Compare predicted poses with the known binding orientation.

### 4️⃣ Cross-Docking

* Dock different ligands into alternative protein structures.
* Generate and compare docking poses.
* Evaluate how ligand binding changes across protein conformations.

### 5️⃣ AI-Based Docking and Scoring

GNINA generates docking poses and evaluates them using its scoring functions, including deep-learning-based scoring.

### 6️⃣ Result Analysis

* Compare docking scores.
* Analyze binding poses.
* Examine ligand-protein interactions.
* Identify favorable binding configurations.

---

# 🛠️ Technologies & Tools

| **Technology / Tool** | **Purpose**                           |
| --------------------- | ------------------------------------- |
| 🧬 GNINA              | AI-based molecular docking            |
| 🐍 Python             | Data processing and analysis          |
| 🧪 Molecular Docking  | Protein-ligand interaction prediction |
| 🧠 Deep Learning      | AI-based molecular scoring            |
| 📊 Data Analysis      | Comparison of docking results         |
| 🧬 Protein Structures | BRAF target structures                |
| 💊 Ligands            | BRAF inhibitor molecules              |

---

# 📊 Results

The docking experiments were successfully performed using GNINA.

### 🔬 Experimental Outcomes

✅ Successfully performed **redocking simulations**

✅ Successfully performed **cross-docking simulations**

✅ Generated multiple ligand binding poses

✅ Obtained docking scores and binding affinity estimates

✅ Compared ligand-protein interaction patterns

✅ Evaluated the binding behavior of different BRAF inhibitors

The docking results can be used to compare the relative binding behavior of different ligands and identify promising binding configurations.

> **Note:** Docking scores and binding affinities should be interpreted as computational predictions and do not by themselves confirm biological or clinical effectiveness.

---

# 📈 Result Analysis

The generated docking results can be analyzed based on:

### 🔹 Binding Affinity

Docking scores can be compared to identify ligands with relatively favorable predicted binding.

### 🔹 Binding Pose

The predicted ligand orientation inside the protein binding pocket can be examined.

### 🔹 Protein-Ligand Interactions

Important interactions such as:

* Hydrogen bonds
* Hydrophobic interactions
* Van der Waals interactions
* Electrostatic interactions

can be investigated to understand ligand binding behavior.

### 🔹 Redocking Performance

Redocking results can be compared with the experimentally known ligand pose to evaluate docking performance.

### 🔹 Cross-Docking Performance

Cross-docking results can be used to evaluate ligand binding across different protein structures or conformations.

---

# 📂 Project Structure

```text
GNINA-Redocking-Cross-Docking/
│
├── proteins/
│   └── BRAF protein structures
│
├── ligands/
│   └── BRAF inhibitor structures
│
├── docking_results/
│   └── GNINA docking outputs
│
├── scripts/
│   └── Python analysis scripts
│
├── results/
│   └── Result tables and analysis
│
├── README.md
├── requirements.txt
└── .gitignore
```

> Update the folder names above if your actual GitHub repository uses a different structure.

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/dnyaneshwari2309/GNINA-Redocking-Cross-Docking.git
```

## 2️⃣ Open Project Directory

```bash
cd GNINA-Redocking-Cross-Docking
```

## 3️⃣ Install Python Dependencies

```bash
pip install -r requirements.txt
```

Or install commonly required Python packages manually:

```bash
pip install numpy pandas matplotlib
```

## 4️⃣ Install GNINA

Download and configure the appropriate GNINA version for your operating system.

After installation, verify that GNINA is accessible from the command line:

```bash
gnina --help
```

---

# ▶️ Running the Project

A typical GNINA docking workflow can be executed using a command similar to:

```bash
gnina -r protein.pdb -l ligand.sdf --out output.sdf
```

The exact command depends on the protein, ligand, docking box, and parameters used in the experiment.

Python scripts can then be used to process and analyze the generated docking results.

---

# 📦 Requirements

Typical Python dependencies include:

```text
numpy
pandas
matplotlib
```

GNINA must also be installed separately because it is the primary molecular docking tool used in this project.

---

# 🔐 Data & File Management

Large molecular structures and generated docking outputs may not be suitable for direct storage in GitHub.

The `.gitignore` file can be used to exclude:

```text
__pycache__/
*.pyc
venv/
*.sdf
*.pdbqt
*.log
docking_results/
```

Only exclude files that are actually present and appropriate to keep out of the repository.

---

# 🧬 Applications

This project demonstrates potential applications of computational molecular docking in:

🧬 Drug Discovery
💊 Drug-Target Interaction Analysis
🧪 Structure-Based Drug Design
🎗️ Cancer Research
🧠 AI-Assisted Molecular Modeling
🔬 Computational Chemistry

---

# 🚀 Future Enhancements

🔹 Develop a visualization dashboard for docking results

🔹 Automate the complete docking workflow using Python

🔹 Add molecular interaction visualization

🔹 Compare multiple docking/scoring methods

🔹 Perform larger-scale virtual screening

🔹 Integrate additional molecular descriptors

🔹 Apply advanced deep-learning models for binding prediction

🔹 Store and visualize docking results using an interactive dashboard

🔹 Extend the workflow to additional cancer-related protein targets

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

✅ Molecular Docking
✅ Redocking and Cross-Docking
✅ Protein-Ligand Interaction Analysis
✅ GNINA
✅ AI-Assisted Drug Discovery
✅ Python-Based Data Analysis
✅ Computational Chemistry Concepts
✅ Scientific Result Interpretation

---

# 👩‍💻 Author

**Dnyaneshwari Sonawane**

🎓 B.E. Artificial Intelligence & Data Science

🔗 GitHub: `https://github.com/dnyaneshwari2309`

---

# ⭐ Acknowledgment

This project was developed as an exploration of **AI-assisted molecular docking and computational drug discovery**, with a focus on BRAF inhibitors and thyroid cancer-related drug research.
