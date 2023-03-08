# Galician _Spacy_ model 
Galician _Spacy_ model (non-official) trained for POS and lemma prediction with the annotated corpus [wikiCTG](). 
You can see how this model performs in this [ _Streamlit_ app](https://llorenzo62-spacy-wrapper-spacy-annotated-lzqlih.streamlit.app/)

In the [_Models_]() directory you'll find trained models for _Spacy_ 3.4 and 3.5. Download and load in your python script with `nlp=spacy.load("path-to-model")`.  
This directory also contains the _floret_ word-vectors used for train the models. These _floret_ word-vectors was trained on the union of two unannotated corpus: 
[Galipedia20221201]() and [SLI_GalWwb.1.0](https://github.com/xavier-gz/SLI_Galician_Corpora/tree/main/SLI_GalWeb.1.0), totaling 241 M words (over 600000 unique words).

Why this is a _non-official_ model? Simply because there is no proper _Spacy_ definition of Galician language. The models were trained as variants of Spanish and Portugese. 
The best models (presented here) happen to be a variant of Spanish.