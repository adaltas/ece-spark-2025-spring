# Final Project

## Scoring

The code must run and provide the correct answers . 1/2 points  
The remainder will come from notebook organization, ccode comments, etc .  
For the questions that have answers, please also provide those in markdown cells in the notebook, and/or part of a mardown file in the repo .  
The link to the notebook will be provided in a github repo in the same way that as the in class . Additionally, you will send an email to joe@adaltas.com when the project has been submitted . Please ensure that the names of all participants are included in the repo and in the submissioin email . 

1. load data
2. How many total people in data set
3. what is the earliest year of birth
4. how many years ago was this person born
5. using only the data in the data set is this date of birth correct . explain the answer
6. what is the latest data of birth  
7. how many people do not have a year of birth
8. what is the length of the longest short after  1900
9. what is the length of the shortest movie after 1900
10. provide a list of all of the genres represented
11. what is the higest rated comedy movie in the dataset . note, if there is a tie, the tie shall be broken by the movie with the most votes .
12. who was the director of the movie.
13. List, if any, the alternate titles for the movie .

## Degrees of seperation

A degree of separation is a way to measure how far apart two people (in this case, actors) are from each other in a network, based on their connections.

Here's a simple explanation:

1st Degree: Direct connection
- If Actor A and Actor B have worked together in a movie, they have 1 degree of separation
Example: Tom Hanks and Tim Allen worked together in "Toy Story", so they are 1 degree apart

2nd Degree: Connection through one intermediary
- If Actor A worked with Actor B, and Actor B worked with Actor C (but A never worked with C), then A and C have 2 degrees of separation
Example: If Tom Hanks worked with Julia Roberts, and Julia Roberts worked with George Clooney (but Tom Hanks never worked with Clooney), then Hanks and Clooney are 2 degrees apart

3rd Degree: Connection through two intermediaries
- Continues the chain with one more person in between
Example: Actor A → Actor B → Actor C → Actor D

Explore the degrees of seperation for nconst nm0000102 to the 6th Degree .
Please note, you may need to persist each degree of seperation to permanent storage as the community edition may not have the resources to do the calculations in one run .

14. Build the degrees of seperation . ( 2 points )
15. Which degree of seperation contains the most people .
16. Aside from Degree 0, which Degree containes the most people .
17. Which contains the least .
18. Is the person from question 3 within 6 Degrees of nm0000102, if so, how many ?
19. Is nm0000102 within 6 degrees of the movie from question 11, if so, how many ?
