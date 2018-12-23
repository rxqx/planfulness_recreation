# Associated files for the manuscript, "Predicting exercise with a personality facet: Planfulness and goal achievement".

Each data file is associated with a specific analysis file. The reasons for this are twofold: a) to preserve the participants' anonymity by removing any identifying information and b) different analyses excluded different participants for missing data; see manuscript for more details. These files include:

====DATA FILES====
1) A .csv file with participant data. This data has been a) cleaned of identifying information, b) cleaned of one participant with an irregular pattern of recreation center access (see manuscript and project pre-registration for details), c) scored in accordance with the original scoring procedures of the included scales, d) summed into number of check-ins per week for each of the twenty weeks observe (in order to preserve participants' anonymity). 
2) A .csv file that is the same as the above, but with aggregate count of check-ins for each ten-week term.
3) A .csv file that is the same as the above, but with individual scale item scores.
4) A .csv file with partcipant scale scores and three independent raters' ratings of the descriptiveness and planfulness of the partcipants' qualitative 'personal projects' free-responses. This data has been a) cleaned of identifying information, including individual participants' qualitative responses, b) cleaned of the same outlier participant as in 1), as well as cleaned of participants who did not provide a response to the 'personal projects' exercise (see manuscript and pre-registration), c) scored as in 1).

====ANALYSIS FILES====
1) A R script that runs a robust regression, regressing scores on the Planfulness Scale on count of check-ins to the recreation center.
2) A R script that builds and runs a piecewise latent growth curve model to test whether scores on the Planfulness Scale moderate check-in activity over time.
3) A R script that includes all personality scale scores in the same model predicting count of check-ins, per ten-week term.
4) A R script that runs all analyses associated with the hypotheses regarding the participants' qualitative 'personal projects' data (see manuscript and pre-registration).
