# HuBot Resume Uploader

 Resume Uploader is a web application that allows users to upload their resumes and view a list of candidates. It is built using the Django web framework and provides a simple way to manage resumes and candidate information.

## Features

- User-friendly web interface for uploading resumes.
- Candidate details such as name, date of birth, gender, contact information, and more.
- List of candidates with view and delete options.
- Integration with Django's built-in admin interface for managing candidate data.
- Responsive design for various screen sizes.

## Screenshots

<img width="922" alt="image" src="https://github.com/mohamed-amar0107/HuBot/blob/main/resumeuploader/media/profileimg/acceuil.PNG">

<img width="922" alt="image" src="https://github.com/mohamed-amar0107/HuBot/blob/main/resumeuploader/media/profileimg/jobrequirement.PNG">


<img width="922" alt="image" src="https://github.com/SuryaPratap2542/Resume-Uploader/assets/89827931/d3924bcc-5483-4dec-9405-7577057ba473">
*Home Page - Upload Resumes*

<img width="887" alt="image" src="https://github.com/mohamed-amar0107/HuBot/blob/main/resumeuploader/media/profileimg/ammar.png">
*Candidates informations*

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/django-resume-uploader.git
   ```

2. Navigate to the project directory:

   ```bash
   cd django-resume-uploader
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
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

1. Access the home page to upload resumes and view the list of candidates.
2. Click the "Submit" button to upload a resume.
3. View candidate details by clicking on their name in the list.
4. Delete a candidate by clicking the "Delete" button.
5. Access the Django admin interface at `http://localhost:8000/admin` to manage candidate data.
