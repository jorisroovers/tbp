# TBP
Task Based Programming (brainstorming).

Many organizations use a form or Agile programming (e.g. SCRUM) in which team members discuss the work to be done during
a daily meeting. While tools such as Rally and Trello allow the definition of user stories and tasks, they often allow
only high-level integration with the actual codebase of the application by linking bug or task ids in the git 
commit message.

At the same time, software development teams are often very heterogeneous with developers in different geographical
locations, timezones and with different levels of experience with the codebase.

This leads to developers spending a lot of time discussing how tasks need to be implemented or going back and forth as
part of code review in order to make sure that things are in line with the existing codebase. This is especially true
in cases where new developers join a team.

This project is a proof-of-concept attempt to come up with a fine-grained task description and validation framework
that allows developers to easily define a set of acceptance criteria of a certain task or functionality. 

In particular:

1. Task definition file that allows a fine-grained of what needs to be done
    - Certain files that need to be changed, deleted or created
    - Content that needs to be part of files
    - Tests/Documentation that need to be written
2. Tool to easily generate/modify task definition files
3. Task validator script to validate that task was completed
