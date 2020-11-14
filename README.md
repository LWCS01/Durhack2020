# Durhack2020
Group project for Durhack 2020 wooo
idea1: lecture feedback website
- accounts for teachers and students
- teachers can upload slides of their lectures beforehand or a video with timestamps
- students can then view the lectures and review specific parts
- lecturer can later review the feedback
  - this could be in a graphed form
- student recieves email when a new lecture is available
- teacher recieves email when all feedback has been recieved

stuff we need for this:
- server
- database with account details
  - storing lecture and feedback
- graphing program for feedback
- email api


account details:
- email addresses
- username
- password

emails are restricted to durham domain

database:
module lecture lecturer

moduleID studentID

studentID username email password

lecture videoLink

