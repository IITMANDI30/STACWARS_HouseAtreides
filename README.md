**House Atreides --- STAC WARS (PS1, PS2 & PS3)**

This repository brings together our work on the three STAC WARS problem
statements. Each problem was different, so we had to switch between
engineering, working with data, and using astronomy to make sense of a
possible new home beyond Earth.

The main idea throughout was to understand why the results made sense,
rather than just show an answer.

What's in the project?

PS1 --- Rocket design and simulation
For the rocket problem, we worked with the mission constraints,
including a two-stage setup, a 1 kg payload, and a target altitude of
4,000 m. We used OpenRocket to explore the design and understand how the
different choices affected the flight.
The simulation met the listed requirements, but we also noted that a
real build would need extra attention to the shock cord and deployment
loads.

PS2 --- Solar radiation data analysis
For this problem, we analysed solar prediction data using Python. The
raw dataset stored the date and time separately, so the first step was
to combine them into a proper datetime column. Getting that right made
it easier to analyse the readings by time and by day.
We looked at both daily plots and the dataset as a whole, then compared
the patterns we could see. We also found the time of the highest
radiation reading for each day and ranked the strongest readings.

PS3 --- Exoplanets and habitability
The third problem focused on identifying which candidate exoplanet might
be the best option for further study. We compared repeating transit
dips, estimated planet sizes from transit depth, and used orbital
periods and stellar mass to estimate orbital distances.

STAC-3 came out as our strongest candidate based on the comparisons
in our analysis: it was closest to the habitable zone, had an Earth-like
estimated temperature, and was likely rocky. That is not proof that it
could support life, though. More evidence --- especially spectroscopy
--- would be needed to understand its atmosphere and conditions.

Tools and concepts used
- Python for working with and analysing the solar dataset
- Pandas and NumPy for data processing
- Data visualisation to inspect solar-radiation patterns
- OpenRocket for rocket design and simulation
- Transit depth and Kepler's third law for estimating exoplanet
  properties
- Habitable-zone comparisons to assess the candidate planets
Main takeaways
- A rocket simulation is useful not only for checking whether
  requirements are met, but also for spotting practical issues that
  need attention.
- Cleaning and understanding the data comes before drawing conclusions
  from plots or summary statistics.
- Exoplanet habitability estimates depend on assumptions, so a
  promising candidate should be treated as a starting point for
  further investigation, not a confirmed second Earth.
Repository contents
The repository contains the files associated with the three STAC WARS
problem statements, including the presentation and the relevant project
materials.
A note on the results
The values and conclusions here are based on our project analysis and
its assumptions. In particular, simulated rocket behaviour is not the
same as a real flight, and a planet's position in or near the habitable
zone does not by itself establish that the planet is habitable.
