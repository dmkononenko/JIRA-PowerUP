<div align="center">
  <img src="https://github.com/user-attachments/assets/11e87758-ca3c-44a9-b97f-e3fbdfa2820c" alt="иконка">

</div>

# JIRA PowerUp
🚀 JIRA PowerUp — Chrome extension that automates and streamlines escalation management in JIRA. 

Instantly detect blocking issues, visualize escalation priorities with color indicators 🟡🟠🔴, and copy task info for quick sharing in messengers (Telegram, Slack, etc.) 📋. 

Supports JIRA Server and DataCenter. 

All settings and keys are stored locally and securely 🔒.

Simplify cross-team dependencies and speed up releases with JIRA PowerUp!

## Features  
- [Copy Helper](#copy-helper)
- [Blocked-by indicator](#blocked-by-indicator)

### Copy Helper
**Feature's Goal**: to allow 1-click copying of task data to pass the full context on the task and share in in messangers.

Quickly copy JIRA task information in various formats.

📋 Copy button - automatically appears on task pages next to the key.

🎨 Flexible output formats:

* Summary - Issue Link (default)
* Summary: Issue Link
* [Summary] (Issue Link)
* Custom templates with placeholders for JIRA fields

📊 Available template fields:
{summary} - task title
{key} - task key (PROJ-123)
{status}, {priority}, {assignee} - basic information
{issueLink} - full link to the task
{date}, {time} - current date/time
And 15+ more JIRA fields

### Blocked-by indicator
**Feature's Goal**: save time and very quickly find tasks that block the selected task.

System of visual indicators of blockers for task cards on kanban board and backlog, /verions page, on task page under Issue Links and epic under Issues in Epic.

Displays badges with the number of blockers on task cards in all sections of JIRA.

**Indicator Color:**

1. Yellow - 1 incoming blocked-by
2. Orange - 2
3. Red - 3 or more

When you hover on the indicator, it shows detailed information about the blocking tasks in a modal window with the ability to copy the data to the clipboard.

Also, you can click on the indicator and it will open a search page with these tasks.