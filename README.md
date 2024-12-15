# HTI Course Project: Cognitive Load and Recovery Interventions

## **Overview**
This project investigates how cognitive load influences stress and performance during problem-solving tasks and evaluates the effectiveness of two recovery interventions: **Tetris (Treatment)** and **Social Media Scrolling (Control)**. The study measures heart rate (HR) trends and accuracy in logical and mathematical tasks before and after the interventions.

The data was collected using a **wearable device** that monitored heart rate variability (HRV) and other related metrics during the experiment. A representative dataset has been included in the project as a sample for the three experimental cases: **Pre-Break**, **Post-Break Control**, and **Post-Break Treatment**. The original data remains confidential and is retained by the team for ethical reasons. This project is conducted as part of the **Human Technology Interaction (HTI)** course.

---

## **Folder Structure**
```
Project/
├── Pre/                       # Files containing pre-break data
├── Post/                      # Files containing post-break data
│   ├── Control/               # Data for post-break control group
│   └── Treatment/             # Data for post-break treatment group
├── Scripts/                   # Python scripts for data processing and analysis
│   ├── random_data_analysis.py   # Simulates data and outputs expected results
│   ├── original_data_analysis.py # Uses original experimental data
├── Outputs/                   # Generated outputs (e.g., tables, plots)
├── README.md                  # Documentation for the project
```

---

## **Steps to Run the Project**

### **1. Random Data Simulation**
The `random_data_analysis.py` script generates random data to simulate the experimental setup and outputs the expected results. This ensures the analysis logic is correct and provides reproducible outputs.

#### **Steps:**
1. Navigate to the `Scripts/` directory.
2. Run the script:
   ```bash
   python random_data_analysis.py
   ```
3. Outputs such as HR trends, accuracy tables, and comparisons will be saved in the `Outputs/` folder.

### **2. Original Data Analysis**
The `original_data_analysis.py` script uses the actual experimental data from the `Pre/`, `Post/Control/`, and `Post/Treatment/` folders.

#### **Steps:**
1. Ensure all necessary data files are correctly placed in their respective folders.
2. Navigate to the `Scripts/` directory.
3. Run the script:
   ```bash
   python original_data_analysis.py
   ```
4. Outputs such as HR trends, accuracy tables, and comparisons will be saved in the `Outputs/` folder.

---

## **Tasks and Features**
### **1. HR Trend Analysis**
- Tracks HR trends during:
  - Pre-Break tasks (Logical & Math).
  - Post-Break interventions (Control: Social Media, Treatment: Tetris).
- Visualizes HR trends over time with clear demarcations for task phases.

### **2. Accuracy Comparison**
- Compares logical and mathematical task scores:
  - Pre-Break vs. Post-Break.
  - Boys vs. Girls.
  - Control vs. Treatment groups.

### **3. Statistical Analysis**
- Calculates:
  - Average HR and variability.
  - Average task accuracy.
  - Differences in performance metrics across groups.

### **4. Visualization**
- Generates bar plots, line graphs, and tables to present results.
- Uses **random data** for testing and **original data** for final outputs.

---

## **Key Metrics Evaluated**
1. **Heart Rate (HR):**
   - Measures cognitive load and recovery effectiveness.
2. **Task Accuracy:**
   - Evaluates performance changes in Logical and Math tasks.
3. **Boys vs. Girls Analysis:**
   - Explores gender differences in HR trends and task accuracy.
4. **Intervention Impact:**
   - Assesses how Tetris and Social Media scrolling influence stress and performance.

---

## **Ethical Considerations**
1. All data is anonymized to protect participants' privacy.
2. Participants provided informed consent for data collection.
3. HR and performance data were monitored in compliance with ethical research guidelines.

---

## **Contact Information**
For any questions regarding this project, please contact:
- **Team Name**: Cognitive Recovery Explorers
- **Email**: cognitive.study@research.edu
- **Course**: HTI Cognitive Load Studies

