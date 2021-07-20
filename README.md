# Instagram clone

A personal blogging website where you can create and share your opinions and other users can read and comment on them.

## User stories

* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects
* View projects overall score
* View my profile page

## Technologies used

* Html,
* python.

## Installation and Setup

Clone the repository below

```
git clone https://github.com/{username}/{repo_name}.git
```

### Create and activate a virtual environment

    *sudo apt-get install python3_venv

    **python3 -m venv virtual

    ***source virtual/bin/activate

### Install required Dependencies

    pip install -r requirements.txt

### Copy environment variable

    cp env.sample .env

### Load/refresh .environment variables

    source .env

## Running the application

```
python manage.py server
```

## Endpoints Available

* update your available endpoints

| Method | Endpoint                        | Description                           | Roles         |
| ------ | ------------------------------- | ------------------------------------- | ------------  |
| POST   |        /auth/signup             | sign up a user                        | users         |
| POST   |        /auth/login              | log in  a user                        | users         |

## Author(s) information

> Ephraim Kamau Junior

## Contact information

> To collaborate, reach out to ephraimkamau54@gmail.com

## License and Copyright information

> The MIT License (MIT) Copyright © 2021 Ephraim Kamau Junior.
