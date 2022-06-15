# Graph Portfolio

This reposity contains a sample of the graphs I've produced throughout my career.


## Heat map / dendrogram of childhood vaccine histories

This plot was made as part of a (currently unpublished) project investigating patterns of the timing of childhood vaccinations and in particular patterns of delay (or outright skipping) of different vaccines in a sample of privately insured children. The data were deidentified and a small amount of noise added to the vaccination dates prior to plotting.

The motivation for this graph was to explore how vaccination histories could be used to cluster patients into groups. It uses daily indicator variables for presence/absence of each vaccine in the first year of life. If patients likely to delay or skip vaccines could be identified using early vaccine histories, timely reminders could be provided or outreach efforts used to address concerns of parents.

![Heat map / dendrogram of early childhood vaccination histories](/output/clusters.png)

Patient histories are shown on the horizontal axis; presence/absence of each vaccine from 30 days to one year of life are shown on the vertical axis. Blue regions represent absence of the vaccine, orange regions represent the presence of vaccine, and white regions represent missing data (i.e., insurance disenrollment). The size of the data set makes a direct visual inspection of the clusters difficult. This plot contains a random sample of 1,000 patient histories (with the data set in /ecv/data/ itself being a 1% sample of the complete analytic file). Nevertheless, we can see a cluster of patients with a significant proportion of their histories colored blue, indicating delay or skipping of recommended vaccinations.