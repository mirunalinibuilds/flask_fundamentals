# Flask Fundamentals – Learning Journey 🚀

This repository documents my journey of learning the fundamentals of Flask before starting a larger web application project.

The goal of this repository is to understand the core concepts by writing and explaining every line of code rather than simply making an application work.

## 📚 Topics Covered

- Setting up a Flask project
- Creating and using a Python virtual environment
- Flask application structure
- Routing (`@app.route`)
- Rendering HTML using `render_template()`
- Jinja2 template engine
- Template inheritance (`base.html` and child templates)
- Understanding the Request → Response lifecycle
- Basic HTML page structure
- Organizing templates and static files

---

## 📂 Project Structure

```
.
├── app.py
├── config.py
├── models.py
├── requirements.txt
├── instance/
├── static/
│   └── style.css
└── templates/
    ├── base.html
    └── index.html
```

---

## 🧠 Concepts Learned

### Flask

- Creating a Flask application
- Running the development server
- Debug mode
- Understanding the application object

### Routing

Learned how URLs are mapped to Python functions.

Example:

```python
@app.route("/")
def home():
    return render_template("index.html")
```

---

### Jinja2

Learned how Flask uses Jinja2 to generate dynamic HTML.

Topics include:

- `render_template()`
- Template inheritance
- `extends`
- `block`
- `endblock`

---

### Template Inheritance

Created a reusable `base.html` template and extended it from `index.html` to avoid repetition and follow better project structure.

---

### Request–Response Lifecycle

Understood how a browser communicates with a Flask application.

```
Browser
    │
HTTP Request
    │
Flask
    │
Route
    │
Python Function
    │
Jinja2 Template
    │
HTTP Response
    │
Browser
```

---

## 🎯 Purpose

This repository serves as my personal learning notebook while studying Flask fundamentals.

The focus is on understanding concepts, writing code from scratch, and building a strong foundation before developing larger applications.

---

## 🛠️ Tech Stack

- Python
- Flask
- Jinja2
- HTML5

---

## 🌱 Learning Philosophy

Instead of copying complete applications, I prefer to understand the "why" behind every line of code.

This repository reflects that approach by documenting concepts incrementally as I learn them.

---

## 📌 Status

✅ Flask setup

✅ Virtual environment

✅ Basic routing

✅ Jinja2 template inheritance

✅ Request–Response lifecycle

🔄 Next: HTML Forms and GET vs POST

---

*This repository is intended for learning purposes and documents my progress while studying Flask and web development fundamentals.*
