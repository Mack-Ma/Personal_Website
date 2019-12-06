# About Me
Hey, what's up! I'm Tianye Ma, currently a visiting scholar in Colorado State University. Although cognitive science is my principal area of interest, I actually have a broad interest in all kinds of new things. Please feel free to contact me by e-mail (mack_ma2018@outlook.com).  

# My Posts

## About Model Assessment
Hey! Here's some of my understandings towards model assessment.  
How do we know that a model is better than another? A common view is that the better the model fits the data, the higher probability of choosing that model should be. While additionally, we may also concern how much the model fits the random error, that is to say, if there's an overfitting problem (like "model 2" in the pic below).   
These views are well-renowned, but when it comes to some specific problems, we might still get confused. For instance, in general linear models, we often set ***covariables*** to control some confounding factors in order to get a more accurate estimation of the regression coefficient of interest. This kind of view can sometimes drive us really crazy about adding more covariables, such as adding head-movement parameters in an fMRI model.   
While as a matter of fact, it might not always be appropriate to add extra covariables since it's not covariables that could make our estimate accurate, it's actually only the **meaningful** covariables have that kind of power. Our purpose is to bring our estimate closer to the truth. Nonetheless, simply increasing the goodness of fit doesn't mean that we're approaching the truth. Our data is more like the truth with a filter on it (e.g. a Gaussian Blur filter, as shown in the upper panel of the pic below) rather than the truth itself. Suppose that the truth of our interest is just the curve shown in the upper panel, we cannot **recover the truth** using model 2 although it could offer a better fit.  
That's the same in linear models. Adding covariables that are not meaningful could make it a bit harder to recover the true parameter value. Thus, in this way, the covariables are actually distorting the truth rather than approaching it. And that's why we always need model assessment and comparison to help us decide whether the covariables are needed in the model and why the formal model assessment should always concern the complexity of models or how much the model could generalize to other datasets.  
![](https://github.com/Mack-Ma/Tianye/raw/master/Pic/ModelAssessment_12052019.jpg)  

12/5/2019 9:56:36 PM 

## Coke Chicken
![](https://github.com/Mack-Ma/Tianye/raw/master/Pic/CokeChicken.jpg)  
Look at the chicken I cooked for Thanksgiving! I actually added some Coca Cola for flavor. :)  
  
12/1/2019 5:18:22 PM  

## Hello World!    
This is Tianye Ma's personal website.  
  
12/1/2019 2:39:31 AM  

