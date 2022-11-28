-----------------
-----------------

<hr>

# Zipa-Agile-Project

# ML-API-DR

---------

### Dataset

![This is an screenshot of the responsive design image]
----

[Live Webpage]

----

## About

## Table of Contents

- [ML]
  - [About](#about)
  - [Table of Contents](#table-of-contents)
  - [Project Goals](#project-goals)
    - [User Goals](#user-goals)
    - [Site Owner Goals](#site-owner-goals)
  - [User Experience](#user-experience)
  - [Design](#design)
      - [Colours](#colours)
      - [Typography](#typography)
    - [Target Audience](#target-audience)
    - [User Requirements and Expectations](#user-requirements-and-expectations)
    - [User Stories](#user-stories)
      - [First-time User](#first-time-user)
      - [Site Owner](#site-owner)
    - [User Manual](#user-manual)
  
  - [Technical Design](#technical-design)
    - [Flowchart](#flowchart)
    - [Wireframes](#wireframes)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Framework and Tools](#framework-and-tools)
  - [Features](#features)

  - [Testing](#testing)

  - [Deployment](#deployment)
    - [Deploying to Github Pages](#deploying-to-github-pages)
  - [Credits](#credits)

  - [Acknowledgements](#acknowledgements)

-----
## Project Goals

### User Goals

### Site Owner Goals

-----
## User Experience

## Design

#### Colours

![Colours Palete]

#### Typography

- The Robot font is used as the main font for the whole project. Is adding to the project by importing from Google fonts.

### Target Audience



### User Requirements and Expectations



### User Stories

#### First-time User

1. As a user, I want to:

#### Site Owner
2.  As the site owner, I would want:
   

### User Manual

<details><summary>Instructions</summary>

## Creating the Model

#### Overview


```     
(venv) gitpod /workspace/Zipa-Agile-Project/ML-HC (main) $ history
    1  ls
    2  cd ML-HC
    3  activate
    4  . venv/activate
    5  . venv/bin/activate
    6  pip  install pandas
    7  git add .
    8  git commit -m "initial data review"
    9  git push
   10  history
(venv) gitpod /workspace/Zipa-Agile-Project/ML-HC (main) $ .venv Set For the model


```
------
------

```
import pandas
from sklearn import tree
import pydotplus
from sklearn.tree import DecisionTreeClassifier
import matplotlib.pyplot as plt
import matplotlib.image as pltimg
from sklearn.metrics import classification_report, plot_confusion_matrix, plot_roc_curve
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler


```
-----
-----


```
df = pandas.read_csv("https://raw.githubusercontent.com/paulwababu/datasets/main/drug200.csv")
print(df.head())
```
----
----
-----
-----


```



```
----
----


```
Age Sex      BP Cholesterol  Na_to_K   Drug
0   23   F    HIGH        HIGH   25.355  drugY
1   47   M     LOW        HIGH   13.093  drugC
2   47   M     LOW        HIGH   10.114  drugC
3   28   F  NORMAL        HIGH    7.798  drugX
4   61   F     LOW        HIGH   18.043  drugY


```


---
---



#### Home page

</details>

[Back to Table Of Contents](#table-of-contents)

## Technical Design

### Flowchart

The following flowchart sumerises the structure of the Game.

![]

----

### Wireframes

----

</details>

## Technologies Used

### Languages Used

- [HTML 5](https://en.wikipedia.org/wiki/HTML/)
- [CSS 3](https://en.wikipedia.org/wiki/CSS)
- [JavaScript](https://www.javascript.com/)

### Framework and Tools
* [Git](https://git-scm.com/) Used for version control to push the code to GitHub.
* [GitHub](https://github.com/) Used as a repository to store the projects code.
* [lucidchart](https://www.lucidchart.com/) Used to create the project flow.
* [Am I Responsive?](https://ui.dev/amiresponsive) To show the website image on arange of devices.


## Features

### Existing Features

#### Home page

#### Home page -sidebar

## Testing

### Validator Testing

   
### Testing User Stories

----

### Testing Site Owner

----

[Back to Table Of Contents](#table-of-contents)

----

### Unfixed Bugs

#### Home page 

![Home page]
<br>



---

## Deployment

### Deploying to Github Pages

* The site was deployed to GitHub pages. The steps to deploy are as follows:


 The live link can be found here:- 
 
## Credits

### Sounds Effect and Ambience Music
  * Sounds Effect [Boombox](https://boombox.mtmograph.com/)
  * Ambience Music [Pixbay](https://pixabay.com/)

### Images and Graphics
  * Background images


### Information Sources / Resources

- [W3Schools](https://www.w3schools.com)
- [Stack Overflow](https://stackoverflow.com/)
- [Code Institute - Slack Community](https://slack.com/)


## Acknowledgements

* [Code Institute](https://codeinstitute.net/) & the hackteam for all their hard work in running the hackathon

[Back to Table Of Contents](#table-of-contents)

--------------
