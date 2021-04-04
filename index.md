# Hello! I'm Vivian. :wave:
## About Me 

![Profile Pic](./images/profile.jpg&s=150x)

I'm currently a second-year undergraduate pursuing a B.S. in computer science at the University of California, San Diego. I'm an aspiring front-end developer with interests in design and UI/UX. My ultimate goal is to create conscious and meaningful content that will inspire others. Striving to improve my skillset and expand my knowledge, I am currently seeking internships and collaborations, so please feel free to contact me if interested! :smile:  

Check out my projects [here](#recent-projects) and download my resume [here](./files/Yan_PWCResume.pdf)!

On a more personal note, I'm a huge fan of crime shows and basketball (Go Warriors! :blue_heart::yellow_heart:), so I'm always watching one or the other during my free time. I also love spending time in nature, especially through hikes and picnics, and with my family, friends, and furry friends.  

![Warriors](./images/warriors.jpg&s=100x)
![Nature](./images/nature.jpg&s=100x)
![BigRats](./images/bigfriends.jpg&s=100x)
![Rat](./images/smallfriend.jpg&s=100x)

#### Skills
###### Programming 
- HTML/CSS
- Javascript 
- Java 
- Python 
- C/C++
  
###### Tools 
- Git/Github 
  
## Recent Projects

### COVID-19 Policies vs. State Economy Analysis 
**role:** data cleaner + analyst    
**duration:** Nov 2020 - Dec 2020  
**overview:** I worked in a team of five to conduct a data science project from start to finish. Our focus was analyzing the relationship between COVID-19 policies and individual state economies to determine if a relationship exists. We chose to analyze California, Nevada, and Utah because of their geographical proximity and varying economies. After *many* iterations, we decided to explore this research question: 
> Do state-wide COVID-19 policies in California, Nevada, and Utah have a significant effect on that state's economy? Specifically, what effect is there, if any, of government policy on a state's unemployment rates, consumer spending, and small business revenue?

Fortunately, we were able to find relevant datasets through Github and open government data sources. My job was to parse through these datasets to extract and clean the data we needed using Python pandas library. Below is an example code snippet of one of the cleaning procedures, specifically the one to extract our desired states and their respective data: 

```
def get_state_df_econ(dataf, fips):  
        state = dataf[dataf['statefips'] == fips]  
        state = state.reset_index(level=0)  
        state = state.drop(columns=['statefips', 'index'])  
        first_col = state.pop('Date')  
        state.insert(0, 'Date', first_col)
        return state  
```


Read more about this project [here](https://github.com/COGS108/group018_fa20/blob/main/FinalProject_group018.ipynb)!

--------------------------------------------------------------------------
### Text-Activated Generator
**role:** programmer + ui design 
**duration:** August 2019 - September 2019
**overview:** Together with a partner, we trained a machine learning classifier in Python to distinguish between two possible intents, generating a joke or photo based on the distance between user’s query and each label cluster. 

How it works: 
1. User enters input
2. Parse input to calculate distance between input and label clusters 
3. Output photo or joke based on smaller distance 


## Goals
- [ ] Become more involved in orgs
- [ ] Complete a personal project by the end of summer
- [ ] Land a web development internship

## Contact 
[LinkedIn](https://www.linkedin.com/in/vivianyan19/) | [Email](mailto:vivianyan19@gmail.com) | [Github](https://github.com/v2yan) 

