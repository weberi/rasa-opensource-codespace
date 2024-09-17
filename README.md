# rasa-opensource-codespace

* Port publizieren

Im Terminal

* NICHT: source .venv/bin/activate
* pip install rasa[spacy]    
* python -m spacy download en_core_web_md;
* cd weatherbotplus
* rasa run --port 5005 --enable-api --cors "*"
