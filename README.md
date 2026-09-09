# Code Guardian
Repository del gruppo SkyNet contenente tutti gli artefatti del progetto del corso di Ingegneria del software (SWE) a.a. 2025/2026

[![Website](https://skynetunigroup.github.io/Code_Guardian/Img/logo.jpg)](https://skynetunigroup.github.io/Code_Guardian/)

> Code Guardian è un progetto per la scansione e l'analisi della qualità del codice sorgente di repository GitHub. Il sistema permette l’esecuzione di analisi di sicurezza (OWASP), l’estrazione e il rendering di documentazioni interne (inline docs) e la generazione di changelog tecnici. L’applicazione è progettata seguendo il paradigma di agenti autonomi, integrati tramite un sistema centralizzato di orchestrazione.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [License](#license)

## Features
- Analisi di sicurezza OWASP per rilevare potenziali vulnerabilità
- Estrazione e rendering di documentazioni inline all’interno dei file del codice sorgente
- Generazione automatica di changelog tecnici
- Architettura modulare basata su agenti autonomi che interagiscono tramite orchestrazione
- Backend in Node.js con API REST e autenticazione JWT
- Frontend React per l’interfaccia utente
- Gestione dei task asincrona per migliorare scalabilità e performance
- Documentazione completa (Norme di Progetto, Analisi dei Requisiti, Piano di Progetto e Qualifica) scritta in LaTeX

## Project Structure
```text
Code Guardian/
├── .github/
│   └── workflows/ (contiene il flusso CI/CD)
├── Documentazione/ (contiene i documenti prodotti durante il ciclo di vita del progetto)
│   ├── Candidatura/ (lettere di presentazione, preventivo costi, valutazioni)
│   ├── LaTeX/ (modelli e sorgenti di documenti in LaTeX)
│   └── Verbali/ (verbali esterni e interni)
├── Src/ (codice sorgente del progetto)
│   ├── PoC/ (Proof of Concept e sperimentazione iniziale)
│   └── PoC nuovo/ (nuova architettura basata su agenti e orchestrazione)
│       ├── agents/ (modulo agenti autonomi)
│       ├── backend/ (API REST)
│       ├── frontend/ (interfaccia utente)
│       └── docker-compose.yml (composizione di servizi Docker)
├── Website/ (sito web del progetto)
├── LICENSE
└── README.md
```

## Available Scripts
- **PoC/PoC nuovo/**: Contiene diversi script e strumenti per testare, eseguire analisi, e gestire il codice:
  ```bash
  docker-compose up  # Avvia il sistema completo tramite Docker
  python scripts/measure_accuracy.py  # Esegue analisi di accuratezza sugli agenti
  ```

  Nota: Per ulteriori dettagli, consulta i file specifici all’interno di `Src/PoC/` e `Src/PoC nuovo/`.

## License
MIT License

[Link al sito web](https://skynetunigroup.github.io/Code_Guardian/)
