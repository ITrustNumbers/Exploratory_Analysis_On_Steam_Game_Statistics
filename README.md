# This is an Exploratory Analysis on Steam Game Statistics Focusing on the Rating of Games and Hours Played on steam

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

## Requirment for Reproduction 

### 1. Python3

### 2. Jupyter Notebook

### 3. ipykernel

### 4. Pandas

### 5. Numpy

### 6. Matplotlib

### 7. Seaborn

### 8. Scipy
