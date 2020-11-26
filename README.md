<h2>Title</h2>
Fine-Grained Mobility Patterns and its Relationship to Social Networks

<h2>Abstract</h2>
The paper explores the structural patterns of mobility due to geographic and social constraints. For long-distance travel, the authors focus on the influence from social network; while for short-ranged travel, the authors claim that it is heavily dependent on periodic behaviors and not effect by the social network.
On the contrary to the paper’s research direction, we are more interested in fine-grained level human mobility. We propose to investigate human daily mobility, including activity differences at different time for every individual, activity difference between people from countries. In addition, we would like to study the relationship between human periodic mobility and social networks.
Understanding mobility provides us insights to make decisions, from small things around us, to big things that would be impactful to a country. For instance, where can I travel during Christmas if I don’t want to visit overcrowded areas? Under covid-19 pandemic, which areas are gathered by people and how should the government respond? Although we don’t answer these two specific questions, our research is a good point to start with.

<h2>Research Questions</h2>

1. Activity differences at different time for every individual
- Will people change their daily mobility at different seasons?
- Will people change their daily mobility at different years?
2. Activity difference between people from countries
- Do people from different countries have different activity preference? 
- Do people from different countries demonstrate different periodic behaviors?
3. Relationship between human periodic mobility and social networks
- Do friends demonstrate similar mobility pattern? 
- What is the probability of establishing a new friendship with respect to mobility behaviors?

<h2>Proposed dataset</h2>
The dataset* (https://drive.google.com/file/d/1PNk3zY8NjLcDiAbzjABzY5FiPAFHq6T8/view) includes long-term (from 2012.04 to 2014.01) global-scale check-in data collected from Foursquare. It contains 22,809,624 checkins by 114,324 users on 3,820,891 locations (userID, check-in time, check-in location, location type). The location type contains home, office, gym, train station, etc, which is important for us to perform fine-grained analysis.
In addition, we have two social network data, which are old friendship before the check-in being recorded, and new friendship after the check-in being recorded.


*Dingqi Yang, Bingqing Qu, Jie Yang, Philippe Cudre-Mauroux, Revisiting User Mobility and Social Relationships in LBSNs: A Hypergraph Embedding Approach, In Proc. of The Web  Conference (WWW'19). May. 2019, San Francisco, USA.

<h2>Methods</h2>
For three main tasks, we need to perform different operations.

1. Activity differences at different time for every individual: 
Separate the data by months/year. Analyze whether check-in location type change?. Analyze whether people go to the office and back home at different time. Analyze whether people visit some places at specific time, eg. Christmas, Holloween, etc.

2. Activity difference between people from countries:
Query several/all countries, depending on the datasize, and how will we visualize the results. Analyze when people from different countries go to the office. Analyze the top 20 most common visiting locations from countries. (We expect Ramen Shop in Japan, Beer Garden in Germany, etc.)

3. Relationship between human periodic mobility and social networks:
Merge the check-in data with old-friendship data. Analyze whether friends visit locations with proximity in terms of physical location. Or, do they visit locations with proximity in terms of type of location, eg. Gym, cafeteria, movie theater? Merge the check-in data with new-friendship data. Analyze the probability of new friendships with respect to users’ activity preference; namely, check-in location, location type, etc.

<h2>Proposed timeline</h2>

**Week1**: Clean and Merge the data. Answer the research questions. Analyze whether the answer match / do not match what we expect.

**Week2**: Analyze the answers. Transform the answers into visualization. 

**Week3**: Prepare the datastory and short Video.

<h2>Organization within the team</h2>

**Yu-Ting Huang**: relationship between human periodic mobility and social networks.

**De-Ling Liu**: activity difference between people from different countries.

**Adel Qasem**: activity difference at different time for every individual.

Everyone is responsible for the analysis and visualization of their own tasks. Create the datastory together.
