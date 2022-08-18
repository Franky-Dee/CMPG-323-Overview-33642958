# CMPG-323-Overview-33642958

## CMPG323 Semester tracking and project organization.

### The following repositories will be used for the correlating projects:

- CMPG323-Project-2-Overview-33642958 => Project 1
- CMPG323-Project-2-API-Development-33642958 => Project 2
- CMPG323-Project-3-Standards-and-Patterns-33642958 => Project 3
- CMPG323-Project-4-Testing-and-RPA-33642958=> Project 4
- CMPG323-Project-5-Reporting-and-Monitoring-33642958 => Project 5

However, the project in the overview repo will be used to track and manage progress of all other projects done throughout the semester. (All projects will be linked, tracked and managed by the overview repo.

### Branching strategies:
For all the projects the same branching strategy will be used. There will be 3 branches:
- Main = this is where main version control will be handled and versions of code will be released to.
- Develop = this is where all development of code will be handled and all pieces of a project will be put together into one cohesive format. develop comes off of the main branch
- Feature = Feature will branch off of develop where one feature of the code or program will be handled and worked with at a time.

### Use of the .gitignore file in each project:
Primarily the .gitignore file will be used to store any files that are known to have sensative information. However in projects 2-5 the .gitignore file will also be used to store generated files ie dist folders. The .gitignore file will be used for the same purpose in all the projects.


### The storage of credentials and sensative information
git-secrets will be used to stop any sensative information or credentials being added into the repos. It is a tool that scans commits and commit messages
to prevent adding secrests into the git repos. If a commit or commit message matches one of my configured prohibited patterns, then the commit is completely rejected and will not be allowed. Additionally the .gitignore file will be used to store any predetermined files with sensative information.
Although there is always a chance of sensative information making its way into the repos, therefore gitrob ,which is a tool that iterates through the repos commit history and flag files that match signatures for potentially sensative information which is then presented in web format to be easily reviewd and analyzed, will be used as the final layer of security to ensure no sensative information whatsoever will be added to the repos.
