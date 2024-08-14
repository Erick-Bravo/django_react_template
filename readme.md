## Django Template

### Evironment
To start local env:
- `source env/bin/activate`

Dependencies are located in the Requirments.txt file <br/>
This will install dependencies:
- `pip install -r requirments.txt`


### Migrations
When creating backend items, follow these steps for migrations
- create serializer (serializer.py)
- import into views (api/views.py)
- create api path (backend/url.py)

Once item is created, input these commands to finalize migration:
- `python3 manage.py makemigrations`
- `python3 manage.py migrate`