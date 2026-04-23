# 🦔 Riccio Pazzo CTF
**Il software che ha un'opinione su di te (e non è positiva).**

Hai deciso di farti insultare da un software? Ottima scelta. **Riccio Pazzo** è un bot arrogante, saccente e custode di un segreto che non ti dirà mai — a meno che tu non sia meno stupido di quello che sembri.

---

## 🛠️ Setup dell'Ambiente (Per chi non sa da dove iniziare)

Visto che probabilmente faresti confusione installando librerie a caso nel sistema, ho previsto l'uso di un **ambiente virtuale (venv)**. Segui queste istruzioni alla lettera se vuoi evitare che il Riccio ti ridisegni il desktop.

### 1. Preparazione
Assicurati di aver clonato la repository e di trovarti nella cartella del progetto:
* `Riccio.py` (Il cuore del bot)
* `requirements.txt` (L'elenco di ciò che ti serve e che non sai di volere)

---

### 2. Creazione dell'ambiente virtuale
Apri il terminale e digita:

```bash
# Crea l'ambiente virtuale
python -m venv venv

# Attivalo (Windows)
.\venv\Scripts\activate

# Attivalo (macOS/Linux)
source venv/bin/activate

---

### 3. Installazione dipendenze
Ora che sei "protetto" dal venv, installa tutto il necessario in un colpo solo. 
Non provare a farlo a mano, sbaglieresti i nomi:


# Installa le dipendenze
pip install -r requirements.txt

---

### 4. Avvio della sfida
Una volta configurato tutto, puoi provare a sfidare l'intelletto superiore del Riccio. 
Se il terminale esplode, la colpa è tua.


# Avvio challenge
python Riccio.py
