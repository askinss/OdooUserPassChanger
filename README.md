# OdooUserPassChanger

Python script to change the password of an Odoo ERP user.

I didn't remember admin password in a testing Odoo installation that I did for a classroom practice, so I was trying to recover or change it. The faster idea I thought was to change the password in the DB. So I thought to make this script to if it happens again it could fix faster.

The script will ask for DB connection settings, user what you want to change the password and the password you want to set to that user. When data are entered the script will connect to the Odoo PostgreSQL DB and will make an update in the DB with the new password for the user.

**NOTE:**
There're two scripts, one for [Python 3](https://github.com/jesusdanielcf/OdooUserPassChanger/blob/master/OdooUserPassChanger.py) and another one for [Python 2](https://github.com/jesusdanielcf/OdooUserPassChanger/blob/master/OdooUserPassChanger.py) version.
