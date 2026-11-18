><> ascii fish tank

A full-screen ASCII ocean in the browser. Fish swim in from the edges, big fish eat small fish, and you can tap anywhere to drop food. Small fish that eat enough grow into big fish.

It's written in Python and runs in the browser on PyScript (MicroPython). There's no build step and no server code. The whole thing is one index.html.

Run it
python3 -m http.server

Then open http://localhost:8000.

Tweak it

All the settings are at the top of the Python code in index.html:

small / big: the fish shapes
castle: the sandcastle
how_many(): how many fish are on screen