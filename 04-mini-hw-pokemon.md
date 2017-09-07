# Mini HW 04 - Visualizing Pokemon
Mine Cetinkaya-Rundel  
Sep 7. 2017  



Load required packages:


```r
library(readr)
library(ggplot2)
library(dplyr)
```

## Data

Load data:


```r
pokemon <- read_csv("data/pokemon.csv")
```

View the data:


```r
pokemon
```

```
## # A tibble: 811 x 8
##       id identifier species_id height weight base_experience order
##    <int>      <chr>      <int>  <int>  <int>           <int> <int>
##  1     1  bulbasaur          1      7     69              64     1
##  2     2    ivysaur          2     10    130             142     2
##  3     3   venusaur          3     20   1000             236     3
##  4     4 charmander          4      6     85              62     5
##  5     5 charmeleon          5     11    190             142     6
##  6     6  charizard          6     17    905             240     7
##  7     7   squirtle          7      5     90              63    10
##  8     8  wartortle          8     10    225             142    11
##  9     9  blastoise          9     16    855             239    12
## 10    10   caterpie         10      3     29              39    14
## # ... with 801 more rows, and 1 more variables: is_default <int>
```


## Analysis

### Task 1: 

*Pick two numerical variables and use a scatterplot to visualize their relationship.*




### Task 2: 

*Pick a third categorical variable, and color the points on the scatterplot by levels of this variable.*



### Task 3: 

*Pick two categorical variables and make a bar plot that depicts the relationship between them.*



### Task 4: 

*Pick a numerical and a categorical variable, and construct side-by-side box plots depicting the relationship between them.*



### Task 5: 

*Learn something new: violin plots! Read about them at http://ggplot2.tidyverse.org/reference/geom_violin.html, and convert your side-by-side box plots from the previous task to violin plots.*



