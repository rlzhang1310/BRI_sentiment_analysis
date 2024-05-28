# BRI_sentiment_analysis 

## Reasearch Question
Find the sentiment of BRI related Projects.

Which sentiment analysis library performs the best?
## File Overview

### Sent_analysis_filtered_entitied.ipynb
using df created from sent_analysis_text_relevant, further filter out incorrectly identified substrings

### Sent_analysis_text_relevant.ipynb
create df which filters relevant tweets with BRI project substrings

### translation_senanalysis_testing_results.ipynb

Finds the best sentiment analysis library between spaCy's spacytextblob, vader, and nltk using rmse, mae, and accuracy. NOTE: rmse/mae calculuations are incorrect and need fixing

download all necessary libraries
