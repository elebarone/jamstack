[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/5fRBlVhQ)

# Lab 02 - Intro to GitHub

## Timeline
<table>
  <thead>
      <td style="text-align:left;">Assigned</td>
      <td style="text-align:left;">Monday 9 September 2024</td>
  </thead>
  <tfoot>
      <td style="text-align:left; color: red;">Deadline</td>
      <td style="text-align:left;">Friday 13 September 2024</td>
  </tfoot>
</table>

![Lab 2 Assignment](https://github.com/allegheny-college-cmpsc-104-Fall-2024/lab02/blob/main/graphics/github-mark2.png)

## Project Goals
- Deepen understanding of GitHub's collaboration features.
- Explore pull and push operations.
- Work on branches on GitHub.
- Demonstrate the GitHub Flow.
- Enhance skills for collaborating effectively on projects using GitHub.

## Tools
- A computer
- Internet connection
- A GitHub account

## Learning Outcomes
These assignment learning outcomes contribute to the following course learning outcomes described in the course syllabus:

1. Describe and explain processes such as software installation or design for a variety of technical and non-technical audiences ranging from inexperienced to expert.
2. Use professional-grade integrated development environments (IDEs), command-line tools, and version control systems to compose, edit, and deploy well-structured, web-ready documents and industry-standard documentation tools.

## Instructions

### Part 1: Clone the Repository and Read the README.md File 
1. Click on the assignment link and accept the assignment.
2. Use the `git clone` command followed by your repository's URL. (Find this URL on your GitHub repository page under the "Code" button.)

### Part 2: Creare a New Branch: 
1. Create a new branch named `update_readme`.
2. In the `update_readme` branch, delete the from the README.md file.
3. Push this new branch to the GitHub repository.

### Part 3: Explore Pull and Push Operations: 
1. Open a pull request for your `update_readme` branch with the comment "Update README.md by removing".
2. Request approval from your instructor by submitting the pull request. The instructor will review and approve it.
3. After receiving approval, merge the pull request, but **do not delete the update_readme branch**. The update_readme branch is required for grading, as GatorGrader will check the contents of this branch.

### Part 4: Git Commands
- Please complete the tasks in `writing/git_command.md`.

### Part 5: Write about GitHub Collaboration
- In `writing/reflection.md`:
    - Discuss how the pull and push mechanisms in GitHub are fundamental to the functionality of distributed version control systems.
    - Share your insights and personal experiences with utilizing GitHub branches
    - Explain What is GitHub Flow? Provide a thorough analysis beyond its basic definition, focusing on the importance of each GitHub Flow step and its impact on collaborative software development.

### _Notes_: 
- Make sure to put your assignments in a folder named after your course. After you upload them to GitHub, your work is saved and you can get to it anytime.
- Within `writing/git_command.md` and `writing/reflection.md`, you will find several tasks awaiting your completion. As you work, please ensure to remove all markers indicating pending work. 
- For this lab, GatorGrader will verify that all indicators of incomplete tasks have been addressed and that your submission includes a minimum of 200 words.

## Resources
- Git Documentation: https://git-scm.com/doc
    - Pro Git book: https://git-scm.com/book/en/v2, specifically chapters 1, 2, and 3. 

## Deliverables
Please submit your work by pushing it to your GitHub Classroom repository.
- You will modify the files `README.md`, `writing/git_command.md` and `writing/reflection.md` to respond questions in the document.

## Project Assessment
- **Completion of Parts 2 and 3 (20%)**: Successfully completing Parts 2 and 3 will each contribute 10% towards the assessment
- **Report Quality (40%)**: The quality of the writing in `writing/reflection.md` will be assessed, focusing on clarity, structure, and adherence to the assignment guidelines.
    - Clarity and Coherence (10%): Writing clearly expresses ideas and concepts, with logical flow and coherence throughout.
    - Structure and Organization (10%): The report is well-structured. Follows the assignment guidelines accurately.
    - Grammar and Style (10%): Correct use of grammar, punctuation, and academic style. Professional and appropriate language is used.
    - Depth of Reflection (10%): Demonstrates deep understanding and thoughtful reflection on each topics. Includes detailed explanations and insights.
- **Git Command Proficiency (30%)**: Correctly answer questions related to Git commands in `writing/git_command.md`.
- **Achieve GatorGrader Compliance (10%)**: Successfully meets the criteria set by GatorGrader.

## Gator Grade
### GatorGrade Checks for Immediate Feedback

To provide immediate feedback on your submissions, we're utilizing GatorGrade. Upon submission, if there's a thick red X, it indicates missing components. This X will turn into a green check mark once your submission is complete. For details on what's missing, click on the red X.

To meet the lab assignment's baseline writing and commit requirements, you can use the department's `GatorGrade` tool. Ensure Python3 is installed on your computer (check with `python --version`). If Python is not installed, please follow these guides:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [Setting Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Installing `GatorGrade`:

- [Install](https://pipx.pypa.io/stable/) [pipx](https://pipx.pypa.io/stable/) if you haven't already (`pip install pipx`).
- Install `GatorGrade` using pipx (`pipx install gatorgrade`).
- Running `GatorGrade`:
 `gatorgrade --config config/gatorgrade.yml`

Good luck!
