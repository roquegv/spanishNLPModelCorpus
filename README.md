# Corpus y modelos entrenados para NLP en Español

Se han creado clasificadores para las siguientes tareas NLP:
* Segmentador de Oraciones (Sentence Splitting)
* Tokenización
* POS Tagging
* Named Entity Recognition (NER)

Para obtener estos modelos se han utilizado y modificado los siguientes corpus:
* [AnCora](clic.ub.edu/corpus/es/ancora)
* [CoNLL-2002](http://www.cnts.ua.ac.be/conll2002/ner/)
* [WikiNER](schwa.org/projects/resources/wiki/Wikiner) 

## Evaluaciones
Segmentación de Oraciones:
|      | CoNLL-A    | CoNLL-B |
| --------|---------|-------|
| Precision  | 0.9762   | 0.9865    |
| Recall | 0.9541 | 0.9763    |
| **F-Measure** | **0.9650** | **0.9814**    |

Tokenización:
|      | CoNLL-A    | CoNLL-B |
| --------|---------|-------|
| Precision  | 0.9953   | 0.9945    |
| Recall | 0.9977 | 0.9973    |
| **F-Measure** | **0.9965** | **0.9959**    |

POS Tagging:
| Cantidad Oraciones           | 4060   |
|------------------------------|--------|
| Tamaño mínimo de oraciones   | 2      |
| Tamaño máximo de oraciones   | 105    |
| Tamaño promedio de oraciones | 26,81  |
| Cantidad de etiquetas        | 320    |
| **Exactitud**                    | **95,09%** |

Named Entity Recognition
| Corpus de Evaluación | F-Measure |
|----------------------|-----------|
| AnCora               | 0.9731    |
| WikiNER              | 0.8408    |
| CoNLL-A              | 0.7672    |
| CoNLL-B              | 0.7998    |

