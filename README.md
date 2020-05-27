Casual Modeling is a very common task in economics/government/business analytics. In this project, my objective is to estimate the casual impact of Progresa program on the schooling outcomes of individuals in Mexico. I have focussed on the impact of the program on the poor, since only the poor were eligible to receive the Progresa assistance.

To analyze the casual effect, I have used the following estimators -
1. Before-After estimator
2. Cross-sectional estimator
3. Differences-in-differences estimator

Lastly, I have clearly stated the underlying assumptions behind each estimator and compared the results of all three estimators.

Background Information - Progresa was a a government social assistance program in Mexico. This program, as well as the details
of its impact, are described in the paper "School subsidies for the poor: evaluating the Mexican Progresa
poverty program", by Paul Shultz.

The timeline of the program was: <br>
 Baseline survey conducted in 1997 <br>
 Intervention begins in 1998, "Wave 1" of data collected in 1998 <br>
 "Wave 2 of data" collected in 1999 <br>
 Evaluation ends in 2000, at which point the control villages were treated. <br>

Each row in the data corresponds to an observation taken for a given child for a given year. There are two years of data (1997 and 1998), and just under 40,000 children who are surveyed in both years. For each child-year observation, the following variables are collected:
year year in which data is collected <br>
sex male = 1 <br>
indig indigenous = 1 <br>
dist_sec nearest distance to a secondary school <br>
sc enrolled in school in year of survey (=1) <br>
grc grade enrolled <br>
fam_n family size <br>
min_dist min distance to an urban center <br>
dist_cap min distance to the capital <br>
poor poor = "pobre", not poor = "no pobre" <br>
progresa treatment = "basal", control = "0" <br>
hohedu years of schooling of head of household <br>
hohwag monthly wages of head of household <br>
welfare_index welfare index used to classify poor <br>
hohsex gender of head of household (male=1) <br>
hohage age of head of household <br>
age years old <br>
folnum individual id <br>
village village id <br>
sc97 enrolled in school in 1997 (=1) <br>
