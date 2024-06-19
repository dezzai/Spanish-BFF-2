[![License: GPL v3](https://img.shields.io/badge/License-GNU-blue)](https://github.com/dezzai/Spanish-BFF/blob/main/LICENSE)
# Spanish-BFF-2

Avaliable in Hugging Face https://huggingface.co/datasets/MMG/SpanishBFF2

## Dataset Description

Spanish-BFF is the first Spanish AI-generated dictionary using GPT3.

- **Paper:** [Building another Spanish dictionary, this time with GPT-4](https://arxiv.org/abs/2406.11218)
- **Point of Contact:** oscar.garcia@dezzai.com , alfonso.ardoiz@dezzai.com


### Dataset Summary

Spanish-BFF contains a total of 76,963 lemmas with its definitions.

These lemmas correspond to nominal, adjetival, verbal and adverbial classes.


### Languages

- Spanish (es)


## Dataset Structure

### Data Instances

<pre>
"retransmisión= [{"pos_tag": "Nombre femenino",
            "definition": "Acción y efecto de retransmitir un evento, generalmente por televisión o radio.",
            "example": "La retransmisión del partido de fútbol fue vista por millones de personas."}]

</pre>

### Data Fields

<pre>
{
  pos_tag: str
  definition: str
  example: str
}

</pre>

### Data Splits

| Split | Size |
| ------------- | ------------- |
| `train` | 76,963|



## Considerations for Using the Data

### Social Impact of Dataset

This corpus is the second open-source complete dictionary produced by LLMs. We intend to contribute to a better understanding and development of NLP and promote responsible use. 

### Biases and Hallucinations

This version has not been postprocessed to mitigate potential errors, biases or hallucinations the AI model could have generated.


## Citation 

```
@misc{ortegamartín2024building,
      title={Building another Spanish dictionary, this time with GPT-4}, 
      author={Miguel Ortega-Martín and Óscar García-Sierra and Alfonso Ardoiz and Juan Carlos Armenteros and Ignacio Garrido and Jorge Álvarez and Camilo Torrón and Iñigo Galdeano and Ignacio Arranz and Oleg Vorontsov and Adrián Alonso},
      year={2024},
      eprint={2406.11218},
      archivePrefix={arXiv},
      primaryClass={id='cs.CL' full_name='Computation and Language' is_active=True alt_name='cmp-lg' in_archive='cs' is_general=False description='Covers natural language processing. Roughly includes material in ACM Subject Class I.2.7. Note that work on artificial languages (programming languages, logics, formal systems) that does not explicitly address natural-language issues broadly construed (natural-language processing, computational linguistics, speech, text retrieval, etc.) is not appropriate for this area.'}
}

```
