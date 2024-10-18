# CMSC320 Final Project

_John Burke, Ryan DeCamp, Rob Hopkins, Tal Ledeniov_


### Analysis Notes

#### Oscar flags
Oscars are more significant in this dataset. There is no column 'Oscars_won' that tells you how many they won like there is for the others (ex: 'Golden_Globes_won').

Instead, each Oscar has its own flag:
```py
[ # oscar award flags
    "Oscar_Best_Picture_nominated"
    "Oscar_Best_Director_won"
    "Oscar_Best_Director_nominated"
    "Oscar_Best_Actor_won"
    "Oscar_Best_Actor_nominated"
    "Oscar_Best_Actress_won"
    "Oscar_Best_Actress_nominated"
    "Oscar_Best_Supporting_Actor_won"
    "Oscar_Best_Supporting_Actor_nominated"
    "Oscar_Best_Supporting_Actress_won"
    "Oscar_Best_Supporting_Actress_nominated"
    "Oscar_Best_AdaScreen_won"
    "Oscar_Best_AdaScreen_nominated"
    "Oscar_Best_OriScreen_won"
    "Oscar_Best_OriScreen_nominated"
    "Oscar_nominated"
    "Oscar_nominated_categories"
]
```