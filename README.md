# Variational Autoencoders for Collaborative Filtering


Our goal is to explore a research paper, implement its findings, and further improve upon the proposed methodology. Through our implementation and enhancements, we strive to contribute to the advancement of personalized recommendations and push the boundaries of existing techniques. By conducting thorough evaluations, we aim to gain valuable insights and draw meaningful conclusions that can guide future developments in the field of recommendation systems.

![image](https://github.com/iRaneem/Recommendation-Systems-using-VAE-CF/assets/85534868/c7b00dfd-fc15-4cf0-97ab-505922e63c40)

## Table of Contents

- [Introduction](#introduction)
- [Objective](#Objective)
- [Contributions](#Contributions)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#Contact)


## Introduction

In our journey through a recommendation system course project, we embarked on an exciting exploration of recommendation system and dive deep into its concepts, implement its findings, and push the boundaries of its capabilities to improve and innovate in the field of personalized recommendations. The major challenging “small-data” problem where most users only interact with a tiny proportion of the items and our goal is to collectively make informed inference about each user’s preference . we find that to make use of the sparse signals from users and avoid overfitting, we build a probabilistic latent-variable model that shares statistical strength among users and items. Empirically, we show that employing a principled Bayesian approach is more robust regardless of the scarcity of the data.  However, we did not stop at mere replication. We fine-tuned parameters of the Variational Autoencoders (VAEs) , explored alternative dataset to create a functional system that could generate personalized recommendations.

## Objective: 
The objective of this project is to leverage Variational Autoencoders (VAEs) for Collaborative Filtering (CF) in recommendation systems. Collaborative filtering predicts user preferences by discovering and utilizing similarity patterns across users and items. By extending VAEs to CF, we can overcome the limitations of linear factor models and explore non-linear probabilistic models, enabling us to handle large-scale recommendation datasets.

## Contributions:  
By implementing the findings of the research paper and enhancing the proposed methodology, we aim to make the following contributions:
- Advancement of personalized recommendations in recommendation systems.
- Pushing the boundaries of existing techniques in collaborative filtering.
- Evaluation and comparison of different likelihood functions in the context of latent factor models.
- Identification of the benefits and drawbacks of employing a principled Bayesian inference approach.
- Characterization of settings where the Bayesian approach provides the most significant improvements.

## Features
1. Deep Learning: Variational Autoencoders (VAEs)
2. Personalized recommendations: Collaborative Filtering

## Installation

install dependencies and libraries

```bash
!pip install imbalanced-learn
```

```bash
!pip install matplotlib 
```
```bash
!pip install tensorflow
```
include this dataset also
```bash
https://www.kaggle.com/datasets/rishitjavia/netflix-movie-rating-dataset
```
## Usage 
To use our project. make sure you have upload
the netflix dataset, the important Installation and configured the enviroment well.

Note: we peovided the code run as if your enviroment not updated you can still see the outpot and the results of our search. 

## Contributing
The contribute in this projec are:

    1. Raneem Alomari
    2. Bedoor Almarini
    3. Deema Al-saygh 

## License
The license, MIT License.
## Contact

Feel free to reach out if you have any questions or feedback.


- GitHub: [iRaneem](https://github.com/iRaneem)
- GitHub: [bedooralmareni](https://github.com/bedooralmareni)
- GitHub: [deema2245](https://github.com/deema2245)
