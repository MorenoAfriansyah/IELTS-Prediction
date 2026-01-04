# IELTS-Prediction
IELTS Prediction with RoBERT, IndoBERT.

## Problem Urgency
Unstructured data, such as text, presents a different level of difficulty compared to structured data, such as tabular data. When dealing with IELTS data in text form, where a model is required to predict IELTS scores in a quantitative format, a deep learning model is necessary to provide an effective solution for transforming text data into quantitative data with accurate results.

## Solution
Creating a predictive model using RoBERTa and IndoBERT as models for processing text data into semi-processed data, and an XGBoost model to convert the data into predicted IELTS scores.

## Data  
Tabular data with a total of 9,912 training data entries, where the textual data relates to respondents' answers to IELTS examiner questions along with their IELTS scores. The training data has feature variables consisting of prompt and essay, and target variables including task_achievement, coherence_and_cohesion, lexical_resource, and grammatical_range. The test data consists of a total of 473 entries with feature variables being prompt and essay.

## Research Results
The results from the testing data where the task_achievement feature was predicted with an MSE of 1.1195, the coherence_and_cohesion feature with an MSE of 1.6605, the lexical_resource feature with an MSE of 1.0495, and the grammatical_range feature with an MSE of 1.073. From these results, the IELTS score prediction model achieves accurate prediction accuracy, as evidenced by the small error values, meaning the model can be used to accurately evaluate the responses of all participants taking the IELTS test to generate their IELTS scores.

