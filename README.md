# "The Annotated Transformer" en Español

Traducción al español del notebook
["The Annotated Transformer" de Harvard NLP](https://nlp.seas.harvard.edu/2018/04/03/attention.html),
donde se explica e implementa el paper ["Attention Is All You Need"](https://export.arxiv.org/abs/1706.03762).

<img src="https://nlp.seas.harvard.edu/images/the-annotated-transformer_0_0.png" alt="logo" width="400"/>

## Objetivo
En primer lugar, nuestro objetivo es entender todas las piezas que componen la arquitectura Transformer. 
Para ello, vamos a explicar e implementar cada una de ellas:

- [ ] Positional Encoding
- [ ] Multi-Head Attention
- [ ] Masked Multi-Head Attention
- [ ] Feed Forward
- [ ] Add & Norm
- [ ] Linear
- [ ] Softmax

La implementación de estas piezas debe ser auto-contenida. Se pueden utilizar, por ejemplo, una entrada y una salida ficticias. 

Una vez comprendida la arquitectura Transformer, nuestra intención es replicar el tutorial original en español a diferentes niveles de abstracción:
- El nivel más bajo sería utilizando solo `numpy`
- El nivel intermedio sería utilizando frameworks como `pytorch` y `tensorflow`
- El nivel más alto sería utilizando la librería `transformers` de Hugging Face

## Cómo contribuir
Para facilitar la organización de las tareas y poder visualizar el avance del proyecto, este repositorio estará asociado a un
tablero.

Para contribuir al repositorio, primero clónalo y después crea una rama donde añadir tu aportación.

Para contribuir a la explicación de la arquitectura Transformer:
1. Elige una de las piezas de la arquitectura
2. Crea una rama llamada `pieza/<pieza>`
(e.g. `pieza/positional_encoding`)
3. Añade tu implementación de la pieza correspondiente al notebook `arquitectura_transformer.ipynb`
4. Abre una Pull Request cuando hayas terminado y menciona el Issue correspondiente para que otro contribuyente pueda revisar tu aportación

Para contribuir a la traducción del tutorial:
1. Elige una de las secciones del notebook original y la librería con la que quieres trabajar
2. Crea una rama llamada `tutorial/<libreria_utilizada>/<seccion>`
(e.g. `tutorial/pytorch/model_architecture`)
3. Añade tu sección al notebook correspondiente (`the_annotated_transformer_<libreria>.ipynb`)
4. Abre una Pull Request cuando hayas terminado para que otro contribuyente pueda revisar la nueva sección
