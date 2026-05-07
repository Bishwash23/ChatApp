# ChatApp

Simple Django Channels chat application (ASGI).

## Overview

This project demonstrates a basic real-time chat using Django and Channels.

## Prerequisites

- Python 3.10+ (or compatible)
- Git (optional)

## Setup (Windows PowerShell)

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser  # optional
```

## Run

Use Django's dev server (Channels integrated):

```powershell
python manage.py runserver
```