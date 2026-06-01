# Portfolio Website

A personal portfolio website built using Django, HTML, CSS, JavaScript, and JSON data files.

## Features

- Responsive portfolio website
- Dynamic skills section using JSON


## Technologies Used

- Python
- Django
- HTML5
- CSS3
- JavaScript
- JSON

## Project Structure

```
portfolio/
│
├── media/
│   ├── skills/
│   ├── resume_roshitha.pdf
│
├── static/
│   ├── css/
│   ├── js/
│   └── data/
│       ├── skills.json
│       └── particles.json
│
├── templates/
│   └── index.html
│
├── portfolio/
│   ├── settings.py
│   ├── urls.py
│   └── views.py
│
├── manage.py
└── README.md
```

## Installation

### Clone Repository

```bash
git clone <repository-url>
cd portfolio
```

### Create Virtual Environment

```bash
python -m venv env
```

### Activate Virtual Environment

Windows:

```bash
env\Scripts\activate
```

Linux/Mac:

```bash
source env/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Server

```bash
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

## Author

**Roshitha Gadugolu**

- Python Developer
- Django Developer
- Machine Learning Enthusiast

## License

This project is for educational and portfolio purposes.
