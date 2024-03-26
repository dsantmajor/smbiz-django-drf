# Django Rest framework

## Setup virtual env

- python3.12 -m venv py312
  this will use the python 3.12 binaries to create a virtual env and place all bin and symlinks under py312 , general practice is to create virtual env under venv or .venv and use python(3) `python3 -m venv .venv` the -m is calling the module, in this install the venv module to create the virtual env
- next create the requirements.txt file
  ```bash
   django>=4.0.0,<=4.1.0
   djangorestframework
   pyyaml
   requests
   django-cors-headers
  ```
- now activate the virtual env
  `source py312/bin/activate`
- install django and additional packages
  `pip install -r requirements.txt`

## Setup folder structure

- create two directories one for backend and one for the client
  - `mkdir backend`
  - `mkdir py_client`
- change into the backend dir
  - `cd backend`
- start a django projects
  - `django-admin startproject <project-name> .`
  - `django-admin startproject organiserBe .`
- we should see 6 files there

  - ```bash

    ├── manage.py
    └── organiserBe
        ├── __init__.py
        ├── asgi.py
        ├── settings.py
        ├── urls.py
        └── wsgi.py

    ```
