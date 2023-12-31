# Swasthya_Mental_Health_Support_WebPage

 Swasthya is a web platform dedicated to providing comprehensive Mental Health Support. The primary focus is to offer valuable information on identifying signs of mental health issues, understanding symptoms, and outlining essential measures for assistance. The platform emphasizes the importance of collective efforts in supporting individuals facing mental health challenges.

The core features of Swasthya include an interactive Chatbot named AI Swasthya. This AI-powered companion serves as a friendly and approachable virtual assistant, allowing users and patients to engage in conversations about mental health. Users can seek information, ask questions, and share their thoughts and feelings with AI Swasthya in a secure and non-judgmental environment.

The project is developed using Python and incorporates advanced technologies such as deep learning and Flask. A key element of the system is the integration of an Artificial Neural Network (ANN) designed to classify user messages into relevant categories. The technology stack includes Flask, NLTK (Natural Language Toolkit), Keras, Python, HTML, CSS, and Javascript, ensuring a seamless and responsive user experience.

Swasthya aims to bridge the gap in mental health awareness and support by leveraging technology to provide accessible, empathetic, and informative assistance. Through the utilization of cutting-edge technologies and a user-friendly interface, Swasthya strives to contribute positively to the mental well-being of individuals in need.

 ---

 # How to run it?
```pip install tensorflow 
pip install keras 
pip install pickle
pip install nltk
pip install flask
```

- **data.json**  – The data file which has predefined patterns and responses.
- **trainning.py** – In this Python file, we wrote a script to build the model and train our chatbot.
- **Texts.pkl** – This is a pickle file in which we store the words Python object using Nltk that contains a list of our vocabulary.
- **Labels.pkl** – The classes pickle file contains the Labels.
- **model.h5** – This is the trained model that contains information about the model and has weights of the neurons.
- **app.py** – This is the flask Python script in which we implemented web-based GUI for our chatbot. Users can easily interact with the bot.

## Steps need to follow:
1. Import and load the data file
1. Preprocess data
1. split the data into training and test
1. Build the ANN model using keras
1. Predict the outcomes
1. Deploy the model in the Flask app

> [!NOTE]
> For making flask app we need to make to folders name as static and templates and app.py files.

- static folder contains a subfolder with name styles. The styles folder contain  all the css files.
- Twmplates folder contains all the html files.
- app.py file for run the flask app using IDE.
  
---
# Overview
- Mental Health Support Webpage named Swasthya. At the `top` of the web page shows the name of the webpage.
- `Top left corner` Logo of the webpage we can see.
- `Top right corner` `Don't Stay Simple, help others` named link redirect to a page which gives the information about how we can help others who have suffering from mental health problem.
- One more speciality of this page is chatbot. You can see `bottom right corner` a chatbot icon.
- This will redirect to a new page which contains `Swasthya AI Chatbot`.
---
# Languages
  [![My Skills](https://skills.thijs.gg/icons?i=js,html,css,python,flask,nlp&theme=light)](https://skills.thijs.gg)
