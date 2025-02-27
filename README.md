java c
Economics 5850: Labor Economics 
Spring 2025 
Problem   set 4
Question   1. Gender Wage Gap – OLS estimation
Return to our Project representing Problem   Set   1 on the Rstudio cloud computing/collaboration   site rstudio.cloud. You used this dataset, and this Project space, for Problem   Set   1.
(a) Load dataset PS1_data.Rdata as before. This dataset (still)   contains more   than   20   distinct variables describing the work and demographic characteristics of   31-35 year-old U.S. workers in 2014, as recorded by the National Longitudinal   Study of   Youth’s   1997 cohort (our nation’s leading panel data resource on young workers, which is developed and maintained   by OSU’s   own CHRR.)
[1 point] Create a subsample containing only women,   and   a   subsample   containing   only men (recall that self-reported gender categories from this earlier era   are   narrow). Calculate and report the mean wage among the women workers in our   sample and   the   mean wage   among   the   men workers in our sample. (Note that all   sample members   in PS1_data work positive hours   and   have positive wages.) What is the difference between the gender means? 
(b) Using Ordinary Least Squares, estimate the following Human   Capital   regression:

where outcome Yi represents the ln(wage)) of   worker i, Fi is an   indicator   taking   the   value   1   if   worker i is female and 0 if   worker i is   male, Si represents the years of   schooling of   worker i,    and Ei represents   the   years   of   work   experience   of   worker i.   The   final   term   in   (1)   is   an idiosyncratic error.   Subscript. i =   1,   …   ,n represents the n members of   the NLSY97 estimation   sample. (This is the Mincer Regression, and has been used to describe the wage returns to schooling and experience by labor economists since Jacob Mincer published this method   in   the   JPE in   1958. But we have modified our Mincer regression to include an indicator   for   Female.)
[1 point] Which coefficient in (1) describes the gender wage gap,   controlling   for human   capital   characteristics?
[1 point] What is your estimate of this coefficient? Is it   significant? Does   your   estimate   of   the   human capital-controlled gender wage gap favor women or men? By how much?
(c)   [1 point] Identify the 代 写Economics 5850: Labor Economics Spring 2025 Problem set 4
代做程序编程语言four most common occupations in the dataset, using   a   tabulation   command in Rstudio (or Stata or…). What are they?
Re-estimate expression (1) adding controls for occupation.   Create   four   dummy variables.   Each   dummy variable represents one of   the four most common occupations. The   dummy   is   1   if   the            worker has that occupation, and 0 otherwise. Add each of   the   four   dummies   to   your regression. (What is the omitted occupation in this   specification?)
[1 point] What is the new gender wage gap coefficient controlling   for human   capital
characteristics and occupation? Is it significant? Does it   favor women   or men?   By how   much?
2. Gender Wage Gap – Oaxaca-Blinder Decomposition
(a) Return to the datasets you created of   female-only and male-only workers. Estimate Human Capital regression (1) in each of   these two datasets. (Drop   the Fi regressor;   its   coefficient will      not be identified in a single-gender sample. Now we are   estimating the   traditional   Mincer regression in each gender   subsample.)
[1 point] Record your estimate of   each βcoefficient   in   the   female   sample   and   each β coefficient in the male sample.
(b) Calculate the mean of   each regressor in expression (1)   (schooling,   schooling   squared,   experience squared) for the female-only dataset and   for the male-only   dataset.
[1 point] Record these means. 
(c) Recall that in the Oaxaca-Blinder decomposition, the:
Explained   component   of   the   gender   wage   gap   =  
Unexplained   component   of   the   gender   wage   gap   =  
Using these formulas, and the coefficient estimates and means you recorded   above   for your   female   and   male   worker   samples, calculate:
[1 point] The explained component of   the gender wage gap
[1 point] The unexplained component of   the gender wage gap.
(d)   [1 point] What do you think is the most informative estimate of   the   gender wage   gap – the   difference in mean wages by gender, as in   1(a)? The gender wage   gap   controlling   for human capital as in   1(b)? Or the gender wage gap controlling   for unionization,   industry,   and   occupation – like an expanded version of 1(c)? Why is this your preferred measure? 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
