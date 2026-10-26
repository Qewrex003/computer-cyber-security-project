# 🚨 Сomputer-Сyber-Security-Project
Cybersecurity project demonstrating secure web development, user authentication, password hashing, SQL Injection (SQLi), Stored XSS, and vulnerability mitigation through vulnerable and secure implementations.


## Development Setup

### Requirements
- Python 3.10+
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/Qewrex003/computer-cyber-security-project.git
cd computer-cyber-security-project
```

Create a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

For Fish shell:

```fish
source .venv/bin/activate.fish
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

Create your environment file:

```bash
cp .env.example .env
```

Generate a SECRET_KEY using Python's secrets module
and set it in .env.

Run the application:

```bash
python app.py
```

Run tests:

```bash
python -m pytest -v
```

The application is available at:
http://127.0.0.1:5000
