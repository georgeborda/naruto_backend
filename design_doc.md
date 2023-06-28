# Naruto Backend
---
## Overview: 
The company "RandomNarutoReviews" needs a system that allows anime professionals to upload character reviews for Naruto, so that anyone from anywhere in the world can search for the reviews and purchase NFTs through their portal.
The company has a team of front-end developers who will create a portal for editors to upload the reviews, and for users to view them. They have requested that you, as a back-end specialist, provide a system, including an API, that allows the following:
Uploading reviews of Naruto characters
Retrieving the content of the reviews to display them in web and mobile versions of the portal.
User management for editors (excluding visitors who read the reviews)
It is also known that the company "RandomNarutoReviews" plans to primarily distribute in South America, where their largest market is located. However, they also have sales in North America, Europe, and very few in Asia.

### Scope


#### Supported use-cases
* As an editor, I would like to be able to post a review about a Naruto's character
* As an editor, I would like to be able to post a review about a Naruto's fight
* As a registered user, I would like to be able to read reviews

#### Out of Scope
* As an unregistred user, I would like to be able to post a review about a Naruto's character
* As an unregistred user, I would like to be able to read reviews

---
## Architecture

### Diagrams

### Data models

---
## Limitations
* API call for posting a review should not exceed latency limits of 500ms.
* API calls for getting reviews for reading should have latency less than or equal to 100ms.
---
## Costs
