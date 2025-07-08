# Progetto - Tecnologie e Architetture per la Gestione dei Dati (TAGD)

Progetto universitario per il corso di Tecnologie e Architetture per la Gestione dei Dati (A.A. 2024/2025) presso l'Università degli Studi Roma Tre.

## Autori
- Alessandro Schmitt (577421)
- Michele Guida (576985)

## Descrizione

Il progetto analizza e modella le prestazioni di un DBMS basato su una traccia di workload (`transaction.csv`) osservata per un intervallo di 24 ore. Sono state utilizzate tecniche di:
- Analisi statistica del carico di lavoro (JWAT e Python)
- Clustering tramite K-Means
- Modellazione analitica con Java Modelling Tools (JMT)
- Studio di configurazioni RAID-0 e RAID-1

## Obiettivi

1. Calcolo del tempo medio di risposta e numero medio di job nel sistema.
2. Studio del massimo carico sostenibile per ogni classe di Workload mantenendo l'utilizzazione del collo di bottiglia ≤ 70%.
3. Verifica della sostenibilità del carico con configurazione RAID-1.

## Tool utilizzati
- [JMT (Java Modelling Tools)](http://jmt.sourceforge.net/)
- Python (per la visualizzazione dei dati)
- JWAT (per l'analisi statistica)

## File
- `Progetto3-TAGD-AS-MG.pdf`: Relazione completa
- `transaction.csv`: Traccia del workload 

## Licenza
Questo progetto è distribuito con licenza MIT.
