Developing-Data-Products
========================
Data developing products to create myAPP

Here, you find the two files ui.R and server.R corresponding to my shiny app. Try this APP by running it in RStudio (Apologies i am not able to provide a link sink I am not able to launch the HTML website due to IP restrictions at work). So, run the following codes in RStudio after you have strored both the ui.R and server.R in a folder on the desktop named, let's say, 'my_app'. The code to run are:

library(shiny)
runApp("my_app")

And the above shold launch the HTML site on which you can enater values and play around with the app. It's pretty basic just to meet the requirements of the assignment.

This APP provides you a prediction for the results of the matches for Brazil soccer team during the current World Cup to 
being held in Brazil. In this APP you enter your the prediction (goals) of the Spanish team rival, and the application 
returns you a number with the prediction of the Goals for the Brazil team (may be against some soccer fans out there 
cheering for other teams). The APP uses the fact that Brazil always get three goals more than its rival. Enjoy it!

Many thanks,
Karuna.
