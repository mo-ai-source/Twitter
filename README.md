
# Twitter Account Authentication via Classification and Distance Measures

Twitter Account Authentication is crucial to prevent impersonation and the spread of misinformation. This repository provides a basic implementation for classifying and authenticating Twitter accounts based on extracted features, distance measures, and classification models.

## Table of Contents
- [Features](#features)
- [Distance Measures](#distance-measures)
- [Classification Models](#classification-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
The following features have been extracted from the given Twitter data:
- Average tweet length
- Number of mentions in tweets
- Number of hashtags in tweets
- Ratio of followers to following

## Distance Measures
The implemented distance measures include:
- Euclidean Distance
- Cosine Distance
- Manhattan Distance

## Classification Models
Currently, the repository uses a Logistic Regression model for classifying Twitter accounts as genuine or fake. Future iterations may include more sophisticated models like Decision Trees, Random Forests, and Neural Networks.

## Evaluation Metrics
The model's performance is evaluated using:
- Precision
- Recall
- F1-Score

## Setup & Installation
```bash
git clone https://github.com/mo-ai-source/Twitter.git
cd twitter-authentication
pip install -r requirements.txt
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

