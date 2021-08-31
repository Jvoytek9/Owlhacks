# What is this
A school hackathon. I used the surfactant dashboard I had been crafting during my time researching and manipulated it to work with Philly bailfund data for this hackathon. Overall, a bit buggy since it was a 24hr hackathon. However, this project helped me realize I could port the surfactant dashboard and do more with it, so I made it easier to change datasets come the data challenge.

This is implementation 2/3 of the portable dashboard I had been producing.

# Installation
If interested in running a local version, clone this repo and make sure to have pip installed.

Then, make a separate virtualenv like so (this example makes a virtual environment named venv at the given path): python -m venv c:\path\to\myenv

copy the contents of the cloned repo into this new venv folder. Activate the venv like so: cd venv\path\to\myenv\Scripts then type "activate" and hit enter

The name of your venv should appear next to the command prompt. Now type: cd ..

And finally: pip install requirements.txt

Then, running the app/app.py file in your editor of choice will boot up a local Flask server, which you can then do as you please with.
