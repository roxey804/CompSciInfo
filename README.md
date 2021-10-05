# CompSci Info
Things a computer scientist might know but a bootcamp/hobby coder won't!

## HTTP Requests and the like

### GET

### POST

### PUT

### Payload
The payload is the part of transmitted data that is the **actual** message. Headers and other metadata are sent only to enable payload delivery
e.g. 

### Client vs Server
You are the client and the server is what you connect to via the internet or another network

## Structure of your application 

### Makefile
A Makefile should be used in a project repo to automate common tasks such as running the app, running tests, cleaning out files etc. Makefiles should be prefered to custom bash scripts / python scripts.

Makefiles consist of "targets" (think of these as jobs / modes e.g. "run"), dependencies (e.g. if a target depends on another target) and sequences of commands to run (the 'recipe')

The primary API for a Makefile is:

clean - Clean out unwanted files or files compiled / built during a build step (includes e.g. .pyc files)
deps - Install dependencies for the project - e.g. Python requirements or Javascript modules.
build - Build the app. This can include running DB migrations, inserting non-user data, compiling modules etc.
test - Run the test suite.
run - Run the app
install - Install the app - e.g. when using setup.py
