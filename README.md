# Minimal reproduction instructions.

- `git clone git@github.com:ArmandoHerra/Profiles-REST-API.git`
- `cd Profiles-REST-API/`
- `vagrant up && vagrant ssh`
- `cd /vagrant/`
- `python -m venv ~/env`
- `source ~/env/bin/activate`
- `pip install -r requirements.txt`
- `python manage.py runserver 0.0.0.0:8000`