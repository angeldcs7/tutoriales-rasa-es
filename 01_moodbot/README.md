# moodbot-es

Este repositorio es utilizado como referencia en el tutorial [Construyendo un Chatbot en español usando RASA — Moodbot](https://medium.com/@jaimetenorio/construyendo-un-chatbot-en-espa%C3%B1ol-usando-rasa-moodbot-b69946235bb).

Para ejecutar el bot localmente es requisito tener un entrono con Python 3.6 o superior pero inferior al 3.9, además del framekork rasa y la librería spaCy. Para ello se recomienda que una vez creado un entorno virtual, en la carpeta del proyecto se ejecuten los siguientes comandos en orden:
* pip install rasa==1.10.11
* pip install spacy==2.3.0
* python -m spacy download es_core_news_md
* python -m spacy link es_core_news_md es.