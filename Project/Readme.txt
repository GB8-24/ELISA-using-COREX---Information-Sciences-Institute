ELISA - Using Anchored Corex / LDA with TF-IDF to find relevant articles for unknown/not translated languages with minimum domain knowledge such as Oromo.

Given a set of keywords such as :

Oromo:
earthquake: chocho'a lafa; socho'a lafaa ("chocho'a" = quake; "lafa" = earth; "socho'a lafaa" is spelling variation)
drought: hoongee; hongee (spelling variation)
flood: galaana (which also means "sea"); galoo
disaster: balaa

Tigrinya (script is left-to-right):
earthquake: ?????? ??? (Romanized: meneqeteqaate mareete)
drought: ??? (Romanized: naqhetsi)
flood: ????? (Romanized: eleqheleqhe)
disaster: ???; ????? (Romanized: maaate; maqhezafeti)

We need to scan every retrieved document, create topics models with anchored key words and then rank them based on the relevance/precision or existing labels.
This can be done using TF-IDF data on LDA, Corex, combination of the above or other relevant NLP methods that can be used for languages with minimum domain knowledge.