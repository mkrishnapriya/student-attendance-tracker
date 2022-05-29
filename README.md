# student-attendance-tracker
![attendance-tracker](https://img.freepik.com/free-vector/students-employees-adding-events-deadlines-calendar-app-young-people-using-time-organizer-planner-flat-illustration_74855-20735.jpg?t=st=1653810447~exp=1653811047~hmac=a49ac50832a1889f8edee045ecf2a3ed0d04e4b356342cf595db9723431e4ac4&w=740)

A simple students attendance tracker application with face-recognition feature.

## Tech-stack used:
- python
- Django
- opencv
- HTML, CSS

## How to run the project
1. Clone or download the repository.
2. Install the required tech-stack by running the command:\
`pip install requirements.txt`
3. After successful installation run the following commands to start the server:\
`python manage.py makemigrations` \
`python manage.py migrate`\
`python manage.py createsuperuser`\
`python manage.py runserver`\
The starts running on your localhost:8000 port.
4. If you couldn't login go to [localhost:8000/admin](localhost:8000/admin) to add users and groups: teacher, admin

## Features implemented
- Login and Logout of the user.
- Attendance marking through face-recognition.
- Analysis of number of students present and absent.
- Downloading the attendance report.
- Direct mailing of the report to the receiver.

