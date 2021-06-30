## Project Directive
Load, clean, and chart pharmaceutical data of squamous cell carcinoma (SCC) within mice.

## Data Cleaning
Utilized pandas within a Jupyter Notebook to remove duplicate mice ID's to ensure a normalized dataframe.

## Charts
![Tumor Response to Treatment](Images/measurements_regimen.png)
![Male vs. Female](Images/measurements_regimen_pie.png)
![Treatment Type Box Plot](Images/boxplot.png)
![Tumor Volume over Time](Images/tumorvol_time.png)
![Tumor Volume vs Weight](Images/tumorvol_weight.png)

## Conclusions
1) When looking at the plot of tumor volume over time for mouse s185, it is easy to see correlation between the Capomulin regimen and reduction of tumor volume. One might be tempted to say that this means the Capomulin regimen reduces tumor volume in all subjects. However, it is important to note that this is a small sample size (n=1), and there could be other factors at play, so it is vital to focus only on correlation rather than causation when analyzing this graph.\

2) The box and whisper plot of final tumor volume by regimen is clearly showing that mice treated with Capomulin and Ramicane display more favorable results in terms of reduction of tumor size at the end of the trial. For Ramicane, the maximum final tumor size is similar to the minimums for Infubinol and Ceftamin (excluding outliers). Thus, the box and whisper plot could indicate that Ramicane is the most effective treatment.\

3) There is very weak correlation between average tumor volume and mouse weight, indicated by the correlation coefficient of -.23. The direction of the correlation (negative relationship) is unexpected, as one would expect tumor size to be loosely correlated with overall mouse size. However, the correlation shows that these two factors have little to no relationship.
