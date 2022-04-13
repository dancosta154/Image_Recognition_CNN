# Capstone: Image Recognition with Neural Networks

## Identifying Wildfire Smoke within an image

#### Project Status: [Incomplete]


### Introduction

Over the past thirty years, the number of wildfires in the United States have decreased, yet the annual average of burned acreage has more than doubled. "Since 2000, an annual average of 70,600 wildfires has burned an annual average of 7.0 million acres. This figure is more than double the average annual acreage burned in the 1990s (3.3 million acres), although a greater number of fires occurred  annually in the 1990s (78,600 average).[[1]](#1)" 

<img src="./acres_burned.png" width="700" height="700">

This spike in fire intensity has caused some of the most costly and destructive fires in United States history. As it stands today, nine of the ten most costly fires (evaluated by loss in millions) in the United States have occurred since 2007.

| Rank | Year | Name | Dollars (in Millions) | State |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 2018 | Camp Fire | \$10,750 | CA |
| 2 | 2017 | Tubbs Fire | \$9,560 | CA |
| 3 | 2018 | Woolsey Fire | \$4,520 | CA |
| 4 | 1991 | Oakland Fire | \$3,350 | CA |
| 5 | 2017 | Atlas Fire | \$3,300 | CA |
| 6 | 2020 | Glass Fire | \$3,070 | CA |
| 7 | 2020 | CZU Lightning Complex Fire | \$2,600	 | CA |
| 8 | 2017 | Thomas Fire | \$2,470 | CA |
| 9 | 2020 | LNU Lightning Complex Fire | \$2,340 | CA |
| 10 | 2007 | Witch Fire | \$2,080 | CA |










The intent of this project is to build a model that can identify smoke within an image for the intended use of being able to identify a wildfire in a remote location.







Wildfire History
- Decade by decade
- Fires nationwide in past 5 years
- Most costly fires in history
- Most destructive in CA

Introduce WPREN camera system in CA

Define Problem Statement


### Executive Summary

Explain modeling
- Data Source
- Image Augmentation
- Convulational Layers ... maxpooling, dropout

Model Performance
- Training Accuracy
- Binary Cross Entropy
- Confusion Matrix - False Negatives vs False Positives


### Conclusions

Predictions on Testing data

Tie back into Problem Statement


### Next Steps

- Increase amount of data
- Incorporate [Roboflow](https://roboflow.com/) to label data in a way needed for building bounding boxes
- Connect to an Alert Notification system when smoke is present




## Project Outline (Pre-Work)

**Paint the recent wildfire picture in US:**

1990 - current (quick-high level)
- Number of Fires burned by year - nationally
- Acres burned by year - nationally

2021 (quick-high level most recent year)
- Wildfires by State (2021) -- num fires & acres burned -- *Already have this*
- Top 10 States for Wildfires Ranked by Number of Acres Burned (2021) (scale based on state size) -- *Already have this*
- *Also have it by number of fires -- but don't care as much about this I don't think.. could join df's if needed*

**Minimize Focus to CA based on previous graph** (little more time spent here, driving home these points as very concerning)
- Count of Largest Fires in this time period vs all time -- *Already have this*
- Count of Most Destructive Fires in this time period vs all time -- *Already have this*
- Count of Costliest wildfires in this time period vs all time -- *Already have this*
- Count of Deadliest wildfires in this time period vs all time -- *Already have this*

... this is a good way to tell the "How Fires are Exploding in the last 30 years" story...

**Next:**

Collect data for how important it is to identify / respond quickly to new start

Talk about challenge in "confirming" a fire (a confirmed fire is anything >= 0.1 acres) -- often times it's crowd-sourced information... i.e. "Saw a bunch of smoke while hiking over by x trailhead" or "There may be smoke in the distance somewhere in the Arapahoe National Forest"

**Capstone Intro**

That will lead nicely into Capstone project of building a model to identify Smoke Columns via imagery


## Project Obective


### File Structure
```
project
│   
│
│
└──clean_data
│     
│         
│   
└──data_cleaning_and_eda
│    
│  
│
└──engineered_data
│     
│
│
│
└──graphics
│     
│      
│    
│          
└──models
│     
│  
│ 
└──raw_data
      

```


## References
<a id="1">[1]</a> 
https://sgp.fas.org/crs/misc/IF10244.pdf

