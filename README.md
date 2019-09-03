

Neda Jabbari;
Sep 2019



###Multiclass Logistic Regression and Genomics

#### Introduction

Scenario #1: A customer walks into a car dealership to buy a car. Given the customer’s age and budget what are the chances that they will buy that specific BMW that the dealer showed them?
Scenario #2: A customer walks into a car dealership to buy a car. Given the customer’s age and budget what is the likelihood of buying a particular model that the dealer showed them (with choices of Toyota, Chevrolet and BMW)?
If you have ever wondered how you could use statistics to answer such questions, “logistic regression” is one answer. At times, we need to know the likelihood of a certain outcome of a dependent categorical variable (e.g. buying the particular BMW) given a set of features (customer’s budget and age). As a binary regression, logistic regression estimates the relationship between independent variables and a certain output of a binary variable. Other times, we are interested in the likelihood of any of the multiple outcomes (e.g. buying any of the certain car models). In this case, a logistic regression is extended to several classes or events to figure out the likelihood of each. We refer to this as multiclass logistic regression.


#### Objective 

Based on my interest in genomics and certain years of experience working on Borrelia genomes, I decided to see if the size and GC content of bacterial chromosome assembly can help tease apart bacterial subgroups. Let me give a little background on the question: Chromosomes are made of DNA and DNA consists of 4 bases of G, C, T and A. A chromosome GC content is the percentage of G and C bases to the total bases in the chromosome.


#### Data Source:

I extracted the information on size and GC content of bacterial chromosome level assemblies from NCBI genome database (https://www.ncbi.nlm.nih.gov/genome). I limited my data to bacteria with human host and one scaffold assembly. In addition, I only considered the three subgroups of Gammaproteobacteria, Firmicutes and Actinobacteria since the number of submissions in these subgroups were relatively comparable. 


The data analyses and workflow are posted on my Medium blog: "Multiclass Logistic Regression and Genomics".
