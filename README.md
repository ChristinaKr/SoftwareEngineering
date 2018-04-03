BNB Booking System Report
===============================

This is the source code for the LaTeX files that will be used to generate the report.

## Setup and Instructions
- You must have your latex distribution package installed
- I started using the built in tex editor that comes with the mactex distibution, but found it was much easier to use VS Code
- Download [VS Code](https://code.visualstudio.com/download) for this! EFFICIENCY WOW!
- You also need to add an extension called: [Latex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- Everything else should be straightforwars, as soon as you open a `.tex` file, a small pdf icon will be shown in the upper left hand corner in the editor
- This pdf will automatically be generated and updated everytime you save the a tex file inside the project.

## Project Management
Project Management Flow using Git and GitHub:

1. To create a new “Ticket”, you should go to https://github.com/zlahham/bnb_report/issues and click on “New Issue”
2. Give the Ticket a short Title and a good description
3. Assign the Ticket to yourself/team member
4. Add a Label(s) to the Ticket
5. Assign it to one of the following “Projects”:
    1. LaTeX Report
    2. Research & Requirements
6. Submit the Issue :)

If the instructions are followed properly, it should automatically add an incoming ticket to a Kanban board depending on the Project. The two kanban projects can be found at https://github.com/zlahham/bnb_report/projects.

For “LaTeX Report” tickets, please only manually move tickets from the “To Do” column to the “In Progress” one when you start working on a specific task/ticket.
This should be done like so:
1. Create a local branch from master on your command line/IDE/whatever and name it using the “Issue” number. e.g using this issue https://github.com/zlahham/bnb_report/issues/1 we would name the new branch 1-test-section.
2. Add your content to the code base
3. When you are done:
    1. Merge master into your branch locally
    2. Push your new branch to GitHub
4. Submit a new Pull Request towards master on Github.
5. In the description, please reference the Issue number. Using the previous example, the comment in the description would be: fixes #1
    1. Please read this article from GitHub https://github.com/blog/1506-closing-issues-via-pull-requests
6. Assign two other team members to review the pull request.
7. Only when all the reviewers approved the pull request, you can then move onto merging the branch.
8. If referenced properly, the approved pull request should close the initial Issue and this will also automatically move that ticket on the kanban board to “Done”

As for the “Research & Requirements” related tickets, you can move the tickets manually when you are done working on them to the “Done” column from “In Progress”
