# UTOPIAE-Bayes
UTOPIAE: Introduction to Bayesian statistics

The repository contains the material presented and distributed in the Lecture Introduction to Bayesian statistics in UTOPIAE,  on Monday 2^th^ July, 2018

### Material

+ Handouts
+ Handwriten notes containing exercises
+ Web applications

### How to run the Web Applets from the server 

You can click on the following links:  

+ For the demo presenting the conjugate priors  
    * <https://georgios-stats-1.shinyapps.io/demo_conjugatepriors/>   
+ For the demo presenting the Mixture priors  
    * <https://georgios-stats-1.shinyapps.io/demo_mixturepriors/>  
* For the demo presenting standard parametric/predictive Bayes point estimators  
    * <https://georgios-stats-1.shinyapps.io/demo_PointEstimation/> 
* For the demo presenting Credible Sets  
    * <https://georgios-stats-1.shinyapps.io/demo_CredibleSets/> 

These applications are currently uploaded on non-Durham Univertity server, which means that we have only 25 active hours per mounth. If we exceed this limit, you will be able to run these applications localy on your computer by dowlnoaded them. (see below.)

### How to download the Web Applets and run them localy

In order to download, edit, run the Web Applets to your computer, do the following:

1. Run rstudio
  1. In the console run  
      * install.packages("rmarkdown")
  2. Go to File>New Project>Version Control>Git  
  3. In the section "Repository URL" type: 
      * https://github.com/georgios-stats/Bayesian_Statistics.git
  4. Then you can run the applications either by clicking and running each 'name'.Rmd script in the demo_'name', or by running the commands: 
      * For the demo presenting the conjugate priors
          * rmarkdown::run("./demo_ConjugatePriors/demo_ConjugatePriors.Rmd")
      * For the demo presenting the Mixture priors
          * rmarkdown::run("./demo_MixturePriors/demo_MixturePriors.Rmd")
      * For the demo presenting standard parametric/predictive Bayes point estimators
          * rmarkdown::run("./demo_PointEstimation/demo_PointEstimation.Rmd")
      * For the demo presenting Credible sets
          * rmarkdown::run("./demo_CredibleSets/demo_CredibleSets.Rmd")
  