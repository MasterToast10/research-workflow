# Collaborative Research Paper-Writing Workflow
A workflow for research paper-writing crafted for efficiency.

## Accounts Required (Preliminary)
 - [A GitHub Account](https://github.com/join)
 - [A Google Account](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp)
 - [A Zotero Account](https://www.zotero.org/user/register)

## Setup
Before using the workflow, the necessary software must be installed.
The necessary software is provided in the [Installation](installation) section.
The workflow also involves templates which can be used over and over again for multiple research topics.
Said templates are hosted online via the same workflow and can be accessed through the [Templates](templates) section.

## The Workflow
### Data Collection
Before writing content, the team must collect sufficient data from both Related Literature and Empirical Evidence.
#### Reference Data
When the team presents a research proposal, there is no Empirical Evidence, and the only basis is from Related Literature.

At this stage, using their Internet browser and Zotero, each team member searches for resources that might be relevant to the research topic.
They then share the references and the respective digital copies that they find to their [Group Library](https://guides.library.oregonstate.edu/c.php?g=359201&p=2426111) for other team members to see.
This prevents redundancy as references that are found and annotated by one team member need not be searched for and annotated by another team member.

The team can also share notes on the references that are found, leading to a more in-depth discussion of the work.
This occurs for several more relevant literature found by the team, and each team member has a copy of the annotated bibliography produced.
#### Empirical Data
Once the research proposal is accepted, the team can proceed to collecting Empirical Data.

The process varies from field to field, however, the methodology must be closely-tied to the related literature.
During this time, the team may also add new sources or insights on the references stored in the Group Library.
### Collaborative Content Management
Using GitHub, progress and relevant changes can be stored in the team repository, forked from the [Forkable GitHub Repository](templates/#forkable-github-repository).

Non-LaTeX information such as the photo documentation or important insights may be stored on the team repository.
Data gathered (e.g. spreadsheets) can be stored in [Google Sheets](https://sheets.google.com), with its own [version control system](https://support.google.com/docs/answer/190843).
These spreadsheets, through the use of Formatted Paste with [LaTeX Utilites](installation/#latex-utilities-by-tecosaur) can be easily integrated into the LaTeX Documents.
Progress on the Research Project itself can be tracked via GitHub, with comment and issue threads.
[Project Boards](https://help.github.com/en/github/managing-your-work-on-github/about-project-boards) can be set up for each logical division of the Research Project, noting the progress of each issue.
These Project Boards can double as the planning calendar, removing the need for making a physical copy of the Planning Calendar.

Research Teachers and Advisers can also watch their team's repository, removing the need to produce a Project Monitoring Documents such as Weekly Accomplishment Reports (WARs).
Peer rating is still advised however, as not everything accomplished in the research is done on a computer.

The structure of the repository tree will be as follows: one master branch (for the most publishable output), and one developmental branch for each team member (the research teacher and adviser are also considered team members) with the naming format `member_name`.

In each developmental branch, the respective team member may make unlimited changes to the files and [commits](https://www.atlassian.com/git/tutorials/saving-changes/git-commit) to the branch.
The team member may also make their own sub-branches to organize their developmental branch with the naming format `member_name-subbranchname`.
After making changes, the team member may make a [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

When a team member begins a pull request, discussions may ensue on why said changes are necessary.
Other members can comment on the changes as well as add commits to revise them.

The GitHub Repository can also double as a daily journal, since important events such as breakthroughs in the research are recorded with a timestamp.
### Content Writing
Using LaTeX, the team can write without regard for the format, as the template ensures that the papers will always follow the format.
The combination of Zotero and LaTeX produces automatic citations and bibliography, removing the need to copy and paste.
This means that the team can focus more on writing content, instead of on minor details such as formatting content and citations/bibliographies.

<!-- ## Thoughts
### Zotero Reference Management
   - Members share their references to the Group Library as well as the digital copies they find (thus each member can read the same work)
### git-powered Collaboration
   - Non-LaTeX information may be stored on the repository, such as the data gathered (spreadsheets) or documentation
   - Development branch per team member (one for adviser too)
   - Comments and issues passed via GitHub (Project Boards)
   - Pull Requests from a branch to start discussing changes (propose changes and code review)
   - Comments on changes as well
   - The GitHub repository can serve as a daily journal as well, since everything is recorded with a timestamp
### LaTeX Writing
   - Automatic formatting for more focus on content
   - Automatic citations and bibliography for less copy-and-paste -->
