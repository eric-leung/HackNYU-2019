# HackNYU-2019
Find relevant clubs based on the courses you are taking! (Still a work in progress)

## Inspiration
NYU has so many clubs it can be daunting, especially for new freshmen, to pick one that is interesting to them. Good thing there's always a source for new interests at college. Really like the courses you are taking? Put them into this program and get suggestions of personalized clubs that you would fit right in! 

## What it does
The user inputs a course name they are taking and the program, using NYU's Course Catalog and Engage API, suggests related clubs.
The program first uses NLP methods to extract keywords from a list of all the clubs at NYU and uses TF-IDF to weigh the terms. A similar process is done to the user-entered course and its description. Using both of these vectors, cosine similarity is used to calculate the most related club for all of that course's topics!
