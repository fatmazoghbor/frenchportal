# French Course Portal

A polished teacher/student French-course dashboard prototype.

## Included
- Teacher and Student role switcher
- Lessons & Resources area
- Teacher homework creation/editing
- Student homework submission
- Teacher grading out of 100
- Teacher remarks/feedback
- Grades & Feedback page
- Student submissions table
- Local persistence with browser localStorage

## Important
This version is a working front-end prototype. Files and data are stored locally in the browser, so it is not yet a true multi-device online classroom.

For a production version, connect the UI to Supabase for:
- teacher/student authentication
- database tables for lessons, homework, submissions and grades
- Supabase Storage for uploaded PDFs/PPTX/DOCX
- per-student permissions
- real submission timestamps
- secure teacher-only grading
