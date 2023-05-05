# Sentiment_Analysis_For_Cross_Lingual_Kannada_English

Sentiment analysis involves analyzing text to identify the emotion behind it and has numerous applications. Kannada is a Dravidian language spoken in India that presents a challenge to monolingual NLP models due to the nature of its script and limited language technology resources, but the Kannada-English code-mixed dataset from the Dravidian-CodeMix-FIRE 2021 shared task provides an opportunity for sentiment analysis research. The dataset was collected and text processing has been carried out at different levels for sentiment analysis. Text cleaning, transliteration, spell check, and translation to monolingual Kannada are some of the stages involved. Different models are built and evaluated based on performance metrics such as precision, recall, F1-score, and accuracy.

## Architecture
![Proposed Methodology](https://user-images.githubusercontent.com/95362556/236432711-b5b56c91-e053-4abf-aeed-2c2d478f7446.png)

## Text Processing
The stages of text processing is shown in the below table:
![data_processing](https://user-images.githubusercontent.com/95362556/236433408-cf784f93-2787-4ac2-b5a2-98d02d3fff4a.JPG)

## Implementation Details:
The preprocessing was done as follows:

![preprocessing](https://user-images.githubusercontent.com/95362556/236435508-3a7b7f12-245e-46e5-ac16-ba9ce942fe67.jpg)

Text Translation Function:

![Translator](https://user-images.githubusercontent.com/95362556/236435815-59c9c67f-3bad-460d-89ab-a314436beed8.jpg)

Conversion to Kannada Text:

![Conversion](https://user-images.githubusercontent.com/95362556/236436008-18ed3ebc-403b-460e-adf3-112f9c53745d.jpg)

After the text processing was carried out, the final dataset was stored in removed_not.csv and used for future evaluations.

## Results
The results obtained from all the models used are as follows:

![Results_Table](https://user-images.githubusercontent.com/95362556/236437406-61363328-f774-4f3e-9e6d-e3dc8c1ba39e.jpg)

![chart](https://user-images.githubusercontent.com/95362556/236436839-5a1e8209-f42f-4507-82d7-d4ed80214a5e.png)
