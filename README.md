
# [Lynette's Portfolio](https://github.com/LAlibrary/LAportfolio)

Hi, my name is Lynette and here is a space to showcase some of my statistics and extracurricular projects.

Thank you for visiting.

## Visualizing The Markov Chain: Chord Progressions
As formula-based music can be, there is also randomness involved. The possibility of any note is equally likely.
The Markov Property can be applied to music in the sense that while a note is random, it may depend only on the current note being played in a sequence. 

For this project, I chose to compare two of my favorite artists by their chord progression usage.
I chose the songs “Playing with Fire” and “Lovesick Girls” by Blackpink and “Landslide” and “Dreams” by Fleetwood Mac.

![Blackpink and Fleetwood Mac](https://github.com/LAlibrary/LAportfolio/blob/main/artists.PNG)

I gathered chord progressions through the sites Chordify and HookTheory (cited in report below), and I constructed a vector of chords in R attributing to each song by each artist.

![Hook Theory: Chord Example](https://github.com/LAlibrary/LAportfolio/blob/main/chordexample.PNG)

I then computed the transition probability matrices for each artist based on their chord progression among both songs.

![Transition Matrices in RStudio](https://github.com/LAlibrary/LAportfolio/blob/main/tmatrices.PNG)

**Full detailed report can be read [here](https://drive.google.com/file/d/134dFluWyTyfalqecKEDoP2qqQ67duInS/view?usp=share_link).**

## Statistical Experimental Design: The Fractional Factorial Design
This was a group project in which an experiment was conducted and a fractional factorial design was used to analyze the data collected. The effects of various factors on carbon dioxide gas production are analyzed in observing the chemical reaction between different vinegar and baking soda amounts among a series of different sized ballons.

![Balloon Reaction Process](https://github.com/LAlibrary/LAportfolio/blob/main/balloon.PNG)

This experiment investigates the interactions among balloon size, vinegar, and baking soda on their collective impact on carbon dioxide gas production. This response was measured by measuring the circumference of the inflated ballon after the chemical reaction was complete.
By implementing a fractional factorial design, this experiment examines these variables through three replicates, creating a comprehensive dataset of 12 observations. The objective of this experiment is to discern the individual and combined effects of the factors. Calculations were calulated by hand, and all factors were found to be statistically significant.

![ANOVA](https://github.com/LAlibrary/LAportfolio/blob/main/ANOVA.balloon.PNG)
 
**Full detailed report with collaboration details can be found [here](https://drive.google.com/file/d/1_qGVklQ63YEqS1izuqWtauyE7r7hO4A6/view?usp=drive_link).**

## Natural Language Processing: Coachella Sentiment Tweet Analysis
The goal of this report is to perform sentiment analysis to better understand what users think about the music festival Coachella, with emphasis on “negative” and “positive” tweets. The dataset used is a Kaggle dataset sourced by Social Media Data consisting of 2015 Coachella tweets. The festival has a strong social media presence that can be applicable in the field of data mining and natural language processing (NLP). Machine learning methods and a multinomial logistic regression were implemented along with the help of Python libraries such as TextBlob and NLTK.

Below is an example of a Positive Word Cloud consisiting of top "positive" words identified by the model.
![Example of a Positive World Cloud Consiting of Top Positive Keywords](https://github.com/user-attachments/assets/241df6bb-c646-4827-a7f7-4f7669274580)

**Full detailed report can be found [here](https://drive.google.com/file/d/1kc6COTGRY0z9KNTIuKKXaXrv4Fe2EnS4/view?usp=drive_link).**

## Survival Analysis: Applying the Cox Regression & Other Survival Methods on Hospitalization Data
The WHAS dataset, fully referred to as the Worcester Heart Attack Study, is a study on long-term survival following hospitalization for an acute myocardial infarction, also abbreviated AMI. This report uses the cox regression model, stratified cox model, and other statistical methods such as the Log-Rank Test and Kaplan Meier curves to help visualize and propose a final model and interpretation of the survival data.

Below is a table of the model building process with variables (with * indicating significance) and the corresponding -2logL statistic, and AIC.
![image](https://github.com/user-attachments/assets/adcbc7a0-653d-46be-9408-0ce07b3b13d2)

**Full detailed report can be found [here](https://drive.google.com/file/d/1UxzUPnogPYd9GKnnvTcPN8OtR4AFGGz6/view?usp=drive_link).**

## Radio Show Work 
Below are examples of some of the posts I designed to promote my radio show, Claws Radio, that hosts weekly music themes through 22 West Radio, a student-run radio station located at Cal State Long Beach. 


