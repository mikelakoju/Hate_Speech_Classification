# Hate Speech Classification

### Hate Speech Classification with Convolutional Neural Network (CNN)

### Author: Dr Mike Lakoju

Hate speech is defined by the Cambridge Dictionary as "public speech that expresses hate or encourages violence towards a person or group based on something such as race, religion, sex, or sexual orientation".

### Steps to classify hate speech:

- Preprocess the text data
- Convert text to numerical tokens
- Build and Train ML
- Test the Model
- Save and use it later

### About the Data:

_Data credit: Laxmimerit_

> **`data.csv`**

- `count` = number of CrowdFlower users who coded each tweet (min is 3, sometimes more users coded a tweet when judgments were determined to be unreliable by CF).

- `hate_speech` = number of CF users who judged the tweet to be hate speech.

- `offensive_language` = number of CF users who judged the tweet to be offensive.

- `neither` = number of CF users who judged the tweet to be neither offensive nor non-offensive.

- `class` = class label for majority of CF users. 0 - hate speech 1 - offensive language 2 - neither
