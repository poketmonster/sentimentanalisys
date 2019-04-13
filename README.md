# NLP Sentiment Analysis

# Ejercicio 2.  

Sentiment Analysis Objetivo: Construir un sistema de SA para el español

Recursos: 
•Sklearnhttp://scikit-learn.org/stable/
•NLTKhttps://www.nltk.org/
•Etc.

# Tarea: T1: TASS2017 (Task 1: Sentiment Analysis at Tweet level) 
http://www.sepln.org/workshops/tass/2017/

Datos: disponibles en Poliformat

Tokenizer
TweetTokenizer
http://www.nltk.org/api/nltk.tokenize.html


Trabajo a realizar.

1.Preproceso de datos.
a.Train, Dev, Test en formato xml.
b.Hacer un parser (sugerencia utilizar minidom de Python): https://docs.python.org/2/library/xml.dom.minidom.html
c.Utilizar un tokenizador

2.Vectorizar los datos (train,dev,test)
a.Obtener una matriz de características (utilizando un vectorizer) a partir de los tweets (Hacer selección de características?)
b.Incluir recursos externos? Añadir a la matriz la información de los diccionarios de polaridad a la matriz de características (Python: scpy, numpy,...)

3.Elegir un clasificador, entrenar con el train y ajustar parámetros con el dev)

4.Una vez elegido el mejor clasificador con los mejores parámetros, recursos, y preproceso, aplicarlo al test.

5.La salida del test, la tenéis que enviar para que os la evalúe, en un fichero texto, el nombre del fichero que sea vuestro ‘nombre’seguido del ‘tipo de clasificador’(Ex. CarlosPerez_svm.txt)

6.Deberéis hacer una pequeña memoria que describa los clasificadores utilizados y el proceso de ajuste realizado sobre el conjunto ‘dev’ incluyendo las tablas de los resultados en términos de P, R,F1 (clase), Accuracy y macroF1(global). La medida para ordenar los sistemas será macroF1. 

7.Todo esto se entregará como una tarea de Poliformat.
