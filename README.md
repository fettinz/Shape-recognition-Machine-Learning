# Progetto Data Mining con PCA Manuale

Questo repository contiene il notebook **`Progetto.ipynb`**, in cui viene implementata passo-passo una pipeline di data mining con l’applicazione manuale della Principal Component Analysis (PCA) su un dataset di forme geometriche generate artificialmente.

---

## Contenuto

- **`Progetto.ipynb`**: notebook principale con:
  - Generazione di dataset di forme (cerchi, triangoli, segmenti, croci)
  - Appiattimento delle forme in vettori numerici
  - Suddivisione in training set e test set
  - Standardizzazione delle feature con `StandardScaler`
  - Implementazione manuale della PCA (eigendecomposition con NumPy)
  - Applicazione della PCA su train e trasformazione del test
  - Analisi della varianza spiegata e selezione delle componenti
  - Visualizzazione della ricostruzione di un campione
  - Esportazione dei dataset (standardizzato e PCA-ridotto) in CSV

- **`Notebook Annotato`**: traccia del file con celle Markdown dettagliate che spiegano ogni passaggio (senza modificare il codice originale).

---

## Prerequisiti

Assicurati di avere installato:

- Python 3.8+
- NumPy
- pandas
- matplotlib
- scikit-learn

Puoi installare le dipendenze con:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## Utilizzo

1. **Apri** il notebook `Progetto.ipynb` in Jupyter o JupyterLab.
2. **Esegui** tutte le celle in ordine:
   - Si creerà il dataset di forme, si appiattirà in vettori e si dividerà in training e test.
   - Verranno calcolate manualmente le componenti principali.
   - Potrai vedere le stampe della varianza spiegata e i grafici di confronto tra forma originale e ricostruita.
   - Al termine, i file CSV con i dati standardizzati e PCA-ridotti saranno esportati.

---

## Struttura del repository

```text
├── Progetto.ipynb             # Notebook con il flusso completo di Data Mining + PCA
├── Progetto_annotato.ipynb    # Versione annotata con spiegazioni Markdown
├── train_standardizzato.csv   # Output: train set standardizzato
├── test_standardizzato.csv    # Output: test set standardizzato
├── train_pca4.csv             # Output: train set ridotto a 4 PC
└── test_pca4.csv              # Output: test set ridotto a 4 PC
```

---

