# excel-logical-formulas
this repository contains examples of Excel logical functions like IF, AND, OR, and nested logical formulas.
# Excel Logical Functions Project (HR & Sales Data Analysis)
<img width="1844" height="570" alt="Conditional-upload-field" src="https://github.com/user-attachments/assets/39e05ff3-8f4f-453e-a056-fcc0d0fc710c" />

This repository contains an Excel-based data analysis project that demonstrates the practical application of logical functions (IF, AND, OR) and their combinations to solve real-world HR and Sales business problems.

## 📊 Business Logic & Conditions Applied

### 1. IF Function Logic
* *Target Achievement:* If Sales ≥ 100,000 → "Achieved", else "Not Achieved".
* *Attendance Status:* If Attendance ≥ 90% → "Regular", else "Irregular".
* *Experience Classification:* If Experience ≥ 5 years → "Senior", else "Junior".
* *Star Performer:* If Sales ≥ 150,000 → "Star Performer", else "Normal".
* *Team Allocation:* If Department is Sales → "Revenue Team", else "Support Team".

### 2. AND Function Logic (All conditions must be met)
* *Bonus Eligibility:* Sales ≥ 100,000 AND Attendance ≥ 90% → "Bonus Eligible".
* *Promotion Eligibility:* Experience ≥ 5 years AND Target Achieved = Yes → "Promotion Eligible".
* *Top Performer:* Sales ≥ 150,000 AND Attendance ≥ 95% → "Top Performer".
* *Best Salesperson:* Department = Sales AND Target Achieved = Yes → "Best Salesperson".
* *Reliable Employee:* Attendance ≥ 90% AND Experience ≥ 3 years → "Reliable Employee".

### 3. OR Function Logic (At least one condition must be met)
* *High Value:* Sales ≥ 150,000 OR Attendance ≥ 95% → "High Value".
* *Potential Leader:* Experience ≥ 5 years OR Target Achieved = Yes → "Potential Leader".
* *Back Office:* Department = HR OR Finance → "Back Office".
* *Needs Attention:* Attendance < 85% OR Target Achieved = No → "Needs Attention".
* *Special Review:* Sales < 120,000 OR Experience > 5 years → "Special Review".

### 4. Combined Logic (IF + AND + OR Advanced)
* *Excellent Rating:* Sales ≥ 100,000 AND (Attendance ≥ 90% OR Experience ≥ 5) → "Excellent".
* *Sales Champion:* Department = Sales AND Sales ≥ 150,000 AND Target Achieved = Yes → "Sales Champion".
* *Admin Excellence:* (Department = HR OR Finance) AND Attendance ≥ 90% → "Admin Excellence".
* *Gold Employee:* Sales ≥ 100,000 AND Attendance ≥ 90% AND Experience ≥ 3 → "Gold Employee".
* *Future Manager:* Target Achieved = Yes AND (Sales ≥ 120,000 OR Experience ≥ 5) → "Future Manager".
*
