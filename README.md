# Monika Datasets

This repository is to easily manipulate the datasets used to train Monika. They are sorted as follows:

- Intents - User actions
    - general - General actions
        - goodbye.yml
        - greet.yml
    - mnk - Actions that are related to Monika herself
        - birthday.yml
        - creators.yml
        - identity.yml
    - moods - Moods expressed by the user Monika is interacting with
        - mood_confused.yml

- Responses - Monika's responses
    - general - General responses
        - utter_greet.yml
    - mnk - Responses about herself
        - utter_identity.yml

The datasets can be fed with data and then the domain.yml and the nlu.yml files can be generated using the script 'rasa_format.py'
