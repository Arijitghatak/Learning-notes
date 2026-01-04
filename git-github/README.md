\# Git \& GitHub Learning Notes



This repository contains my \*\*handwritten learning notes on Git and GitHub\*\*, created while learning version control fundamentals from scratch.



These notes focus on \*\*core concepts, mental models, and command-level understanding\*\*, rather than advanced workflows or tooling.



---



\## 📘 PDF Access (Google Drive)



The complete handwritten notes are available as a PDF on Google Drive:



👉 \*\*\[Download Git \& GitHub Initial Notes (PDF)]
https://drive.google.com/file/d/1CzTJPbPrF3Ei8IIPIXFrrjmmG3Be2ls9/view?usp=drive_link


---



\## 🧭 What These Notes Cover



The notes are structured progressively and include both explanations and diagrams.



\### 1. Git Fundamentals

\- What Git actually is (DVCS)

\- Git vs GitHub (clear distinction)

\- Why Git is needed

\- Problems without version control



\### 2. Git as a System (Core Mental Model)

\- Working Directory

\- Staging Area (Index)

\- Local Repository

\- Remote Repository (GitHub)

\- Data flow between these components (with diagrams)



\### 3. Repository Basics

\- What a repository is

\- Role of the `.git` folder

\- What happens if `.git` is deleted

\- Creating a local repository using `git init`



\### 4. Git Internal Data Model (Conceptual)

\- Blob (file content)

\- Tree (directory structure)

\- Commit (snapshot + metadata)

\- HEAD (pointer to current branch)

\- Why Git is fast (snapshots, not diffs)



\### 5. Commits

\- What a commit really represents

\- Commit as a snapshot

\- What each commit contains:

&nbsp; - tracked files

&nbsp; - commit message

&nbsp; - author info

&nbsp; - timestamp

&nbsp; - parent commit

\- Importance of commits for history and accountability



\### 6. Commit History \& Inspection

\- Viewing history using `git log`

\- Compact history with `git log --oneline`

\- Inspecting changes using `git show`

\- Why history is a graph, not a straight line



\### 7. Branches (Core Concept)

\- What a branch actually is (lightweight pointer)

\- Initial state with `main`

\- Creating branches

\- Switching branches using `git switch`

\- Role of `HEAD`

\- Branch diagrams explaining pointer movement



\### 8. Merging

\- Why merging is needed

\- Merging feature branches into `main`

\- Merge commit concept (high-level)



\### 9. Remote Repositories

\- What a remote is

\- Local vs remote repository

\- Adding a remote (`git remote add`)

\- Verifying remotes (`git remote -v`)



\### 10. Push, Pull, Fetch

\- Difference between push, pull, and fetch

\- Data flow diagrams

\- `git push origin main`

\- `git pull = git fetch + git merge`

\- What fetch does \*without\* modifying working files



\### 11. Clone

\- What `git clone` does

\- What gets copied

\- Automatic remote setup



\### 12. Pull Requests (Conceptual)

\- What a pull request is

\- Why PRs exist

\- Code review, discussion, quality control

\- Created on GitHub, not locally



\### 13. `.gitignore`

\- Purpose of `.gitignore`

\- Excluding files from tracking



\### 14. Git Workflow as Phases

\- Installing Git

\- Initial configuration

\- Creating a project

\- Editing → staging → committing cycle



---



\## 🚫 What These Notes Do NOT Cover (Yet)



Being honest — these topics are \*\*not included\*\*:



\- Rebase (interactive or normal)

\- Merge conflicts (hands-on resolution)

\- Cherry-pick

\- Stash

\- Tags \& releases

\- Git hooks

\- GitHub Actions / CI-CD

\- Advanced branching strategies (Git Flow, Trunk-based)

\- LFS (Large File Storage)



These notes are \*\*foundational\*\*, not advanced.



---



\## 🎯 Intended Audience



These notes are suitable for:

\- Beginners learning Git for the first time

\- Students preparing for exams

\- Developers who want \*\*clear mental models\*\*, not just commands

\- Interview preparation for \*\*basic to intermediate Git questions\*\*



They are \*\*not\*\* meant to replace official documentation or advanced Git books.



---



\## 📝 Disclaimer



These are \*\*personal learning notes\*\*, not official documentation.

They prioritize \*\*clarity and understanding\*\* over exhaustiveness.



I plan to extend and refine them as I gain more practical experience.



---



\## 📌 Status



\- Current state: \*\*Foundational / Beginner–Intermediate\*\*

\- Format: Handwritten → scanned PDF

\- Future updates: Possible (advanced topics, real workflows)



---





