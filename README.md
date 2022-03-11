# Bot Accidentes Aviacion

* Link al detalle: https://github.com/bernaberb/Bot-Accidentes-Aviacion/blob/main/Aviation_Accidents_Bot.ipynb

* Link al Google Colab con pasos detallados: https://colab.research.google.com/drive/1SjquMOrk2QM37N9NNQyqqyoXEGyo0LSM#scrollTo=VN8r3NeaGWFf

* Link al bot: https://twitter.com/AirAccidentsBot


Este es un bot para Twitter hecho con Python, en Google Colab, que usa información de accidentes aereos ocurridos entre 1908 y 2009 obtenidos de un dataset de Kaggle.

Filtré los datos según mis intereses y de esa manera quedarme con las entradas ocurridas entre 1950 y 2009 con más de 30 fallecidos.

Con el dato de la aerolínea y el número de vuelo usé la API de Wikipedia para obtener el link al artículo.

Generamos un texto con información del dataset y el link de wikipedia y el bot twittea usando la API de Twitter y Tweepy.
