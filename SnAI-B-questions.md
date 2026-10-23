# EVERY SnAI-B question (portal, till now)
Generated: 2026-10-24T01:57:36 by `scrape.py --export SnAI`

For the AI tutor: teach these in due-date order. Status and
XP are the student's real portal state. Question text is
included in a code block wherever the tracker captured it;
questions without text are listed at the end.

---
## CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ...  [Post Class]  — due 2026-09-15 18:05

### Advanced File Management — 40/40 XP — SOLVED — deadline 2026-09-15 18:05
Topics: CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/74blhrfcuwmj

```
Back
Advanced File Management
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Advanced File Management
Medium
2x
40/40
Time Limit: 2, Memory Limit: 128000

You are helping your team clean up and organize project files. 

Steps to follow:

Create a folder called project-files.

Inside it, create three files:

report.docx

summary.docx

draft.docx

Make a copy of report.docx and name it report_backup.docx.

Create a new folder called old. Move draft.docx into old/.

Rename summary.docx to final_summary.docx.

Copy final_summary.docx into the old/ folder as well.

Delete report_backup.docx.

Final structure should look like this:

project-files/
├── report.docx
├── final_summary.docx
└── old/
    ├── draft.docx
    └── final_summary.docx

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Create a Project Folder Structure — 40/40 XP — SOLVED — deadline 2026-09-15 18:05
Topics: Command-Line Interface (CLI), CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/l3u71naqswpk

```
Back
Create a Project Folder Structure
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Create a Project Folder Structure
Medium
2x
40/40
Time Limit: 2, Memory Limit: 128000

You have recently joined a backend team that develops services for an e-commerce platform.

To ensure consistency across projects, the team uses an internal command called create-service to generate the standard structure for new API services.

During the onboarding of several new developers, the team noticed that newly generated services are missing important files and some directories are named incorrectly.

The engineering manager asks you to investigate and repair the scaffold generator before the next batch of services is created.

Tasks:
Locate the create-service command.
Inspect the script used by the command.
Fix all issues in the script.
Ensure the command can be executed.
Run the command to generate a new service.

Expected Service Structure:
service/
├── controllers/
├── models/
├── routes/
├── middleware/
├── server.js
└── README.md


Expected README Content:
API Service


Expected server.js Content:
console.log("Server started");


Requirements:
Directory names must exactly match the expected structure.
The middleware directory must be present.
README.md must exist inside the service directory.
server.js must exist inside the service directory.
The contents of README.md must exactly match the expected text.
The contents of server.js must exactly match the expected text.
The command should execute successfully after your fixes.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Recover the Emergency Access Token — 40/40 XP — SOLVED — deadline 2026-09-15 18:05
Topics: Command-Line Interface (CLI), CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/7252j93o5izb

```
Back
Recover the Emergency Access Token
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Recover the Emergency Access Token
Medium
2x
40/40
Time Limit: 2, Memory Limit: 128000

You are assisting the Site Reliability Engineering (SRE) team during a production incident.

An emergency access token is required to restore a critical service. The token was intentionally stored somewhere inside a deeply nested backup directory structure for security reasons.

The backup system has created many nested folders containing many files. Most of these files are not readable due to permission restrictions.

The SRE team remembers only one thing:

The emergency token is stored in the only readable text file within the backup directory tree.

Your task is to locate the readable file, inspect its contents, and recover the token.

Tasks:
Explore the directory structure.
Find the readable file inside the backup directory tree.
Create a file named token.txt in the current directory containing only the token value.

Example Token Format:
ACCESS_TOKEN_VALUE=abc123xyz789


Expected Output File:
abc123xyz789


Requirements:
Do not modify any existing files.
token.txt must contain only the token value.
No additional text or whitespace should be present.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Locate and Extract the Recovery Key — 40/40 XP — SOLVED — deadline 2026-09-15 18:05
Topics: Command-Line Interface (CLI), CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/n8l45pooo4km

```
Back
Locate and Extract the Recovery Key
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Locate and Extract the Recovery Key
Medium
2x
40/40
Time Limit: 2, Memory Limit: 128000

A production server experienced a critical failure overnight. Before shutting down, the backup system created multiple backup folders and scattered diagnostic files across them.

Your team needs to restore access, but the recovery key was saved in only one backup file. The file name and location are unknown.

Search through the backup directory tree, find the recovery key, and save only the key value (without RECOVERY_KEY=) into a file named key.txt in the current directory.

Task:

Locate the recovery key hidden somewhere inside the backups directory.
Extract only the recovery key value.
Save the key value into a file named key.txt in the current directory.

For example, if a file contains:

RECOVERY_KEY=7fK92mXqL8pR3vNz

then key.txt should contain:

7fK92mXqL8pR3vNz

The recovery key may be located in any file within the backups directory tree.

Input
NA
Output
NA
Constraints
NA
Example
NA
```
---
## S&AI Contest 1 (Coding) - SVYASA  [Contest]  — due 2026-09-25 12:30

### Detective Shubham: The Hidden Network — 0/40 XP — NOT SOLVED — deadline 2026-09-25 12:30

URL: https://my.newtonschool.co/playground/code/z3twplcreddo

```
Back
Detective Shubham: The Hidden Network
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
Try AI Plan Mode
QUESTION
Detective Shubham: The Hidden Network
Easy
0/40
Time Limit: 2, Memory Limit: 128000

You are playing the role of Detective Shubham, a cyber investigator.

You have received information about a secret digital operation.
The entire operation follows a strict folder structure, and your job is to recreate it exactly using Linux CLI commands only.

You are currently inside the box/ directory.

Your Mission Steps :-

Step 1
Create a main folder named: OperationX
This folder will act as the control center.

Step 2
Move inside the OperationX folder.

Step 3
Inside OperationX, create three folders:
intel
agents
logs

Step 4
Inside the intel folder, create two folders:
documents
images

Step 5
Inside the agents folder, create three folders:
alpha
bravo
charlie

Step 6
Inside the logs folder, create two folders:
system
security


Expected Final Folder Structure
OperationX
├── intel
│   ├── documents
│   └── images
├── agents
│   ├── alpha
│   ├── bravo
│   └── charlie
└── logs
    ├── system
    └── security
Input
na
Output
na
Constraints
na
Example
na
```

### New Recruit — 40/40 XP — SOLVED — deadline 2026-09-25 12:30

URL: https://my.newtonschool.co/playground/code/lbr0104oudhx

```
Back
New Recruit
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
Try AI Plan Mode
QUESTION
New Recruit
Easy
2x
40/40
Time Limit: 2, Memory Limit: 128000

You are playing the role of a new recruit at a Company.

Before you can access any real case files, you must set up your personal workspace exactly the way the agency requires — using Linux CLI commands only.

You are currently inside the box/ directory.

Your Mission Steps:

Step 1
Create a main folder named: MyWorkspace

Step 2
Move inside the MyWorkspace folder.

Step 3
Inside MyWorkspace, create two folders:

notes
tasks

Step 4
Inside the notes folder, create an empty file named: day1.txt

Expected Final Folder Structure

MyWorkspace
├── notes
│   └── day1.txt
└── tasks
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### A Digital Investigator — 0/80 XP — NOT SOLVED — deadline 2026-09-25 12:30
Topics: CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/m4k7nv37p1an

```
Back
A Digital Investigator
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
A Digital Investigator
Medium
0/80
Time Limit: 2, Memory Limit: 128000

You are playing the role of Detective Senorita, a digital investigator.

You’ve just received an encrypted folder named CaseFiles from an anonymous source.

Your task is to organize the evidence, record your findings, and prepare a quick summary report — using Linux commands only.

Your Mission Steps
Create a new folder named CaseFiles.
Move inside the CaseFiles folder.
Inside this folder, create three empty files:
suspects.txt
evidence.txt
summary.txt
Add the following lines to suspects.txt, one line at a time without overwriting previous content:
John - Seen near crime scene
Maya - Works at nearby cafe
Raj - Security guard on duty
Add the following lines to evidence.txt, one line at a time without overwriting previous content:
CCTV footage found
Fingerprints on glass
Combine suspects.txt and evidence.txt into summary.txt. The suspects must appear first, followed by the evidence.
Display the contents of summary.txt.
Expected Final Report
John - Seen near crime scene
Maya - Works at nearby cafe
Raj - Security guard on duty
CCTV footage found
Fingerprints on glass
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### CID — 0/120 XP — NOT SOLVED — deadline 2026-09-25 12:30
Topics: CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/5ehlciw97nbc

```
Back
CID
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
CID
Hard
0/120
Time Limit: 2, Memory Limit: 128000

You are playing the role of a CID wrapping up a compromised operation.

The old operation folder OldBase contains leftover, disorganized files from a previous mission. Your job is to inspect, reorganize, rename, back up, and clean up the entire structure using Linux CLI commands only — exactly as instructed. This mission tests every command in your toolkit.

You are currently inside the box/ directory, and OldBase/ already exists with the following starting structure:

OldBase
├── draft.txt        (contains the text: TOP SECRET)
├── temp
│   └── junk.txt
└── old_logs
    └── log1.txt

Your Mission Steps:

Step 1
Create a new main folder named: NewBase

Step 2
Move inside the NewBase folder.

Step 3
Inside NewBase, create three folders:

reports
archive
backup

Step 4
Move back OUT of NewBase (using cd ..) so you're inside box/ again and print working directory.

Step 5
Copy the file OldBase/draft.txt into NewBase/reports/ (keep the same filename).

Step 6
Move (rename) NewBase/reports/draft.txt to NewBase/reports/final_report.txt.

Step 7
Add a new line of text — MISSION COMPLETE — to the end of NewBase/reports/final_report.txt without deleting its existing content.

Step 8
Display the contents of NewBase/reports/final_report.txt in the terminal to confirm it now contains BOTH lines.

Step 9
Move the entire OldBase/old_logs folder into NewBase/backup/.

Step 10
Delete the file OldBase/temp/junk.txt (the file only, not the folder).

Step 11
Delete the now-empty OldBase/temp folder using the command meant for removing empty directories.

Step 12
Delete the entire OldBase folder and everything remaining inside it in a single command.

Expected Final Folder Structure

NewBase
├── reports
│   └── final_report.txt   (contains: TOP SECRET \n MISSION COMPLETE)
├── archive
└── backup
    └── old_logs
        └── log1.txt

(OldBase should no longer exist at all.)

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Mr. Robot — 0/120 XP — NOT SOLVED — deadline 2026-09-25 12:30
Topics: CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/0o52fr5gg4nk

```
Back
Mr. Robot
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Mr. Robot
Hard
0/120
Time Limit: 2, Memory Limit: 128000

You are playing the role of a Mr. Robot closing out a classified operation known as Mirage.

Nothing about this operation is straightforward — every file has a decoy, every path has a twist, and one wrong move will corrupt the evidence. Follow the mission exactly.

You are currently inside the box/ directory, and MirageBase/ already exists with the following starting structure:

MirageBase
├── vault
│   └── secret.txt        (contains: CODE ALPHA)
├── decoys
│   ├── decoy1.txt
│   └── decoy2.txt
└── archive
    └── old.txt            (contains: ARCHIVE DATA)

Your Mission Steps:

Step 1
Create a new folder named: Mirage

Step 2
Move inside the Mirage folder.

Step 3
Inside Mirage, create three folders:

vault_copy
confirmed
discarded

Step 4
Move inside the vault_copy folder.

Step 5
From here, copy MirageBase/vault/secret.txt into your current folder (vault_copy), keeping the same filename. ⚠️ Remember — you are now two folders deep, so a plain ../ won't reach box/.

Step 6
Add a new line — VERIFIED — to the end of the secret.txt now sitting in vault_copy. ⚠️ The original content (CODE ALPHA) must still be there afterward. One wrong symbol here will silently destroy it.

Step 7
Display the contents of this secret.txt in the terminal to confirm both lines are present.

Step 8
Move back out of vault_copy, and then out of Mirage, so that you are back inside box/ — using cd .. twice, not any shortcut.

Step 9
Confirm your current location using the appropriate command.

Step 10
Move (not copy) MirageBase/archive/old.txt into Mirage/confirmed/.

Step 11
Delete the two files inside MirageBase/decoys — decoy1.txt and decoy2.txt — one at a time.

Step 12
Now remove the MirageBase/decoys folder using the command meant strictly for empty directories. ⚠️ If you try this before Step 11 is fully done, it will refuse to work — that's the point.

Step 13
Finally, delete the entire MirageBase folder — which still contains the original vault/secret.txt you never removed, plus an now-empty archive folder — in a single command.

Expected Final Folder Structure

Mirage
├── vault_copy
│   └── secret.txt      (contains: CODE ALPHA \n VERIFIED)
├── confirmed
│   └── old.txt          (contains: ARCHIVE DATA)
└── discarded             (empty)

(MirageBase should no longer exist anywhere.)

Input
NA
Output
NA
Constraints
NA
Example
NA
```
---
## Operating System, Filesystem Management, File Ownership and Permissions, PATH, O ...  [Post Class]  — due 2026-09-27 16:00

### Audit Trail Setup — 10/20 XP — SOLVED — deadline 2026-09-27 16:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/eu8eoa3cnihv

```
Back
Audit Trail Setup
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Audit Trail Setup
Easy
10/20
Time Limit: 2, Memory Limit: 128000

You are given the following folder structure inside the current directory.

audit_trail/
└── access.log

Perform the following operations:

Change the permissions of the audit_trail/ directory so that the owner has full access (read, write, execute), the group has read and execute only, and others have no access at all.
Inside audit_trail/, create a new file named summary.txt containing the exact text Audit Summary Generated.
Set the permissions of summary.txt so that the owner can read and write, the group can only read, and others have no access.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Three Levels of Access — 10/20 XP — SOLVED — deadline 2026-09-27 16:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/74dyuwbfq6i4

```
Back
Three Levels of Access
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Three Levels of Access
Easy
10/20
Time Limit: 2, Memory Limit: 128000

After a security review, three files in the clearance directory were found with wide-open permissions. Each file must be tightened to a different clearance level using numeric chmod.

Given Directory Structure:

clearance/
├── public.txt     
├── team.txt      
└── private.txt   

Current Permissions:

All three files: full permissions for everyone.

Tasks to Complete:

public.txt: owner can read and write; group and others can only read.
team.txt: owner can read and write; group can only read; others get nothing.
private.txt: owner can read and write; group and others get nothing.
Do not modify the content of any file.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Deployment Project Permissions — 20/40 XP — SOLVED — deadline 2026-09-27 16:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/33n9tt9kovhd

```
Back
Deployment Project Permissions
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Deployment Project Permissions
Medium
20/40
Time Limit: 2, Memory Limit: 128000

You are preparing a shared deployment project where different roles (developers, CI system, general viewers) need different levels of access to different parts of the codebase. You need to set the correct permissions on each part of the project so it is accessed only as intended.

Given Directory Structure:

deployment/
├── app/
│   ├── server.py
│   ├── handler.py
│   └── settings.py
├── datasets/
│   ├── train.csv
│   └── test.csv
├── docs/
│   └── OVERVIEW.md
└── bin/
    ├── start.sh
    ├── stop.sh
    └── healthcheck.sh

All files currently have default permissions (644 for files, 755 for directories). Apply the following rules:

Python source files (every .py file inside deployment/app/):

Owner: read, write, execute
Group: no access
Others: no access
The datasets/ directory, and every file inside it:
Owner: read, write, execute
Group: read, write, execute
Others: no access
docs/OVERVIEW.md:
Owner: read, write
Group: read only
Others: read only
Every shell script (every .sh file inside deployment/bin/):
Owner: read, write, execute
Group: read, execute (no write)
Others: read, execute (no write)

Deliverable: Write the chmod command(s) you would run, one rule at a time, to reach the end state described above. You may use wildcards (e.g. *.py) instead of listing files individually.

Note: Run your commands from outside the deployment/ directory (i.e. paths should start with deployment/..., not be run from inside it).

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Purge the Locked Workspace — 20/40 XP — SOLVED — deadline 2026-09-27 16:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/23ga7xbyeihy

```
Back
Purge the Locked Workspace
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Purge the Locked Workspace
Medium
2x
0/40
Time Limit: 2, Memory Limit: 128000

A corrupted draft is stuck inside a locked workspace. The draft itself is read-only, and the workspace directory has no write permission. Deleting a file requires write permission on the directory, not on the file. Delete the corrupted draft, create a clean replacement, and lock the workspace again.

Given Directory Structure:

workspace/     (Write access removed)
├── old_draft.txt   (Read-only, corrupted)
└── notes.txt

Current Permissions:

workspace/ directory: Write permission removed (chmod 555).
old_draft.txt: Read-only for everyone (chmod 444).

Tasks to Complete:

Delete workspace/old_draft.txt.
Create a new file workspace/final_draft.txt containing exactly Clean copy.
Using chmod, set the permissions of final_draft.txt to read and write for user, read for group and no permissions for others.
notes.txt must remain untouched.
Restore workspace/ permissions to read and execute for user, group and others.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Data Breach Response — 0/60 XP — NOT SOLVED — deadline 2026-09-27 16:00
Topics: Cp, Mv, Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/lkwqrg7jcc14

```
Back
Data Breach Response
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Data Breach Response
Hard
2x
0/60
Time Limit: 2, Memory Limit: 128000

You have been tasked with handling Data Breach Response, a secure directory of evidence and reports from an active security incident. Some files and directories currently have restricted permissions that you must work around without permanently weakening security.

Given Directory Structure:

breach_response/
├── evidence/
│   └── log_dump.txt
├── secure/
├── reports/
│   └── incident_summary.txt
└── classified.txt


Pre-existing Permissions:

evidence/ directory — write permission removed (chmod 555)
log_dump.txt — read-only (chmod 444)
incident_summary.txt — read-only (chmod 444)
classified.txt — no permissions (chmod 000)

Actions to Perform:

Copy a file into breach_response/:

Copy evidence/log_dump.txt to breach_response/log_dump.txt.
Move the restricted directory:
Move the entire evidence/ directory into secure/, resulting in secure/evidence/.
evidence/ currently has no write permission (555). Since moving a directory into a new parent requires updating its own metadata, you'll need to temporarily add write permission to evidence/ before moving it.
After the move, restore secure/evidence/ to permission 555.
Edit the read-only report:
Append the exact line Breach confirmed to reports/incident_summary.txt.
incident_summary.txt currently has no write permission (444), so you'll need to temporarily adjust permissions to edit it.
Restore the file permissions to 444 afterward.
Create a new report:
Create secure/forensics_report.txt containing the exact text Forensics Complete.
Set its permissions to 600.
Append to the report again:
Append the exact line Escalated to security team to reports/incident_summary.txt.
As before, temporarily adjust permissions to write, then restore incident_summary.txt to 444 afterward.

Important: Do not modify classified.txt. It must remain unchanged with permission 000.

Input
NA
Output
NA
Constraints
NA
Example
NA
```
---
## Computer Software, Compiler, Interpreter, Number Representation & Data Encoding  [Post Class]  — due 2026-09-29 18:05

### Execute a Python Script Directly — 10/20 XP — SOLVED — deadline 2026-09-29 18:05
Topics: Interpreter

URL: https://my.newtonschool.co/playground/code/zdzrhay58r5t

```
Back
Execute a Python Script Directly
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Execute a Python Script Directly
Easy
10/20
Time Limit: 2, Memory Limit: 128000
A teammate has asked you to create a Python script that can be executed directly from the terminal without typing python3 before the filename.
Create a file named hello.py that prints: Hello from Python
Configure the script so that it can be executed directly from the terminal.
Expected Result:
Running the following command:
./hello.py
should display:
Hello from Python
Input
NA
Output
Hello from Python
Constraints
The script must be named hello.py.
Example
NA
```

### Resolve the Issue with hello.py — 10/20 XP — SOLVED — deadline 2026-09-29 18:05
Topics: Interpreter

URL: https://my.newtonschool.co/playground/code/axl0qpre44oq

```
Back
Resolve the Issue with hello.py
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Resolve the Issue with hello.py
Easy
10/20
Time Limit: 2, Memory Limit: 128000
A teammate has handed over a Python script named hello.py and says:
"The script works on my machine, but I can't run it directly from the terminal on yours. Can you fix it?"

You are not allowed to modify the script itself. Investigate the problem and make the script executable so it can be run directly from the terminal. Running the following command:
./hello.py
should display:
Hello from Python
Input
NA
Output
Hello from Python
Constraints
Do not modify the contents of hello.py.
Run the script directly from the terminal using ./hello.py instead of invoking it through the Python interpreter.
Example
NA
```

### Simplify the Compilation Process — 10/20 XP — SOLVED — deadline 2026-09-29 18:05
Topics: Compiler

URL: https://my.newtonschool.co/playground/code/4k42t5ma5fc3

```
Back
Simplify the Compilation Process
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Simplify the Compilation Process
Easy
10/20
Time Limit: 2, Memory Limit: 128000
Your team frequently compiles a C program before testing it. Instead of typing the compilation command every time, your manager wants a reusable build script.
Create a shell script named build.sh that compiles hello.c into an executable named hello.
The script should be executable and should automate the build process using terminal commands only.
Expected Result
After creating the script, run both of the following commands:
./build.sh
./hello
The output should be:
Hello from C
Input
NA
Output
Hello from C
Constraints
NA
Example
NA
```
---
## Version Control, Repository, Git, Git Commands  [Post Class]  — due 2026-10-06 18:35

### Undo Incorrect Changes and Commit the Fix — 20/20 XP — SOLVED — deadline 2026-10-06 18:35
Topics: Git Commands, Git add, Git commit

URL: https://my.newtonschool.co/playground/code/bn4ab0f3usca

```
Back
Undo Incorrect Changes and Commit the Fix
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Undo Incorrect Changes and Commit the Fix
Easy
2x
20/20
Time Limit: 2, Memory Limit: 128000

You accidentally added the wrong line Wrong line to app.txt and have NOT staged it.

Undo the unstaged change using git checkout.

Then add the correct line Correct line to the end of app.txt as a new line, stage the file, and commit it with the message:

Fix app content

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### A new team member sets up a repository — 20/20 XP — SOLVED — deadline 2026-10-06 18:35
Topics: Cd, Git, Git Commands, Git init, Git add, Git commit

URL: https://my.newtonschool.co/playground/code/37kjlfh777he

```
Back
A new team member sets up a repository
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
A new team member sets up a repository
Easy
2x
20/20
Time Limit: 2, Memory Limit: 128000
You joined a new project. The folder my-app already exists with a file app.py inside it. Navigate into my-app, initialize Git, stage everything, and make the first commit with message: Project setup
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Multiple File Commits and Commit History Review — 20/20 XP — SOLVED — deadline 2026-10-06 18:35
Topics: Git Commands, Git add, Git commit, Git log

URL: https://my.newtonschool.co/playground/code/3kt2aexvwinx

```
Back
Multiple File Commits and Commit History Review
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Multiple File Commits and Commit History Review
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

Repository is already initialized.

The files header.html and footer.html already exist in the repository.

Add some content to header.html, then stage and commit your changes with the message:

Add header

Next, add some content to footer.html, then stage and commit your changes with the message:

Add footer

Finally, run:

git log --oneline

to verify that both commits appear in the commit history.

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Selective Staging with Multiple Commits and Log Review — 40/40 XP — SOLVED — deadline 2026-10-06 18:35
Topics: Git Commands, Git add, Git commit, Git log

URL: https://my.newtonschool.co/playground/code/6ljwbtbf4xcr

```
Back
Selective Staging with Multiple Commits and Log Review
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Selective Staging with Multiple Commits and Log Review
Medium
2x
0/40
Time Limit: 2, Memory Limit: 128000

A Git repository is already initialized, and both README.md and main.py already exist.

Add some content to README.md, stage only README.md, and commit it with the message:

Update readme

Then add some content to main.py, stage only main.py, and commit it with the message:

Update main

Finally, run:

git log --oneline

to view the commit history.

Input
NA
Output
NA
Constraints
NA
Example
NA
```
---
## GitHub, Remote Repository Management, GitHub Collaboration, Github Pull Requests  [Post Class]  — due 2026-10-11 17:00

### Clone and Verify Before Working — 0/20 XP — NOT SOLVED — deadline 2026-10-11 17:00
Topics: Git log, Git Pull, Git Clone, GitHub Collaboration

URL: https://my.newtonschool.co/playground/code/6582532yohso

```
Back
Clone and Verify Before Working
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Clone and Verify Before Working
Easy
0/20
Time Limit: 2, Memory Limit: 128000
Before starting work on a shared project, your process is: clone https://github.com/org/inventory-system.git, navigate into inventory-system, verify the remote is set correctly, pull any latest changes (just to be safe), and check the commit log in compact format.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Full Team Collaboration Simulation — 0/40 XP — NOT SOLVED — deadline 2026-10-11 17:00
Topics: Git add, Git commit, Git log, Git Pull, Git Push, Git Clone, GitHub Collaboration

URL: https://my.newtonschool.co/playground/code/ex8k2ivitbin

```
Back
Full Team Collaboration Simulation
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Full Team Collaboration Simulation
Medium
0/40
Time Limit: 2, Memory Limit: 128000

You're picking up a teammate's CRM project. Clone https://github.com/teamdev/crm-tool.git and cd into crm-tool. Someone may have pushed a last-minute commit right after you cloned, so run git pull to be safe.

The cloned src/contacts.js and src/deals.js are empty stub files — write some real content into each before staging them (e.g. echo "export const contacts = [];" > src/contacts.js). Do not commit until you have added content to both files.

Stage only src/contacts.js and src/deals.js — never stage src/internal-notes.js or build/output.min.js. Commit with message Add CRM core modules. The remote is already set from the clone, so just push.

Finally, run git log and git remote -v to confirm.

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Collaborative Git Workflow Challenge — 0/40 XP — NOT SOLVED — deadline 2026-10-11 17:00
Topics: GitHub, Git, Git Pull, Git Push, GitHub Collaboration

URL: https://my.newtonschool.co/playground/code/i9yx66qyanbb

```
Back
Collaborative Git Workflow Challenge
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Collaborative Git Workflow Challenge
Medium
0/40
Time Limit: 2, Memory Limit: 128000
You are working on a collaborative project in the chat-app directory. Navigate into it. A remote repository is already configured. Then pull to check if there are any changes on remote or not.  Add content Resolved message issue in client.js, then stage and commit it using the commit message: "fix: resolve message duplicate issue". Finally push your update to the remote repository.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### New Machine, Same Project — 0/40 XP — NOT SOLVED — deadline 2026-10-11 17:00
Topics: Git add, Git Pull, GitHub Collaboration

URL: https://my.newtonschool.co/playground/code/9it7iqcu91y9

```
Back
New Machine, Same Project
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
New Machine, Same Project
Medium
0/40
Time Limit: 2, Memory Limit: 128000

You just got a new laptop. Clone https://github.com/yourname/recipe-app.git. Navigate into recipe-app. Pull (to be safe).

Add some content to app.js, db.js, and helpers/format.js. Do not commit until you have made changes to all three files. Then stage all three — but NOT helpers/debug.js.

Commit with message Resume recipe app development. Push back.

Input
NA
Output
NA
Constraints
NA
Example
NA
```
---
## SVYASA - S&AI Practice  [Other]  — due 2026-12-31 00:00

### Reorganizing the HR Folder Structure — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: CLI File & Directory Management, Cp, Mv, Rm

URL: https://my.newtonschool.co/playground/code/u9neqiv40vde

```
Back
Reorganizing the HR Folder Structure
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Reorganizing the HR Folder Structure
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

Kartik has just joined a new company as a data analyst. However, on his first day, his manager asks him to help the HR team organise their folder structure. Kartik’s task is to reorganise the HR team's existing folder hierarchy according to the instructions provided by the manager.

Kartik must work with various terminal commands to complete this task.

Kartik begins with the following folder structure inside the 

home directory:

home

    ├── employees/

    │    ├── john_doe/

    │    │    ├── profile.txt

    │    │    └── contract.txt

    │    ├── jane_smith/

    │    │    ├── profile.txt

    │    │    └── contract.txt

    ├── temp_documents/

    │    └── guidelines.txt

    ├── management/

    │    └── confidential.txt

    ├── to_process/

    └── completed/

 

Kartik's manager gives him the following tasks to reorganise the structure:

The files inside the employees/ directory are not named properly. The manager wants Kartik to rename the contract.txt files to match the employee's name for better organization. Rename john_doe/contract.txt to john_doe/john_contract.txt. Rename jane_smith/contract.txt to jane_smith/jane_contract.txt.
There is no backup folder in the current HR structure. Kartik needs to create a backup/ directory right under the home/ folder and copy the entire management/ folder (along with its files) into this new backup directory.
Kartik needs to create a file in the to_process/ directory that contains some text for the team to process later. Create a file named tasks.txt inside the to_process/ folder and add the following content: Organize all employee records and ensure contracts are securely stored.
The management/confidential.txt file contains sensitive information, and it should only be accessed by the owner (the HR manager). Kartik needs to change the file permissions so that only the owner can read and write to it, and no other users should have access to it.
The temp_documents/ folder is no longer needed. Kartik needs to remove the entire folder and its contents. 
 
Help Kartik shine in his new job by completing these tasks for him.
Input
NA
Output
NA
Example
NA
```

### ClientVault Reorganization — 0/60 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Cp, Chmod

URL: https://my.newtonschool.co/playground/code/hjqj3xta292m

```
Back
ClientVault Reorganization
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
ClientVault Reorganization
Hard
2x
0/60
Time Limit: 2, Memory Limit: 128000

You have been tasked with reorganizing ClientVault, a secure directory holding sensitive client files. The folder structure is already in place, but some files and directories currently have restricted permissions. Your job is to copy, move, and update files while respecting (and correctly restoring) those permissions.

Given Directory Structure:

client_vault/
├── originals/
│   └── contract.pdf
├── staging/
├── audit/
│   └── access.log
└── notes.txt

Pre-existing Permissions:

originals/ directory — write permission removed (chmod 555)
contract.pdf — read-only (chmod 444)
access.log — write permission removed (chmod 444)
notes.txt — read permission removed (chmod 000)

Actions to Perform:

Copy a file into client_vault/:

Copy contract.pdf from originals/ into client_vault/ (result: client_vault/contract.pdf).
Move a restricted directory:
Move the entire originals/ directory into staging/ (result: staging/originals/, containing contract.pdf).
originals/ currently has no write permission (555). Since moving a directory into a new parent requires updating its own metadata, you'll need to temporarily add write permission to originals/ before moving it.
After the move, staging/originals/ must be restored to 555.
Edit a read-only log file:
Append the exact line Client data reviewed to audit/access.log.
access.log currently has no write permission (444), so you'll need to temporarily adjust permissions to edit it.
After appending, restore access.log to 444.
Create a new report file:
Inside staging/, create a new file named staging_report.txt.
Its content should be exactly: Staging Review Complete.
Set its permissions to 600 (owner: read+write; group: no access; others: no access).
Append to the log file a second time:
Append the exact line Second review complete to audit/access.log.
As before, temporarily adjust permissions to write, then restore access.log to 444 afterward.

Important: notes.txt is not part of any task above. Do not touch it — at the end of the task it must still be exactly as it started, with permissions 000.

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Directory Manager — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/1kkb4fj7k0f5

```
Back
Directory Manager
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Directory Manager
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000
You have been assigned the task of setting up the directory structure for a new project. The project requires the following directory hierarchy:

project/
├── src/
│   ├── components/
│   ├── services/
│   └── utils/
├── tests/
│   ├── unit/
│   └── integration/
└── docs/
    ├── api/
    └── guides/
 

Your task is to create this entire directory structure using a single mkdir command. Ensure that all directories are created in one go, without needing to navigate into each parent directory.

Example : To create multiple nested directories, you can utilise this command format 
mkdir -p /var/www/html/project/{css,js,images}
This piece of code created the following directory structure : 

/var/www/html/project/
                    ├── css
                    ├── js
                    └── images

Write the mkdir command you would use to accomplish this.

Input
NA
Output
NA
Example
NA
```

### Directory cleaning — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Rm, CLI Flags, Options & Operators

URL: https://my.newtonschool.co/playground/code/aiuy5ec8md92

```
Back
Directory cleaning
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Directory cleaning
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

You are managing a project directory that has accumulated unnecessary files and directories over time. Your task is to clean up the directory by removing specific files and folders that are no longer needed.

Given the following directory structure:

project/
├── src/
│   ├── old_components/
│   ├── temp. txt
│   └── services/
├── tests/
│   ├── old_tests/
│   ├── unit/
│   └── integration/
├── docs/
│   ├── old_api/
│   ├── api/
│   └── guides/
└── README. md
 

You need to remove the following:

The entire old_components directory inside src/.
The temp. txt file inside src/.
The entire old_tests directory inside tests/.
The entire old_api directory inside docs/.

Write the rm command(s) you would use to accomplish this task.

Input
NA
Output
NA
Example
NA
```

### Important files — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: CLI File & Directory Management, Cp

URL: https://my.newtonschool.co/playground/code/7refpfus5inr

```
Back
Important files
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Important files
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000
You are working on a project where you need to back up important files to a separate backup directory. The project directory has the following structure:

project/
├── src/
│   ├── main.py
│   ├── utils.py
│   └── config/
│       └── settings.py
├── data/
│   ├── input.csv
│   └── output.csv
├── docs/
│   ├── README.md
│   └── requirements.txt
└── scripts/
    ├── deploy.sh
    └── test.sh

Your task is to:

Copy the entire src/ directory (including all its contents) to a backup directory named backup/ (backup directory will be created outside project directory).
Copy the docs/README.md file and scripts/deploy.sh file to the backup/ directory.
Ensure that the directory structure in backup/ mirrors the structure in project/, so the backup/ directory should look like this after the operation:
backup/
├── src/
│   ├── main.py
│   ├── utils.py
│   └── config/
│       └── settings.py
├── README.md
└── deploy.sh

Write the cp commands you would use to accomplish this task.

Note:
Make sure you are outside the backup directory before running the code.
Input
NA
Output
NA
Example
NA
```

### The Internship Application Folder — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Command-Line Interface (CLI)

URL: https://my.newtonschool.co/playground/code/6pvubbu0attm

```
Back
The Internship Application Folder
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
The Internship Application Folder
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

You are preparing to apply for a summer internship. Your resume and application documents are scattered across the current directory, making them difficult to manage.

Organize your application documents into a dedicated folder while keeping the original resume in the current directory.

Tasks:

Perform the following steps in the current directory:

Create a directory named Internship.
Copy resume.pdf into Internship, keeping the original file unchanged in the current directory.
Move cover_letter.txt into Internship.
Rename hobbies.txt to personal_interests.txt in the current directory.
Create an empty file named checklist.txt inside Internship.

Starting Structure:
├── resume.pdf
├── cover_letter.txt
└── hobbies.txt


Expected Structure:
├── resume.pdf
├── personal_interests.txt
└── Internship/
    ├── resume.pdf
    ├── cover_letter.txt
    └── checklist.txt


Requirements:
The original resume.pdf must remain in the current directory, and its copy must exist inside Internship.
cover_letter.txt must exist only inside Internship.
hobbies.txt must be renamed to personal_interests.txt, preserving its contents.
checklist.txt must be an empty file.
Do not delete or modify the contents of the original files.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Giving Permissions — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: CLI Permission Management, Command-Line Interface (CLI), Chmod

URL: https://my.newtonschool.co/playground/code/ajn5zihq8dhr

```
Back
Giving Permissions
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Giving Permissions
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

You are working on a shared project where multiple users have different roles and permissions. You need to set the correct permissions on various files and directories to ensure that they are accessed only as intended.

The project directory structure is as follows:

project/
├── src/
│   ├── main.py
│   ├── utils.py
│   └── config.py
├── data/
│   ├── input_data.csv
│   └── output_data.csv
├── docs/
│   └── README.md
└── scripts/
    ├── run.sh
    ├── deploy.sh
    └── test.sh

 

Your tasks are:

Ensure that all Python files in the src/ directory (.py files) are executable only by the file owner. To play it safe, also provide read and write permissions for the owner.
Make the data/ directory and its contents are readable, writable, and executable by the owner and the group, but not accessible by others.
Make README.md readable by everyone but writable only by the owner.
Make all the script files in the scripts/ directory (.sh files) readable and executable by everyone but writable only by the owner.

Write the chmod commands you would use to accomplish these tasks.


Note:
Make sure that you are outside the project directory before running the code.

Input
NA
Output
NA
Example
NA
```

### The Missing Project Credentials — 0/40 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Command-Line Interface (CLI)

URL: https://my.newtonschool.co/playground/code/hy35jexzlhnf

```
Back
The Missing Project Credentials
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
The Missing Project Credentials
Medium
2x
0/40
Time Limit: 2, Memory Limit: 128000

You are setting up a web application for a college event. The application cannot connect to its database because the required database credentials are missing from the output file.

Your teammate tells you:

"The database password is stored in a hidden file somewhere inside the EventApp project. Find the file containing the database password and copy its contents into a new file in the project directory."

For example, if the hidden file contains:

DB_PASSWORD=EvT_x9Kp!7m 

The output file should contain the same line:

DB_PASSWORD=EvT_x9Kp!7m 

The EventApp directory already exists and contains multiple files and subdirectories. The credentials file is hidden and may be located inside a nested directory.

Note: The DB_PASSWORD value in the hidden credentials file is dynamically generated and may differ across test cases. Do not hardcode the password.

Tasks:


Perform the following steps:

Navigate into the EventApp directory and inspect its contents, including hidden files and subdirectories.
Locate and inspect the hidden credentials file containing the DB_PASSWORD entry.
Create a file named db_password.txt directly inside EventApp, containing the complete DB_PASSWORD entry (key and its value) exactly as it appears in the source file.
Requirements:

The password must be retrieved dynamically from the existing credentials file.
Do not hardcode the example password.
Do not modify or delete any existing files.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Project Cleanup & Backup — 0/60 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Command-Line Interface (CLI)

URL: https://my.newtonschool.co/playground/code/3zr8ema6bu2t

```
Back
Project Cleanup & Backup
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Project Cleanup & Backup
Hard
2x
0/60
Time Limit: 2, Memory Limit: 128000

You are organizing a project directory before submission. The Project directory contains source code, documentation, assets, temporary files, and a hidden configuration directory.

Your task is to create a backup of the required files, organize the documentation, and clean up the project while preserving the specified original files.

Initial Directory Structure:
Project/
├── src/
│   ├── app.py
│   └── old_app.py
├── docs/
│   ├── setup.txt
│   └── usage.txt
├── assets/
│   └── logo.png
├── draft.txt
├── temp.txt
└── .config/
    └── version.txt

Tasks:

Perform the following steps inside the Project directory:

Create an empty file named index.txt in the Project directory.
Create a directory named Backup and copy the entire src directory into it, preserving both files and their contents.
Move logo.png from assets into Backup.
Inspect the hidden files and directories inside Project. Locate the hidden configuration directory, find version.txt inside it, and copy the file into the root Project directory.
Rename draft.txt to README.txt and move it into Backup.
Combine the contents of docs/setup.txt and docs/usage.txt, in that order, into a file documentation.txt inside Backup folder. Preserve the contents of both files.
Append Backup completed as a new line at the end of Backup/documentation.txt.
Delete old_app.py from the original src directory and delete temp.txt.
Remove the assets and docs directories after handling their contents.
Create an empty file named backup.log inside Backup folder.

Expected Directory Structure:
Project/
├── index.txt
├── version.txt
├── src/
│   └── app.py
├── .config/
│   └── version.txt
└── Backup/
    ├── src/
    │   ├── app.py
    │   └── old_app.py
    ├── logo.png
    ├── README.txt
    ├── documentation.txt
    └── backup.log

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### The Daily Study Tracker — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Command-Line Interface (CLI)

URL: https://my.newtonschool.co/playground/code/ge5mztr0qaz1

```
Back
The Daily Study Tracker
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
The Daily Study Tracker
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

You are maintaining a daily study tracker for your Systems & AI Essentials course. Your current directory contains two files: study.txt, which stores your completed study sessions, and temp.txt, which contains your latest study entries.

Combine the new entries with your existing tracker, remove the temporary file, and organize the tracker into a separate directory.

Tasks:

Perform the following steps in the current directory:

Append the contents of temp.txt into study.txt, preserving the existing entries.
Delete temp.txt after appending its contents.
Create a directory named StudyNotes.
Move study.txt into the StudyNotes directory.

Initial Directory Structure:
├── study.txt
└── temp.txt
Expected Directory Structure:
└── StudyNotes/
    └── study.txt
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Create a Private Diary — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/8ccpzg9bgesh

```
Back
Create a Private Diary
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Create a Private Diary
Easy
10/20
Time Limit: 2, Memory Limit: 128000

You want a personal space on a shared machine where nobody else can read your notes. You will create the file yourself and lock it down using chmod.

Scenario:

There is no existing structure. You must build everything from scratch in your current directory.

Tasks to Complete:

Create a directory called personal_space.
Inside it, create a file called diary.txt containing exactly the text Top Secret Entry.
Using chmod, set the permissions of diary.txt so that only the owner can read and write it. Group and others must have no permissions at all.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Archiving a Release Directory — 0/40 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Command-Line Interface (CLI), Mkdir, Cp, Mv, Rm

URL: https://my.newtonschool.co/playground/code/2i80v5xjienl

```
Back
Archiving a Release Directory
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Archiving a Release Directory
Medium
2x
40/40
Time Limit: 2, Memory Limit: 128000

You are given the following directory structure:

release/
├── app.js
├── config.json
└── README.md

Requirements
Create a directory named archive.
Copy the entire release directory into archive.
Rename the copied directory from release to release_v1.
Remove the original release directory.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Organize and Review Study Notes — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Command-Line Interface (CLI), Cat

URL: https://my.newtonschool.co/playground/code/06s0kttczaaf

```
Back
Organize and Review Study Notes
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Organize and Review Study Notes
Easy
2x
20/20
Time Limit: 2, Memory Limit: 128000

You want to organize your study notes for different subjects and quickly review them from the terminal.

notes/
├── linux/
│ └── notes.txt
├── git/
│ └── notes.txt
└── javascript/
    └── notes.txt

Task
Add a heading to each notes.txt file:
Linux Notes in linux/notes.txt
Git Notes in git/notes.txt
JavaScript Notes in javascript/notes.txt
Append the content of all notes files in notes/final.txt.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Project Treasure Hunt — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: Touch, CLI File & Directory Management, Mkdir

URL: https://my.newtonschool.co/playground/code/ay3epjwefy0v

```
Back
Project Treasure Hunt
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Project Treasure Hunt
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000
You receive a mysterious envelope containing an old map and a cryptic note hinting at buried treasures. Following the map leads you to a computer terminal, where you must navigate a directory to uncover the next clue.

Folder structure: 

home/user/treasure_hunt
├── clues
│   ├── first_clue.txt
│   └── second_clue.txt
├── history
│   ├── year_2000
│   │   └── event.txt
│   └── year_1990
└── notes
    └── secrets.txt
 
Task Instructions:
Navigate to the treasure_hunt directory located inside the user directory in the home directory.
Inside the history folder, create a new directory named year_1980.
Inside the clues folder, create a new empty text file named third_clue.txt.
Inside the notes folder, create two new empty text files: reminder.txt and next_step.txt.
Use relevant terminal-based commands to complete the tasks.
 

Note:

Get rid of all the debugging code at last to have the test cases passed.

 
Input
NA
Output
NA
Example
NA
```

### ProjectNST — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: CLI File & Directory Management

URL: https://my.newtonschool.co/playground/code/2zj9bqg1m4u4

```
Back
ProjectNST
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
ProjectNST
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

You have just joined a new software development team, and your first task is to add a new project called Capstone_Project to the workspace ProjectNST.

The existing folder structure is:

ProjectNST
│
├── Dev_Project
│
├── Portfolio
│
└── WindowSwap
    └── README.txt


The lead developer gives you the following responsibilities:

Add the Project: Start by creating a directory named Capstone_Project for the project inside the ProjectNST workspace so all files can be neatly stored.
Provide Documentation: The team requires every project folder to include a README.txt file with a brief description.
Include README.txt file inside each project -> Portfolio, Dev_Project, and Capstone_Project. The text inside README.txt must be according to the project, in the given format, ProjectName Documentation. Eg: for Project Portfolio, README.txt file must contain Portfolio Documentation.
Input
NA
Output
NA
Example
NA
```

### Library Organization — 0/20 XP — NOT SOLVED — deadline 2026-12-31 00:00
Topics: CLI File & Directory Management, Mv

URL: https://my.newtonschool.co/playground/code/61flprigwbhn

```
Back
Library Organization
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Library Organization
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

In a futuristic society, the Digital Library of Alexandria holds vast collections of ancient and modern knowledge. However, due to some recent changes, the library’s digital archive has become somewhat disorganized. As a digital librarian, your task is to reorganize some key files and collections, move entire sections and ensure everything is in the right place.

 
Current Folder Structure:
 

DigitalLibrary
├── Ancient
│   ├── scrolls.txt
│   ├── manuscripts.txt
├── Modern
│   ├── novels.txt
│   ├── essays.txt
│   ├── plays.txt
├── TemporaryFiles
│   ├── backup_novels.txt
│   ├── backup_plays.txt

 
Note: You are currently right outside the DigitalLibrary folder.
Tasks:
Copy Files:
Create a new folder called AncientTexts right inside the DigitalLibrary folder and copy the file scrolls.txt from the Ancient folder into the AncientTexts folder.
Move a Folder:
Create a new folder called Archives right inside the DigitalLibrary folder and move the entire Modern folder inside the Archives folder so that all modern literature is stored under the Archives folder.
Organize Backup Files:
Move the files backup_novels.txt and backup_plays.txt from TemporaryFiles inside the Modern folder that you just moved inside the Archives folder.

Final Folder Structure:

DigitalLibrary
├── Ancient
│   ├── scrolls.txt
│   ├── manuscripts.txt
├── AncientTexts
│   ├── scrolls.txt
├── Archives
│   ├── Modern
│   │   ├── novels.txt
│   │   ├── essays.txt
│   │   ├── plays.txt
│   │   ├── plays.txt
│   │   ├── backup_novels.txt
│   │   ├── backup_plays.txt
├── TemporaryFiles
Input
NA
Output
NA
Example
NA
```
---
## Mandatory - Practice Questions  [Other]  — due 2027-01-30 18:00

### Recovering a Lost API Key — 0/20 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Cd, Ls, Cat

URL: https://my.newtonschool.co/playground/code/4kouv5rmrisj

```
Back
Recovering a Lost API Key
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Recovering a Lost API Key
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

You have joined a team that is testing a weather application. The application keeps failing with the following error:

Error: API_KEY not found


A senior developer tells you:

"The API key is already stored somewhere in the project directory. We usually keep sensitive configuration in hidden files. Find the API key and save it to a file named api_key.txt."
Task:
Explore the projects directory.
Find the hidden file that contains the API key.
Create a file named api_key.txt in the projects directory containing only the API key value.

Example Project Structure:
projects/
├── app.js
├── README.md
├── logs/
├── src/
└── .env


Requirements:
Do not modify the hidden file containing the API key.
The file api_key.txt must contain only the API key value.
No extra text, spaces, or additional lines should be added.

Expected File Content (api_key.txt):
<API_KEY_VALUE>

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Inspect Repository Status and Commit a Specific File — 0/20 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Git add, Git commit, Git status

URL: https://my.newtonschool.co/playground/code/ko1aj9k1nc6a

```
Back
Inspect Repository Status and Commit a Specific File
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Inspect Repository Status and Commit a Specific File
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

Repo has two files: main.py (modified) and README.md (unmodified). Run git status first to inspect. Then stage only main.py and commit with message: Update main script.

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Cleanup and Organize Documents — 0/60 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Cat, Cp, Mv, Rm

URL: https://my.newtonschool.co/playground/code/vt9bxz5qhrjy

```
Back
Cleanup and Organize Documents
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Cleanup and Organize Documents
Hard
2x
0/60
Time Limit: 2, Memory Limit: 128000

You have a directory Office with the following structure:

Office/
├── Reports/
│   ├── jan.txt
│   ├── feb.txt
│   └── mar.txt
├── old_notes.txt
└── draft.txt

Perform the following tasks :

Create a new empty file named Office/index.txt.
Delete the file old_notes.txt from Office — it is outdated.
Rename draft.txt to final.txt inside Office.
Delete the file Office/Reports/mar.txt — it's no longer required.
Create a new folder named Office/Reports_Backup, and inside it, combine the contents of Office/Reports/jan.txt and Office/Reports/feb.txt into a new file named q1_summary.txt.
Create an empty file named Office/Reports_Backup/backup_created.txt to mark the backup.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Updating an Existing Application Log — 0/20 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Command-Line Interface (CLI), Essential Commands (ls, mkdir, cat, echo)

URL: https://my.newtonschool.co/playground/code/to5dtb3jixoc

```
Back
Updating an Existing Application Log
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Updating an Existing Application Log
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

You are helping your team debug a web application. The application already maintains a log file named app.log that contains important startup information.

Before you begin, the file already contains:

Server Initializing...
Server Started


A user has just successfully logged in, and you need to record this event in the log file.

Task:

Add the following line to the end of app.log:

User login successful 

Requirements:
Do not delete or modify the existing contents of app.log.
Append the new log entry to the file.

Expected File Content:
Server Initializing...
Server Started 
User login successful 

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Banking Records Under Lock — 0/60 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/9ovqf4iihb88

```
Back
Banking Records Under Lock
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Banking Records Under Lock
Hard
2x
0/60
Time Limit: 2, Memory Limit: 128000

You are an internal auditor at a national bank. The first-quarter ledgers must be reviewed, archived, consolidated into a secure vault, and temporary files cleaned up. The bank's file system is locked down: some directories cannot be written to, and the vault cannot even be entered. You must work out exactly which permissions each task needs. Some tasks need no permission changes at all, and some need a temporary change to a directory. Every temporary change must be reverted, and every final permission must match the requirements exactly.

Given Directory Structure:

bank/
├── ledgers/
│   ├── jan.txt
│   ├── feb.txt
│   └── mar.txt
├── vault/
├── reports/
├── tmp/
│   ├── a.tmp
│   ├── b.tmp
│   ├── c.tmp
│   └── session.log
└── master.key

Pre-existing Permissions:

ledgers/: read and execute for owner, group and others; no one has write permission.
jan.txt, feb.txt, mar.txt: read-only for owner, group and others.
vault/: no permissions for anyone.
reports/: read, write and execute for owner; read and execute for group and others.
tmp/: read and execute for owner, group and others; no one has write permission.
a.tmp, b.tmp, c.tmp, session.log: read and write for owner; read-only for group and others.
master.key: no permissions for anyone.

Actions to Perform:

Copy February's ledger for review.

Copy ledgers/feb.txt into reports/ as feb_copy.txt.
A copied file does not automatically carry the original's permissions. Set feb_copy.txt to read and write for owner, read-only for group, and no permissions for others.
Annotate February's ledger.
Append the exact line FEB-28 Reviewed by auditor to ledgers/feb.txt.
After appending, feb.txt must be read-only for owner, group and others again.
Update the session log.
Append the exact line Audit session opened to tmp/session.log.
Create the archive.
Inside reports/, create the nested path archive/2026/.
The 2026/ directory must have read, write and execute for owner, read and execute for group, and no permissions for others.
Archive the review copy.
Move reports/feb_copy.txt into reports/archive/2026/ and rename it to feb_review.txt in the same command.
Tag and secure the reports.
Create an empty hidden file reports/.audit_tag with no permissions for owner, group or others.
Set reports/ to read, write and execute for owner, read and execute for group, and no permissions for others.
Consolidate the ledgers in the vault.
Create vault/q1_ledger.txt containing the full contents of jan.txt, feb.txt and mar.txt, in exactly that order. The q1_ledger must be readable only by the owner, with no write permission for anyone.
At the end, vault/ must have no permissions for anyone, exactly as it was at the start.
Purge temporary files.
Delete all three .tmp files inside tmp/ using a single wildcard command. session.log must not be deleted.
At the end, tmp/ must have exactly its original permissions.

Important:

master.key must not be touched. At the end it must still have its original content and no permissions for anyone.
feb_review.txt must not contain the line added in step 2, but q1_ledger.txt must contain it.
session.log must still exist with its original permissions, containing its original content plus the line from step 3.
jan.txt and mar.txt must remain unchanged, with their original content and permissions.
Order matters. Read all the actions before you begin.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Multiple File Commits and Commit History Review — 0/20 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Git Commands, Git add, Git commit, Git log

URL: https://my.newtonschool.co/playground/code/3kt2aexvwinx

```
Back
Multiple File Commits and Commit History Review
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Multiple File Commits and Commit History Review
Easy
2x
0/20
Time Limit: 2, Memory Limit: 128000

Repository is already initialized.

The files header.html and footer.html already exist in the repository.

Add some content to header.html, then stage and commit your changes with the message:

Add header

Next, add some content to footer.html, then stage and commit your changes with the message:

Add footer

Finally, run:

git log --oneline

to verify that both commits appear in the commit history.

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Selective Staging with Multiple Commits and Log Review — 0/40 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Git Commands, Git add, Git commit, Git log

URL: https://my.newtonschool.co/playground/code/6ljwbtbf4xcr

```
Back
Selective Staging with Multiple Commits and Log Review
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Selective Staging with Multiple Commits and Log Review
Medium
2x
0/40
Time Limit: 2, Memory Limit: 128000

A Git repository is already initialized, and both README.md and main.py already exist.

Add some content to README.md, stage only README.md, and commit it with the message:

Update readme

Then add some content to main.py, stage only main.py, and commit it with the message:

Update main

Finally, run:

git log --oneline

to view the commit history.

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Three Levels of Access — 0/20 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/74dyuwbfq6i4

```
Back
Three Levels of Access
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Three Levels of Access
Easy
10/20
Time Limit: 2, Memory Limit: 128000

After a security review, three files in the clearance directory were found with wide-open permissions. Each file must be tightened to a different clearance level using numeric chmod.

Given Directory Structure:

clearance/
├── public.txt     
├── team.txt      
└── private.txt   

Current Permissions:

All three files: full permissions for everyone.

Tasks to Complete:

public.txt: owner can read and write; group and others can only read.
team.txt: owner can read and write; group can only read; others get nothing.
private.txt: owner can read and write; group and others get nothing.
Do not modify the content of any file.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Purge the Locked Workspace — 0/40 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/23ga7xbyeihy

```
Back
Purge the Locked Workspace
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Purge the Locked Workspace
Medium
2x
0/40
Time Limit: 2, Memory Limit: 128000

A corrupted draft is stuck inside a locked workspace. The draft itself is read-only, and the workspace directory has no write permission. Deleting a file requires write permission on the directory, not on the file. Delete the corrupted draft, create a clean replacement, and lock the workspace again.

Given Directory Structure:

workspace/     (Write access removed)
├── old_draft.txt   (Read-only, corrupted)
└── notes.txt

Current Permissions:

workspace/ directory: Write permission removed (chmod 555).
old_draft.txt: Read-only for everyone (chmod 444).

Tasks to Complete:

Delete workspace/old_draft.txt.
Create a new file workspace/final_draft.txt containing exactly Clean copy.
Using chmod, set the permissions of final_draft.txt to read and write for user, read for group and no permissions for others.
notes.txt must remain untouched.
Restore workspace/ permissions to read and execute for user, group and others.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Deployment Project Permissions — 0/40 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/33n9tt9kovhd

```
Back
Deployment Project Permissions
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Deployment Project Permissions
Medium
20/40
Time Limit: 2, Memory Limit: 128000

You are preparing a shared deployment project where different roles (developers, CI system, general viewers) need different levels of access to different parts of the codebase. You need to set the correct permissions on each part of the project so it is accessed only as intended.

Given Directory Structure:

deployment/
├── app/
│   ├── server.py
│   ├── handler.py
│   └── settings.py
├── datasets/
│   ├── train.csv
│   └── test.csv
├── docs/
│   └── OVERVIEW.md
└── bin/
    ├── start.sh
    ├── stop.sh
    └── healthcheck.sh

All files currently have default permissions (644 for files, 755 for directories). Apply the following rules:

Python source files (every .py file inside deployment/app/):

Owner: read, write, execute
Group: no access
Others: no access
The datasets/ directory, and every file inside it:
Owner: read, write, execute
Group: read, write, execute
Others: no access
docs/OVERVIEW.md:
Owner: read, write
Group: read only
Others: read only
Every shell script (every .sh file inside deployment/bin/):
Owner: read, write, execute
Group: read, execute (no write)
Others: read, execute (no write)

Deliverable: Write the chmod command(s) you would run, one rule at a time, to reach the end state described above. You may use wildcards (e.g. *.py) instead of listing files individually.

Note: Run your commands from outside the deployment/ directory (i.e. paths should start with deployment/..., not be run from inside it).

Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Audit Trail Setup — 0/20 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/eu8eoa3cnihv

```
Back
Audit Trail Setup
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Audit Trail Setup
Easy
10/20
Time Limit: 2, Memory Limit: 128000

You are given the following folder structure inside the current directory.

audit_trail/
└── access.log

Perform the following operations:

Change the permissions of the audit_trail/ directory so that the owner has full access (read, write, execute), the group has read and execute only, and others have no access at all.
Inside audit_trail/, create a new file named summary.txt containing the exact text Audit Summary Generated.
Set the permissions of summary.txt so that the owner can read and write, the group can only read, and others have no access.
Input
NA
Output
NA
Constraints
NA
Example
NA
```

### Data Breach Response — 0/60 XP — NOT SOLVED — deadline 2027-01-30 18:00
Topics: Cp, Mv, Chmod, File Ownership and Permissions

URL: https://my.newtonschool.co/playground/code/lkwqrg7jcc14

```
Back
Data Breach Response
Total XP
5,795
Leaderboard Unlocked
Rank Increased
Run
Submit
QUESTION
Data Breach Response
Hard
2x
0/60
Time Limit: 2, Memory Limit: 128000

You have been tasked with handling Data Breach Response, a secure directory of evidence and reports from an active security incident. Some files and directories currently have restricted permissions that you must work around without permanently weakening security.

Given Directory Structure:

breach_response/
├── evidence/
│   └── log_dump.txt
├── secure/
├── reports/
│   └── incident_summary.txt
└── classified.txt


Pre-existing Permissions:

evidence/ directory — write permission removed (chmod 555)
log_dump.txt — read-only (chmod 444)
incident_summary.txt — read-only (chmod 444)
classified.txt — no permissions (chmod 000)

Actions to Perform:

Copy a file into breach_response/:

Copy evidence/log_dump.txt to breach_response/log_dump.txt.
Move the restricted directory:
Move the entire evidence/ directory into secure/, resulting in secure/evidence/.
evidence/ currently has no write permission (555). Since moving a directory into a new parent requires updating its own metadata, you'll need to temporarily add write permission to evidence/ before moving it.
After the move, restore secure/evidence/ to permission 555.
Edit the read-only report:
Append the exact line Breach confirmed to reports/incident_summary.txt.
incident_summary.txt currently has no write permission (444), so you'll need to temporarily adjust permissions to edit it.
Restore the file permissions to 444 afterward.
Create a new report:
Create secure/forensics_report.txt containing the exact text Forensics Complete.
Set its permissions to 600.
Append to the report again:
Append the exact line Escalated to security team to reports/incident_summary.txt.
As before, temporarily adjust permissions to write, then restore incident_summary.txt to 444 afterward.

Important: Do not modify classified.txt. It must remain unchanged with permission 000.

Input
NA
Output
NA
Constraints
NA
Example
NA
```

---
## Quizzes / quiz contests (11) — schedules only
(Portal shows quiz QUESTIONS only after starting a test — starting tests is forbidden, so no question text exists for these.)
- Course and Instructor Introduction, Computer Systems - Revision — 2026-09-01 17:00 -> 2026-09-06 17:00 — xp 32/38
- Computer Hardware, Computer Software, Operating System - Revision — 2026-09-03 18:35 -> 2026-09-08 18:35 — xp 0/26
- Command-Line Interface (CLI), Terminal - Revision — 2026-09-08 16:05 -> 2026-09-13 16:05 — xp 16/16
- CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ... - Revision — 2026-09-10 18:05 -> 2026-09-15 18:05 — xp 28/26
- Operating System, Operating System Architecture, Device Management, Process Mana ... - Revision — 2026-09-16 13:00 -> 2026-09-21 13:00 — xp 0/34
- Operating System, Filesystem Management, File Ownership and Permissions, PATH, O ... - Revision — 2026-09-22 16:00 -> 2026-09-27 16:00 — xp 0/24
- Computer Software, Compiler, Interpreter, Number Representation & Data Encoding - Revision — 2026-09-24 18:05 -> 2026-09-29 18:05 — xp 0/48
- Number Systems, Decimal Number System, Binary Number System, Hexadecimal Number  ... - Revision — 2026-09-29 17:35 -> 2026-10-04 17:35 — xp 13/30
- Version Control, Repository, Git, Git Commands - Revision — 2026-10-01 18:35 -> 2026-10-06 18:35 — xp 24/24
- GitHub, Remote Repository Management, GitHub Collaboration, Github Pull Requests - Revision — 2026-10-06 17:00 -> 2026-10-11 17:00 — xp 0/34
- Computer Networks, LAN, MAN, WAN, DNS, Packet Switching, Network Protocols, Rout ... - Revision — 2026-10-19 16:00 -> 2026-10-24 16:00 — xp 0/22

---
## Questions below lecture videos (per lecture)

### 00rpem1820ri  [eq7lnkj6lo7s]
=== Assignments tab (quiz cards + in-class + post-class sections) ===
Assignments1
Lecture Notes
QUIZ
Version Control, Repository, Git, Git Commands - Revision
Attempt duration - Oct 1st 2026 6:35 pm to Oct 6th 2026 6:35 pm
Attempted on Oct 5th 2026 1:51 pm
View Solutions
In class assignments
This section contains the assignments and questions solved in the class
No in-class assignments for this lecture
Post class assignments
This section contains the assignments related to the topics covered in this lecture
Q1. Undo Incorrect Changes and Commit the Fixeasy

You accidentally added the wrong line Wrong line to app.txt and have NOT staged it.

Undo the unstaged change using git checkout.

Then add the correct line Correct line to the end of app.txt as a new line, stage the file, and commit it with the message:

Fix app content

Read More
Your Solution
Q2. A new team member sets up a repositoryeasy
You joined a new project. The folder my-app already exists with a file app.py inside it. Navigate into my-app, initialize Git, stage everything, and make the first commit with message: Project setupRead More
Your Solution
Q3. Multiple File Commits and Commit History Revieweasy

Repository is already initialized.

The files header.html and footer.html already exist in the repository.

Add some content to header.html, then stage and commit your changes with the message:

Add header

Next, add some content to footer.html, then stage and commit your changes with the message:

Add footer

Finally, run:

git log --oneline

to verify that both commits appear in the commit history.

Read More
Your Solution
Q4. Selective Staging with Multiple Commits and Log Reviewmedium

A Git repository is already initialized, and both README.md and main.py already exist.

Add some content to README.md, stage only README.md, and commit it with the message:

Update readme

Then add some content to main.py, stage only main.py, and commit it with the message:

Update main

Finally, run:

git log --oneline

to view the commit history.

Read More
Your Solution

### 4mq9i71pn3lf  [eq7lnkj6lo7s]
=== Assignments tab (quiz cards + in-class + post-class sections) ===
Assignments1
In-class Quizzes
3
Lecture Notes
QUIZ
Computer Software, Compiler, Interpreter, Number Representation & Data Encoding - Revision
Attempt duration - Sep 24th 2026 6:05 pm to Sep 29th 2026 6:05 pm
Your submission will be marked as “LATE SUBMISSION” because you have crossed the given submission deadline
Attempt Now
In class assignments
This section contains the assignments and questions solved in the class
No in-class assignments for this lecture
Post class assignments
This section contains the assignments related to the topics covered in this lecture
Q1. Execute a Python Script Directlyeasy
A teammate has asked you to create a Python script that can be executed directly from the terminal without typing python3 before the filename.
Create a file named hello.py that prints: Hello from Python
Configure the script so that it can be executed directly from the terminal.
Expected Result:
Running the following command:
./hello.py
should display:
Hello from PythonRead More
Your Solution
Q2. Resolve the Issue with hello.pyeasy
A teammate has handed over a Python script named hello.py and says:
"The script works on my machine, but I can't run it directly from the terminal on yours. Can you fix it?"

You are not allowed to modify the script itself. Investigate the problem and make the script executable so it can be run directly from the terminal. Running the following command:
./hello.py
should display:
Hello from PythonRead More
Your Solution
Q3. Simplify the Compilation Processeasy
Your team frequently compiles a C program before testing it. Instead of typing the compilation command every time, your manager wants a reusable build script.
Create a shell script named build.sh that compiles hello.c into an executable named hello.
The script should be executable and should automate the build process using terminal commands only.
Expected Result
After creating the script, run both of the following commands:
./build.sh
./hello
The output should be:
Hello from CRead More
Your Solution

=== In-class Quizzes tab ===
In-class Quizzes
3
Lecture Notes
In-class Quizzes
These in-class quizzes are only for learning purposes and are not meant for evaluation.
Classroom Quiz - Computer Software
not attempted
Total Questions
1 Questions
Your Score
-/1
Classroom Quiz - Computer Software, Compiler
not attempted
Classroom Quiz - Computer Software, Compiler, Interpreter
not attempted
Classroom Quiz - Computer Software
Submit Quiz
QUESTION 1/1
Mark for review
Clear Selection
A CPU can directly execute which of the following?
A
C source code stored in a .c file
B
Python source code stored in a .py file
C
Machine code instructions represented in binary
D
Assembly code written by a programmer
Previous
Next

Newton School

### jxn4cile2qht  [eq7lnkj6lo7s]
=== Assignments tab (quiz cards + in-class + post-class sections) ===
Assignments1
Lecture Notes
QUIZ
GitHub, Remote Repository Management, GitHub Collaboration, Github Pull Requests - Revision
Attempt duration - Oct 6th 2026 5:00 pm to Oct 11th 2026 5:00 pm
Your submission will be marked as “LATE SUBMISSION” because you have crossed the given submission deadline
Attempt Now
In class assignments
This section contains the assignments and questions solved in the class
No in-class assignments for this lecture
Post class assignments
This section contains the assignments related to the topics covered in this lecture
Q1. Clone and Verify Before Workingeasy
Before starting work on a shared project, your process is: clone https://github.com/org/inventory-system.git, navigate into inventory-system, verify the remote is set correctly, pull any latest changes (just to be safe), and check the commit log in compact format.Read More
Complete Now
Q2. Full Team Collaboration Simulationmedium

You're picking up a teammate's CRM project. Clone https://github.com/teamdev/crm-tool.git and cd into crm-tool. Someone may have pushed a last-minute commit right after you cloned, so run git pull to be safe.

The cloned src/contacts.js and src/deals.js are empty stub files — write some real content into each before staging them (e.g. echo "export const contacts = [];" > src/contacts.js). Do not commit until you have added content to both files.

Stage only src/contacts.js and src/deals.js — never stage src/internal-notes.js or build/output.min.js. Commit with message Add CRM core modules. The remote is already set from the clone, so just push.

Finally, run git log and git remote -v to confirm.

Read More
Complete Now
Q3. Collaborative Git Workflow Challengemedium
You are working on a collaborative project in the chat-app directory. Navigate into it. A remote repository is already configured. Then pull to check if there are any changes on remote or not.  Add content Resolved message issue in client.js, then stage and commit it using the commit message: "fix: resolve message duplicate issue". Finally push your update to the remote repository.Read More
Complete Now
Q4. New Machine, Same Projectmedium

You just got a new laptop. Clone https://github.com/yourname/recipe-app.git. Navigate into recipe-app. Pull (to be safe).

Add some content to app.js, db.js, and helpers/format.js. Do not commit until you have made changes to all three files. Then stage all three — but NOT helpers/debug.js.

Commit with message Resume recipe app development. Push back.

Read More
Complete Now

### mqndqqj16b1s  [eq7lnkj6lo7s]
=== Assignments tab (quiz cards + in-class + post-class sections) ===
Assignments0
In-class Quizzes
3
Lecture Notes
QUIZ
Computer Hardware, Computer Software, Operating System - Revision
Attempt duration - Sep 3rd 2026 6:35 pm to Sep 8th 2026 6:35 pm
Your submission will be marked as “LATE SUBMISSION” because you have crossed the given submission deadline
Complete Now
In class assignments
This section contains the assignments and questions solved in the class
No in-class assignments for this lecture
Post class assignments
This section contains the assignments related to the topics covered in this lecture
No post-class assignments for this lecture

=== In-class Quizzes tab ===
In-class Quizzes
3
Lecture Notes
In-class Quizzes
These in-class quizzes are only for learning purposes and are not meant for evaluation.
Classroom Quiz - Computer Hardware
attempted
Total Questions
6 Questions
Your Score
7/7
Classroom Quiz - Computer Hardware, Computer Software
not attempted
Classroom Quiz - Computer Hardware, Computer Software, Operating System
not attempted
Classroom Quiz - Computer Hardware
Revise
QUESTION 1/6
Which component executes instructions in a computer?
A
SSD
CPU
Explanation:The CPU executes instructions and manages the tasks performed by a computer. Actions like opening applications, browsing the internet, or running software are processed by the CPU.
C
Speaker
D
Monitor
CORRECT ANSWER
QUESTION 2/6
Which component is mainly responsible for graphics rendering and parallel processing?
A
CPU
B
RAM
GPU
Explanation:The GPU (Graphics Processing Unit) is designed for graphics rendering and handling parallel processing tasks efficiently.
D
SSD
CORRECT ANSWER
QUESTION 3/6
Which hardware component connects all major components together?
A
GPU
Motherboard
Explanation:The motherboard is the main circuit board that connects and allows communication between all major computer components.
C
SSD
D
RAM
CORRECT ANSWER
QUESTION 4/6
Which of the following is an input device?
A
Speaker
B
Monitor
Keyboard
Explanation:A keyboard is an input device used to enter data and commands into a computer. The others are output devices.
D
Projector
CORRECT ANSWER
QUESTION 5/6
You open 20 browser tabs and your laptop becomes slow. Which component are you most likely running out of?
A
GPU
RAM
Explanation:Each browser tab uses RAM while it is running. Opening too many tabs can fill up the available RAM, causing the laptop to slow down and lag.
C
Monitor
D
Speaker
CORRECT ANSWER
QUESTION 6/6
Which of the following is an output device?
A
Mouse
B
Scanner
C
Microphone
Monitor
Explanation:A monitor displays information like text, images, and videos from the computer to the user, so it is an output device.
CORRECT ANSWER

Newton School

### uh4th8cl61s2  [eq7lnkj6lo7s]
=== Assignments tab (quiz cards + in-class + post-class sections) ===
Assignments1
In-class Quizzes
5
Lecture Notes
QUIZ
CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ... - Revision
Attempt duration - Sep 10th 2026 6:05 pm to Sep 15th 2026 6:05 pm
Attempted on Sep 12th 2026 12:50 am
View Solutions
In class assignments
This section contains the assignments and questions solved in the class
No in-class assignments for this lecture
Post class assignments
This section contains the assignments related to the topics covered in this lecture
Q1. Advanced File Managementmedium

You are helping your team clean up and organize project files. 

Steps to follow:

Create a folder called project-files.

Inside it, create three files:

report.docx

summary.docx

draft.docx

Make a copy of report.docx and name it report_backup.docx.

Create a new folder called old. Move draft.docx into old/.

Rename summary.docx to final_summary.docx.

Copy final_summary.docx into the old/ folder as well.

Delete report_backup.docx.

Final structure should look like this:

project-files/
├── report.docx
├── final_summary.docx
└── old/
    ├── draft.docx
    └── final_summary.docx

Read More
Your Solution
Q2. Create a Project Folder Structuremedium

You have recently joined a backend team that develops services for an e-commerce platform.

To ensure consistency across projects, the team uses an internal command called create-service to generate the standard structure for new API services.

During the onboarding of several new developers, the team noticed that newly generated services are missing important files and some directories are named incorrectly.

The engineering manager asks you to investigate and repair the scaffold generator before the next batch of services is created.

Tasks:
Locate the create-service command.
Inspect the script used by the command.
Fix all issues in the script.
Ensure the command can be executed.
Run the command to generate a new service.

Expected Service Structure:
service/
├── controllers/
├── models/
├── routes/
├── middleware/
├── server.js
└── README.md


Expected README Content:
API Service


Expected server.js Content:
console.log("Server started");


Requirements:
Directory names must exactly match the expected structure.
The middleware directory must be present.
README.md must exist inside the service directory.
server.js must exist inside the service directory.
The contents of README.md must exactly match the expected text.
The contents of server.js must exactly match the expected text.
The command should execute successfully after your fixes.
Read More
Your Solution
Q3. Recover the Emergency Access Tokenmedium

You are assisting the Site Reliability Engineering (SRE) team during a production incident.

An emergency access token is required to restore a critical service. The token was intentionally stored somewhere inside a deeply nested backup directory structure for security reasons.

The backup system has created many nested folders containing many files. Most of these files are not readable due to permission restrictions.

The SRE team remembers only one thing:

The emergency token is stored in the only readable text file within the backup directory tree.

Your task is to locate the readable file, inspect its contents, and recover the token.

Tasks:
Explore the directory structure.
Find the readable file inside the backup directory tree.
Create a file named token.txt in the current directory containing only the token value.

Example Token Format:
ACCESS_TOKEN_VALUE=abc123xyz789


Expected Output File:
abc123xyz789


Requirements:
Do not modify any existing files.
token.txt must contain only the token value.
No additional text or whitespace should be present.
Read More
Your Solution
Q4. Locate and Extract the Recovery Keymedium

A production server experienced a critical failure overnight. Before shutting down, the backup system created multiple backup folders and scattered diagnostic files across them.

Your team needs to restore access, but the recovery key was saved in only one backup file. The file name and location are unknown.

Search through the backup directory tree, find the recovery key, and save only the key value (without RECOVERY_KEY=) into a file named key.txt in the current directory.

Task:
Locate the recovery key hidden somewhere inside the backups directory.
Extract only the recovery key value.
Save the key value into a file named key.txt in the current directory.

For example, if a file contains:

RECOVERY_KEY=7fK92mXqL8pR3vNz

then key.txt should contain:

7fK92mXqL8pR3vNz

The recovery key may be located in any file within the backups directory tree.

Read More
Your Solution

=== In-class Quizzes tab ===
In-class Quizzes
5
Lecture Notes
In-class Quizzes
These in-class quizzes are only for learning purposes and are not meant for evaluation.
Classroom Quiz - CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ...
attempted
Total Questions
1 Questions
Your Score
2/2
Classroom Quiz - CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ...
attempted
Classroom Quiz - CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ...
attempted
Classroom Quiz - CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ...
attempted
Classroom Quiz - CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ...
attempted
Classroom Quiz - CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ...
Revise
QUESTION 1/1
Your friend runs this command:
cowsay -f dragon "Deploy successful"
What does -f do here?
A
Creates a file template
Modifies the command behaviour
Explanation:-f is a command-line flag that modifies how cowsay behaves. Specifically, it tells cowsay to use the dragon character template instead of the default cow when displaying the message.
C
Deletes the dragon template
D
Finds the output message
CORRECT ANSWER

Newton School

### vfo5u6bvobpf  [eq7lnkj6lo7s]
=== Assignments tab (quiz cards + in-class + post-class sections) ===
Assignments0
In-class Quizzes
1
Lecture Notes
QUIZ
Command-Line Interface (CLI), Terminal - Revision
Attempt duration - Sep 8th 2026 4:05 pm to Sep 13th 2026 4:05 pm
Attempted on Sep 9th 2026 5:35 pm
View Solutions
In class assignments
This section contains the assignments and questions solved in the class
No in-class assignments for this lecture
Post class assignments
This section contains the assignments related to the topics covered in this lecture
No post-class assignments for this lecture

=== In-class Quizzes tab ===
In-class Quizzes
1
Lecture Notes
In-class Quizzes
These in-class quizzes are only for learning purposes and are not meant for evaluation.
Classroom Quiz - Command-Line Interface (CLI), Terminal
not attempted
Total Questions
1 Questions
Your Score
-/1
Classroom Quiz - Command-Line Interface (CLI), Terminal
Submit Quiz
QUESTION 1/1
Mark for review
Clear Selection
Which command is used to to make colorful rainbow output in the terminal?
A
say
B
fortune
C
lolcat
D
mkdir
Previous
Next

Newton School

### ywvwme2ev25q  [eq7lnkj6lo7s]
=== Assignments tab (quiz cards + in-class + post-class sections) ===
Assignments0
In-class Quizzes
1
Lecture Notes
QUIZ
Course and Instructor Introduction, Computer Systems - Revision
Attempt duration - Sep 1st 2026 5:00 pm to Sep 6th 2026 5:00 pm
Attempted on Sep 1st 2026 11:47 pm
View Solutions
In class assignments
This section contains the assignments and questions solved in the class
No in-class assignments for this lecture
Post class assignments
This section contains the assignments related to the topics covered in this lecture
No post-class assignments for this lecture

=== In-class Quizzes tab ===
In-class Quizzes
1
Lecture Notes
In-class Quizzes
These in-class quizzes are only for learning purposes and are not meant for evaluation.
Classroom Quiz - Course and Instructor Introduction, Computer Systems
late submission
Total Questions
14 Questions
Your Score
18/24
Classroom Quiz - Course and Instructor Introduction, Computer Systems
Revise
QUESTION 1/14
Which statement best describes a computer?
A
A machine with a screen and keyboard
B
A machine that stores digital files only
A machine that follows changeable instructions
Explanation:A computer works by following instructions that can be changed or updated.
D
A machine that connects to the internet
CORRECT ANSWER
QUESTION 2/14
In a smartphone, which action is an example of input?
A
Showing photos on the display
Saving videos into storage memory
C
Vibrating after a notification alert
Tapping an icon on the screen
Explanation:Tapping the screen sends information into the device, making it an input action.
INCORRECT ANSWER
QUESTION 3/14
After a computer processes data, what happens next?
Output is produced for the user
Explanation:After processing information, the computer generates an output.
B
Input is collected from sensors
C
Storage is removed from memory
D
Instructions are deleted forever
CORRECT ANSWER
QUESTION 4/14
Why is a juicer not considered a computer?
A
It cannot produce useful output
It cannot be programmed to perform different tasks.
Explanation:A juicer performs fixed actions and cannot be programmed with different instructions.
C
It cannot receive physical input
D
They are commonly used as general-purpose computers.
CORRECT ANSWER
QUESTION 5/14
Which device is best classified as an embedded computer?
Smartwatch tracking daily steps
Explanation:A smartwatch is an embedded computer because it contains a dedicated computing system designed for specific tasks such as fitness tracking and notifications. In contrast, a desktop and laptop are general-purpose computers that can run many different applications, while a cloud system consists of networked servers providing computing resources rather than a computer embedded within a device.
B
Desktop used for video editing
C
Cloud system hosting websites
D
Laptop used for online classes
CORRECT ANSWER
QUESTION 6/14
Which example best represents storage in an MRI system?
A
Radio waves entering the scanner
Processors rebuilding body images
Scan reports saved in records
Explanation:Saving scan reports for later use is an example of storage.
D
Display screens showing the scan
INCORRECT ANSWER
QUESTION 7/14
Why do data centres use thousands of computers together?
A
To reduce the need for electricity
B
To avoid using processing units
To support very large workloads
Explanation:Data centres combine many computers to handle massive computing tasks.
D
To remove all storage devices
CORRECT ANSWER
QUESTION 8/14
Which feature makes a smartwatch different from a laptop?
A smartwatch is designed mainly for limited and specific computing tasks
Explanation:Smartwatches are designed for focused tasks, while laptops are general-purpose systems.
B
A laptop is designed mainly for limited and specific computing tasks
C
A smartwatch is designed mainly for storing and printing large documents
D
A laptop is designed mainly for tracking fitness and measuring heart rate
CORRECT ANSWER
QUESTION 9/14
A self-checkout machine prints a receipt after scanning items. The receipt is an example of:
A
Input sent into the system
Output produced by the system
Explanation:The printed receipt is information produced for the user.
C
Storage kept inside memory
D
Processing done by hardware
CORRECT ANSWER
QUESTION 10/14
What mainly separates a phone from a data centre?
A
Internet access and connectivity features
Software installation and update methods
C
Information storage and retrieval functions
Scale of operation and primary purpose
Explanation:Both phones and data centres can connect to the internet, run software, and store information. The main difference is their scale of operation and primary purpose: phones are designed for individual users, while data centres handle large-scale computing and storage workloads.
INCORRECT ANSWER
QUESTION 11/14
Mark for review
Clear Selection
Temporary working memory inside a computer is called ______. (3-letter abbreviation, e.g. ABC)
RAM
Explanation:RAM stores data temporarily while programs are running.
Correct answer: RAM
QUESTION 12/14
Mark for review
Clear Selection
Long-term file storage in modern laptops is often an ______. (3-letter abbreviation, e.g. ABC)
ROM
Explanation:SSDs store files even when the computer is turned off.
Correct answer: SSD
QUESTION 13/14
Mark for review
Clear Selection
Every computer must follow input, processing, output, and storage. (State true or false, should be in lowercase)
true
Explanation:All computers fit the IPOS model in some form.
Correct answer: true
QUESTION 14/14
Mark for review
Clear Selection
A mechanical juicer is programmable like a computer. (State true or false)
false
Explanation:A juicer performs fixed actions and cannot execute new instructions.
Correct answer: false

Newton School

---
## WHERE THESE QUESTIONS CAME FROM (sources)
- **Subject assignment pages / My Assignments + Assignment Contests API** — 8 assignments, 53 questions; full statement captured from each question's playground page (read-only visit) — 53/53 texts present.
- **Lecture pages** (Course Content sidebar list) — 7 of 16 lecture windows carry content: post-class question text below the video (`Read More` expanded) and in-class quiz questions via read-only views only (Revise / View Solutions / Next-Previous walk — never Attempt/Start/Submit).
- **Assessments API** — 11 quiz schedules (title, window, XP earned). No question text in the API (hidden until test start).

---
## NOT FETCHED — open these yourself
(These sit behind `Attempt Now` / `Start Test` buttons. I never click those — they consume quiz attempts. Everything else above is complete.)

### Revision quizzes whose questions never became visible (6)
(quiz window closed while unattempted — try `Attempt Now` on that lecture's Assignments tab yourself, or check My Assessments)
- Computer Networks, LAN, MAN, WAN, DNS, Packet Switching, Network Protocols, Rout ... - Revision
- GitHub, Remote Repository Management, GitHub Collaboration, Github Pull Requests - Revision
- Version Control, Repository, Git, Git Commands - Revision
- Number Systems, Decimal Number System, Binary Number System, Hexadecimal Number  ... - Revision
- Operating System, Filesystem Management, File Ownership and Permissions, PATH, O ... - Revision
- Operating System, Operating System Architecture, Device Management, Process Mana ... - Revision

### Quiz Contests tab (separate MCQ tests)
- Quiz contest questions only appear after `Start Test` (graded, consumes an attempt): open the Quiz Contests tab manually if you want these: Computer Networks, LAN, MAN, WAN, DNS, Packet Switching, Network Protocols, Rout ... - Revision, GitHub, Remote Repository Management, GitHub Collaboration, Github Pull Requests - Revision, Version Control, Repository, Git, Git Commands - Revision, Number Systems, Decimal Number System, Binary Number System, Hexadecimal Number  ... - Revision, Computer Software, Compiler, Interpreter, Number Representation & Data Encoding - Revision, Operating System, Filesystem Management, File Ownership and Permissions, PATH, O ... - Revision, Operating System, Operating System Architecture, Device Management, Process Mana ... - Revision, CLI File & Directory Management, CLI Package Management, CLI Flags, Options & Op ... - Revision, Command-Line Interface (CLI), Terminal - Revision, Computer Hardware, Computer Software, Operating System - Revision, Course and Instructor Introduction, Computer Systems - Revision
- What IS captured: all assignment questions (53), all in-class quiz questions shown above, all contest ASSIGNMENT texts

---
TOTALS: 53 assignment questions (16 solved), 11 quizzes, 0 questions without captured text, 7 lecture windows with content
