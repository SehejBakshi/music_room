# Music Room
A shared room for everyone to play songs in and enjoy! Built using Django and React, and integrated with Spotify API.

## Setup Instructions

### Install Required Python Modules

```bash
1. django
2. djangorestframework
```

### Add Credentials

Before starting the web server, make sure to make a <code>.env</code> file in the directory where your django settings file is located and write your Spotify Developer ClientID and SecretClientId in it.

<br>

| **WARNING**: If you try to build this app, make sure you have Spotify Premium as no controls will work on the web without Premium. |
| --- |

<br>

### Start Web Server

To start the web server you need to run the following sequence of commands.

Run the django web server in the main directory.
```bash
python manage.py runserver
```


To view the frontend, first install [Node.js](https://nodejs.org/en/)

### Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependencies.
```bash
npm i
```

### Compile the Front-End

Run the production compile script in the frontend
```bash
npm run build
```
or for development:
```bash
npm run dev
```
<br>

### To do

- [x] Integrate frontend with backend
- [x] Integrate app with Spotify API
- [x] Add Controls using API
- [ ] Integrate with Spotify Web Playback SDK
- [ ] Add functionality to give names to users' device
- [ ] Add list of names of devices connected 
- [ ] Give users permission to add songs to play
