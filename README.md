# Mountain Car Problem: Tabular Q-Learning vs RBF Approximation

Questo repository contiene il progetto finale e il caso studio d'esame per il corso di *Learning-Based Control* presso l'**Università degli Studi di Trieste**, focalizzato sulla risoluzione del *Mountain Car Problem* tramite tecniche di Reinforcement Learning.

## Descrizione del Progetto
Il problema richiede che un'auto compia una salita ripida accumulando energia potenziale tramite oscillazioni. Il progetto mette a confronto due approcci fondamentali basati sui dati:
1. **Q-Learning Tabulare:** Risoluzione del problema in uno spazio degli stati discretizzato tramite politiche di esplorazione/sfruttamento.
2. **Q-Learning con Approssimazione Lineare RBF:** Implementazione di Funzioni a Base Radiale (Radial Basis Functions) per mappare e gestire in modo efficiente lo spazio degli stati continuo, garantendo una superficie di valori fluida.

## Contenuto della Repository
* **`Progetto_LBC_presentazione.pptx`**: Slide complete utilizzate per la discussione dell'esame.
* **`Progetto_LBC_presentazione.pdf`**: Slide complete utilizzate per la discussione dell'esame (in formato pdf).
* **`Progetto_LBC.mlx`**: MATLAB Live Script contenente l'algoritmo completo di addestramento dell'agente intelligente.
* **`animation_Mountain_Car_RBF.mp4`**: Animazione video che mostra le performance dell'agente addestrato con il Q-Learning RBF.
* **`animation_Mountain_Car.mp4`**: Animazione video che mostra le performance dell'agente addestrato con il Q-Learning Tabular.

---
*Studente: Alessandro Di Santo*  
*Professoressa: Erica Salvato*  
*Corso di Laurea Magistrale in Computer Engineering (Robotics & AI) — Università degli Studi di Trieste*
