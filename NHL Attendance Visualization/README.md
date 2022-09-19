# NHL Attendance - Curve Fit

Hi and welcome to my cool regression model data visualization tool!

### Purpose:

The purpose of this post is to demonstrate my python programming ability to generate linear and non-linear regression model with confidence bands. The evaluation the quality of the fit to the data with a cool data visulaiztion summary output.

I originally completed this project in one of my co-op internships working for a biotechnology start-up called Ekidan Sensing. Part of my role was to generate a regression model to predict the level of THC concentration in cannabis using data collected from a sensor device. The models considered to predict THC concentration from a sensor output are **linear, parabolic and power model**, these all relate to probably chemical phenomenons occuring between the sensor and THC molecules.  However all of the data and some of the code are proprietary information to Ekidna. Therefore I had to decide on a data source to demonstrate my code. So I chose data from an industry I enjoy.... Sports Marketing!!

### NHL Attendance

This code will try to fit a linear, parabolic and power modle to every NHL teams per game home attendance in the 2018-19 season. I chose the data from this season, becuase that was the last full NHL sesaon unaffected from covid protocols. This entire project will feel like trying to fit a square peg into a circle hole.... and that becuase it is! I do not expect any curve fit to look nice becuase I don't not epect any NHL team per game home attendance to follow a linear, parabolic or power trend. So maybe this wasn't the best dataset to demonstrate by code but too late now.... I alreday scaped the data.

### Project Outline
- 'NHL_attendance_scape.ipynb' : Jupyter Notebook scipt perfroming a quick we scrape from Hockey-Refernce.com to extract the attendnace data from teh 2018-19 season
- 'NHL_attendance_data.csv' : CSV file with the attendance data
- 'NHL_regression_script.ipynb': Jupyter Notebook scipt with the main code to generate models and eveluate with visulaization tools
- 'NHL_attendnace_vis.pdf':  Multi-page pdf output of the all plot for every team and every regression model
- 'Curve_Metrics.xlsx' : Excel file storing all the metrics evaluating each regression fit
