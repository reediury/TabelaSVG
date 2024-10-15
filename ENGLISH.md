📊 SVG table in Power BI
=

This repository contains an example of an SVG table visualization, developed using DAX and SVG. The visual displays information about employees, such as name, status, position, hire date, and performance score, along with a dynamic progress bar representing the employee's performance.

👤 Author
=

Name: Reed Iury

LinkedIn: linkedin.com/in/reediury

📦 Files
=

tabela_svg.pbix: Example Power BI report with the employee status visualization.
README.md: This documentation file.

🚀 Usage Instructions
=

To use this visual in Power BI, you can incorporate the provided DAX code into a card or table that supports SVG rendering. The code generates a dynamic SVG that displays engaging information about employee statuses.

Example File:
=

The tabela_svg.pbix file contains a complete example with the applied code.

Code Explanation:
= 
The code is structured to generate an SVG visualization that shows:

Employee Status:

The status is determined by the [Status] column, where 1 represents "Active" and 0 represents "Inactive."
Colors are assigned based on the status, using green (#4CAF50) for "Active" and orange (#FF9800) for "Inactive."

Employee Information:

The employee's name is displayed in bold text.
The employee's position and hire date are presented below the name, formatting the date as "dd/MM/yyyy."

Performance:

The performance score is obtained from the [PerformanceScore] column, which ranges from 0 to 100.
The performance bar changes color based on the score:
Green (#4CAF50) for scores ≥ 80.
Yellow (#FFC107) for scores between 50 and 79.
Red (#F44336) for scores < 50.

Animations:

The progress bar is animated to grow from 0 to the performance score over 2 seconds, creating a dynamic visualization.
The percentage text inside the bar changes color during the animation, highlighting the performance.

Key Variables:
=

Status: Column indicating whether the employee is "Active" or "Inactive."
Position: Employee's position.
HireDate: Employee's hire date.
PerformanceScore: Employee's performance score, ranging from 0 to 100.

Key Functions:
=

SVG Animation: Generates a dynamic SVG that displays the employee's name, status, position, hire date, and performance score with visual animations.
Dynamic Colors: The colors of the progress bar and status change dynamically based on defined conditions (active/inactive and performance score).

🛠 How to Customize
=

Modify the colors and styles of the animations in the SVG to suit your preferences.
Adjust the logic to integrate additional metrics or information about the employees as needed.
To test and visualize, you can adjust the example data in Power BI.

🌟 Visual Demonstration
=

https://github.com/user-attachments/assets/ebec55d2-7f26-48ad-bb52-8a794b775654


If you have any questions or suggestions, feel free to contact me on LinkedIn.
