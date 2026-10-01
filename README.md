# Employee Directory (Django)

A Django web app that keeps employee records in one place: name, photo, role/responsibilities and salary, instead of scattered spreadsheets.

## Features
- Add, view, edit and delete employee records
- Employee photo upload
- Role and responsibilities per employee
- Django admin panel for managing data
- Config and secrets kept in a `.env` file (not committed)

## Tech Stack
| Area | Tools |
|------|-------|
| Backend | Python, Django |
| Frontend | HTML, CSS, JavaScript |
| Version control | Git, GitHub |
| Dev tools | VS Code, Windsurf (AI assistant) |

## How AI was used
- **Windsurf (AI coding assistant):** scaffolded the initial project structure and boilerplate.
- **Me:** wrote and debugged the core logic (models, views, templates, static files), fixed template syntax errors, and configured static/media handling.
- I was learning Django from scratch while building this, so AI sped up boilerplate while I made sure I understood each part.

## Screenshots
Add your screenshots to the `screenshots/` folder and they will show here.

| Employee list | Add / edit employee | Admin panel |
|---|---|---|
| ![List](screenshots/list.png) | ![Form](screenshots/form.png) | ![Admin](screenshots/admin.png) |

## Run locally
```bash
git clone https://github.com/<your-username>/employee-directory.git
cd employee-directory

python -m venv venv
source venv/Scripts/activate      # Git Bash on Windows
# venv\Scripts\activate           # Windows CMD / PowerShell

pip install -r requirements.txt

cp .env.example .env              # then edit values in .env

python manage.py migrate
python manage.py createsuperuser  # optional, for admin panel
python manage.py runserver
```
Open http://127.0.0.1:8000/

## Roadmap
- [ ] Search and filter employees
- [ ] Natural-language search using an LLM (planned, not built yet)
- [ ] Dockerize and add CI

## Author
**Charan Pittala**, MCA graduate (2026), Hyderabad.
Skills: Python, SQL, Snowflake, Power BI, Django.
