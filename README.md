# Automated Exam Marking System (AEMS)

## Overview
AEMS is an AI-driven grading system that automates exam marking using Optical Character Recognition (OCR) and Natural Language Processing (NLP).

## Features
- Handwritten & printed script digitization using OCR
- Automated grading using NLP
- Web-based dashboard for teachers and students
- Secure storage with PostgreSQL

## Technologies Used
- Backend: Django, Django REST Framework, PostgreSQL
- Frontend: React.js
- OCR: Google Vision API
- NLP: Hugging Face Transformers

## Setup Guidelines
1. Clone the repository
```sh
git clone https://github.com/jruheni/aems.git
cd aems
```
2. Create the virtual environment
```sh
python3 -m venv venv
source venv/bin/activate
```

3. Install requirements
```sh
pip install -r requirements.txt
```

4. Configure Environmnet Variables
```sh
SECRET_KEY=your-secret-key
DEBUG=True
DATABASE_URL=your-database-url
```
5. Apply Migrations
```sh
python manage.py migrate
```

6. Create a Superuser (Admin)
```sh
python manage.py createsuperuser
```

7. Start the Development Server
```sh
python manage.py runserver
```

### Once The Backend is Setup
8. Run the Frontend
```sh
cd frontend
npm install
npm start
```


