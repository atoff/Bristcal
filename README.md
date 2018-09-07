# Bristcal
A simple python script to pull your University of Bristol course timetable into .ics (iCal) format, allowing it to be imported directly in almost every calendar app

Originally based on [SotonCal](https://github.com/aliaksei135/sotoncal) by [Aliaksei Pilko](https://github.com/aliaksei135)

# Installation
1. Download and extract the source to your computer.
2. Install [Python 3](https://www.python.org/downloads/)
3. Open a command prompt, and install the following python packages if you don't have them already (using `pip install <package>`): icalendar, beautifulsoup4, lxml

# Usage
1. Copy the 'secrets.py.example' file, and rename it to 'secrets.py'. Then edit the contents of the 'secrets.py' file, filling in your details.

> Username is you full University email address (e.g ab12345@bristol.ac.uk), Password is your password and coursecode is the programme "name" found at https://www.bris.ac.uk/timetables/myprogrammes.html

2. Open a command prompt and run the script (`py uobical.py`) *or* double click on the `run.bat` file. Once it is complete, there will be a 'UOBTimetable.ics' in the same directory as the script
3. Import the file into your preferred calendar
4. Relax in the comfort that you no longer have to trawl through the timetables site...
