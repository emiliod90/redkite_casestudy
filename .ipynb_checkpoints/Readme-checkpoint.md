## Redkite case study

This repo contains my answer to an interview case study. It is composed of the raw content file (an Ipython Notebook accessible via Jupyter) and a presentation slide deck 
(the glossy version of my findings and recommendations etc.).

### Introduction

##### Hey, I'm Emilio 👋
I'm a tech consultant based in London. I love building applications and bringing products to life. In my spare time I enjoy creating open source projects to test my knowledge of technology concepts and have recently enjoyed playing around with a few frameworks - FastAPI & React.js ... the next aim is to clear major VC funding and watch my shares go the moon after we IPO 🚀😆. Aside from this, my other hobbies include football, cycling and the occasional "Meetup" to listen to a broad range of topics (A.I. & Cosmology in particular).

Career-wise, I have developed my skills and experience from a firm base within Engineering. This has greatly helped me visualise problems at a detailed level, whilst ensuring congruence with the big picture and business benefit. As far as achievements go, I am quite fortunate that the range of projects I've worked on have been varied - this has given me experience on a number of small and large projects (agile & waterfall) to deliver solutions which have had a positive impact on end-users. A particular proud moment was taking on the role of a quasi-developer/architect/business analyst role to analyse, define and design Nest Pensions Data Hub (within Azure).

### Overview

The objective of the case study is to assess whether the food company's member referal campaign has been successful.
    
#### Approach

The case study has been approached from the perspective of a consulting/advisory peice of work undertaken for a leadership client. It is therefore meant to be concise and to-the-point on determining whether the objective has been met. In this instance, I will walk the client through how we arrived at our destination, pausing to explore topics in greater detail should they wish.

Please open the Redkite_presentation PowerPoint Slides to see the presentation.

#### Intial Thoughts

- What is our definition of success?
- Have we defined the objective of the campaign? What sort of questions should we thinking about to query our data so that we obtain helpful insights about where to focus our efforts on (low hanging fruit / quick wins)
    - Is this a hypothesis test to explore a specific question/answer? E.g. 
        - Does seasonality have an impact on revenue/user growth?
        - Does location have an impact on revenue/user growth?
        - What difference does the referal amount have on revenue/growth?
    - Is this to determine whether a particular outcome of the referal is successful? E.g.:
        a. Does this lead to an increase in follow-on orders?
        b. Do the refered customers make large value purchases? Is their a relationship to the members that refered them (social networks)
        c. Does this lead to a sustained increase in user growth? What is their engagement score
        e. Etc.
- What are the key variables within the dataset which will help us answer this?
- Can we establish who is a refered member?
- Who is the referal value being deducted from? the organisation or the member?
- *Primary concern:* what value are the members that were refered bringing to the company?
    - What is their level of engagement to the service? I.e.:
        a. do these members have consistent ordering habits
        b. high total value orders?
- What is the quality of the data? Has it been cleansed?
- What is the initial approach? 
    - KISS (Keep is simple, stupid)