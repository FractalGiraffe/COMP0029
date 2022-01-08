# Data

The data is stored as a pickled pandas dataframe. The dataset contains 5 columns:

`count` = number of CrowdFlower users who coded each tweet (at least 3; more users coded a tweet when judgments were determined to be unreliable by CF)

`hate_speech` = number of CF users who judged the tweet to be hate speech

`offensive_language` = number of CF users who judged the tweet to be offensive but not hate speech

`neither` = number of CF users who judged the tweet to be neither offensive nor hate speech 


`class` = class label determined by majority rule:
- 0 : hate speech
- 1 : offensive  language
- 2 : neither
