# CMPG-323-Overview-38205742

_This repository serves as an overview for the projects I will be working on during this semester._

```mermaid
flowchart LR
    subgraph SemesterProjectsOverview[Semester Projects Overview]
        Project1[Project 1 - Agile & Scrum] -- Uses --> Repo1[Repository for Project 1]
        Project2[Project 2 - API Development] -- Uses --> Repo2[Repository for Project 2]
        Project3[Project 3 - Standards & Patterns] -- Uses --> Repo3[Repository for Project 3]
        Project4[Project 4 - Testing & RPA] -- Uses --> Repo4[Repository for Project 4]
        Project5[Project 5 - Reporting & Monitoring] -- Uses --> Repo5[Repository for Project 5]
    end


```



## Project Repositories

_Each project will have its own repository._

### [Project 1](https://github.com/Albert-Willemse/CMPG-323-Overview-38205742)
<details>
<summary>Agile & Scrum (Mandatory)</summary>
  
_Due Date: 10 August 2023_

Develop a project & repository, and use it throughout the semester. This project focuses on understanding Agile principles and Scrum methodology. 

Training in:

- Agile (Scrum)
- Source Control using GitHub.

</details>

### Project 2 (Link to be added)
<details>
<summary>API Development</summary>
  
*Due Date: 31 August 2023*

Develop an API and host it on the Cloud. This project's value lies in using the API in the subsequent Reporting & Monitoring Project. 

Training in:

- Cloud Basics
- API Basics
- .NET Core

</details>
  
### Project 3 (Link to be added)
<details>
<summary>Standards & Patterns</summary>
  
*Due Date: 21 September 2023*

Apply Design Pattern to an existing project and host the Web App on the Cloud. This project aims to teach me how to adapt existing code and apply design patterns effectively. 

Training in: 

- Design Patterns Basics
- Architecture Pattern Basics
- Coding Standards Basics
- .NET Core MVC Web Application.

</details>
  
### Project 4 (Link to be added)
<details>
<summary>Testing & RPA</summary>
  
*Due Date: 19 October 2023*

Use UiPath to enter data from an existing dataset into an existing web application to conduct user testing. This project will introduce me to various testing techniques and teach me how to use RPA. 

Training in: 

- Testing Basics
- RPA & Automation Basics
- UiPath

</details>
  
### Project 5 (Link to be added)
<details>
<summary>Reporting & Monitoring</summary>
  
*Due Date: 26 October 2023*

Visualize backend data using API endpoints created in Project 2. This project focuses on creating basic yet meaningful reports.

Training in:

- Data Visualization Basics
- Dashboarding Versus Reporting Versus Monitoring (with Basics)
- Power BI

</details>

## Branching Strategy

I will be following the Gitflow branching strategy for all my projects. This strategy involves two main branches: `main` and `develop`. Each project will have its own feature branches based on the `develop` branch. Once a feature is complete, it will be merged back into the `develop` branch.
```mermaid
gitGraph:
       commit
       branch develop
       commit tag:"v0.1.0"
       commit
       branch feature
       commit tag:"v0.1.1"
       commit
       checkout develop
       merge feature
       commit
       checkout main
       merge develop tag:"v1.0.0"
       
```

## .gitignore

I will use a `.gitignore` file to exclude unnecessary files and directories from being tracked by Git. This ensures that only relevant code and configuration files are included in the repositories.

## Storing Credentials

To ensure the security of sensitive information such as API keys and passwords, I will use environment variables to store these credentials. The environment variables will be set on the deployment platform securely, and they will not be stored in the repositories.

## Kanban Project & Progress Tracking

My GitHub Kanban project will help me visualize my progress throughout the semester. I've set up different views to track tasks, sprints, and assessment deadlines. I will regularly update the Kanban board to reflect the current status of tasks.
