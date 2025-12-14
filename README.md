# DisasterPrep – Git Version Control Assignment
## Project Overview
DisasterPrep is a simple web-based project created to demonstrate Git and GitHub version-control operations.
The project focuses on applying Git concepts such as repository initialization, branching, merging, conflict resolution, and remote repository management using GitHub.
This repository is created specifically for academic Git evaluation purposes.

## Technologies Used
- HTML
- CSS
- JavaScript
- Git (Git Bash)
- GitHub

## Project Structure
DisasterPrep_GitAssignment/
│── index.html
│── login.html
│── signup.html
│── quiz.html
│── style.css
│── app.js
│── README.md

## Branches Created
The following branches were created and used during development:
- master
- branch
- feature
- test
- bugfix
- experiment
  
Each branch contains at least one meaningful commit.

## Git Commands Used
- Repository Initialization :-
  [git init]
  
- Staging & Committing :-
  [git add .]
  [git commit -m "commit message"]

- Branching :-
  [git branch]
  [git checkout -b branch_name]

- Merging :-
  [git merge branch_name]
  
- Merge Conflict Resolution :-
  - Conflict created intentionally in index.html
  - Conflict resolved manually
  - Final merged commit created

- Remote Repository :-
  [git remote add origin <repository_url>]
  [git push -u origin master]
  [git push origin branch]
  [git push origin feature]
  [git push origin test]
  [git push origin bugfix]
  [git push origin experiment]


## Merge Conflict Demonstration
A merge conflict was intentionally created while merging the bugfix branch into the master branch by modifying the same line in index.html.

- Conflict Resolution Steps:
  Conflict detected during merge.
  File edited manually.
  Conflict markers removed.
  Final version committed successfully.
This demonstrates proper understanding of conflict handling in Git.

## Git Commit Graph
The Git commit history with branching and merging was visualized using :-
  [git log --oneline --graph --all --decorate]

  This graph clearly shows:
  - Branch creation
  - Parallel development
  - Merge commits
  - Conflict resolution commit

## Screenshots
- Creating Directory & entring into it
  <img width="1436" height="358" alt="Screenshot 2025-12-14 022107" src="https://github.com/user-attachments/assets/ec6b439e-5975-4bde-bef9-1f4394b30657" />

- Creating basic project files
  <img width="952" height="576" alt="Screenshot 2025-12-14 023154" src="https://github.com/user-attachments/assets/b2f1ab41-f32e-456f-ad77-2778601206c1" />

- Initalizing git
  <img width="994" height="679" alt="Screenshot 2025-12-14 023642" src="https://github.com/user-attachments/assets/77e8700b-6108-4f55-b63c-74ba0433911d" />

- Adding all the project files to git
  <img width="1118" height="864" alt="Screenshot 2025-12-14 023850" src="https://github.com/user-attachments/assets/9189ab70-1ca4-440b-9bca-2832286bea7d" />

- Initalizing the first commit
  <img width="1479" height="1030" alt="Screenshot 2025-12-14 023953" src="https://github.com/user-attachments/assets/cbce2d1f-4db1-4258-9aeb-ad7d9d1388c9" />
  Here, the 1st commit done.

- Checking the log
  <img width="1485" height="1123" alt="Screenshot 2025-12-14 024116" src="https://github.com/user-attachments/assets/138f12d2-1457-4f41-aab5-b8d28f487724" />

- Creating all 5 branches(more than 4 are required)
  <img width="956" height="869" alt="Screenshot 2025-12-14 030409" src="https://github.com/user-attachments/assets/023543d5-c91b-49a0-8f51-9d82e05775ed" />

- Adding commits on all the branches
  <img width="1052" height="1138" alt="Screenshot 2025-12-14 032213" src="https://github.com/user-attachments/assets/112fe239-0a95-4906-b411-ded245e18641" />
  <img width="1109" height="1133" alt="Screenshot 2025-12-14 032230" src="https://github.com/user-attachments/assets/1ef71bdb-2bd5-48cb-9db5-a62491ba08cc" />
  Total 6 commits done till here.

- Done the clean merge of "Feature" branch and also created merge conflict(intentionally)
  <img width="1188" height="825" alt="Screenshot 2025-12-14 033109" src="https://github.com/user-attachments/assets/3f4ac0b3-4499-4cac-9449-0941156edae7" />
  7th and 8th commits done till now.

- Resolve the Merge conflict

  <img width="737" height="383" alt="Screenshot 2025-12-14 033600" src="https://github.com/user-attachments/assets/b3627185-62a5-49d3-8689-004075588118" />
  <img width="748" height="401" alt="Screenshot 2025-12-14 034235" src="https://github.com/user-attachments/assets/1bf08ba1-d52b-4342-95ae-5683995ef401" />
  
  Total 13 commits done till now(as merging all the remaining 3 branches also counts for commit).

- Checking Git Merge Graph
  <img width="900" height="428" alt="Screenshot 2025-12-14 034429" src="https://github.com/user-attachments/assets/0b85d713-6779-4b22-a7b8-09794a4d1486" />

- Added remote origin & pushed master
  <img width="821" height="326" alt="Screenshot 2025-12-14 035334" src="https://github.com/user-attachments/assets/f3dda438-f517-4e7c-87f6-fd8c77e193f2" />

- Pushed all the created branch
  <img width="1180" height="895" alt="Screenshot 2025-12-14 040051" src="https://github.com/user-attachments/assets/71fe781e-fa6b-43d3-a639-a85123cf826c" />

- Updated the README.md file then added, commited and pushed it to the repository.
  <img width="1240" height="460" alt="Screenshot 2025-12-14 040649" src="https://github.com/user-attachments/assets/d548a99f-c68f-4c9a-a97c-ae60202bb197" />
  And, the last 14th commit done here.

  
## Challenges Faced
- Understanding branch-based workflow
- Handling merge conflicts correctly
- Maintaining clean commit history
- Synchronizing local and remote repositories

## Learning Outcomes
  - Practical use of Git Bash
  - Understanding of staging, committing, and history
  - Branch creation and management
  - Merge conflict resolution
  - GitHub remote operations
  - Writing professional documentation using Markdown
    
## Conclusion
This project successfully demonstrates core Git and GitHub concepts required for version control and collaborative development.
The structured workflow, meaningful commits, and proper documentation reflect professional Git practices.

## Author
Utkarsh Raj
Department of Computer Science & Engineering
