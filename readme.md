# Simulazione di un Processo Produttivo Multi-Prodotto

Questo progetto realizza un modello di simulazione per stimare i tempi di produzione in un sistema manifatturiero multi-prodotto, utilizzando il linguaggio Python.

Il programma permette di:
- Generare casualmente le quantità da produrre per ciascun prodotto.
- Definire i parametri produttivi (tempi unitari e capacità giornaliere).
- Simulare il processo produttivo e calcolare il tempo totale e i giorni necessari.
- Visualizzare un output esplicativo che mostra giorno per giorno l’avanzamento della produzione.

Per eseguire il programma assicurati di avere installato Python 3.10 o superiore, quindi digita i seguenti comandi e osserva l’output:

pip install -r requirements.txt
python main.py

--- SIMULAZIONE PRODUZIONE ---

Quantità da produrre:
  Prodotto_A: 120 unità
  Prodotto_B: 75 unità
  Prodotto_C: 100 unità

Parametri di produzione:
  Tempi unitari (ore): {'Prodotto_A': 1.4, 'Prodotto_B': 2.1, 'Prodotto_C': 1.6}
  Capacità giornaliere: {'Prodotto_A': 100, 'Prodotto_B': 90, 'Prodotto_C': 120}
  Capacità totale giornaliera: 300 unità

--- Giorno 1 ---
  Prodotto_A: 100 unità prodotte (140.00 ore)
  Prodotto_B: 75 unità prodotte (157.50 ore)
  Prodotto_C: 100 unità prodotte (160.00 ore)

--- RISULTATI ---
Giorni di produzione: 2
Tempo totale di produzione: 457.50 ore

Questo modello può essere impiegato per pianificare la produzione, valutare colli di bottiglia, analizzare scenari “what-if” e per scopi didattici nei corsi di economia e ingegneria gestionale.

Riferimenti principali:
- Chase, R. B., Jacobs, F. R., & Aquilano, N. J. (2006). Operations Management for Competitive Advantage. McGraw-Hill.
- Slack, N., Brandon-Jones, A., & Johnston, R. (2016). Operations Management. Pearson.
- Python Software Foundation (2024). Python 3.12 Documentation. https://docs.python.org/3/
