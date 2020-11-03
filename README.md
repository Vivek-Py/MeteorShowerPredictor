# Inspiration
Looking into the night sky and seeing stars, planets, and meteor showers can often kindle a scientific and imaginative curiosity about our universe. On one hand, you might feel awe about what we collectively know about the universe, thanks to the scientists, engineers, and astronauts who have built upon collective knowledge for hundreds of years. On the other hand, you might feel an otherworldly wonder about the stories you've heard about what causes meteor showers or who lives on the Moon. These perspectives often drive each other. New scientific discoveries create new narratives for films, and fiction provides us with the creativity to solve real problems in new ways.

<p align="center">
<img src="meteor-showers/images/meteorshower.gif" alt="animated" />
</p>

## Requirements
Python must be installed in your system with the modules like ipykernel, jupyter-client, jupyter-core, etc. In case you haven't installed any of these, There's a requirements.txt file here which will install all the required modules for you. In order to install from the file, copy and paste this command: 
```python
pip install -r requirements.txt
```
<strong>Or,</strong>
```python
python3 pip install -r requirements.txt
```

We've started to gather some data for the example in this module. On your own, try to find additional data that will help you explore the predictions of meteor showers.

## Data Sources
Here's the data we've already gathered:
<ul>
<li>moonphases.csv  - This file contains the Moon phases for every day of 2020. The missing data will be added in the next unit. (Data acquired from <a href="https://www.timeanddate.com/moon/phases/">timeanddate.com</a> )</li>
<li>meteorshowers.csv  - This file contains data for each of the five meteor showers that we described earlier. Data includes their preferred viewing month, the months when they're visible, and the preferred hemisphere for viewing. (Data acquired from <a href="https://solarsystem.nasa.gov/asteroids-comets-and-meteors/meteors-and-meteorites/in-depth/">NASA</a>)</li>
<li>constellations.csv  - This file contains data for the four constellations that are radiants for the five meteor showers. Data includes the latitudes for which they're visible and the month for the best viewing. (Data acquired from <a href="https://en.wikipedia.org/wiki/IAU_designated_constellations">Wikipedia</a>)</li>
<li>cities.csv  - This file contains a list of country capitals and their associated latitudes. (Data acquired from <a href="https://en.wikipedia.org/wiki/List_of_national_capitals_by_latitude">Wikipedia</a>)</li>
</ul>

## Other data to consider
This module focuses on the four data files. But you can also gather other types of data that might affect the likelihood of viewing a meteor shower:
<ul>
<li>Weather</li>
<li>Other comets or known meteors</li>
<li>City light pollution</li>
</ul>