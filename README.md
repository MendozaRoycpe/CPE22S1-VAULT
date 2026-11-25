<div align="center">

<h1>CPE22S1-VAULT</h1>

<p><b>Obsidian study vault for section CPE21S1</b><br>
First Semester SY 2026-2027 &middot; Technological Institute of the Philippines</p>

<p>
  <a href="#quick-start">Quick Start</a> &middot;
  <a href="#courses">Courses</a> &middot;
  <a href="#vault-structure">Structure</a> &middot;
  <a href="#workflow">Workflow</a> &middot;
  <a href="#git-routine">Git Routine</a>
</p>

</div>

<hr>

<h2 id="overview">Overview</h2>

<p>This repository is an Obsidian vault. It holds lecture notes, reviewers, assignments, exam prep, study session notes, and the weekly timetable for ten courses. It uses only built-in Obsidian features, so no community plugins are required.</p>

<h2 id="quick-start">Quick Start</h2>

<ol>
  <li>Install <a href="https://obsidian.md">Obsidian</a>.</li>
  <li>Clone this repository outside any cloud-synced folder (OneDrive can cause file conflicts):<br>
    <code>git clone https://github.com/MendozaRoycpe/CPE22S1-VAULT.git</code></li>
  <li>In Obsidian, choose <b>Open folder as vault</b> and select the cloned folder.</li>
  <li>Open <code>00 Home.md</code> and read <code>How This Vault Works.md</code>.</li>
  <li>Check <b>Settings &gt; Core plugins</b>: <b>Templates</b> and <b>Daily notes</b> must be on.</li>
</ol>

<h2 id="courses">Courses</h2>

<table>
  <thead>
    <tr><th>Code</th><th>Course</th><th>Days</th><th>Room</th></tr>
  </thead>
  <tbody>
    <tr><td>CPE 013</td><td>Logic Circuits and Design</td><td>Tue, Thu</td><td>5424 (Tue), 5426 (Thu)</td></tr>
    <tr><td>CPE 18A</td><td>Emerging Technologies 1 in CPE</td><td>Wed</td><td>3201</td></tr>
    <tr><td>CPE 021A</td><td>Computer Architecture and Organization</td><td>Fri</td><td>3201</td></tr>
    <tr><td>CPE 011A</td><td>Database Management</td><td>Wed, Sat</td><td>5218</td></tr>
    <tr><td>CPE 111</td><td>IoT and Applications</td><td>Wed, Fri</td><td>5424 (Wed), 5426 (Fri)</td></tr>
    <tr><td>CPE 302</td><td>Computer Networks</td><td>Sat (two sessions)</td><td>5202, 5206</td></tr>
    <tr><td>CPE 015A</td><td>Optimization Techniques</td><td>Sat</td><td>5310A</td></tr>
    <tr><td>MATH 020</td><td>Numerical Methods</td><td>Tue, Thu</td><td>5306</td></tr>
    <tr><td>GEC 002</td><td>Reading in Philippine History</td><td>Tue, Thu</td><td>5402</td></tr>
    <tr><td>PATHFIT 4</td><td>PathFit 4</td><td>Fri</td><td>2F</td></tr>
  </tbody>
</table>

<details>
<summary><b>Weekly timetable</b></summary>

<table>
  <thead>
    <tr><th>Day</th><th>Time</th><th>Course</th><th>Room</th></tr>
  </thead>
  <tbody>
    <tr><td rowspan="3">Tuesday</td><td>7:30-10:30 AM</td><td>CPE 013</td><td>5424</td></tr>
    <tr><td>10:30 AM-12:00 PM</td><td>MATH 020</td><td>5306</td></tr>
    <tr><td>12:00-1:30 PM</td><td>GEC 002</td><td>5402</td></tr>
    <tr><td rowspan="3">Wednesday</td><td>7:30-10:30 AM</td><td>CPE 18A</td><td>3201</td></tr>
    <tr><td>10:30 AM-1:30 PM</td><td>CPE 111</td><td>5424</td></tr>
    <tr><td>1:30-4:30 PM</td><td>CPE 011A</td><td>5218</td></tr>
    <tr><td rowspan="3">Thursday</td><td>7:30-10:30 AM</td><td>CPE 013</td><td>5426</td></tr>
    <tr><td>10:30 AM-12:00 PM</td><td>MATH 020</td><td>5306</td></tr>
    <tr><td>12:00-1:30 PM</td><td>GEC 002</td><td>5402</td></tr>
    <tr><td rowspan="3">Friday</td><td>7:30-10:30 AM</td><td>CPE 021A</td><td>3201</td></tr>
    <tr><td>10:30 AM-12:30 PM</td><td>CPE 111</td><td>5426</td></tr>
    <tr><td>1:30-3:30 PM</td><td>PATHFIT 4</td><td>2F</td></tr>
    <tr><td rowspan="4">Saturday</td><td>7:30-10:30 AM</td><td>CPE 011A</td><td>5218</td></tr>
    <tr><td>10:30 AM-12:30 PM</td><td>CPE 302</td><td>5202</td></tr>
    <tr><td>1:30-4:30 PM</td><td>CPE 302</td><td>5206</td></tr>
    <tr><td>4:30-7:30 PM</td><td>CPE 015A</td><td>5310A</td></tr>
  </tbody>
</table>

<p>Monday has no classes. Verify rooms and times against the official schedule.</p>

</details>

<h2 id="vault-structure">Vault Structure</h2>

<table>
  <thead>
    <tr><th>Folder</th><th>Purpose</th></tr>
  </thead>
  <tbody>
    <tr><td><code>00 Home.md</code></td><td>Dashboard with course links and live lists of notes</td></tr>
    <tr><td><code>01 Schedule/</code></td><td>Weekly timetable and deadlines</td></tr>
    <tr><td><code>02 Courses/</code></td><td>One folder per course: index note plus Lecture Notes, Reviewers, Assignments, Quizzes and Exams, Files</td></tr>
    <tr><td><code>03 Templates/</code></td><td>Lecture Note, Reviewer, Assignment, Quiz or Exam Prep, Study Session, Weekly Review, Daily Note</td></tr>
    <tr><td><code>04 Projects/</code></td><td>Project tracker and repository links</td></tr>
    <tr><td><code>05 Study Sessions/</code></td><td>One note per group study session</td></tr>
    <tr><td><code>06 Daily/</code></td><td>Daily notes</td></tr>
    <tr><td><code>07 Inbox/</code></td><td>Default location for new notes. File them into a course folder later</td></tr>
    <tr><td><code>08 Attachments/</code></td><td>Pasted images and files</td></tr>
    <tr><td><code>09 Resources/</code></td><td>Programming languages roadmap and links</td></tr>
  </tbody>
</table>

<h2 id="workflow">Workflow</h2>

<details open>
<summary><b>After every class</b></summary>

<ol>
  <li>Create a note and insert the <b>Lecture Note</b> template: <kbd>Ctrl</kbd>+<kbd>P</kbd>, then <b>Templates: Insert template</b>.</li>
  <li>Fill in <b>Persons, Dates, and Events</b> for every person named in the lecture.</li>
  <li>Move the note into the course's <code>Lecture Notes</code> folder.</li>
  <li>Add any new quiz, exam, or submission to <code>01 Schedule/Deadlines.md</code>.</li>
</ol>

</details>

<details>
<summary><b>Before a quiz or exam</b></summary>

<ol>
  <li>Create a note from the <b>Quiz or Exam Prep</b> template.</li>
  <li>Build a reviewer from the <b>Reviewer</b> template, using your lecture notes.</li>
  <li>Export a PDF copy: File menu &gt; <b>Export to PDF</b>.</li>
</ol>

</details>

<details>
<summary><b>Naming convention</b></summary>

<ul>
  <li>Lecture notes: <code>YYYY-MM-DD Topic</code></li>
  <li>Assignments: <code>HOA 1 Topic</code> or <code>Assignment 1 Topic</code></li>
  <li>Reviewers: <code>Prelim Reviewer</code> or <code>Quiz 1 Reviewer</code></li>
  <li>Study sessions: <code>YYYY-MM-DD Course Topic</code></li>
</ul>

</details>

<h2 id="git-routine">Git Routine</h2>

<ol>
  <li>Run <code>git pull</code> before every push, and before you start editing.</li>
  <li>Stage and commit: <code>git add .</code> then <code>git commit -m "Describe the change"</code></li>
  <li>Push: <code>git push</code></li>
</ol>

<p>Edits made by Claude arrive on the <code>claude-edits</code> branch. Review and merge them on GitHub, then run <code>git pull</code>.</p>

<p><b>Notes:</b></p>
<ul>
  <li>Do not use <code>git push --force</code>. It deletes remote-only changes.</li>
  <li><code>.obsidian/workspace.json</code> is ignored, so window layouts are not committed.</li>
  <li>Encode parentheses in Markdown URLs as <code>%28</code> and <code>%29</code>.</li>
  <li>Do not commit passwords, tokens, or webhook URLs.</li>
</ul>

<hr>

<div align="center">
  <sub>CPE21S1 &middot; First Semester SY 2026-2027</sub>
</div>
