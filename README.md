## This is an Exploratory Analysis on Steam Game Statistics Focusing on the Rating of Games and Hours Played on steam

## Research Question or Motivation For this Project/Analysis

### Ѳ To Determine the relation if any between the rating of a game and its market Success (Measuredas Hours the game was played)

### The Data Sets Used in this Analysis :-

#### 1. [MetaCritic Rating DataSet On Kaggle for Games On Steam](https://www.kaggle.com/skateddu/metacritic-games-stats-20112019)

####     -> This Data Set contains different ratings and user feedback on different games on steam which are used to calculate the Normalized Rating Score for each game in this Analysis

#### 2. [Steam Game Played by Hours DataSet On Kaggle](https://www.kaggle.com/tamber/steam-video-games)

####     -> This Data Set contains different game played on steam along with the number of hours the game was played by different users this information is used to calculate Normalized Play Score for each game in this Analysis

## Normalization Method Used :

## To have the rating and the play time on the same scale we have to Normalize Both values to a scale of [0,2] :

### Normalizing the Rating Score To a Range of [0,2] by :-

## <img src="https://render.githubusercontent.com/render/math?math=Normalized Rating = (\frac{Rating - Min(Rating)}{Max(Rating) - Min(Rating)})*2">   
   
### Normalizing the Playtime To a Range of [0,2] by :-

## <img src="https://render.githubusercontent.com/render/math?math=Normalized Hours = (\frac{Hours - Min(Hours)}{Max(Hours) - Min(Hours)})*2">

## Final Visualization :

![Final Visualization](https://github.com/ITrustNumbers/Exploratory_Analysis_On_Steam_Game_Statistics/blob/master/Final_Visualization.PNG)

## Corollary :-
### First, As we can see there are really next to no co-relation between the rating and the play time of a game, This Peculiar phenomena is described below:

1. The rating system is found to be skewed along the genre of a game i.e if a game is a FPS(first person shooting) type game then you cannot compare its rating to the rating of a non FPS game

2. The Rating is developed as soon as the game hits the market whereas the play time increases gradually over the years therefor new game with better rating has infinitesimally small chance of having a play time more than the older games

3. Then there are the challenge of competitive games which demands rigorous play time and determination, this act skews our analysis

4. The nature of rating and repeated gaming is highlighted in the visualization in the fact that the set of top rated games and the set of most played games is disjoint in nature

## Final Summary:
#### To Further increase the accuracy of this analysis clustering is a good option and as of now rating and Play Hours Does not carry or Does but very little co-relation and hence rating is not a good indictor of a games market success

## Requirment for Reproduction 

### 1. Python3

### 2. Jupyter Notebook

### 3. ipykernel

### 4. Pandas

### 5. Numpy

### 6. Matplotlib

### 7. Seaborn

### 8. Scipy
