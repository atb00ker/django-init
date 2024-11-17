<Change "Project Title" everywhere in the template to init repository>

# Project Title

Project Title

## Getting Started

### Prerequisites

### Setup Repository

1. Setup environment variables: Copy 'sample.env' to '.env' and set appropriate values.

2. Setup Python

```sh
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

3. Run Django

```bash
cd src/
python manage.py migrate
python manage.py runserver
```
