# AMLbasic
❐ APPLIED MACHINE LEARNING BASIC PROJECT
this is a project for AML basic course at university of Bologna, Bioinformatics master's degree - Beatrice Pastorino
# ➽ Aim of this Project
I created a decision tree and a random forest machine learning model for the prediction of the best city to pass by during a road trip based on Weather conditions. this project is called "vAI" and it's made to appreciate the weather during a long road trip or to drive to a safe stop in case of weather emergencies.
# ➽ How does it work?
Let's imagine some trips from a starting city to a destination, I want to predict the best city as a step of my road trip based on weather conditions. So I gather cities in the vicinity of the start city moving towards the destination. Using a Weather website API, I retrieve weather data for these cities. Subsequently, I calculate a weather score for each city based on this data. In each trip, the city with the highest weather score is identified as the optimal city to pass through, labeled as '1', while all other potential cities are labeled '0'. Following data splitting into train and test sets, I train a random forest and decision tree model and make predictions
