# Crowdsourcing CHICAS expertise to provide practical guidance for data analysis

## Aim
To harness the collective knowledge and experience of CHICAS members on a wide range of different areas of data science to collaboratively create a practical resource which is easily understandable for “early career data scientists”* and provides an overview of best practices and important considerations when conducting a range of different analyses. The intention is that this will contain concise and practical explanations of key steps in data manipulation and analysis which will be written in clear and accessible language with R code and plots where possible. This resource focuses on practical guidance but a brief discussion of relevant theory or a reference to additional resources are encouraged when they aid in the justification of a certain approach. This project is motivated by three concerns of data science students: i) that the literature is often inaccessible and lacks a discussion of best practices, tricks and tools ii) at CHICAS we often end up focussing on innovative methods in specific areas and may not gain experience in a wide-range of areas; iii) that there is a wealth of practical experience within CHICAS which is currently untapped and not shared beyond discussions about specific topics within supervisions.
*e.g. without a full degree in statistics

## The writing process
Those interested in contributing can choose a topic or subsection and write a skeleton/draft. Each subsection should be as concise and clear as possible, taking the reader through key steps and any tricks or tools you use. This can then be followed by an iterative and collaborative process with the section being discussed in meetings or through comments made online and additional suggestions or alternative approaches included.

## Feedback/ideas
Please leave comments, criticisms and ideas about any aspects of the project (aims, writing process, topics, useful resources etc.) and any topics that you feel would be useful to include, no matter how basic it may seem. You can do this by directly editing this page or by adding an issue using the 'Issues' tab.

## Topics
Please add any topics you think would be useful below - they could be anything from the analysis of a specific type of data to a clever tool you have found for manipulating or displaying data.

Using Git/GitHub
Using the HEC
Mount HEC on computer
Good practice in R
Projects & version control
Coding
Reproducible workflow with R
Exploratory analysis
Visualizing data
Plotting binary outcome data against continuous variables
Summarize data
Manipulating spatial data (maybe update Barry’s cheatsheet with sf?)
Transforming data (when do you do it, and why?)
Generalized additive models
Using splines
Linear piecewise (broken stick)
Polynomial
Basic modelling
Linear models
Generalized linear models
Model selection
Diagnostic checking (e.g. different residuals for different GLM distributions)
Criteria for model fitting
Criteria for prediction (RMSE,...)
R-square
Information Criterion (AIC, DIC, BIC)
Model assumptions & checking them
Using ‘predict’ to show regression results
Random effect models (non-spatial models)
Linear mixed effect models
Generalized linear mixed effect models 
Analysis of spatial data:
Geostatistical data (do we include an additional Bayesian Hierarchical model section?)
Point process 
Lattice data
Within each of these:
Exploratory analysis
Modelling fitting
Prediction
Making figures in R
Outputting in high resolution (for journals)
Maps
Colour schemes
Analysis of temporal data
Time series
Longitudinal
Survival analysis
Kaplan-Meier
Cox regression
Modelling zero-inflated data
Bootstrapping
Explanation of the concept
Non-parametric (when to do, how and examples)
Parametric (when to do, how and examples)
Sample size calculations
Bayesian Inference in Stan
MCMC
Hamiltonian MCMC
Metropolis-Hasting MCMC
Langevin-Hasting MCMC
Probability distribution functions
Deriving likelihood functions (tricks and examples)
Computing
Best practices in manipulating covariance/correlation matrices to enhance the speed and accuracy of matrix algebra
Some useful matrix calculus and how to do them in R
Simple tricks for computing derivatives of likelihood functions
An introduction to machine learning methods: 
Unsupervised vs Supervised learning, 
Clustering
Classifiers
Tree based methods.


Useful resources
Please add references to resources which you think are relevant and will be useful for this project:

An example of accessible statistics is this YouTube channel called statquest. Although this is a different medium, some key things this channel does well in communicating complex concepts to a general audience are: 
Easy language
A lot of visual aids- graphs and images are always better than complicated maths or long sentences. 
A good flow, i.e it’s important to link concepts in a way that flows naturally, taking care not to make assumptions about the audience’s knowledge. Don’t assume anything is ‘obvious’ or ‘intuitive’. 
An example of a good guide for this project is this website explaining R for data scientists. This is a good model we could adapt for our purposes. 


## Meetings notes
### Meeting 03/12/2019 - 
Key points:
- Our project is aimed at individuals with prior knowledge of R and basic statistics concepts.
- It will aim to produce cheat-sheets and overviews of key areas of data analysis and tips and tricks (which often aren’t in books). This can range from very practical explanations of key steps or a brief overview of a topic - whatever you think would have been helpful for you to have known when you first approached the topic.
- How the process of contributing to this resource can fit in with your daily life: We often have to search the internet or books for answers on how to do something. From now on, we should firstly search the project github to see if someone has written a section on this topic. If they have not, conduct your own search to find the answer and then write a brief summary of how to do it or provide a link to a resource which explains it.
- This will be a ‘community-driven’ project and we will use GitHub to create a wiki page for the project (this has a title page with links to other pages using hyperlinks, i.e. not in the format of a document). We can then use the issues section to open a ‘query’, with labels referring to what is needed - these can then be answered by the group. It also has interactions such as up and down voting. Everything is written in RMarkdown.
- Peer-reviewing of content will be useful to ensure that everything is easily readable, understandable and covers the topic adequately.

### Action points:
- Everyone comments/edits the structure for the topics above and agrees on the final structure (Friday 6th Dec 5pm)
- Set up the wiki & send round resources for using github (Friday 13th Dec)
- Everyone reviews the resources, tests out making a test contribution, writing an ‘issue’ etc. Then raise any problems or questions with the group and agree on approach to contributing.
- Choose a small and easy first topic to contribute and get started!
- Finish the explanation of the project, circulate around CHICAS and organise a time to discuss with the group.
