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

