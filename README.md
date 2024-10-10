## To run the chatbot

* Start the Codeplace
* Publish the port (set it from Private to Public)

### When the code space is started
Check if spacy is installed
* Do not: ```source .venv/bin/activate```
* Do: ```spacy validate```

In case it is not properly installed 
* ```pip install rasa[spacy] ```   
* ```python -m spacy download en_core_web_md```

Fire up the chatbot
* switch to the directory of the bot you want to run, e.g. ```cd weatherbotplus ``` 
* ```rasa run --port 5005 --enable-api --cors "*"```
