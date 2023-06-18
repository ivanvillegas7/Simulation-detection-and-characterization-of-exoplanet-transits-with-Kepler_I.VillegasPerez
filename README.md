# Simulation, detection, and characterization of exoplanet transits' with Kepler space mission

During the last decade, the discovery and characterization of exoplanets (planets orbiting stars other than the Sun) have gained significant scientific and social relevance. To date, there are more than five thousand confirmed exoplanets in nearly four thousand planetary systems, with nearly ten thousand additional candidates awaiting confirmation. Thanks to these discoveries, we now have the certainty that the existence of planetary systems, perhaps not dissimilar to our own, is a common phenomenon in our galactic environment. Many of the exoplanet discoveries are attributed to the Kepler space observatory, which collected data from thousands of stars between 2009 and 2016. These data are publicly available, and many of them have yet to be fully analyzed.

In this project, we propose applying some of the stellar data analysis techniques used in the Corot mission to the study of light curves from stars observed by the more recent Kepler space mission. The objective is to improve the identification of exoplanets through the periodic decrease they cause in the star's luminosity during their transits across the stellar disk. Due to the intrinsic variability of stars and the presence of strongly non-Gaussian instrumental systematic effects, Kepler's light curves are very noisy. In our project, we will apply noise reduction techniques to optimize the detectability of exoplanets and the estimation of their physical parameters (period, distance to the star, temperature and, if possible, size).

In the initial phase, we will develop a code to realistically simulate data similar to what Kepler obtained, including the intrinsic stellar light curve, exoplanet transits, and non-Gaussian instrumental noise. These simulations will serve to study the effectiveness of the signal reduction and analysis techniques we intend to use. Once we determine the capabilities and limitations of these techniques, we will apply them to Kepler data, starting with well-known systems and then moving on to candidate systems where detection has not yet been confirmed with sufficient statistical significance.

In folder 'Code' all the most recent Python programs can be found. In folder 'Plots' can be found all the made plots using simulated data, and data from TrES-2 b and Kepler-75 b.
In folder 'Data' there are a couple data files from Tres2b and Kepler75b. 
To run the code, maintain the structure of the repository and simply run the main code ('main.py').
If you want to make the same simulation I did, check the final report ('Simulación, detección y caracterización de tránsitos de exoplanetas con la misión espacial Kepler.pdf') for the parameters.
