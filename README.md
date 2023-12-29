# Language detection app

A language detection application based on an ai model made using sklearn, a python library for machine learning.

## Demo

The model endpoint is deployed in heroku, to interact with and test make a post request to the following api:

https://languagedetectionapp-443b1bd9ab32.herokuapp.com/predict

following this format of body in JSON format:

    {
        "text" : "Example of phrase in english."
        }

If everything is okay, then you should get a response :

    {
        "language" : "english"
        }

Or you can simply make an api call following a template provided in :
https://languagedetectionapp-443b1bd9ab32.herokuapp.com/docs

## Lessons Learned

I learnd how to build this language detection model, also i learnd the steps of deploying an ml model, including :

- Exporting the model
- Interact with .pkl model via python
- Use FASTApi to create the backend
- Dockerizing the project
- Deploy the model in heroku plateforme

## Feedbacks

For any feedbacks or improvement never hesitate to get in touch with me via my discord soulayman31 or send me a message via the form provided in my portfolio.
