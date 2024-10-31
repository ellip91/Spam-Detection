**Software Anti-Spam per un'Università**

Questo progetto si basa sulla creazione di un modello di classificazione in grado di distinguere tra email SPAM e HAM. 
Il dataset è in formato csv. 
Dopo aver effettuato un'analisi esplorativa del dataset, si è proceduto con il preprocessing che include pulizia del dataset 
(rimozione punteggiature,lemming, stemming, lemmatization e rimozione stopwords e numeri) e la vettorizzazione tramite la funzione bow_tfidf().
Si addestra il modello di classificazione, partendo da un modello semplice come la logistic regression.  
Infine,come richiesto, vengono affrontati i seguenti punti:  
- Individuare i Topic principali tra le email SPAM presenti nel dataset  
- Calcolare la distanza semantica tra i topics ottenuti, per dedurne l'eterogeneità, tramite cosine similarity
- Estrarre dalle mail NON SPAM le Organizzazioni presenti.  
