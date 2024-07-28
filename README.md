# Hazardous-Asteroid-Prediction-Near-Earth

This dataset contains information about asteroids orbiting earth. It is important to understand objects close to earth, as they can impact the earth in many ways and distrupt the earths natural phenomena. Information about the size, relative velocity, distance from earths orbit, sentry object and the magnitude of the luminosity of the asteroid can help experts identify whether an asteroid poses a threat or not. There are many asteroids which are nearer to the earth, but all are not hazardous. So, the target in this project is to predict the asteroids is dangerous for the earth or not, and attempt to create a model to predict whether or not an asteroid is potentially hazardous.

The attributes of this dataset are:

id : identifier (the same object can have several rows in the dataset, as it has been observed multiple times)
name : name given by NASA (including the year the asteroid was discovered)
est_diameter_min : minimum estimated diameter in kilometers
est_diameter_max : maximum estimated diameter in kilometers

relative_velocity : velocity relative to earth

miss_distance : distance in kilometers it misses Earth
orbiting_body : planet that the asteroid orbits
sentry_object : whether it is included in sentry - an automated collision monitoring system
absolute_magnitude : intrinsic luminosity

hazardous : whether the asteriod is potentially harmful or not

This dataset has 10 columns and 31249 rows.
