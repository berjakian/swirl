# Swirl

Swirl is a teaching tool for learning R, it comprises questions and answers and a bit of AI (for positive reinforcement).

## Important points

* **Install Swirl**
* **Download the units from Github**
* **Create a user ID that is your UNI (the first 4-6 numbers/letters at the start of your TC email address)**
* **After completing a lesson you will be directed to a Google Form - you need to be connected to the internet and logged into MyTC**
* **Just in case the form does not work please copy and paste the code from the form into a text document and save it**

## Details

* Install the Swirl package by clicking the "packages" tab in the right hand pane and then clicking "install" or by typing `install.packages("swirl")` in the console window (located on the left hand side of the RStudio interface). 
* Once we have installed the package we need to turn it on, we do this by inputing the code `library(swirl)` - Swirl will tell you to type `swirl()` **but don't do that just yet!**
* First, make sure that there are no lessons already loaded. Type the following code: `uninstall_all_courses(force = FALSE)`. You should see the following:
`Are you sure you want to uninstall all swirl courses? | This will delete all of the contents of your swirl course directory.`

* Type `1`

You should see the message: `All courses uninstalled successfully!`

* Next, we need to load a lesson into Swirl, to do this cut and paste the following code into the console window (you will need to be connected to the internet):  
`install_course_github("core-methods-in-edm", "swirl", multi = TRUE)`. After downloading, you should see the message: `Course installed successfully!`

* Once the lesson finishes installing type `swirl()`, 
, **- please use your UNI  (the first 4-6 numbers/letters at the start of your TC email address** so we can identify you later. Choose the `Unit 1 - Introduction` course and the `Basic Building Blocks` lesson when you have the option.

* At the completion of the lesson you will submit your answers through a Google form. 
* **You will need to be signed in to MyTC to submit the form.** 
* **Please copy and paste the code from the form and save it in a text file just in case it does not work**
* **Press the "submit" button**

We will collect information on how many questions you answer, how many attempts you took to answer each question and the time you answered. Please use your TC email address on the form
