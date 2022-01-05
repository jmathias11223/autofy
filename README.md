# Autofy - A Spotify Application

Autofy is an application intended to run in the background that will, every Friday, compile
a list of all music released in the past week by your favorite artists and create a playlist
to house that list.

------------------------------------------

How to run with scheduler:
nohup python3 scheduler.py &

How to run without scheduler:
python3 driver.py

Necessary packages: 
spotipy
tqdm
