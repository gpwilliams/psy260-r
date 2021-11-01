# psy260-r
:mortar_board: An Introduction to R for the PSY260 Module at The University of Sunderland

# Installing R

Some details are provided below. Please note that Option 1 is preferable.

## Option 1: R in the Cloud

Register an account at [https://rstudio.cloud/](https://rstudio.cloud/). Please note that you are limited to 15 hours per month at the free tier of this service at the time of writing.

## Option 2: Local Install

### Download and install R

Follow the link to [https://cloud.r-project.org/](https://cloud.r-project.org/) to install R. Choose Download R for Linux, Mac (OS X), or Windows as appropriate and follow the install instructions.

### Download and install RStudio

Follow the link to [https://rstudio.com/products/rstudio/download/](https://cloud.r-project.org/) and select the free version of RStudio Desktop. Click download RStudio for Linux, Mac, or Windows as appropriate and follow the install instructions.

## Option 3: R at the University of Sunderland

We will have local installations of R/RStudio for use on the computers in Psychology. These are controlled so that you do not have admin rights, so cannot install any additional packages. However, we will have the core packages (e.g. `here`, `tidyverse`) installed for you so you do not need to install any packages.

# Following the Content

There are three weeks of content based around lectures and seminars. Please attend or watch a recording of the lecture each week in preparation for the seminar. 

In seminars we will work through questions in the seminars folder (described below). Here you will complete exercises in an existing R-markdown file that builds upon content taught directly in the lecture. Following this there are additional questions which involve incorporating knowledge from within and across lectures and will sometimes involve learning new methods in the seminar from self-guided study.

## With RStudio Cloud

In RStudio Cloud set up your account and then click New Project. Select New Project from GitHub Repository, and then paste in the following: https://github.com/gpwilliams/psy260-r. This will clone this repository so you can work on the seminars file without manually downloading and uploading content.

## With a Local R Installation

Click the green Code button on this repository and click Download Zip and unzip the files. To do this either double click on the zipped folder (Mac) or right click and choose 7zip, Unzip here (PC). (Or use other methods if you are comfortable with GitHub.)

You now have access to everything I used to create the lectures and seminar content.

**To complete the seminar content each week, open RStudio by double-clicking the psy260-r.Rproj file in the root directory (main folder) of the repository. This ensures RStudio will work with the current working directory set properly.**

## All Methods

Lecture content can be found in the /lectures/ subdirectory. In the /seminars/ folder there are subdirectories for each session. Please complete the main exercises before the additional, optional questions.

**Please be aware that if you re-download this repository your changes will not be reflected in it. Keep your work safe and do not overwrite it.**

# Session 1: Introduction to R

Take the opportunity in this session to get to grips with R and complete the work below.

The content for all seminars is in the seminars folder. For the first session, go into 01_intro-to-r. The guidance for this session is in the `01_seminar_intro-to-r.Rmd` and `01_seminar_intro-to-r.html` files. Open the .html file in your browser. This has some instructions on what to do in the seminar. You will work from the `01_questions.Rmd` file. Follow the instructions to create your own code chunks or add to existing code chunks. Press play to execute your code. When you are ready to finish your work, click Knit. This will overwrite the existing `01_questions.html` file with your added content. You can view this in a browser for ease of viewing.

## Session 2: Processing Data in R

We will complete the content in a similar method as in Session 1. Guidance from the seminar is again in the seminar folder in the file `02_processing-data-in-r.Rmd` and `02_processing-data-in-r.html`. Answer the questions in `02_questions.Rmd` and Knit your final document to `02_questions.html` for ease of viewing.

## Session 3: Summarising and Plotting Data in R

We will complete the content in a similar method as in Session 1. Guidance from the seminar is again in the seminar folder in the file `03_analysing-data-in-r.Rmd` and `03_analysing-data-in-r.html`. Answer the questions in `03_questions.Rmd` and Knit your final document to `03_questions.html` for ease of viewing.
