---
type: guide
tags: [guide]
---
# How This Vault Works

## Folder Layout
| Folder | Purpose |
|---|---|
| 00 Home | Dashboard and links |
| 01 Schedule | Weekly timetable and deadlines |
| 02 Courses | One folder per course, each with an index note and subfolders |
| 03 Templates | Note templates (do not store notes here) |
| 04 Projects | Project tracker and repository links |
| 05 Study Sessions | One note per group study session |
| 06 Daily | Daily notes |
| 07 Inbox | Default location for new notes. File them into a course folder later |
| 08 Attachments | Pasted images and files |
| 09 Resources | Roadmaps and links |

## Course Folder Structure
Each course folder contains: Lecture Notes, Reviewers, Assignments, Quizzes and Exams, Files. The index note in each course lists the contents of each subfolder automatically.

## Naming Convention
- Lecture notes: `YYYY-MM-DD Topic`
- Assignments: `HOA 1 Topic` or `Assignment 1 Topic`
- Reviewers: `Prelim Reviewer` or `Quiz 1 Reviewer`
- Study sessions: `YYYY-MM-DD Course Topic`

## After Every Class
1. Create a note from the **Lecture Note** template. Insert it with the command palette: **Templates: Insert template**.
2. Fill in Persons, Dates, and Events for every person named in the lecture.
3. Move the note into the course's Lecture Notes folder.
4. Add any new quiz, exam, or submission to [[Deadlines]].

## Before a Quiz or Exam
1. Create a note from **Quiz or Exam Prep**.
2. Build the **Reviewer** from your lecture notes.
3. Export a PDF copy: File menu > Export to PDF.

## Tags
`#lecture` `#reviewer` `#assignment` `#exam-prep` `#study-session` `#deadline` `#daily` `#weekly-review`

## Properties
Every template includes properties (code, course, date, type). Fill in `code` and `course` so notes can be searched by course.

## Backup
Copy this folder to cloud storage or a private GitHub repository. A `.gitignore` is included for the repository option. Never commit passwords or tokens.
