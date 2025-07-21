CGPA Calculator
Overview
The CGPA Calculator is a web-based application designed to help students calculate their Grade Point Average (GPA) for individual semesters and Cumulative Grade Point Average (CGPA) across multiple semesters. Built using HTML, CSS, and JavaScript, it provides a user-friendly interface for tracking academic performance efficiently. This project is ideal for students at universities like UET Lahore (Narowal Campus) to monitor their grades and plan their academic journey.
Features

GPA Calculation: Calculate the GPA for a single semester based on grades and credit hours.
CGPA Calculation: Compute the cumulative CGPA across multiple semesters (up to 8 semesters).
Responsive Design: Works seamlessly on both desktop and mobile devices.
Grade System: Supports a standard grading scale (A+ to F) with corresponding grade points (e.g., A+ = 4.0, A = 4.0, B+ = 3.5, etc.).
User-Friendly Interface: Clean and intuitive design with input fields for subjects, grades, and credits.
Local Storage: Saves semester data and student information for persistence across sessions.

Technologies Used

HTML: For structuring the web page.
CSS: For styling and responsive design, using a pastel-themed aesthetic.
JavaScript: For dynamic calculations and local storage functionality.
Chart.js: For visualizing semester-wise GPA trends (optional feature).
Font Awesome: For icons to enhance the UI.

Installation
To run the CGPA Calculator locally, follow these steps:

Clone or Download the Repository:
git clone https://github.com/sairabatool/cgpa-calculator.git

Alternatively, download the project as a ZIP file and extract it.

Navigate to the Project Directory:
cd cgpa-calculator


Run the Application:

Open index.html in a web browser (e.g., Chrome, Firefox) by double-clicking the file or using a local server.
To run with a local server (recommended for proper functionality):python -m http.server 8000

Then, access the application at http://localhost:8000 in your browser.


Dependencies:

Ensure an internet connection to load external libraries (e.g., Chart.js, Font Awesome) via CDN.
No additional installations are required as all dependencies are linked via CDN in the HTML file.



Usage

Open the Application:

Launch the CGPA Calculator in your web browser.


Enter Semester Details:

Select a semester (1 to 8) from the dropdown.
Input the number of subjects, grades (A+, A, B+, etc.), and credit hours for each subject.
Click "Calculate GPA" to view the semester GPA.


Calculate CGPA:

After adding data for multiple semesters, click "Calculate CGPA" to see the cumulative CGPA.
The CGPA is calculated using the formula:CGPA = (Sum of (Grade Points * Credit Hours) for all semesters) / (Total Credit Hours)




View Results:

Results are displayed in a table format, showing each semester's GPA and the overall CGPA.
Data is saved in local storage, so it persists when you revisit the page.


Optional Features:

View a graphical representation of GPA trends across semesters (if Chart.js is integrated).
Clear saved data via a "Reset" button to start fresh.



Project Structure
cgpa-calculator/
├── index.html        # Main HTML file for the application
├── styles.css        # CSS file for styling
├── script.js         # JavaScript file for calculations and logic
├── images/           # Folder for assets (e.g., screenshots)
└── README.md         # This file

Screenshots
(Add screenshots of the application interface here, e.g., images/screenshot.png)
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch: git checkout -b feature/your-feature-name.
Make your changes and commit: git commit -m "Add your feature description".
Push to your branch: git push origin feature/your-feature-name.
Submit a pull request on GitHub.

Please follow the contributing guidelines for more details.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For any queries or suggestions, reach out to:


Email: batoolsaira@gmail.com
GitHub: Saira-Batool123


Created by Saira Batool, UET Lahore (Narowal Campus), 2025
