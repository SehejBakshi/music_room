# Music Room
A shared room for everyone to play songs in and enjoy! Built using Django and React, and integrated with Spotify API.

## Setup Instructions

### Install Required Python Modules

```bash
1. django
2. djangorestframework
```
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
- [ ] Add functionality to give names to users' device
- [ ] Add list of names of devices connected 
- [ ] Give users permission to add songs to play
