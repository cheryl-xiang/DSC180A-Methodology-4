Cheryl Xiang, c3xiang@ucsd.edu

DSC180A D06- Dr. Duncan Watson-Parris

**1. What is the most interesting topic covered in your domain this quarter?**
The most interesting thing we have covered in our domain this quarter was when we evaluated the climatology of SPEEDY and JAX-JCM against large Earth System Models such as ERA5 and NorESM2. Something we analyzed when comparing the climatologies was zonal-mean cross sections of temperature and wind, specifically looking at different vertical sigma levels of the atmosphere at different latitudes. It was very interesting to seen patterns of bias in the SPEEDY model, where there was too much or too little warming/wind and see how this bias was amplified during certain seasons. It was very useful to see where the SPEEDY model could perform well, and what areas we would need to alter so it can more closely emulate the climatology of our planet.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
Something I am interested in pursuing next quarter is improving the methods we use to model the Earth's oceans and ocean currents. Currently, we have only implemented a slab ocean model, which is essentially just a large, well mixed bucket of water about 50m deep all around. This means that our current ocean cannot simulate aspects like the ocean layers, and the deep ocean, currents and convection in the ocean, and other phenomena like upwelling. I want to try implementing a more accurate ocean model in order to create better emulators for different emissions scenarios.


**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
For our current project, we need to use some domain knowledge of climate and androgenic emissions in order to run and understand the climate emulators and JCM/JEM models. For the most part, my group and I learned the new technologies like JAX and xarray in tandem with domain concepts. I believe our progress could be more streamlined if went through more of the the domain knowledge prior to implementing the first emulators, because it was occaosionally difficult to interpret results and graphs, when I was not sure what I should be expecting. After a few weeks, I went ahead and read a few relevant chapters in two climate science textbooks, and found it much easier to implement the code and models afterwards. 


**4. What other techniques would you be interested in using in your project?**
I am interested in using JAX to create differentiable climate emulators. When we reproduced ClimateBench in week 3, most of the baseline emulators were not differentiable, which limited how much analysis we could perform based on the emulators' outputs. With differentiable emulators we could potentially determine how different emissions create effects on a regional and temporal level. I am also interested in seeing if emulator gradients have any physical meaning.