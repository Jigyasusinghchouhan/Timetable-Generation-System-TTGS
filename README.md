# Timetable Generation System (TTGS)

## School of Computer Science, MITWPU
### Academic Year 2023-24
### MCA Sem III
### Mini Project on Open-Source Development

**Project Team Member:**
- Name: Jigyasu Singh Chouhan
- Roll No: 39
- Class: SYMCA
- Batch: 2022-2024
- Email: SINGHJIGYASU53@GMAIL.COM

## Configuration Setup
<b>Project Configuration Guidelines(Step by Step):</b>

To run this project on your local server, follow the following steps:
* Install Python 3.8 on your Computer from the official website.
* Install Django on your computer by running this command 
                      
                      pip install Django(For windows)  

* Install Django Crispy Forms by running this command:

                      pip install django-crispy-forms
* Install Django Multi select fields on your computer:

                      pip install django-multiselectfield
* If you don’t have Git Bash/Git Bucket on your computer. Then install it first.
* Run this command on your git terminal

                      git clone “https://github.com/mHuzefa/TimetableGeneratorApp.git”
* After clonning the repository in your computer, run the command:

                      cd TimetableGeneratorApp
* Run this command to run server on your localhost:8000

                       python manage.py runserver
- App is running on your Computer now. Enjoy!!!

**Project Overview / Background:**

The Timetable Generation System (TTGS) is a comprehensive web application developed to address the complex scheduling needs of educational institutions, such as colleges and universities. This project was undertaken to streamline and optimize the process of creating timetables, which is a critical aspect of academic management.

**Need of Work / Reason for Selection of this Project:**

The selection of the Timetable Generation System (TTGS) project was driven by several key factors:

- **Manual Timetable Creation is Time-Consuming:** Traditional methods of manually creating timetables are labor-intensive, error-prone, and time-consuming. This project aims to automate and expedite this process.

- **Complex Constraints:** Academic timetables are subject to numerous constraints, both hard and soft, such as unique class timings, classroom capacities, teacher availability, and departmental requirements. Handling these constraints manually is challenging, and automation can significantly reduce scheduling conflicts.

- **Resource Optimization:** Efficiently allocating resources like classrooms, teachers, and students is essential for the smooth functioning of educational institutions. TTGS uses optimization techniques to achieve this.

- **Real-World Application:** Timetable generation is a practical problem faced by educational institutions worldwide. By creating a solution for this common issue, TTGS has practical applicability and potential benefits for a broad user base.

**Problem Statement:**

Efficiently and automatically generate conflict-free academic timetables for educational institutions while considering hard and soft constraints, optimizing the allocation of teachers, classrooms, and courses, and simplifying the scheduling process.

**Benefits to the surrounding/society:**

The Timetable Generation System (TTGS) offers several benefits to both the immediate educational environment and society at large:

- **Improved Academic Experience:** Optimized timetables ensure that students and teachers can engage in productive and organized learning and teaching experiences, enhancing the overall quality of education.

- **Resource Optimization:** TTGS maximizes the utilization of available resources, including classrooms and teacher schedules, leading to cost savings for educational institutions.

- **Time Savings:** By automating the timetable generation process, TTGS saves administrators and staff valuable time that can be redirected towards other essential tasks.

- **Reduced Conflicts:** The genetic algorithm used by TTGS minimizes conflicts, such as overlapping class schedules, reducing stress and frustration for both teachers and students.

- **Enhanced Efficiency:** Educational institutions can operate more efficiently with well-designed timetables, resulting in improved productivity and student satisfaction.

- **Data-Driven Decision-Making:** TTGS generates timetables based on data and constraints, enabling educational institutions to make informed decisions about resource allocation.

- **Scalability:** The system can accommodate the needs of various educational institutions, from small schools to large universities, making it accessible to a wide range of stakeholders.

**Proposed Techniques or methods to be implemented:**

- **Genetic Algorithm (GA):** TTGS uses Genetic Algorithm, a powerful optimization method, to create timetables by evaluating the quality of timetables based on constraints and objectives.

- **SQLite Database:** For data storage and retrieval, TTGS employs SQLite, a lightweight and efficient database solution.

- **Web Development (Django):** Django, a high-level Python web framework, is used to create the web application's user interface and backend, ensuring security and scalability.

**Advantages:**

- **Efficiency:** TTGS automates the timetable generation process, saving significant time and effort compared to manual scheduling.

- **Optimization:** The genetic algorithm optimizes timetables, minimizing conflicts and maximizing resource utilization.

- **User-Friendly:** The web-based interface makes it easy for administrators to input data, monitor progress, and download timetables.

- **Flexibility:** TTGS can accommodate various educational institutions, from schools to universities, with different scheduling needs.

- **Resource Utilization:** By optimizing room and teacher allocations, TTGS helps institutions make the most of their resources.

- **Conflict Resolution:** The system efficiently handles constraints and minimizes conflicts, leading to fewer scheduling disputes.

**Limitations:**

- **Dependency on Input Data Quality:** The quality and accuracy of input data significantly impact the effectiveness of the timetable generated.

- **Complex Constraints:** Extremely complex constraints may require additional customization beyond the standard features of TTGS.

- **Computation Time:** The genetic algorithm may require substantial computation time for large institutions or complex scheduling scenarios.

- **Optimality Guarantee:** While TTGS aims to generate optimal timetables, there is no guarantee that it will always find the global optimum.

- **Scalability:** The system's performance may degrade as the dataset grows significantly.

**Applications:**

- Educational Institutions
- Training Centers
- Conference and Event Planning
- Employee Shift Scheduling
- Resource Management
- Project Planning

**Project requirements:**

**Software Technologies Used:**
- HTML5
- CSS3
- Python 3.8
- Django 3.0
- JavaScript
- sqlite3

**Software Dependencies:**
- python3.6
- Django

**References:**

- [GeeksforGeeks - Genetic Algorithms](https://www.geeksforgeeks.org/genetic-algorithms/)
- [Ander Fernandez Blog - Genetic Algorithm in Python](https://anderfernandez.com/en/blog/genetic-algorithm-in-python/)
- [Towards Data Science - Using Genetic Algorithms to Schedule Timetables](https://towardsdatascience.com/using-genetic-algorithms-to-schedule-timetables-27f132c9e280)


---

*This project is a part of the academic curriculum and aims to address the challenges faced by educational institutions in timetable generation.*
