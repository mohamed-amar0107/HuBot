# HuBot Resume Uploader

HuBot Resume Uploader is a simple web application for managing resumes. Users can upload resumes, view a list of candidates, and manage their information easily. It is built using the HuBot web framework and provides a user-friendly experience.

## Features

- User-friendly web interface for uploading resumes.
- Candidate details such as name, date of birth, gender, contact information, and more.
- List of candidates with view and delete options.
- Integration with Django's built-in admin interface for managing candidate data.
- Responsive design for various screen sizes.

## Screenshots

<img width="922" alt="image" src="https://github.com/mohamed-amar0107/HuBot/blob/main/resumeuploader/media/profileimg/acceuil.PNG">

<img width="922" alt="image" src="https://github.com/mohamed-amar0107/HuBot/blob/main/resumeuploader/media/profileimg/jobrequirement.PNG">


<img width="887" alt="image" src="https://github.com/mohamed-amar0107/HuBot/blob/main/resumeuploader/media/profileimg/hh.png">
*Candidates informations*

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mohamed-amar0107/HuBot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd HuBot
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
     ```bash
     venv\Scripts\activate
     ```



5. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Run the development server:

   ```bash
   python manage.py runserver
   ```

7. Access the application in your web browser at `http://localhost:8000`.

## Usage

1 -Access the Application
 Open the application in your web browser at:
 http://localhost:8000.

2 -Upload a Resume
 On the homepage, select a file to upload.
 Click the "Submit" button to add it to the list of candidates.

3-View the Candidate List
 Access the list of candidates after uploading a resume.
 Click on a candidate's name to view their details.

4-Delete a Candidate
 Use the "Delete" button next to a candidate to remove them from the list.
 
5-Admin Interface
 Log in to the Django admin interface at:
 http://localhost:8000/admin.
 Manage candidate data, including adding, editing, or deleting records.
