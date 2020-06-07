# GitHub Project's Guide
This guide is for any team member that needs guidance on understanding what a GitHub Project is, why it is so valuable to our team, and/or how to use it.

For quick navigation:

- [Overview](#overview)
- [Why we use GitHub Projects](#whygp)
- [GitHub Project Components](#gpcomponents)
- [Guideline](#guideline)

## <a name="overview"></a> Overview
GitHub Projects are a project management tool. The Projects are meant to keep the team transparent and on schedule. Projects are made up of project boards that have 3 columns:

1. **To do** column
2. **In progress** column
3. **Done** column

Thess columns are how the tasks within each team will be organized, assigned, and collaborated on.

For more information on project boards, see this [documentation](https://help.github.com/en/github/managing-your-work-on-github/about-project-boards) from GitHub.

## <a name="whygp"></a> Why we use GitHub Projects
We want to be world-class developers after this whole journey ends. So our team will be attempting to work in an [Agile mindset using the Kanban framework](https://www.atlassian.com/agile/kanban). Due to this attempt, it is important that every member has a basic understanding of GitHub Projects.

## <a name="gpcomponents"></a> GitHub Project Components
There are 4 main components of GitHub Projects that you should know about. Namely:

1. [Project Board](#gpcomponents-project-board)
2. [**To do** Column](#gpcomponents-to-do-column)
3. [**In progress** Column](#gpcomponents-in-progress-column)
4. [**Done** Column](#gpcomponents-done-column)

### <a name="gpcomponents-project-board"></a> 1. Project Board
The Project board is basically just container for all columns.

### <a name="gpcomponents-to-do-column"></a> 2. **To do** Column
The first column in the Project Board. This column is responsible for containing all cards (tasks) that a team would have to finish by a certain deadline.

These cards are under the **To do** column. This means that these would be cards (tasks) that haven't been assigned to anyone to work on yet.

### <a name="gpcomponents-in-progress-column"></a> 3. **In progress** Column
The second column in the Project Board. This column is responsible for containing all cards (tasks) that a team is actively working on.

These cards are under the **In progress** column. This means that these would be cards (tasks) that have been assigned to one or more members of the team and the assignees are currently working on completing the card (task).

### <a name="gpcomponents-done-column"></a> 4. **Done** Column
The third, and final, column in the Project Board. This column is responsible for containing all cards (tasks) that a team has completed.

These cards are under the **Done** column. This means that these would be cards (tasks) that have been assigned to one or more members of the team and the assignees have completed the card (task).

## <a name="guidelines"></a> Guidelines
There are 4 guidelines you should always follow:

### 1. Card Format (Team Without Repository)
Each card should have a basic format that remains consistent. Here's how a template for a team without a repository should look like:

```markdown
###### <Your Task Name>
####### Assigned To: @<assignees-github-username>, ..., ...

<Your-Brief-Description-Of-Task>

Requirements:
<Your-Checklist>
```

The <Your-Checklist> section should be in this format for each item:

```markdown
- [ ] Item Not Done
- [x] Item Done
```

Here is an example of a card in the format shown above.

```markdown
##### Create GITHUB_PROJECTS_GUIDE file for executive repo
###### Assigned To: @theguy

The executive repo is the entry point for all team members.
As such, the GITHUB_PROJECTS_GUIDE.md file must be created to
ensure that all members know why and how to use Projects.

Requirements:
- [ ] Add overview section
- [ ] Add why github projects section
- [ ] Add github project components section
- [ ] Add guidelines section
```

### 2. Card Format (Team With Repository)
Each card should have a basic format that remains consistent. Here's how a template for a team with a repository should look like:

### 3. Card Assignments
Cards should be assigned to one or more team members before transferred to the **In progress** column.

### 4. Card Transfer
Card transfers to **To Do** should occur only if a new task is required.

Card transfers to **In progress** should occur only if a card has been assigned to one or more members of the team.

Card transfers to **Done** should occur only if a card's checklist has been completed.
