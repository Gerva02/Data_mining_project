# Data_mining_project
**Utilizzare solo il markdown per evitare di copiatura lavoro dopo**.   
Utilizzeri questo read me come in generale una to do list, quindi in ordine :   

1) trovare Dataset   
    1.1) Deve avere NA   
    1.2) Sarebbe meglio senza qualitative   

3) Pre-processing (analisi esplorativa/outliers???)   
4) Analisi (io direi di non fare text mining)

To do list :
- [ ] andare a rivedere bene il dataset iniziale
    - [ ] E' giusto fare trasformazioni
    - [ ] box-cox
    - [ ] controllare se dopo trasformazioni almeno per alcune variabili abbiamo la normalità per classi (così applichiamo LDA e QDA)
- [x] settare seed ovunque c'è roba random
- [x] Scegliere data set
- [x] Fare grafici analisi esplorativa
- [x] Normalizzazione
    - [x] bisogna salvare min e max di ogni colonna (probabilmente)
    - [ ] rifare alcuni grafici (?)
    - [x] problema dei valori tutti uguali
- [x] Applicare KNN
    - [ ] trattare collinearità
        - [ ] distanza malanhobis (?) (a quel punto toccherà salvare correlazioni lineari) 
        - [ ] magari buttare via variaibli troppo correlate ( il prof ha detto di vedere quale ha più impatto su y) 
- [x] Modificare tavola P-value
- [x] Applicare alberi decisionali (Possiamo anche evitare di normalizzare questi dati)
        - [ ] aggiungere log loss (?)
- [ ] andare a vedere fonte vera se ha dati diversi e se dice di più del dataset ( https://archive.ics.uci.edu/ml/datasets/Glass+Identification) [non sembra dire granche]
- [ ] (?) regressione logistica multiclasse
   - [ ]  manca la parte di diagnostica
- [ ] aggiustare i grafici l'asse delle x è troppo piccolo per ogni grafico (i vilion plot)
- [x] alberi decisionali
      

