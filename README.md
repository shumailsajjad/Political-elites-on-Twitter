# Political Elites' Social Media Analysis Project - Meta-Funded Research at Center for Speech and Language Technologies (CSaLT), Pakistan.

## Overview

This project aimed to investigate how political elites in Pakistan utilize social media, particularly Twitter, to amplify their narratives and agendas through disseminating misinformation, polarization, and incivility via tweets.

## Data Collection

I utilized the **Twitter API** to extract tweets from 32 politicians belonging to two prominent political parties in Pakistan: Pakistan Tehreek-e-Insaf (PTI) and Pakistan Muslim League N (PMLN). The data collection period spans from May 1, 2022, to August 23, 2022.

Files: 
1) ImranKhanPTI.xlsx: sample ouput file from **Twitter API**
2) Twitter data.xlsx: An overview of politicians used for this research and their data on background

## Data Processing

Upon collecting the tweets, I categorized them into three groups based on their engagement rates (top 10%, average 10%, bottom 10%) measured by likes, replies, and retweets. The processed tweets were then saved into separate Excel files for each politician (e.g., output_2_ImranKhanPTI.xlsx).

Files: 
1) Twitter engagement rates.ipynb: Extracting Twitter engagement metrics and language of the text via **tweepy API**
2) output_2_ImranKhanPTI.xlsx: sample of output file from previous jupyter notebook (same outputs were obtained for each politician)

## Fact-Checking

To verify the authenticity of the tweets, I conducted fact-checking against local sources such as sochfactcheck and AFP Pakistan, as well as utilizing **Google Fact-Check Scholar**. This meticulous process aimed to create a labeled dataset for further analysis.

Files: 
1) False information in tweets_ URLs_ RT.xlsx

## URL Classification

The project involved the classification of URLs shared by political elites on Twitter. This analysis aimed to identify the primary sources of mainstream media or other information channels used by these elites to propagate false narratives and gain influence.

Files:
1) Extracting URLs from Twitter tweets.ipynb: extracting URLs from tweets for each politician from each party
2) Twitter URLs.xlsx: sample of output from previous jupyter notebook
3) Classified Twitter URLs.xlsx: Led a group of 4 students to classify these URLs manually
4) Krippendorff's alpha - Interrater Agreement.ipynb: Found the interrater agreement to show strong agreement association across the raters (raters were the students and I who manually classified these URLs)

## Toxicity Analysis

In addition to the analyses above, I employed the **Perspective API** to assess the **toxicity** of tweets shared by political elites. This allowed for identifying potentially harmful or inflammatory content within the tweets, providing further insight into the discourse generated by these individuals on social media platforms. Considering the **toxicity** levels alongside other metrics, such as engagement rates and fact-checking results, a more comprehensive understanding of the impact and nature of political narratives propagated on Twitter was attained. This multi-faceted approach contributes to a nuanced evaluation of how political elites utilize social media to shape public opinion and disseminate information.

Files:
1) Perspective **API**.ipynb
2) PTI.csv: A final dataset of the PTI party after classifying URLS and finding **Toxicity** 
3) PMLN.csv: A final dataset of the PMLN party after classifying URLS and finding **Toxicity**
4) Final Dataset.xlsx: Merged PTI and PMLN files

## Statistical Analysis

Subsequently, I formulated research questions based on the data and conducted statistical analysis to answer them. This phase involved identifying causal inferences and uncovering meaningful relationships within the dataset.

Files:
1) Final Dataset - Descriptive statistics.ipynb

## Project Objective

Overall, this project sheds light on how political parties leverage social media platforms, particularly **Twitter**, to perpetuate **polarization** and disseminate **fake news**. The analysis encompasses various aspects, including URL sharing, retweets, tweets, and fact-checking sources.
