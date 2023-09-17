![](images/cap.png)

👋 Hi! My name is Guillem Miralles, and I'm a passionate data scientist and AI enthusiast. 📚🧠

I have a degree in **Data Science** 📊 and a master's degree in **Artificial Intelligence** 🤖 from **University of Valencia.** 🎓 

Welcome to my vibrant portfolio, where I showcase some of my diverse projects and their exciting results. 💼✨

Explore the intersection between data and creativity through my data visualizations 📊, predictive modeling 📈 and cutting-edge AI applications. 🌟

# [Project 1 (Python) - Estimation through non-destructive analysis of the nutritional levels of citrus leaves applying Machine and Deep Learning techniques](https://github.com/GuillemMiralles/Nutritional-Sleuths) 🍊🌿🤖🔍

## Presentation 📊
This is my Bachelor's Thesis, titled 'Estimation of Nutritional Levels of Citrus Leaves through Non-Destructive Analysis Using Machine and Deep Learning Techniques.' It has been an incredible journey of research and exploration, and obtaining a score of 9.7 fills me with immense pride. I firmly believe in the potential of this work to bring significant social value by revolutionizing the way we monitor and manage citrus tree health. 🌳🍃🎓

The main focus of this project is to estimate the nutritional levels of citrus trees using hyperspectral images generated by their leaves. By leveraging cutting-edge Machine Learning and Deep Learning techniques, we have developed a non-destructive approach that allows us to gain valuable insights into the health and nutrient status of these vital plants without causing any harm. 🛠️💻🌈

This project was done in collaboration with the Instituto Valenciano de Investigaciones Agrarias (IVIA) 🤝🌍

I believe that open knowledge-sharing can foster innovation and progress, which is why I am thrilled to share this work with the wider community. I hope it inspires others and sparks fruitful collaborations in the field of agriculture and beyond. 🌱🌎✨

# [Project 2 (Python) - Field Wizard: Predicting Positions and Formations for Success on the Soccer Field](https://github.com/GuillemMiralles/Field-Wizard)⚽🧐🔥

## Objectives 🎯
In this project, we sought to accomplish the following objectives using **Deep Learning techniques**:

1. **Predict possible player positions** on a soccer field based on their attributes. 🏃💨
2. **Predict the optimal team formation** for a team given the attributes of its players and the attributes of its opponents. 📊⚽

Throughout the course of this project, we utilized multiple dataframes and undertook a significant amount of data adaptation work. This included a comprehensive **Exploratory Data Analysis (EDA)**, which helped us gain insights into the data and inform our modeling process. 📈💡

## Why this? 💭
- The first project is interesting for its potential applications in player development, talent identification, strategic planning, and injury management. It demonstrates the power of AI in sports analysis and decision-making. 🤖💪
- The second objective is intriguing for its potential to revolutionize strategic decision-making in soccer. This model could help coaches design effective game plans, taking into account the strengths of their team and the specific challenges posed by opponents. It could also be valuable in dynamic situations, such as responding to player injuries or suspensions. 🚑📈

## Results 📊
The results were impressive. Below is a summary of our findings:

| Task | Accuracy | F1-Score |
| --- | --- | --- |
| Predicting Player Positions | 0.97 | 0.99 |
| Predicting Optimal Team Formation | 0.783 | 0.782 |
  

# [Project 3 (Python) - Reinforcement Learning in OpenAI Gym: Tackling the Taxi Problem](https://github.com/GuillemMiralles/RL-Taxi-v3) 🚖🤖🎮

## Objectives 🎯
- The objective of the project is to apply and evaluate a Reinforcement Learning (RL) approach to solve the challenging Taxi problem within the OpenAI Gym environment. Specifically, the goal is to train an RL agent capable of learning an optimal policy to maximize efficiency in picking up and delivering passengers, minimize travel time, and optimize the routes used by the virtual taxi driver. 🗺️🚀

## Why this? 💭
- The project focuses on the Taxi problem within the OpenAI Gym environment because it presents a unique and complex scenario that challenges the capabilities of Reinforcement Learning (RL). This problem involves various factors, such as route planning, optimal decision-making, and time utilization, all within the context of traffic constraints and passenger demands. By successfully applying RL techniques to this problem, the project aims to demonstrate the adaptability and effectiveness of RL algorithms in solving real-world, dynamic, and multi-dimensional challenges, which can have applications in various domains beyond virtual taxi navigation. 🌐💡

## Results 📊

Q-Learning proves to be effective in this scenario. This algorithm is capable of solving the Taxi v3 problem efficiently and optimally, as can be observed in the video displaying the 10,000 training episodes.

Through the exploration and exploitation policy and the iterative update of the Q-table, the agent has learned to pick up and drop off passengers efficiently in the correct locations. The results obtained have been remarkable, with the taxi consistently optimizing the route, reaching the passenger and their destination in the most efficient manner possible. ✅🚖


# [Project 4 (RStudio) - Deep in the Depths of Sleep: Creating Interpretable Models to Detect Sleep Phases Using Polysomnography Signals from Patients](https://github.com/GuillemMiralles/Sleep-Phases) 🛌💤🔍

## Objectives 🎯
In this project, we try to **classify sleep stages** based on PSG signals using **Interpretable Machine Learning techniques**. Throughout the project, we employed interpretability-focused machine learning models to analyze PSG signals and accurately identify the different phases of REM sleep. 💡🔬

## Why this? 💭
- Classifying sleep stages based on PSG signals using interpretable machine learning techniques is useful for medical diagnosis and treatment of sleep disorders, monitoring sleep quality, providing personalized sleep recommendations, advancing sleep research, and enhancing sleep tracking with wearable devices. Interpretable machine learning models help identify relevant PSG features and their relationships to sleep stages, empowering individuals to understand their sleep patterns and make informed decisions for improved sleep health. 🩺💤

## Results 📊

Below is a table of results for the models used:

| Model            | Accuracy | Sensitivity | Specificity | Best Model |
|------------------|----------|-------------|-------------|------------|
| Logistic Regression | 0.85     | 0.79        | 0.89        | ❌          |
| Random Forest    | 0.94     | 0.98        | 0.66        | ✅          |
| Rule-Based Model (CBA) | 0.93 | 0.99      | 0.66        |            |

✅ **Best Model**: Random Forest

- The Random Forest model achieved an accuracy of approximately 94% in sleep classification, with high sensitivity (98.9%) but lower specificity (66.4%).

- We identified that variables related to channel standard deviation are crucial in classification, especially in the Random Forest model.

- We observed interesting interactions between the variables of standard deviation of channel O1 and the electromyograms.

- We used techniques like LIME and Shapley to interpret models at a local level and understand how variables affect predictions.

  
# [Project 5 (RStudio) - Data Dunk in the NBA: A Shiny Dashboard of Advanced Metrics and NBA Predictions](https://github.com/GuillemMiralles/Shiny-NBA-App) 🏀📊👁‍🗨

## Objectives 🎯
The purpose of this dashboard is to view advanced NBA statistics and prediction models. The user can interact by selecting season, team, players ... 

We have:
- Tables with statistics of teams and players given the season that the user indicates. 📈
- Advanced statistics of teams, players and players' shooting. 🏀📊
- Prediction on which players will be in the ALL-NBA Team. 🌟
- Evolution of the average salary in the NBA. 💰

## Why this? 💭
- This project could serve as a template for a more comprehensive NBA statistics dashboard. It offers numerous possibilities for expanding both the range of statistics and the models used. By enhancing the dashboard, we can explore a wider array of statistical insights. Moreover, we have the opportunity to develop new models that can predict future game outcomes, championship results, and more. Additionally, there is room for improvement in the All-NBA Team model, as it currently relies on linear models. 📈🔍

## Results 📊
### [Shiny Dashboard](https://guillemmiralles.shinyapps.io/5_42/) 🌐

# [Project 6 (Python)  - News Categorizer: NLP's Quest to Sort Meneame.net News](https://github.com/GuillemMiralles/Meneame_News_Classifier/tree/main) 📰🏷🕶💻

## Objectives 🎯
In this previous project, we sought to accomplish the following objective using **NLP (Natural Language Processing) techniques** to **Classify the type of news** in the meneame.net database which contains 177,000 news from different newspapers. 🗞️🔍

## Why this? 💭
- This project was intriguing due to its potential for various applications, such as improving news organization, content recommendation, and understanding user preferences. It showcased the power of NLP in handling large volumes of text data and extracting valuable insights. 📄🧠

## Results 📊

The results of this project were significant and provided valuable insights into the classification of news articles. Here's a summary of our findings:

| Task | F1 | Leisure F1 |
| --- | --- | --- |
| SVC with Doc2Bow | 0.7655 | 0.52 |
| Logistic Regression with TF-IDF | 0.7741 | 0.45 |
| Linear SVC with LSA | 0.7589 | 0.38 |
  
#### [The Complete Article in Medium](https://guillemmiralles1.medium.com/news-classification-unbalanced-classes-nlp-e865ac33eb85)📜✍️







