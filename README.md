# SmartReg: Empowering Education in Low-Resource Environments 🎓

## 📌 Project Overview

**SmartReg** is a terminal-based academic management system designed to bridge educational inequality and digital access gaps among Software Engineering students in Africa, particularly in remote and underserved areas. Built to function fully offline, SmartReg allows students to:

- ✅ Register for courses  
- 📊 Track and manage grades  
- 🧠 Take quizzes for academic improvement  
- 📑 Receive personalized recommendations  

The system runs entirely on the command line and is optimized for low-end devices with limited or no internet connectivity.

---

## 🚀 Key Features

- **🎓 Student Registration & Grade Input**  
  Register students and input grades for two core courses. If a grade is below 70, SmartReg initiates a short quiz to assess and improve understanding.

- **📋 View All Students**  
  Displays all registered students with their grades and AI-generated performance clusters:
  - Advanced  
  - Intermediate  
  - Needs Support  

- **📄 PDF Report Generation**  
  Export personalized reports including grades, quiz scores, and learning recommendations.

- **📚 Course Recommendations**  
  Based on performance, SmartReg advises students to either revisit foundation topics or proceed to advanced modules.

- **🛜 Fully Offline Mode**  
  All functionalities work offline with data stored locally in a MySQL database.

- **🖥️ Lightweight CLI Interface**  
  Simple numeric input system with text-based menu navigation for ease of use on low-spec terminals.


-**How to use**
```
python3 -m venv path/to/venv
    source path/to/venv/bin/activate

python3 main.py
```
---

## 🛠️ Technologies Used

- Python  
- MySQL  
- PDF Generation (via open-source libraries)  
- K-Means Clustering for student performance analysis  
- GitHub for version control and collaboration  

---

## 🧪 Prototype Description

Upon launch, users are guided through a series of text-based options via a CLI menu:


2. **Auto-Trigger Quiz for Low Scores (<70%)**  
3. **View All Registered Students**  
4. **Export Personalized Reports**  
5. **Receive AI-Driven Learning Recommendations**

---

## 🎯 Challenges Faced

- **Limited Experience with Database Optimization**  
  Resolved via peer learning and task segmentation.

- **Offline MySQL Configuration Issues**  
  Addressed by setting up a unified testing environment and deployment scripts.

- **Time Constraints**  
  Managed using weekly milestones, GitHub issue tracking, and role delegation.

---

## ✅ Conclusion

SmartReg provides a robust, offline-first solution for managing academic data in low-resource environments. It simplifies course registration, enables progress tracking, and promotes continuous learning—all accessible without internet connectivity. SmartReg directly supports digital equity and contributes to leveling the academic playing field for students across Africa.

---

## 👥 Team Contributions

| Group Member                | Sessions Attended | Git Contributions | Key Responsibilities                          |
|----------------------------|-------------------|-------------------|-----------------------------------------------|
| Wisdom Okechukwu Ikechukwu| Present           | 3                 | Database Connection, Main Scripting, Readme           |
| Orla Lennie Ishimwe        | Present           | 2                 | Student Management, Main Scripting            |
| Nsenga Willy               | Present           | 1                 | Registration Services, Main Scripting         |
| Cyuzuzo Germain            | Present           | 1                 | Database Design, Main Scripting               |
| Divin Munezero Bonheur     | Present           | 1                 | Registration Management, Main Scripting       |
| Nawaf Ahmed                | Present           | 1                 | Course Scripting, Main Scripting              |

---

## 📂 Repository & Resources

- 🔗 [GitHub Repository](https://github.com/owizdom/Group11-SmartReg_PLP-2)  
- 🖥️ [Presentation Slides](https://docs.google.com/presentation/d/1YmLb1bi5A-3GoqgsScc3w-6b10C1WzsVG9x4WPO1Rag/edit?usp=sharing)

---

## 💬 License & Contact

This project is developed for educational purposes.  
For inquiries or collaborations, please contact any of the group members via the GitHub repository.

---
