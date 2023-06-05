# Water Quality

This project builds upon an analysis of a public health study conducted in rural Bangladesh (Gelman et al., 2004). The study examined arsenic contamination in drinking water wells and whether households switched wells. We measured several variables thought to influence well-switching decisions. Our goal is to predict household well-switching accurately based on these variables. The study collected data on arsenic levels (in hundreds of 𝜇g/L) in Araihazar, Bangladesh during 1999-2000. Additional information was obtained through a survey, including well-switching, distance to the nearest safe well, household involvement in community organizations, and highest education level. Arsenic contamination in drinking water is a global concern, affecting over 140 million people in 50 countries above the WHO guideline of 10 μg/L, with associated health risks (WHO, 2018a).

The data set: wells.csv 
See van Geen et al. (2002) Links to an external site. for a discussion of data collection. Briefly, arsenic levels (in hundreds  μg/L) were measured in Araihazar, Bangladesh during the years 1999 - 2000. Additional information was collected by a survey:
Whether or not the household switched wells.
The distance (in meters) to the closest known safe well.
Whether any members of the household are involved in community organizations.
The highest education level in the household.

In preparing our data, we undertook several essential steps. Firstly, we provided a comprehensive description of the data source, including relevant links to access the data whenever possible. Secondly, we carefully inspected the contents of each data set to gain a thorough understanding of their structure and contents. If needed, we performed data type conversions to ensure the columns were in the appropriate formats. To ensure data cleanliness, we removed any unnecessary parts from the data sets, such as duplicate entries or out-of-range values. From the available columns, we selected a subset that would serve as predictors in our analysis, omitting those that were not required. We also addressed missing values by either imputing them or removing rows with NaN values, depending on the situation. To conform to best practices, we organized the data frame in a tidy or long format. Additionally, if necessary, we renamed columns to adhere to conventions of lowercase, snake_case naming that is easily understandable. Finally, we created derived variables that would provide valuable insights for our analysis. These steps ensured that our data was appropriately prepared and ready for further analysis.

My data analysis notebook is titled: SF -  Well Switching Project.

Author: Sammuel (Sam) Farias. Seattle University. License: This work is licensed under the Creative Commons CC0 1.0 Universal Public Domain Dedication.
