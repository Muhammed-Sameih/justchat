# JustChat Project

<details>
<summary>Table of content</summary>

- [Description](#description)
- [Features ✨](#features-)
- [Project structure](#project-structure)
- [Installation 📥](#installation-)
- [Tech/Framework used 🧰](#techframework-used-)
</details>

## Description

Welcome to our JustChat project! This project is live chat rooms is a simple web application that allows users to create chat rooms and communicate in real-time with other participants. With Live Chat Rooms, users can easily enter a room by simply entering its name, and then send and receive messages to and from any other user in that room.

## Features ✨

1. `Create and Join Rooms:` Create and Join Rooms: Users can create their own chat rooms and invite others to join, or join existing rooms by entering the room name.

2. `Real-Time Messaging:` All messages are sent and received in real-time, providing a seamless chat experience.

3. `Multiple Participants:` Any number of users can join a room, and all messages are visible to all participants.

4. `Simple and Intuitive Interface:` The interface is easy to use and requires no special training or technical expertise.

5. `Responsive Design:` The web application is designed to work seamlessly across all devices, including desktops, tablets, and mobile devices.

## Project structure

<details>
<summary>Click to expand!</summary>

```bash
## Project Structure


  justchat
    ├── build_env.sh
    ├── chat
    │   ├── admin.py
    │   ├── apps.py
    │   ├── consumers.py
    │   ├── __init__.py
    │   ├── migrations
    │   ├── models.py
    │   ├── __pycache__
    │   ├── routing.py
    │   ├── templates
    │   │   ├── index.html
    │   │   └── room.html
    │   ├── tests.py
    │   ├── urls.py
    │   └── views.py
    ├── justchat
    │   ├── asgi.py
    │   ├── __init__.py
    │   ├── __pycache__
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── manage.py
    ├── README.md
    └── requirements.txt


```

</details>

## Installation 📥

#### Clone Project

```bash
git clone https://github.com/Muhammed-Sameih/incomeexpensesapi.git
cd incomeexpensesapi
git checkout main
rm -rf .git
git init .
git branch [branch-name] # make it descriptive
git add [file]  # individual commits for each file are prefered
git commit -m "Your Commit Message"
```

### Create virtual environment and activate it

```bash
python -m venv venv
source venv/bin/activate
```

Use `.\venv\Scripts\activate` if on windows

### Install requirements

###### Run redis docker image

```bash
docker run -p 6379:6379 -d redis:5
```

###### Give Permissions to build_env.sh file

```bash
chmod +x build_env.sh
sudo ./build_env.sh
#################### OR ###################
(venv) python -m pip install pip --upgrade
(venv) python -m pip install -r requirements.txt
```

###### Open VSCode & Start Coding

```bash
cd /path/incomeexpensapi
code .
```

## Tech/Framework used 🧰

- [Django framework](https://www.djangoproject.com/)
- [Django Channels](https://channels.readthedocs.io/en/stable/index.html#django-channels)
- [Git](https://git-scm.com/)
- [Daphne](https://pypi.org/project/daphne/)
- [docker](https://docs.docker.com/)
- [redis docker image](https://hub.docker.com/_/redis)
- [selenium](https://selenium-python.readthedocs.io/)
- [VSCode](https://code.visualstudio.com/)
