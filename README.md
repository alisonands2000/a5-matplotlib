#### a5-matplotlib
- All solutions in main.ipynb

# Pymaceuticals Inc.
## Analysis
- At the start of the analysis, there is a mouse_id with duplicated timepoints for the same drug, which could be incorrectly noted data and can affect the final data. The data for this mouse is dropped and a new dataframe without the mouse is created.
- We then look at the mean, median, std. dev and std. err on for each drug for all the mice over all timepoints. Here we can see which drug contributes to the largest and smallest tumours. In this case, Ketapril gives the largest tumor volumes given the mean and median data.
- In the Pie and Bar charts section, bar charts are provided to show the number of timepoints for each drug, in descending order. The pie charts show an almost even distribution between male and female Mice.
- In the ‘Quartiles, Outliers and Boxplots’, datapoints are taken for each mouse on each for the final timepoints. The IQR and final tumor is calculated across four drugs, Capomulin, Ramicane, Infubinol and Ceftamin. The only drug with an outlier is Infubinol, every other drug has points that fall within the IQR. This was attributed to mouse c326, female, and 18 months old.
- In the Line and Scatter plots section, we examine the capomulin treatment of mouse l509. Looking at the Tumor Volume, the tumor volume starts to decrease at around 20 days. We also see a positive correlation between the average tumor volume for Capomulin and the weight of the mice. The Tumor Volume is higher as the weight increases.
