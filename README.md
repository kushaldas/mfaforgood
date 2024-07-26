# Multi-factor authentication in Django

This is an example project show casing how to enable [Multi-factor
authentication (MFA)](https://en.wikipedia.org/wiki/Multi-factor_authentication) in a Django
web application. One can use TOTP based phone applications or hardware token
(say Yubikey) for this example project.


## Install / Usage

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
./manage.py migrate
./manage.py createsuperuser
./manage.py runuser
```

Then visit the [home page](http://localhost:8000/).


