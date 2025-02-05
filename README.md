# Flask Web Application

## Project Overview
This is a simple Flask web application that serves an HTML page using Jinja2 templating.

## Project Structure
```
C:\softronics_machine_test\
│── app.py                # Main Flask application
│── /templates            # Folder containing HTML templates
│   └── index.html        # Homepage template
```

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo/flask-app.git
   cd flask-app
   ```

2. **Create a virtual environment (optional but recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

## Running the Application

1. **Ensure the correct folder structure** (index.html should be inside a `templates/` folder)
2. **Run the Flask app**
   ```sh
   python app.py
   ```
3. **Open the browser and visit:**
   ```
   http://127.0.0.1:5000/
   ```

## Troubleshooting

- If you get `jinja2.exceptions.TemplateNotFound: index.html`, ensure that your `index.html` is inside a `templates` folder.
- Restart Flask if changes are not reflecting.

## License
This project is licensed under the MIT License.

---

Feel free to modify this `README.md` based on your project requirements. 🚀

