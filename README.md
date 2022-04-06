# Pymaceutical_ANOVA_Tukey

# Analysis of Drug Treatments on the Reduction of Tumor Volume and Metastasis

For this Project, I first applied an analysis of variance (ANOVA) model to the Pymaceutical dataset and then did a post-hoc analysis of the results by using Tukey Honest Significant Difference (HSD) to determine which drug treatments in the dataset significantly reduce tumor volume and metastasis. I then wrote a summary of my findings.

## Steps

1. Read the `Pymaceutical_data.csv` file into a DataFrame.

2. Determined which drug treatments significantly reduce tumor volume by completing the following:

    * Created a box plot that compares the drug regimens with tumor volume.

    * Created a Series of data for each drug treatment that has the tumor volume for each mouse.

    * Performed ANOVA to compare the means of the tumor volume for each drug regimen.

    * Perform eda pairwise Tukey HSD test to compare the means of the tumor volume for each drug regimen.

    * Answered the following question: Which drug treatments significantly reduce tumor volume? Used the statistical analysis to support my results.

3. Determined which drug treatments are more effective than the others at reducing the number of metastatic sites at 45 days by completing the following:

    * Created a new DataFrame that contains data from the the last time point&mdash;that is, 45 days.

    * Create da box plot that compares the drug regimens and metastatic sites.

    * Created a Series of data for each drug treatment that has the number of metastatic sites for each mouse.

    * Performed ANOVA to compare the means of the metastatic sites for each drug regimen.

    * Performed a pairwise Tukey HSD test to compare the means of the number of metastatic sites for each drug regimen.

    * Answered the following question: Which drug treatments significantly reduce the number of metastatic sites? Used the statistical analysis to support your results.

4. Wrote a summary based on both statistical analyses.

