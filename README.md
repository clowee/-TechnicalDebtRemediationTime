# TechnicalDebtRemediationTime

The repository contains the results and the data used in the paper "On the Accuracy of SonarQube Technical Debt
Remediation Time".

All of the data presented in the tables can be found from the Excel file [data_for_RQ1-RQ3.xlsx](data_for_RQ1-RQ3.xlsx). The file contains the following tabs:

* _Total TD items dist (RQ1)_

   The number of introductions per TD item for all of the analyzed projects.

* _Total type severity dist (RQ1)_

   The number of TD items introduced in the analyzed projects per different type and severity values. Please note that each rule has a type and a severity.
   
* _Fixed TD items dist (RQ2)_

   The number of fixed TD items per TD item in the analyzed projects.
   
* _Fixed type severity dist (RQ2)_

   The number of fixed TD items per different type and severity values. The table also reports the number of fixed items we could not identify from the student reports.
   
* _Remediation (RQ2 and RQ3)_
   
   The results from the analysis of remediation time accuracy. The table contains measures RE (mean), RE (median), MmRE, MdmRE, MAR, PRED25, and PRED50. The results calculated for all of the data as well as for all of the values of type and severity.
   
* _TD item desctiptions_

   The description, remediation time, type, and severity for all of the TD items SonarQube used to analyze the projects.
   
   
   
Folders [RQ1](RQ1) and [RQ2](RQ2) contain the data visualizations for all of the data.

* [RQ1/histograms_TD_item_distribution](RQ1/histograms_TD_item_distribution)

   Histograms visualizing the number of total TD items and fixed TD items (Figure 1 in the paper).
   
* [RQ1/total_item_introduction_boxplots](RQ1/total_item_ingroduction_boxplots)

   Boxplots for the total number of TD items in the projects. The folder contains the boxplots with and without outliers.
   
* [RQ2/boxplots_fixed_items_per_squid](RQ2/boxplots_fixed_items_per_squid)

   Boxplots for the number of fixed TD items in the projects. The folder contains the boxplots with and without outliers.
