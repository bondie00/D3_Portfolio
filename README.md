# D3_Portfolio
By: Katie Donia

# [Guam (Final Project)](https://bondie00.github.io/D3_Portfolio/Project/)

## Abstract

This project is about Guam, one of the United States' Pacific Island territories. Before this project, I had very little knowledge of Guam, and I am willing to bet that most people are in the same boat.  That is why I decided to create an interactive visualization introducing audiences to Guam, particularly where it is located, why it is important to the United States, and who lives there.  I wanted to emphasize just how small Guam is and how very far away it is from the United States.  As such, the world map and then a closeup of Guam make up most of the visual experience of the project.  I also wanted to explore the importance of Pacific Ocean travel and how far people travel across the ocean to end up settling on a tiny island like Guam.  I used a breakdown of Guam’s population by race (according to the 2020 US census) to explore long-term migration to Guam. My project is an attempt to be as interactive and narrative as possible. By giving audiences only one way to progress through the project, I am able to guide their developing understanding of Guam to the aspects I find most interesting.  I also focused on creating visually interesting transitions so that viewing my project takes up a certain amount of time and cannot be absorbed all at once.

## Design Development
### initial sketches, final sketches, project screenshots

<img width="400" alt="guamdemo1" src="https://github.com/bondie00/D3_Portfolio/assets/35945154/1a0c3273-8316-4137-84ba-fa1e00ad1d02">
<img width="400" alt="guamdemo1" src="https://github.com/bondie00/D3_Portfolio/assets/35945154/cbf21a03-015a-4ffb-b33c-05ec01270a34">
<img width="400" alt="guamdemo1" src="https://github.com/bondie00/D3_Portfolio/assets/35945154/d941f06a-ac69-426b-9051-90bbf12fa505">
<img width="400" alt="guamdemo1" src="https://github.com/bondie00/D3_Portfolio/assets/35945154/88a6031a-7938-44dc-a111-15353a72a068">
<img width="400" alt="guamdemo2" src="https://github.com/bondie00/D3_Portfolio/assets/35945154/985a2bc8-b92b-4712-839d-23a4d8aaad84">
<img width="400" alt="guamdemo3" src="https://github.com/bondie00/D3_Portfolio/assets/35945154/fff5ac7d-9c0e-4ec6-bef0-afc4800fc26c">

## Data

Race data for Guam was taken from 2020 US Census, Decennial Census of Island Areas, general demographic characteristics table (https://data.census.gov/table?q=guam&d=DECIA+Guam+Demographic+Profile&tid=DECENNIALDPGU2020.DP1).

I took the population numbers and percentages from the table above and entered them by hand into an array of objects that holds all the necessary information about the data, including total number, percentage, name of race, and race cateogry, as well as containing the coordinates necessary to make a stacked bar chart, which I also calculated by hand using the percentages given by the census.

# [Quarterbacks Updated Tutorial](https://bondie00.github.io/D3_Portfolio/3_2_distributions/)

## Abstract

This visualization is about how much effect a quaterback's performance has on the final outcome of a football game. This is illustrated using a scatter plot with quarterback passer rating on the x-axis and total points scored by the qb's team on the y-axis. The scatterplot displays information for one qb at a time, chosen by the user using a dropdown list. Each point represents one game played between 2019 and 2021. The color of the point represents whether the qb's team won or lost, and the size of the point represents the score different at the end of the game (ie how much the qb's team won or lost by). The differences in the overall trend of the scatterplot between qbs goes to show the differences in how successful certain qbs are or are not.  The tooltips allow for a deeper exploration into each game to try and figure out what other factors beside qb performance may have been at play.

## Data

I used this dataset of nfl offensive stats between 2019 and 2021 from Kaggle: https://www.kaggle.com/datasets/dtrade84/nfl-offensive-stats-2019-2022. This dataset contains the stats for every player who played in every game between 2019 and 2021.  Before appending the data to the DOM, I filter to get only the entries pertaining to quarterbacks who made at least 5 pass attempts (to ensure the qb was in the game long enough to have an effect).  I also created a few columns to make displaying the tooltip information easier, including a column for how many points scored by the qbs team, for point difference, and for whether the qbs team won or lost.  I used pandas scripts to quickly generate and populate the new columns.

