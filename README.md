# MLOps – Data Versioning using DVC

This project demonstrates **data versioning in MLOps** using **DVC (Data Version Control)** along with Git.  
It shows how multiple versions of data can be tracked efficiently without storing large files directly in Git.

---

## 📌 Objective
- Understand and implement **data versioning**
- Track multiple versions of datasets using **DVC**
- Maintain clean Git history while handling large data files

---

## 🛠 Tools & Technologies
- Python
- Git & GitHub
- DVC (Data Version Control)
- AWS S3 (for remote storage)

---

## 📂 Project Structure
MLOPS-DVC-Dataversion/
│── .dvc/ # DVC metadata
│── S3/files/md5/ # DVC cached files
│── .gitignore
│── .dvcignore
│── datadvc # Versioned dataset
│── mycode.py # Sample code
│── projectflow.txt # Project workflow explanation
│── README.md


---

## 🔄 Data Versioning Workflow
1. Initialize Git and DVC
2. Add dataset using DVC
3. Track dataset versions without pushing raw data to Git
4. Store data remotely using AWS S3
5. Switch between data versions easily using Git commits

---

## 🚀 Key Learnings
- Difference between **code versioning** and **data versioning**
- How DVC helps in scalable ML pipelines
- Best practices for MLOps data management

---

## 📎 Use Case
This setup is useful for:
- Machine Learning pipelines
- Experiments with multiple dataset versions
- Team-based ML projects

---

## 👩‍💻 Author
**Shubhi Singh**  
BTech CSE (AI) | ML • NLP • MLOps Enthusiast
