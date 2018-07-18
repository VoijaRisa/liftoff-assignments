# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
One of my hobbies is medieval reenactment. Within that, I have undertaken a large project to recreate the state of knowledge of astronomy in the late 16th century by reproducing instruments and techniques used by Tycho Brahe, Johannes Kepler, and others. In particular, Brahe used decades of observations to create the first star charts since antiquity with the posthumus publication of the Uranometria.

As creation of a similar star chart is part of my project’s goals, I will need to take in data and for each object. Since this data is taken in a coordinate system that is fixed to the sky and not the celestial sphere, the data will first need to be converted to a static coordinate system (Right Ascension-Declination), and for each object have averages calculated as well as parameters exploring systematic and observational error calculated. These values will be validated and compared against the astronomical database Set of Identifications, Measurements, and Bibliography for Astronomical Data (SIMBAD).

### Features
1. Add star - Adds a new star to the catalog
2. Add observation - Add an observation to an individual star
3. Coordinate system conversion - Freely converts observations from Alt-Az to RA-Dec
4. Unit conversion - Flexibly display observations in both decimal and HMS units
5. Search - Finds an individual star and displays all observations
6. Statistics - Calculates various important figures
    a. Positional average - Takes all observations for an individual star and calculates the average
    b. Standard deviation - Calculates a standard deviation for each object
    c. Position vs “true” error - Uses modern value of position for each star to compare average and modern value and determine error
    d. Instrumental error - Searches all observations and compares to true positions to search for large trend error indicative of instrumental error
8. Star Map - Displays a 2D map of the celestial sphere with the position for each star displayed
    a. Error bars - Displays statistical uncertainty as error bars
8. Observational scheduling tool - From a list of entered stars, produces a list of objects that will be easily visible that night from a given location between ~9pm and 3am for follow up observations. (Stretch goal due to complex math)


### Technologies
Java
Gradle
MySQL
Spring
Hibernate
HTML
CSS

### What I'll Have to Learn
Javascript graphing tools.
