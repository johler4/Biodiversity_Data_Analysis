# biodiversity
Biodiversity Data Analysis Project

For this project, I will interpret data from the National Parks Service about endangered species in different parks.

I will perform some data analysis on the conservation statuses of these species and investigate if there are any patterns or themes to the types of species that become endangered. During this project, I will analyze, clean up, and plot data, as well as pose questions and seek to answer them in a meaningful way.

### Skills
Python, Matplotlib, Pandas, data cleaning, exploration, analysis, and visualization, communicating results.

## Project Scoping:
1) Problem Understanding: What is the problem? Who does it impact and how much? How is it being solved today and what are some of the gaps?
   - The problem is species of plants and/or animals that may be going extinct. The problem impacts the species directly, and can have the potential to affect us as humans. Efforts may be in place to combat extinction of species that we already know are endangered, but keeping up to date information about levels of endangerment for all species will help us focus efforts towards other species that may also need it.
2) Goals: What are the goals of the project? How will we know if our project is successful?
   - The goals of this project are to find what species are currently endangered or at risk of going extinct, and to find correlations, if there are any, within our available data that may give insight as to why certain species are being affected. The minimum expected success of our project is to find what species are endangered. The next level of success would be to find reasons why these species are at a certain level of endangerment. The bigger success would be to find any correlation between variables that could help identify any possible future species that may be endangered. 
3) Actions: What actions or interventions will this work inform? What actions can the organization take to achieve their goals?
   - If we find certain species of animals that are allowed to be hunted are at risk of being endangered/extinct, then an action could be to restrict the hunting period or eliminate it altogether. If a plant that grows in a certain area of the woods is at risk, then the action could be to move foot-paths or trails to steer away from where that species of plant is growing.
4) Data: What data do we have access to internally? What data do we need? What can you augment from external and/or public sources?
   - We have access to two .csv files; obsevations.csv(scientific_name, park_name, observations), and species_info.csv(category, scientific_name, common_names, conservation_status). We would like to know the period of time that the 'observations' took place over, but other then that, we can analyze and manipulate this data to find possible useful information.
5) Analysis: What analysis needs to be done? Does it involve description, detection, prediction or behavior change? How will the analysis be validated?
    - We need to look at our available variables to fin counts of some things, to find which values in some columns fall in specific categories of other columns, and to see which variables we can compare to find correlations, if any. Some things we need to find are: levels of endangerment, the type and number of species that are in each level, category counts of each status level, what observation count equates to what level of endangerment, the count of one species possibly affecting the count of another (ie: mice and hawks, wolves and deer, bears and fish), how the counts at each park compare for species on our endangered lists, etc.
