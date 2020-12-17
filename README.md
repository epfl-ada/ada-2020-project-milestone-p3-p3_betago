<h2>Title: Someone like you</h2>

<h2>Abstract</h2>

With more than 7.7 billion world population, do you want to understand the binding force between people? Is it more likely for sociable people to meet someone homogeneous? Are you curious about how similar are you to the strangers, or to your friends? Could you meet someone with similar mobility pattern with you in a restaurant or convenience store? Or is it more likely to meet someone like you in bar or gym?

In this datastory, we start with a high-level investigation on similarity between two of people's features: sociability and average traveling distance. Then we study fine-grained level human mobility, which are similarity from people around the world, to people living in the same country, then to pairs of friends. As we reveal the story, you can find that cultural difference in country plays an important role in inflencing people's movement. Consequently, we  the periodic and non-periodic mobility difference between countries.
study fine-grained level human mobility, and investigate similarity from people around the world, to people living in the same country, then to pairs of friends. As we reveal the story, you can find that cultural difference in country plays an important factor in inflencing people's movement. Consequently, we focus on the periodic and non-periodic mobility difference between countries.

<h2>Research Questions</h2>

1. Broad introduction: example of criterias
- How does sociability affect one's mobility?
- How does traveling distance affect one's mobility?
2. Friendship and Mobility
- How similar it is between friends, strangers in different, same countries?
- How far away are the strangers?
- Are the friendships fading?
3. Country and Mobility
- What are the popular visited location types (non-periodic) in different countries?
- Seasonality - Will visited frequencies of popular location types change with time?
- Case Study in US: What are the location types to meet strangers similar to you?
- What are the periodic behaviors difference in different countries?

<h2>Proposed dataset</h2>
The dataset* (https://drive.google.com/file/d/1PNk3zY8NjLcDiAbzjABzY5FiPAFHq6T8/view) includes long-term (from 2012.04 to 2014.01) global-scale check-in data collected from Foursquare. It contains 22,809,624 checkins by 114,324 users on 3,820,891 locations (userID, check-in time, check-in location, location type). The location type contains home, office, gym, train station, etc, which is important for us to perform fine-grained analysis.
In addition, we have two social network data, which are old friendship before the check-in being recorded, and new friendship after the check-in being recorded.


*Dingqi Yang, Bingqing Qu, Jie Yang, Philippe Cudre-Mauroux, Revisiting User Mobility and Social Relationships in LBSNs: A Hypergraph Embedding Approach, In Proc. of The Web  Conference (WWW'19). May. 2019, San Francisco, USA.

<h2>Methods</h2>
For three main tasks, we need to perform different operations.

1. Broad introduction: 
Analyze how the median cosine similarity evolves in a group as a function of the distance a function of how many friends the group's members have. Analyze how the median cosine similarity evolves in a group as a function of the average dstance traveled from home for each check-in by members of the group. These broad example serve as an introduction to the more focused material that follows.

2. Friendship and Mobility:
Analyze the similarity (computed in two ways) of the mobility of users depending on two criterias: frendship/strangerhood and if they are in the same/different country. Compute the similarity as a function of the relationship between users (from friends to strangers, for 6 categories in total). Analyze how the similarity between two friends evolves in time. Analyze the similarity between non-friends users who visit certain places (for a total of 18 places).

3. Country and Mobility:
Analyze the most commonly visited places in 10 major countries (e.g. noodle places in Japan and bakeries in France). Analyze the difference in periodic behavoir in different countries by analyzing at what times of the day are users more suseptible to check-in in "Office" throughout the world. Analyze the seasonality of check-ins in 4 major countries by representing the evolution of common places (park, temple..) throughout almost two years.

<h2>Proposed timeline</h2>

**Week1**: Clean and Merge the data. Answer the research questions. Analyze whether the answer match / do not match what we expect.

**Week2**: Analyze the answers. Transform the answers into visualization. 

**Week3**: Prepare the datastory and short Video.

<h2>Organization within the team</h2>

**Yu-Ting Huang**:  Friendship and Mobility, research questions and their visualization. Website setup + datastory content.

**De-Ling Liu**: Country and Mobility, research questions and their visualization. Datastory content + overall structures. 

**Adel Qasem**: Broad introduction, research questions and their visualization. Datastory content + introduction.
