Idee generala a solutiei:
- tokenizare input cu max_length 128 si padding
- inlocurie caractere speciale(de exemplu '\n' cu caractere randabile)
- implementare dataset si dataloader
- incarcare model preantrenat AutoModelForTokenClassification(bert-base-romanian-cased-v1)
- inghetarea anumire layere(numar si layere diferite pt fiecare submisie)
- contracarare bias de unbalanced dataset cu weights
- reducere LR pe platou
- antrenare per epoca cu batch=16
- incarcare test set si predictie