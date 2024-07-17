
<h1 align="center">Research Position Search App</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/mitchellkolb/research-position-search-app?color=003B57">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/mitchellkolb/research-position-search-app?color=003B57">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/mitchellkolb/research-position-search-app?color=003B57">

  <img alt="Github stars" src="https://img.shields.io/github/stars/mitchellkolb/research-position-search-app?color=003B57" />
</p>

<p align="center">
<img
    src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/Flask-0078D6?style=for-the-badge&logo=flask&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"
    alt="Website Badge" />
</p>

The Research Position Search App is a web application designed to connect undergraduate students with faculty research opportunities. Students can create profiles, browse available positions, and apply for those that match their interests, while faculty can post and manage research opportunities.

![project image](resources/lama.gif)

<details>
<summary style="color:#5087dd">Watch the Full Video Demo Here</summary>

[![Full Video Demo Here](https://img.youtube.com/vi/XV8JiobX_7g/0.jpg)](https://www.youtube.com/watch?v=XV8JiobX_7g)

</details>

---


# Table of Contents
- [What I Learned](#what-i-learned-in-this-project)
- [Tools Used / Development Environment](#tools-used--development-environment)
- [Team / Contributors / Teachers](#team--contributors--teachers)
- [How to Set Up](#how-to-set-up)
- [Project Overview](#project-overview)
- [Project Details](#project-details)
   - [Student Interface](#student-interface)
   - [Faculty Interface](#faculty-interface)
- [Technical Plan](#technical-plan)
- [CI / CD](#ci--cd)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)

---

# What I Learned in this Project
- How to develop a website while implementing the Model-View-Controller design pattern.
- Building and deploying web applications using Python, Flask, and SQLite.
- Implementing continuous integration and deployment with Selenium for automated testing.
- Designing and developing user-friendly interfaces with HTML, CSS, and Flask templates.
- Using Github Issues to distribute the work load to complete deliverables on time.



# Tools Used / Development Environment
- Python
- Flask
- SQLite
- Selenium
- VS Code
- Terminal
- Windows 10
- MacOS





# Team / Contributors / Teachers
- [Mitchell Kolb](https://github.com/mitchellkolb)
- [Louis Kha](https://github.com/LouisKha)
- [Albert Lipaev](https://github.com/Endeavour-Innovations-Inc)
- Alex Castillo
- Professor. Sakire Arslan Ay
- Team Name: LAMA



# How to Set Up
This project was implemented on our local machines on both windows and macOS:
- Clone this repository 
- Open terminal at the codebase `~.../research-position-search-app/TermProject-TeamLAMA/`
- Install all of the requirements with
```zsh
pip install -r requirements.txt
```
- Install SQLite and configure your local instance in the `config.py` file.
- Run the config.py and smile.py files to start the project with
```zsh
python3 smile.py
```
- The codebase will startup on your localhost






# Project Overview
The Research Position Search App is a web application designed to connect undergraduate students with faculty members offering research positions. It enables students to create profiles, browse available research opportunities, and apply for positions that match their interests and qualifications. Faculty members can post research positions, review applications, and manage the hiring process. Our site aims to streamline the process of matching students with research opportunities, enabling greater engagement in academic research.

## Project Details
The Research Position Search App provides two main interfaces: one for students and one for faculty members.

### Student Interface:
- When a student creates an account they enter profile information including contact details, academic background, and research interests.
- They can view open research positions and recommended positions based on their interests.
- Apply for multiple research positions, submit statements of interest, and provide references on the positions.
- Track the status of applications (Pending, Approved for Interview, Hired, Not Hired).
- Withdraw applications if no longer interested.

### Faculty Interface:
- Create a faculty account and enter profile information.
- Post research positions with details such as project goals, required qualifications, and time commitments.
- View applications from students and access their academic and research backgrounds.
- Update application statuses (Approved for Interview, Hired, Not Hired) and manage postings.

## Technical Plan
When working on this website our team used a Model-View-Controller (MVC) architectural pattern to organize the codebase. The technologies used include:
- **Python** and **Flask** for the backend.
- **SQLite** for the database.
- **HTML** and **CSS** for the frontend.
- **Selenium** for continuous integration and testing.


## CI / CD
In this project, Selenium was used for continuous integration and continuous deployment (CI/CD) testing. The automated tests ensure that:
- All pages load correctly.
- Forms accept and validate input as expected.
- User actions, such as logging in, applying for positions, and posting positions, perform as intended.
- Application statuses update correctly and are reflected in the UI.

## Future Work
Future improvements could include:
- Enhancing the recommendation algorithm for matching students to research positions.
- Implementing a notification system to alert students and faculty of updates.
- Adding a messaging system for direct communication between students and faculty.
- Integrating more advanced search and filter options for both students and faculty.
- Expanding the application to support multiple institutions.






--- 
# Acknowledgments
This codebase and all supporting materials was made as apart of a course for my undergrad at WSU for CPTS 322 - Software Design and Architecture in the Fall of 2021. This project was originally submitted to a campus controlled repository as all WSU assignments are. This repository serves as a backup place to showcase this project. The original repo is [linked here.](https://github.com/WSU-CptS322-Fall2021/TermProject-TeamLAMA/tree/iteration3)

