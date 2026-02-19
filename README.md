# AI Job Hunting System (Flask)

## Local Run
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

cp .env.example .env
# Set OPENAI_API_KEY in .env

export FLASK_APP=app
flask run

## Railway Deploy
1. Push to GitHub
2. Connect to Railway
3. Add Postgres plugin
4. Set OPENAI_API_KEY and SECRET_KEY
