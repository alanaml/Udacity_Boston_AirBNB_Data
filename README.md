# Udacity Boston AirBNB Data


## Libraries used
Libraries related to data visualization and data processing
```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt.
```

## Motivation for the project
### Business Question

For us to think about expanding in the Boston area, we need to understand which characteristics our clients prefer in an apartment.

The analyses could be very complex and highly detailed, everything depends on how reliable you want your results. For small analyses, I choose to work with correlations regarding the ''Scores''. What made our clients choose the score? And how the apartment's features are relating, and with particular characteristics are related to the score rating? I've used some heatmaps to understand this relation, also using changing the correlation mode to Spearman's correlation.

## Files in the repository
 - Listings &mdash;  full descriptions and average review score;
 - Reviews &mdash; unique id for each reviewer and detailed comments;
 - Calendar &mdash; listing id and the price and availability for that day.

To use the Jupyter-Notebook extract the data zip files in the root.

## Summary of the results
Apartments location does not affect the overall score! Theres is no correlation between score location and score value, score cleanliness, score rating.

Review score value seems to increase together with score rating, accuracy and cleanliness.

### Curiosity!
There is a negative correlation between number_of_reviews and square_feet, which means that when one increases,
the other decreases. Therefore, the more square meters, the smaller the number of evaluations, or else we will have, for the most part, small apartments.

