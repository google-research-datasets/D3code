# D3code
This repository contains data resources for the following paper: 

- [Disentangling Perceptions of Offensiveness: Cultural and Moral Correlates](https://arxiv.org/abs/2312.06861) (accepted at FAccT 2024).

- [D3CODE: Disentangling Disagreements in Data across Cultures on Offensiveness Detection and Evaluation]() (under review).

D3code is a large-scale cross-cultural dataset of parallel annotations for offensive language detection by over 4k annotators, balanced across gender and age, from across 21 countries, representing eight geo-cultural regions.

# Dataset Description

The repo contains the data card for the SeeGULL dataset, following the format proposed by [Pushkarna et al.](https://arxiv.org/abs/2204.01075). The data card includes details of the dataset such as intended usage, field names and meanings, annotator recruitment and payments. The dataset folder contains the following 3 files:

- ```raters.csv```: each row represents a participant of the study, along with their unique anonomous id, age, gender, self-reported socio-economic statues, country and region of residence.

- ```items.csv```: each row represents an item, selected from the Jigsaw dataset, along with their textual content, their category (one of moral, random, or social group) and their subcategroy. These two fields point to the strategy used for collecting the item.

- ```ratings.csv```: each row represents a rating assigned to an item by a rater. Two columns show the (1) raw rating: a value from 0 to 4, 0 being not offensive at all and 5 being extremely offensive, a value of -1 in this column means that the rater did not understand the message, and (2) binary rating: a binary value, with 0 showing a raw rating of 0 or 1, and 1 showing a raw rating of 2 or higher. A ```na``` value is equal to a raw rating of -1. 

# Citation
TBA
