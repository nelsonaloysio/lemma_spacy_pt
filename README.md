# lemma_spacy_pt_3
Set of rules designed to improve the lemmatization process in Spacy for portuguese (Aug, 2021: updated to spacy 3.0)

pt-br

O programa toma como base a lematização feita pelo Spacy (versão 2.3.2 e usando o modelo 'pt_core_news_lg') e aplica uma série de regras para gerar uma lematização mais próxima do padrão.
Como exemplo, a frase:

"Uma empresa não é como uma família."

"Uma* empresar* não ser comer* umar* família" (lematização do Spacy)

"um empresa não ser como um família" (lematização após as regras)

Obs.: * O artigo "Uma" não foi transformado; o substantivo "empresa" se tornou o verbo inexistente "empresar"; a preposição "como" se tornou o verbo "comer"; e o artigo "uma" se transformou no verbo inexistente "umar"

Em um corpus de 861 lemas, a acurácia subiu de 80,5% para 97,3% 


en

Taking as starting point,the output of lemmatization provided by Spacy (version 2.3.2 and using the model 'pt_core_news_lg'), a set of rules was built to generate lemmas that are closer to the standard.
As an example, take the sentence below:

"Uma empresa não é como uma família."

"Uma empresar não ser comer umar família" (lematização do Spacy)

"um empresa não ser como um família" (lematização após as regras)

In a corpus of 861 lemmas, accuracy raised from 80,5% to 97,3% 

Obs.: * The determiner "Uma" did not receive a lemma; the lemma for the noun "empresa" became the non-existent verb "empresar"; the one for the preposition "como" became the verb "comer"; and for the determiner "uma", the lemma generated was the non-existent verb "umar"
