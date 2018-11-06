# Personalization Project

Phase 1: 
-> Preprocessing (Current)

comment 1: 
- I have made a tidy version of the data, just need to transform it into sparse. 
- The project actually doesn't need so many users and games, so we can limit the number of users and games before transforming into sparse. 

- Taking a random sample is giving a very empty matrix.  I think we need to filter for like top users and top games for hours played and then take a random sample.

Phase 2: 
Modeling
Evaluation

Phase 3: 
Write Up/Business Case
Clean up Github Repo.


# Personalization Project - Part 1 HW2
**Team:**  Muf Tayebaly (mt3195), James Xue (jx2181)  
**Data Set:**  Steam Video Game (Kaggle)

### Objective
The Steam gaming platform distributes games to its users and allows for multi-player management and a community for gaming.  Game sales is an important revenue stream and some gamers are known to play the same game for long periods of time instead of branching out.  With the increasing advertising platforms becoming available (Facebook, Instagram, Snapchat, etc..), costs of advertising can be pricey to gain new sales.  Studies have shown (e.g. Waggener Edstrom Worldwide) that word-of-mouth is the primary leader in new game sales. 

A recommender system can behave similarly to word-of-mouth where it can help identify new games for a user based on similar users or items.  This can lead to more game sales by making the users aware of games they might be interested in without having to pay for expensive advertisements.  If the recommendations prove to be successful with the user, it can even increase the validity for the users to continue to use the recommendations going forward to find new games.  New sales creates increased revenue and the potential to decrease advertisements costs (if recommendations prove to sell more than advertisements) and therefore increasing profits.  While advertisements are good to get the names known to larger audiences, especially those who are unfamiliar with the Steam platform, but for existing users, recommendation systems can be very useful and what we will test within this project.

Recommendation systems can even strengthen the gaming community by getting users who are interested in similar games actually playing more of those games together and creating stronger relationships between gamers that can ultimately retain users in the long run.

We will use existing user and game data to prove we can make accurate (to some significance) recommendations of games that we already know the user is interested in since we will hold out known data.
