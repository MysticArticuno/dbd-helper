# Dead by Daylight Helper
Single Page Application created by Grayson murdock

## Background

Dead By Daylight is an asymmetrical 4 vs 1 survival game where four players assume the role of survivors and one player assumes the role of a deadly killer. The objective of the survivors is to repair a total of five out of seven generators scattered around the playable area, while the objective of the killer is to attack, injure, and sacrifice the survivor on one of many sacrificial hooks scattered around the playable area. Each side has different tools to work with to help them accomplish their goal. The survivors can bring items and work as a team to efficiently repair all of the generators, and the killer can use their special power to assist them in catching the survivors. Every killer has a unique power which can drastically change the way they go about completing their goal. Both sides can utilize boosts known as perks to provide benefits to themselves. A total of four different perks can be brought into a game by each player. Survivors and killers each have different perks to choose from. With a total of 35 killers and 255 different perks to choose from, it can get complicated to remember precisely what every perk does, especially in the heat of the moment. This SPA is intended to make reading up on perks and killer powers easy and quick, and is intended to be used alongside the game.

This project contains two parts, the frontend SPA, and a backend REST API that serves both images and details about the perks and powers

## Installation

### Setting up the backend:
Open a terminal window in the API directory.
Please download and install [Python](https://www.python.org/downloads/), if you haven't already.
Verify that Python is installed correctly by running `py -V` or `python3 -V`
Python should display the currently installed version. If it does not, [please ensure that Python is added to the system path](https://realpython.com/add-python-to-path/).
Once Python is verified to be working correctly, create a virtual environment (venv) to ensure the program functions correctly.
```
python3 -m venv .venv
./.venv/Scripts/activate
```
Next, install Flask
```pip3 install flask```
Once flask is installed, run the following command to start the server
```flask --app ./flask-server.py run```

### Setting up the frontend:
nah not rn i dont feel like typing more
