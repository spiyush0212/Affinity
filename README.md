# Affinity

A child welfare management platform that streamlines adoption, fostering, welfare home administration, and donation management through a centralized web application.

## Features

* Child record management
* Adoption workflow management
* Foster care management
* Welfare home administration
* Donation tracking
* Government agency integration
* Secure user authentication

## Tech Stack

**Backend**

* Flask
* Python

**Database**

* MySQL

**Frontend**

* HTML
* CSS
* Bootstrap
* Jinja Templates

## Project Structure

```text
Affinity/
├── website/
│   ├── app.py
│   ├── templates/
│   ├── static/
│   └── AffinityLib/
├── Embedded Queries/
└── Database Schema Files
```

## Setup

```bash
git clone https://github.com/spiyush0212/Affinity.git
cd Affinity

pip install flask
pip install mysql-connector-python
```

Configure MySQL and import the provided SQL schema files.

Run the application:

```bash
cd website
python app.py
```

## Database Entities

* Child
* Welfare Home
* Adoptive Parent
* Foster Parent
* Biological Donor
* Government Agency
* Donation
