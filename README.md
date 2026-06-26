Trabajo Grupal universitario para la materia Deeplearnig

Descripción general:

Es un sistema de inteligencia artificial que lee documentos PDF, extrae su texto y lo clasifica automáticamente por tipo de contenido usando una red neuronal.


Lee PDFs con pdfplumber y extrae el texto
Limpia el texto con técnicas NLP: elimina stopwords, caracteres especiales y normaliza
Clasifica el documento en 4 categorías (Mundo, Deportes, Negocios, Ciencia/Tech) usando una red neuronal GRU entrenada con el dataset AG News
Reconoce entidades como personas, organizaciones y lugares (NER con NLTK)
Extrae datos estructurados como correos, teléfonos y fechas usando expresiones regulares

Tecnologías usadas:

Python, TensorFlow/Keras, NLTK, pdfplumber, scikit-learn, pandas
