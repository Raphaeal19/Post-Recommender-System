# Post-Recommender-System
A Social Media Post recommender system

## Architecture:
* Uses KMeans unsupervised clustering to bring together similar posts.
* Uses both Collaborative and Content-based Filtering to cluster posts and users.
* Uses item-item collaborative. [Item-item collaborative filtering](https://en.wikipedia.org/wiki/Item-item_collaborative_filtering#:~:text=Item%2Ditem%20collaborative%20filtering%2C%20or,by%20Amazon.com%20in%201998.), or item-based, or item-to-item, is a form of collaborative filtering for recommender systems based on the similarity between items calculated using people's ratings of those items.
* Uses Tfidf for vectorization of documents for better weightage to important words.

## How to use:
* Clone repository
* Put CSVs into Data folder.
-- posts.csv: contains post id, post title, post type and post category
-- users.csv: contains user id, user name, user gender, user academic status
-- views.csv: contains user id, post ids which the user has seen, and timestamp of the viewing time
* run through the IPyNB till you can evaluate on the dataset

## Future works:
* Form a database of posts' contents to display the actual contents of the post.
* Form a webpage for better UX to showcase the similar posts
