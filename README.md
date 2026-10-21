# odoo19-demo

Demo repository for Odoo 19 Community.

## Setup
1. Clone Odoo 19 Community into `src19/com`
2. Create a virtualenv and run `pip install -r src19/com/requirements.txt`
3. Copy `odoo.conf.example` to `odoo.conf` and set your DB credentials
4. Run: `python src19/com/odoo-bin -c odoo.conf -d demo19 -i base`
