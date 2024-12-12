# quick-to-do

Django To-Do List Application

This is a simple To-Do List web application built using Django. The application allows users to create, read, update, and delete (CRUD) tasks with timestamps for tracking when tasks were created and updated.



Features

Add Tasks: Users can create new tasks.

View Tasks: List all tasks with their timestamps.

Update Tasks: Edit the details of existing tasks.

Delete Tasks: Remove completed or unnecessary tasks.

Timestamps: Each task includes created and updated timestamps for tracking.





Prerequisites

Before running this project, make sure you have the following installed:

Python (>= 3.8)

Django (>= 4.0)

SQLite (or any preferred database)





Installation and Setup

1. Clone the Repository:

git clone <repository-url>
cd todolist-django


2. Create a Virtual Environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3. Install Dependencies:

pip install -r requirements.txt


4. Apply Migrations:

python manage.py migrate


5. Run the Development Server:

python manage.py runserver


6. Access the Application:
Open your browser and navigate to http://127.0.0.1:8000/.





Project Structure

todolist/
│
├── todolist/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── tasks/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── templates/
│   │   ├── tasks/
│   │   │   ├── task_list.html
│   │   │   ├── task_form.html
│   │   │   └── confirm_delete.html
│   └── admin.py
│
├── manage.py
└── requirements.txt


---

Models

The Task model includes:

title: A string field for the task's title.

description: An optional text field for details.

created_at: Auto-generated timestamp for task creation.

updated_at: Auto-generated timestamp for task updates.







How to Use

1. Homepage: View all tasks.


2. Add a Task: Use the "Add Task" button to create new tasks.


3. Edit a Task: Click the "Edit" button next to a task.


4. Delete a Task: Click the "Delete" button next to a task.






Future Enhancements

Add user authentication for personalized task management.

Implement categories or tags for tasks.

Add search and filter functionality.

Create a REST API for the application.

Contact

If you have any questions or suggestions, feel free to reach out to  rajkumar.b.r.2003@gmail.com
