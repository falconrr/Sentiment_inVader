### Instrucciones
vaderSentiment analyzer modificado para ejecutar reseñas en inglés y español.

##Uso
$ python3 vaderSentiment_Eng.py data/reviewEng.txt
$ python3 vaderSentiment_Span.py data/reviewESP2.txt
$ python3 vaderSentiment_SpanList.py < data/adjetivos3.txt

Ojo: el analyzer para español utiliza un restful API de http://mymemory.translated.net. El traductor está limitado a 1000 palabras por día. Después de esto, el programa dejará de funcionar apropiadamente. Se podría utilizar el API de Google pero tiene precio después del tiempo de prueba.

#Licencia
- Este programa es una versión adaptada de:
Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for
Sentiment Analysis of Social Media Text. Eighth International Conference on
Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014.

- The MIT License (MIT)
Copyright (c) 2016 C.J. Hutto (Ver LICENSE.txt)
