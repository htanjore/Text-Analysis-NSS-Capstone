# Text Analysis of Reviews from Drugs.com

## Executive Summary
Prescription drugs or over-the-counter medications can have adverse drug reactions (ADR) even after the approval following clinical trials.  During Clinical trials, the drugs undergo a rigorous evaluation  for safety or effectiveness and the drugs are tested on a subset of selected patients.Since these are controlled studies, the drugs may or may not show adverse reactions during clinical trials. Post surveys on drugs or opinions expressed by patients could yield valuable insights about the drugs benefits or side effect. The reviews from patients might also be useful to make informed decisions by the doctors to identity the effectiveness or side effects of the drugs. This project focuses on identifying the key terms or sentiments from patients reviews using Natural Language processing and predict overall ratings based on key terms or sentiments. 

## Motivation
I am a Biomedical Scientist working in the hospital and health care industry.  I am curious to understand whether opinions expressed by patients on the drugs they are prescibed give meaningful insigts into the sentiments. Can these sentiments predict ratings in the reviews?

## Data Question
Can we use Natural Language Processing (NLP) to analyze the patient reviews to identify the key terms or sentiments and predict the average drug ratings based on key terms?

## Data Sources
The University of California - Center for Machine Learning and Intelligent Systems repository.
## Data: Drugs.com reviews

#### Citation: Felix Gräßer, Surya Kallumadi, Hagen Malberg, and Sebastian Zaunseder. 2018. Aspect-Based Sentiment Analysis of Drug Reviews Applying Cross-Domain and Cross-Data Learning. In Proceedings of the 2018 International Conference on Digital Health (DH ‘18). ACM, New York, NY, USA, 121-125.

## Known Issues and Challenges:
Classification of drug side effects based on opinions as features could be challenging. Identifying the medical terminology to determine the key terms in the opinions expressed might lead to misclassification of the key terms.Comparing a base line model with word embedding might identify the potential missclassification issues.  
