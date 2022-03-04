# Final Project: Bias in AI and ML Algorithms

Contents:
1. [Part I](#part-i)
2. [Part II](#part-ii)
3. [Part III](#part-iii)

***

## Part I
Sunday, February 13, 2022

### Outline
**Summary**: ML algorithms have proven to bake in and scale up human and societal biases, failing to provide services to people equally and transparently.

**Reader objective:** As a reader, *I want to understand how we introduce biases in ML algorithms* so that I can *apply techniques and good practices to avoid them.*

### Story Arc
* **Setup**: Companies have used ML algorithms as a refreshing antidote to overcome the objective interpretation of data in human decisions.
* **Conflict**: these algorithms are exacerbating human and societal biases, and in some cases, they can have terrible consequences for the people they're supposed to serve. 
* **Resolution**: the ML community is creating standards and open-source toolkits to prevent these biases.

The project structure would like like the following: 

<img src="final_project-story-arc.jpg" width="500">

As you can see, I've highlighted the sections I'd like to go over during my presentation:

1. What is bias in its broadest terms? [Setup]
2. How are biases present in human-based decisions, and why can ML help us overcome those biases?
3. Companies use AI and ML algorithms as a refreshing antidote to overcome human-based decision biases, but they can bake in and scale up human and societal biases if misapplied.
4. Is AI really the answer? go through some examples of how algorithms are making detrimental decisions against protected demographies
5. ML biases can have dire consequences in a human's life [peak of the conflict, where I present a case study]
6. Biases and fairness are complex notions: why is it so hard to prevent and sometimes, even identify.
7. Recommendations of experts to maximize fairness in ML implementations [resolution] 

### The Data

For the project, initially, I'll use four datasets. Here I list the sources with the links. For the next milestone, I'll incorporate the data attributes (columns, datatypes, timeframe, etc.). I'll use these datasets to exemplify how ML algorithms can have detrimental effects and consequences for the populations they're built to serve. I plan to create one visualization for each dataset that conveys how the underlying algorithm scaled-up societal biases, going from minor to deadly consequences. 

| Name | Description | Link | Citation |
|:-----|:------------|:-----|:---------|
| Gender-based discrimination in job-related ads | The dataset contains hundreds of fresh browser instances (ids) along with the Ads seen by "male" and "female" browsers. It was used to test the likelihood of a high-paying job Ad being shown to women vs. men | [Publications section](https://www.cs.cmu.edu/~mtschant/ife/) | Michael Carl Tschantz et al., “A Methodology for Information Flow Experiments,” in 2015 IEEE 28th Computer Security Foundations Symposium (2015 IEEE 28th Computer Security Foundations Symposium (CSF), Verona: IEEE, 2015), 554–68, https://doi.org/10.1109/CSF.2015.40. |
| Assessing Gender Bias in Machine Translation | The dataset contains comprehensive list of job positions from the U.S. Bureau of Labor Statistics (BLS) and used it to build sentences in constructions like "He/She is an Engineer" in 12 different gender neutral languages such as Hungarian, Chinese, Yoruba, and several others. It also provides translations of these sentences into English using the Google Translate API, along with statistics about the frequency of female, male and gender-neutral pronouns in the translated output. | [GitHub Repo](https://github.com/marceloprates/Gender-Bias) | Marcelo O. R. Prates, Pedro H. C. Avelar, and Luis Lamb, “Assessing Gender Bias in Machine Translation -- A Case Study with Google Translate” ArXiv:1809.02208 [Cs], March 11, 2019, http://arxiv.org/abs/1809.02208.| 
| Gender and Jobs in Online Image Searches | The data contains the proportion of women who work in each occupation, using 2017 [Bureau of Labor Statistics data](https://www.bls.gov/cps/cpsaat11.htm). Additionally, it contains the percent of individuals estimated to be women, across 100 Google image search results for each occupation | [Pew Research](https://www.pewresearch.org/social-trends/2018/12/17/gender-and-jobs-in-online-image-searches/) |  “How Men and Women Appear in Online Job Image Searches,” Pew Research Center’s Social & Demographic Trends Project (blog), December 17, 2018. |
| Dissecting racial bias in an algorithm used to manage the health of populations | Commercial prediction algorithms to identify and help complex health needs divided broken down by race. | [GitLab Repo](https://gitlab.com/labsysmed/dissecting-bias) | Ziad Obermeyer et al., “Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations,” 2019, 8. https://www.science.org/doi/10.1126/science.aax2342 |

### Sketches

The sketches below show how I'll represent the datasets described above. Please consider that until I have a look at the data, I won't know what is the message they're conveying. These sketches belong mainly to sections 4 and 5 of the outline above.

<img src="final_project-sketches.png" width="500">

### 4. Method and Medium
The project will be implemented using [Shorthand](https://shorthand.com) to create an immersive narrative and either Tableau or Flourish for visualizations (and incorporate interactivity when applicable). After exploring the options offered by Shorthand, I think it will help me to elevate my story and introduce the tensions I'd like to, based on the readings from Chapter 8 of Good Charts. There's really not much I can say at this point.

[Go back to main page](/README.md) | [Part II](#part-ii) | [Part III](#part-iii)

***

## Part II

### Storyboard

<div class="flourish-embed" data-src="story/1144840"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

***

### User research and interviews

**Reader objective (revised)**: As an ML practitioner, I want to understand how we introduce biases in ML algorithms so that I can apply techniques and good practices to avoid them.

#### Protocol

|Target audience   | ML practitioners  |
|:-----------------|:------------------|
| Type of sampling | Non-probabilistic |
| Sampling method  | Convenience sampling |
| Explanation | As an ML practitioner myself and BIDA student, I know several people close to me that are ML practitioners with relevant work experience, who I think will be good judges of the content of my project. Additionally, when applying ML algorithms in their work, I know they’ll be very interested in understanding why this happens and how they can prevent them. |

#### Questionnaire

|**Dimensions**         | **Questions included** |
|:----------------------|:-----------------------|
|Familiarity with presentation | 1 Likert-type |
| Clarity of intent | 2 open-ended and 1 Likert-type | 
| Credibility | 3 of semantic differential |
| Relevance of information | 1 open-ended |
| Emotional appeal | 1 Likert-type and 1 ranking |
| Visual aids | 3 open-ended, 2 Likert-type and 3 semantic differential |
| Comprehension | 1 Likert-type |
| Gestalt | 2 open-ended and 1 Likert-type |
| **Total** | **22** |

For more details, please see the complete questionnaire [here](https://forms.gle/zXccjWHdapGHU5DU6).

#### Analysis

**Total of responses:** 4

**Likert-type Questions**
Averages to Likert-type questions with agreement scale [strongly disagree - strongly agree], ordered from highest (agree) to lowest:

| Statement | Average |
|:----------|:-------:|
| The visualizations are relevant to the contents | 4.8 |
| The examples provided triggered in me an emotional response | 4.5 |
| I would be interested in knowing more about biases in machine learning and AI | 4.5 |
| I was already familiar with the contents | 4.3 |
| I am familiar with AI and machine learning | 4.3 |
| I learned new things I can employ in my work/life | 4.3 |
| The content was clear and followed a logical order | 4.3 |
| I've heard or read about biases in AI and machine learning | 4.0 |
| The visualizations played a significant role in understanding the contents | 4.0 |

As seen from the table above, the interviewees think the contents followed a good structure and the visualizations were relevant. I also like that the storyline made them want to learn more about biases in AI and ML, which is one of the goals of the project. Additionally, I was interested in knowing how much tension the project creates (based on the [story arc](#story-arc) designed in Part I), and what was their emotional response. 

The top three emotions felt by the interviewees when reviewing the visualizations are: concern (75%), empathy (50%) and upset (50%).  This is very promising as my intention when including the examples was to create concern and build tension so they feel steered towards taking action. Feeling concerned and upset about what is happening out there with industry-use ML algorithms inspires you to learn more and do something about it.

**Semantic Differential**
> Note:  The idea here is to present two opposite adjectives to each end so users can rate the contents, in this case.

| Attribute | Rate |
| :-------- | :--: |
| Unreliable (1) - Authoritative (5) | 4.5 |
| Illogic (1) - Rational (5) | 5.0 |
| Unappealing (1) - Pleasant (5) | 4.5 |
| Bewildering (1) - Insightful (5) | 4.5 |

The results are very positive and help me quickly assess the credibility of the project.

**Open-ended Questions**

*Clarity of intent*

I asked respondents what they thought was the objective of the project and based on their responses, I realized that I'm not writing to ML practitioners wanting to apply de-biasing techniques in their algorithms. The answers were:
 
 * "Sharing findings about how AI and ML bias affect human life and what actions to take to mitigate it"
 * "Show how machines, algorithms or robots are prepared to build messages with biases predetermined by humans"
 * "Raise awareness on biases, AI and ML"
 * "Raise awareness about bias and discrimination, and how those manifest in the digital world."

I need to find a way to be more precise when delivering the content. For example, saying, "as an ML practitioner, you may want to take a look at these methods" or maybe customizing the contents depending on who is the audience by creating different sections for different audiences; "if you're an ML practitioner, click here," "if you work with ML algorithms and like to know how to start the conversation, click here," etc. I'm still not sure how to tweak the contents in this sense.

*Takeaways*

I liked that the contents leave ideas to be remembered, and that's very important. I asked: "If you were to choose one takeaway from the contents, what would it be?" and they answered:

* "There is unspoken bias among AL and ML algorithms"
* "Be aware about AI: When could be a help or a risk"
* "AI is presented as a way to mitigate bias, but this is not entirely true. It replicates them."
* "Technology can amplify the negative impact of cognitive biases."

*Effectiveness of the data visualizations*

There are two specific comments about what didn't work in the visualizations: 1) some say they wish they had seen color legends to identify variables, and 2) the racial bias plot was not at all straightforward. Regarding the former, I thought that color-coding the text would make the legends redundant, but I can think about that further. The comment about the racial bias plot was not surprising because I've been struggling with that data, so I need to think about better ways to represent it.

Regarding what they would do differently, they said that some DataViz are hard to read so they would add more information on how to interpret the data and what it means. I think that adding a paragraph with discussion may tackle this problem, where I can further develop the insight that I tried to include in the titles.

**Closing Questions**

Finally, I asked them what change they would make to the storyline and the answers were:

* "I may start the story with a shocking bias example to get audience's attention first and then introduce my topic in detail."
* "Transition between 8 and 9 because although the theme is bias, it doesn't give closure to the previous topic"
* "Given that there is no consensus on the issue, I would have used questions in closing to engage readers and leave them the space to reflect on their own ideas and draw their own conclusions"
* "Get to the visuals faster."

I loved all these recommendations and I am planning to include them all; I think addding these changes to the storyline can definitely make it more impactful.

[Go back to main page](/README.md) | [Part I](#part-i) | [Part III](#part-iii)

***

## Part III
March 3, 2022

Once I received the user feedback, I focused on changing the storyline to introduce some of the suggestions made by my interviewees. For example, in the streamlined version of my project, I start with a "shocking" example to grab the audience's attention. That also helped me get to the visuals quickly and not waste much time introducing the topic. Additionally, I tried to include either a short explanation or the main takeaway on my more extended version, so the reader knows what they're looking at and how it is relevant to the topic. I didn't change much in terms of the visualizations (as suggested by one interviewee) as I felt including legends to identify the series would've been redundant with the color-coding used in the titles.

On the other hand, I worked on different ways to speak to my audience. My first thought was customizing the content for ML practitioners. Still, considering the presentation we had to do in class, I later thought about tweaking the content to talk to a broader and less-specialized audience. That entailed not using much jargon and not going into the details of how to debias the algorithms. Instead, I included at the very end a link to valuable resources for ML practitioners in case they want to dig deeper and get their hands dirty with the different debiasing techniques proposed by the scientific community. 

*"Knowing your audience"* is how I'd summarized the journey when working on this project. That influenced how I defined the storyline, my project's specific contents, and the type of visuals I used throughout the presentation. Doing the user research was extremely helpful to understand better whether my storyline had the impact that I was intending. Also, identifying any gaps between my visuals and the contents was very important to find different ways to fill those.
In general, I enjoyed the creation process and comparing my first sketches with my final result.

### Final project Links

1. [Streamlined version](https://carnegiemellon.shorthandstories.com/bias-ai-ml/index.html)
2. [Complete version](https://carnegiemellon.shorthandstories.com/when-algorithms-failed-us/index.html)

[Go back to main page](/README.md) | [Part I](#part-i) | [Part II](#part-ii)
