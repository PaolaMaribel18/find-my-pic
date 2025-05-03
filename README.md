# 🔍 FindMyPic: Image-Based Information Retrieval System

## 📌 Introduction

The goal of this project is to design and develop **FindMyPic**, an image retrieval system that allows users to make queries using images instead of text. This system is built to find similar images within a given database. The project is divided into several phases, described below.

---

## 🧩 Project Phases

### 1. 📥 Data Acquisition  
- **Goal:** Obtain and prepare the Caltech101 dataset.  
- **Tasks:** Download, unzip, and organize the dataset.

### 2. 🧼 Preprocessing  
- **Goal:** Prepare the images for analysis.  
- **Tasks:** Normalize, resize, and denoise the images; document the process.

### 3. 🧠 Feature Extraction  
- **Goal:** Extract meaningful features from the images.  
- **Tasks:** Use a CNN to extract features, apply transfer learning or train a model, and document methods and results.

### 4. 🗂️ Indexing  
- **Goal:** Build an index for efficient searches.  
- **Tasks:** Develop an indexing system using techniques like k-NN, KD-Trees, or LSH; document the process.

### 5. 🔎 Search Engine Design  
- **Goal:** Implement the search functionality.  
- **Tasks:** Develop query logic, ranking algorithm, and document the system architecture and algorithms.

### 6. 📊 System Evaluation  
- **Goal:** Measure the system’s effectiveness.  
- **Tasks:** Define evaluation metrics, set benchmarks, compare configurations, and document results.

### 7. 🌐 Web User Interface  
- **Goal:** Create a user-friendly interface.  
- **Tasks:** Design a web interface to upload images and display results, ensure intuitive UX, and document the design.

---

## 🧪 Virtual Environment

To ensure consistency in the development environment, a virtual environment has been set up. Activate it before working on the project:

```bash
# Activate the virtual environment
source .venv/bin/activate
```
## 📦 Installing Dependencies
All necessary dependencies are listed in the requirements.txt file. Install them with the following command:
```bash
pip install -r requirements.txt
```

