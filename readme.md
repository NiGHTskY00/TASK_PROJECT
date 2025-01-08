# Training Program Analytics Dashboard

## Project Overview
A 4-month digital literacy, AI, and robotics training program for students in grades 6–12 required an end-to-end data management system. This project delivers a scalable, automated solution to track attendance, material usage, performance, and teaching effectiveness, empowering stakeholders with actionable insights via interactive Power BI dashboards.

## Key Features

### 1. **Streamlined Data Processing**
- Automated file monitoring using Python's Watchdog library for seamless updates.
- Robust data cleaning routines:
  - Removed duplicates and standardized missing values (e.g., 'Unknown', 'Absent').
  - Ensured consistent data formats, including datetime conversions.
  - Resolved data inconsistencies efficiently.

### 2. **Comprehensive SQL Database Design**
- **Core Tables**:
  - **Students**: Name, grade, gender, and contact details.
  - **Trainers**: Expertise and assigned grades.
  - **Subjects**: Topics taught in the program.
  - **Attendance**: Daily records tied to students and trainers.
  - **Performance**: Weekly scores and feedback metrics.
  - **Material Usage**: Insights into resource consumption.
  - **Method Effectiveness**: KPIs like engagement scores and feedback ratings.

!![Database Design](database/Design%20of%20database.png)

### 3. **Dynamic Dashboards**
- Real-time visualizations for:
  - Attendance trends.
  - Trainer and student performance.
  - Material usage metrics.
  - Effectiveness of teaching methods.
- Designed using Power BI for interactivity and clarity.

![Dashboard Preview](dashboard deploy/TP_dashboard(beta).png)

### 4. **Seamless Deployment**
- Dashboards hosted on [Netlify](#) for easy remote access (replace with actual link).

## Tools and Workflow
- **Programming**: Python (Watchdog, Pandas for automation and analysis).
- **Database**: PostgreSQL (relational database design and management).
- **Visualization**: Power BI (interactive dashboards).
- **Deployment**: Netlify (real-time dashboard hosting).

### Workflow Steps
1. Collect data via Excel files.
2. Automate ingestion and cleaning with Python.
3. Store data in a structured SQL database.
4. Visualize insights with Power BI dashboards.
5. Deploy dashboards for stakeholders to access in real time.

## Outcomes
- Built a fully functional and automated data management system.
- Delivered interactive dashboards enabling real-time insights.
- Enhanced decision-making through detailed analytics and visualizations.

## Future Roadmap
- Improve Python error handling for dynamic data validation.
- Scale the system for larger datasets and diverse data sources.
- Introduce predictive analytics with machine learning models.
- Optimize dashboard performance and interactivity.

## Get Started
1. Clone this repository.
2. Set up the SQL database using the provided schema.
3. Configure Python scripts for automated data updates.
4. Connect Power BI to the database using the template file.
5. Deploy the dashboard on your preferred platform.

## Contact
For questions or suggestions, feel free to reach out:
- **Name**: Rushi Birewar
- **Email**birewarrushi0@gmail.com

---
Explore, contribute, and provide feedback to help refine the project!


