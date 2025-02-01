ABET Course Assessment & Student Learning Outcomes Tracker: R Shiny App
1. Overview

This R Shiny application is designed to assist engineering instructors, department chairs, and accreditation coordinators in evaluating Course Learning Objectives (CLOs) and Student Learning Outcomes (SLOs) in accordance with ABET accreditation standards.

The tool provides an interactive and automated approach to tracking student performance and evaluating whether course objectives align with ABET’s requirements.

The web-based app for the American University of Iraq Sulaimani Engineering Program is available at: https://switzner.shinyapps.io/Course_Assessment_Report_App/

The R-code for the app is available here in Zenodo. Please contact the creator with any inquiries. A 6-minute video demonstration about app usage is available at https://drive.google.com/open?id=1v_HjZ_euyEHq5xenNUU5hychK_Pq1tyh&usp=drive_fs

Feel free to download the code and make any adjustments necessary for your institution/program. Please reference this publication as a source. If using this tool for academic or research purposes, please cite as:

Author(s): Nathaniel T Switzner, PhD, PE
Title: ABET Course Assessment & SLO Tracker (R Shiny App)
Version: 1.0
DOI: [Zenodo DOI]
Year: 2025
Key Features

✅ Define and map CLOs to ABET SLOs

✅ Import student grades and calculate performance

✅ Compute CLO and SLO achievement levels on a 0–4 scale

✅ Generate downloadable assessment reports for accreditation

✅ Reset and evaluate multiple courses efficiently

2. System Requirements
Software Requirements
R (Version 4.0 or later)
RStudio (Recommended)
R Shiny Package (install.packages("shiny"))
Dplyr Package (install.packages("dplyr"))
Hardware Requirements
Minimum 4GB RAM (for smooth execution)
At least 200MB of disk space (for data storage and reports)
Internet connection (for downloading R packages and dependencies)
3. Installation & Setup
Step 1: Install R and RStudio

Download and install the latest versions of:

R
RStudio
Step 2: Install Required Packages

Run the following command in RStudio to install the required dependencies:

install.packages(c("shiny", "dplyr"))

Step 3: Download and Run the App
Download the source code from Zenodo or GitHub.
Open the R script (app.R) in RStudio.
Run the app by executing:
shiny::runApp()

The app will open in your default web browser.
4. How to Use the Application

The web-based app for the American University of Iraq Sulaimani Engineering Program is available at: https://switzner.shinyapps.io/Course_Assessment_Report_App/

The R-code for the app is available here in Zenodo. Please contact the creator with any inquiries. A 6-minute video demonstration about app usage is available at https://drive.google.com/open?id=1v_HjZ_euyEHq5xenNUU5hychK_Pq1tyh&usp=drive_fs

Feel free to download the code and make any adjustments necessary for your institution/program. Please reference this publication as a source. If using this tool for academic or research purposes, please cite as:

Author(s): Nathaniel T Switzner, PhD, PE
Title: ABET Course Assessment & SLO Tracker (R Shiny App)
Version: 1.0
DOI: [Zenodo DOI]
Year: 2025
Step 1: Select Course & ABET SLO
Use the "Select Course Code" dropdown to choose the course.
Use the "Select ABET SLO" dropdown to select the learning outcome the course contributes to.
Step 2: Enter Course Learning Objectives (CLOs)
Type the CLO description in the "Enter Course Learning Objective (CLO)" text box.
Click "Add CLO" to save it.
The CLO will now appear in the CLO table.
Step 3: Enter Student Grades
Copy student grades from Excel and paste them into the "Enter Grades Data" box.
Ensure the data is tab-separated (e.g., Assignment1\tAssignment2\t85\t90).
Click "Update Grades Table" to save the grades.
Step 4: Map Assignments to CLOs
Select the CLO and use the dropdown menu to assign relevant assignments.
Click "Update CLO Mapping and Max Scores".
Step 5: Generate Course Assessment Report
The app automatically calculates CLO & SLO scores based on student performance.
Click "Download Report" to export a CSV file for accreditation records.
Step 6: Reset for New Course Assessment
Click "Reset All Data" to clear the current data and evaluate another course.
5. How the App Works
1. CLO-SLO Mapping
CLOs are linked to ABET Student Learning Outcomes (SLOs).
Each CLO is evaluated based on student performance in assignments.
2. Grade Processing
Grades are normalized using maximum possible scores.
Scores are scaled to a 0–4 system for accreditation assessment.
3. Automated Report Generation
The final report includes:
Course Information
CLO-SLO Mappings
Assignment-Level Scores
CLO & SLO Performance Summaries
Instructor Recommendations
6. Benefits for Engineering Departments
For Faculty & Instructors:

✅ Eliminates manual data entry with an interactive interface.
✅ Automates performance evaluation, reducing administrative burden.
✅ Enhances course design by identifying areas needing improvement.

For Accreditation Coordinators:

✅ Provides structured ABET assessment data for reports.
✅ Improves tracking of student learning progress over multiple years.
✅ Streamlines CLO-SLO mapping, ensuring compliance with ABET standards.

For Department Chairs:

✅ Supports data-driven decision-making for curriculum improvements.
✅ Simplifies multi-course evaluation through a centralized tool.
✅ Reduces faculty workload, making accreditation processes more efficient.

7. Troubleshooting & Common Issues
Issue: Grades Table is Not Updating

✔ Ensure the data is tab-separated (\t) before pasting.
✔ Verify that column headers are included in the copied data, and there are no special characters in the headers or blanks in the data.
✔ Restart the app and try again.

Issue: "Max Scores Data is Missing" Error

✔ Ensure each assignment has a max score entered.
✔ Click "Update CLO Mapping and Max Scores" after entering scores.

Issue: Report is Not Downloading

✔ Ensure data has been entered before downloading.
✔ Try restarting the app and reattempting.

8. Citation & Attribution

If using this tool for academic or research purposes, please cite as:

Author(s): Nathaniel T Switzner, PhD, PE
Title: ABET Course Assessment & SLO Tracker (R Shiny App)
Version: 1.0
DOI: [Zenodo DOI]
Year: 2025

9. Future Development & Contribution
Planned Features:
🌟 Improved Data Visualization for SLO trends.
🌟 Multi-Course Comparison Dashboard for department-wide assessments.
🌟 Integration with Learning Management Systems (LMS).
How to Contribute

We welcome contributions via Zenodo. Feel free to:

Submit feature requests
Report bugs
Contribute code enhancements

For inquiries, contact Nathaniel T Switzner PhD, PE via Zenodo.

10. License & Terms of Use

This software is released under the MIT License, meaning:

✅ Free to use and modify
✅ Attribution is appreciated
✅ Not liable for data loss/errors in assessment results

11. Conclusion

This ABET Course Assessment Tracker is a powerful tool for engineering faculty and administrators, providing a structured, automated way to assess student learning outcomes and meet ABET accreditation requirements. By leveraging R Shiny, this tool reduces manual workload, improves accuracy, and facilitates curriculum improvements based on real student data.

🚀 Ready to streamline your ABET assessment process? Download the tool and start tracking CLO-SLO performance today!
