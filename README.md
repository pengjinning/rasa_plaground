# rasa_plaground

- <https://rasa.com/docs/rasa/installation/>

```bash
python3 -m venv ./venv
# Activate the virtual environment:
source ./venv/bin/activate
.\venv\Scripts\activate # windows
# Install Rasa Open Source using pip (requires Python 3.7, or 3.8).
pip3 install -U --user pip && pip3 install rasa
# 报错：ERROR: Can not perform a '--user' install. User site-packages are not visible in this virtualenv.
# 修改 pyvenv.cfg 中 include-system-site-packages = true，然后 source ./venv/bin/activate
# brew install postgresql
# pip3 install psycopg2
```
