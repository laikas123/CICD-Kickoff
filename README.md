# Jenkins Worflow

test
test2
test3
test4
test5
test
test

my pull request stuff!!!!!

```mermaid
flowchart LR
   
   
     
   
    Dave -->|"1) push"|SOM-WWW 

    SOM-WWW -->|"2) notify"|Jenkins{Jenkins}
    Jenkins -->|"3) pull"|SOM-WWW 
    Jenkins -->|"4) start"|Pipeline(("Pipeline"))
    
   
    style Jenkins fill:#E0FFFF,stroke:#000,stroke-width:2px,color:#000,stroke: 5 5
    style SOM-WWW fill:#808080,stroke:#000,stroke-width:2px,color:#FFF,stroke: 5 5
    style Pipeline fill:#00FF00,stroke:#000,stroke-width:2px,color:#FFF,stroke: 5 5
    
```


# Pipeline Workflow

```mermaid
    flowchart LR
   
   
     
   
    Unit_Tests("Unit Tests") --> Build{"Build"}
    Build -->Selenium_Tests("Selenium \n Tests")
    Selenium_Tests --> Deploy

   
    style Unit_Tests fill:#E0FFFF,stroke:#000,stroke-width:2px,color:#000,stroke: 5 5
    style Build fill:#808080,stroke:#000,stroke-width:2px,color:#FFF,stroke: 5 5
    style Selenium_Tests fill:#E0FFFF,stroke:#000,stroke-width:2px,color:#000,stroke: 5 5
    style Deploy fill:#00FF00,stroke:#000,stroke-width:2px,color:#FFF,stroke: 5 5
    

```




## General Questions


### Will we be using docker to build the website? Or are we going to launch to AWS? <br>(I had trouble using the docker instructions)
<br>

### Is there a single development branch all the devs work on before merging to main? Or do they <br> each have their own branch?
<br>

### How do we make sure all the developers are in sync? E.g. "Hey I'm about to commit to main". For instance says <br> Dave is working on feature 1 then mike is working on feature 2. How do we make sure that if Dave commits <br> feature 1 to main that Mike first checks out Daves newest commit before merging to main?
<br>

### Where are the unit tests in the SOM-WWW repo? Also how are the selenium tests created?
<br>

### What kind of agents will we use in Jenkins? Docker containers? AWS?
<br>

### What visualization tools will we use? E.g. Blue Ocean?
   
   test
test
test
test
test
test
test
test
test
test
test
test
test
test
test
