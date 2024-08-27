# pythonflaskrestapi
Following auth0's tutorial on how to create a python/flask restapi

Motivations
Had a discussion this morning with a friend regarding best practices to creating a webapp. He had a quick look at my code and suggested that I look at decoupling my front/backend.

Initial Version: The initial version of the web app, which was in a private repository, was heavily based on a YouTube tutorial.

Challenges with Integration: The first implementation used Flask/Python, but the tight integration between the frontend and backend made it challenging to extend and maintain the code.

Decoupling Suggestion: Based on my friend's suggestion, I decided to decouple the frontend from the backend. This involves creating REST API endpoints on the backend that the frontend can interact with, allowing for greater flexibility and scalability.


Tutorial link: https://auth0.com/blog/developing-restful-apis-with-python-and-flask/
