# Python & Flask Tutorial

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.0+-green.svg)](https://flask.palletsprojects.com/)

Comprehensive Python and Flask tutorial website covering basics to advanced topics including web development, database integration, and deployment.

## Overview

This repository contains a complete tutorial website for learning Python programming and Flask web development. The tutorials are designed for beginners to intermediate learners and include practical code examples, detailed explanations, and hands-on projects.

**Live Website**: [http://kklab.mobi/Python_Flask_Tutorial/](http://kklab.mobi/Python_Flask_Tutorial/)

## Contents

### 1. Python Beginner Tutorial

A comprehensive guide covering Python fundamentals with 11 chapters:

- **Chapter 1**: Hello World - Your first Python program
- **Chapter 2**: Variables and Data Types
- **Chapter 3**: String Manipulation
- **Chapter 4**: Lists and Tuples
- **Chapter 5**: Dictionaries and Sets
- **Chapter 6**: Control Flow (if, for, while)
- **Chapter 7**: Functions
- **Chapter 8**: Modules and Packages
- **Chapter 9**: Classes and Object-Oriented Programming
- **Chapter 10**: File Handling
- **Chapter 11**: Error Handling and Exceptions

**Formats Available**:
- Interactive HTML: `Python_Beginner_Tutorial_Complete.html`
- Markdown: `Python_Beginner_Tutorial_Complete.md`
- Executable Examples: `python_beginner_tutorial/examples/`

### 2. Flask Web Development Tutorial

A practical guide to building web applications with Flask:

- **Getting Started**: Environment setup and basic Flask app
- **Routing**: URL patterns, HTTP methods, dynamic routing
- **Templates**: Jinja2 templating engine, template inheritance
- **Forms**: Form handling, validation, file uploads
- **Database**: SQLAlchemy integration, CRUD operations
- **Real-World Examples**: Complete working applications

**Formats Available**:
- Interactive HTML: `Flask_Tutorial_Complete.html`
- Markdown: `Flask_Tutorial_Complete.md`
- Working Apps: `flask_tutorial/`

## Repository Structure

```
Python_Flask_Tutorial/
├── index.html                              # Main landing page
├── LICENSE                                 # MIT License
│
├── Python_Beginner_Tutorial_Complete.html  # Python tutorial (HTML)
├── Python_Beginner_Tutorial_Complete.md    # Python tutorial (Markdown)
├── python_beginner_tutorial/
│   └── examples/                           # Executable Python examples
│       ├── 01_hello_world.py
│       ├── 02_variables_and_types.py
│       ├── 03_strings.py
│       ├── 04_lists_and_tuples.py
│       ├── 05_dictionaries_and_sets.py
│       ├── 06_control_flow.py
│       ├── 07_functions.py
│       ├── 08_modules.py
│       ├── 09_classes_and_oop.py
│       ├── 10_file_handling.py
│       └── 11_error_handling.py
│
├── Flask_Tutorial_Complete.html            # Flask tutorial (HTML)
├── Flask_Tutorial_Complete.md              # Flask tutorial (Markdown)
├── flask_tutorial/
│   ├── app.py                              # Basic Flask app
│   ├── routes_example.py                   # Routing examples
│   ├── template_example.py                 # Template examples
│   ├── forms_example.py                    # Form handling
│   ├── database_example.py                 # Database integration
│   ├── requirements.txt                    # Python dependencies
│   ├── README.md                           # Flask tutorial guide
│   ├── templates/                          # HTML templates
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── about.html
│   │   ├── contact.html
│   │   ├── forms/                          # Form templates
│   │   │   ├── index.html
│   │   │   ├── simple.html
│   │   │   ├── register.html
│   │   │   ├── contact.html
│   │   │   ├── upload.html
│   │   │   └── result.html
│   │   ├── db/                             # Database templates
│   │   │   ├── index.html
│   │   │   ├── users.html
│   │   │   ├── user_detail.html
│   │   │   ├── add_user.html
│   │   │   ├── post_detail.html
│   │   │   ├── add_post.html
│   │   │   └── edit_post.html
│   │   └── macros/                         # Reusable template macros
│   │       └── forms.html
│   └── static/                             # Static assets
│       ├── css/
│       └── js/
│
├── convert_to_html.py                      # Tutorial conversion script
└── convert_python_to_html.py               # Python tutorial converter
```

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- A text editor or IDE (VS Code, PyCharm, etc.)

### Running Python Examples

1. Navigate to the Python examples directory:
```bash
cd python_beginner_tutorial/examples
```

2. Run any example:
```bash
python 01_hello_world.py
```

### Running Flask Applications

1. Navigate to the Flask tutorial directory:
```bash
cd flask_tutorial
```

2. Create a virtual environment:
```bash
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on macOS/Linux
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the basic Flask app:
```bash
python app.py
```

5. Open your browser and visit: `http://localhost:5000`

### Exploring Different Flask Examples

Each Flask example demonstrates different features:

- **Basic App**: `python app.py` - Simple Flask application
- **Routing**: `python routes_example.py` - URL routing patterns
- **Templates**: `python template_example.py` - Jinja2 templating
- **Forms**: `python forms_example.py` - Form handling and validation
- **Database**: `python database_example.py` - SQLAlchemy CRUD operations

## Features

- **Beginner-Friendly**: Clear explanations and step-by-step examples
- **Comprehensive**: Covers fundamentals to advanced topics
- **Practical**: Real-world code examples and projects
- **Multiple Formats**: HTML, Markdown, and executable code
- **Japanese Language**: Complete tutorials in Japanese
- **Hands-On**: Interactive examples you can run and modify
- **Modern Stack**: Latest Python and Flask versions

## Learning Path

### For Python Beginners

1. Start with `Python_Beginner_Tutorial_Complete.html`
2. Work through each chapter sequentially
3. Run the example code in `python_beginner_tutorial/examples/`
4. Experiment by modifying the examples

### For Flask Learners

1. Complete the Python beginner tutorial first
2. Read `Flask_Tutorial_Complete.html`
3. Follow the setup instructions in `flask_tutorial/README.md`
4. Run each Flask example application
5. Build your own project using the patterns learned

## Topics Covered

### Python Fundamentals

- Basic syntax and program structure
- Data types: strings, numbers, lists, dictionaries
- Control structures: conditions and loops
- Functions and modules
- Object-oriented programming
- File I/O operations
- Exception handling
- Best practices and coding standards

### Flask Web Development

- Flask application structure
- URL routing and view functions
- HTTP methods (GET, POST, etc.)
- Template rendering with Jinja2
- Template inheritance and macros
- Form handling and validation
- File uploads
- Database integration with SQLAlchemy
- ORM models and relationships
- CRUD operations
- Session management
- Error handling
- RESTful API basics

## Contributing

Contributions are welcome! If you find errors or have suggestions for improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Resources

- [Python Official Documentation](https://docs.python.org/)
- [Flask Official Documentation](https://flask.palletsprojects.com/)
- [Jinja2 Documentation](https://jinja.palletsprojects.com/)
- [SQLAlchemy Documentation](https://www.sqlalchemy.org/)
- [WTForms Documentation](https://wtforms.readthedocs.io/)

## Author

Created by katzkawai

## Acknowledgments

- Python Software Foundation
- Flask development team
- The open-source community

---

**Happy Coding with Python!** 🐍🚀
