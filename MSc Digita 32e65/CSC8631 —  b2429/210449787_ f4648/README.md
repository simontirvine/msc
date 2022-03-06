# CSC8631-SIrvine

# CSC8631: Data Management and Exploratory Data Analysis
### Simon Irvine | 210449787
### 03 December, 2021

# The Brief
## Scenario
Learning Analytics, a rapidly-growing application area for Data Science, is defined as “the measurement, collection, analysis and reporting of data about learners and their contexts, for purposes of understanding and optimising learning and the environment in which it occurs”1.

Existing mechanisms to record student engagement (e.g. attendance monitoring) fail to capture the extent and quality of engagement outside of the classroom environment. Further complementary sources of data are routinely collected about our learners (e.g. use of on-campus facilities, Virtual Learning Environment (VLE) and Re-Cap access, and student wellbeing referrals); however, these currently reside in a number of silos.

Learning Analytics seeks to aggregate these sources of data to derive shared insights, and provide effective measures of engagement. Insights may inform learning design, inform intervention processes for at-risk students, and improve student attainment.

The most complete introduction is available in government policy policy report “From Bricks To Clicks”2. The report is quite extensive, but there are some nice case studies from Nottingham Trent and the OU to give you a flavour of the types of projects in this area.

## Challenge
In this project we will emulate a very familiar process undertaken by data analysts. We will take a dataset provided to us, and develop a suite of tools which allow us to extract interesting insights from this data in a quick, reliable and repeatable manner. The datasets you are expected interpret as a data analyst are commonly previously unseen, so the process of building a pipeline is an exploratory one. Consequently, you will be expected to review and interrogate the data to gain an understanding of its structure and composition.

In this coursework you will develop a data analysis pipeline to explore a given dataset. There are no formal requirements for the functionality or focus of your analysis. Your data analysis should follow routes of enquiry which are of greatest interest to you. Therefore, there exists scope for a great deal of flexibility so we anticipate solutions to this challenge will vary.

We encourage you to pursue ambitious analysis, but just as importantly we are looking for good programming practice. When developing large systems such as these, it is important that you write your code incrementally, and test it carefully before continuing to add additional functionality.

## Success Criteria
Based on these main objectives, the author proposes the following simple success critera for this exploratory data analysis:

Data are imported and processed allowing exploratory data analysis;

- A repository and version control system is established;

- Appropriate questions are asked throughout to further analysis;

- Processes and code are understandable and reproducible;

- A final report is produced.

It is the intention of the author to employ a plan based on CRISP-DM4 to set guardrails to help plan, organize and implement this project. A relevant distillation of this can be found in the “R for Data Science” model with the steps included within the interation cycle. The author will use this model as the basis for his plan, as follows:

1. Import
> - Preparing project structure
> - Setting up environment and packages
> - Collecting data
2. Tidy
> - Exploring data
> - Pre-processing and cleaning
3. The Loop
> - Questioning
> - Transforming
> - Visualizing
> - Insights
4. Communicate
> - Report
> - Presentation
> - Future work

# Instructions
To load this project, you'll first need to `setwd()` into the directory
where this README file is located. Then you need to run the following two
lines of R code:

	library('ProjectTemplate')
	load.project()


For more details about ProjectTemplate, see http://projecttemplate.net
