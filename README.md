
<img width="969" height="823" alt="1" src="https://github.com/user-attachments/assets/ace8bd69-3865-468d-9ad1-e61c6224eca9" />

# 🐼 PandaQuiz Patente A/B 🇮🇹

Benvenuti su **PandaQuiz**, l'applicazione web open-source definitiva per esercitarsi sui quiz della patente di guida italiana (A/B). Creato da **zMykerd**, questo strumento combina un'interfaccia moderna ed elegante con funzionalità avanzate di tracciamento dei progressi per aiutarti a superare l'esame teorico con facilità.

---

## 🚀 Caratteristiche Principali

PandaQuiz non è un semplice simulatore di quiz, ma un ecosistema completo per lo studio:

### 1. Sistema di Quiz Dinamico
- **Database JSON:** Carica le domande direttamente da un file `quizbase.json`, rendendo il software facilmente aggiornabile.
- **Filtri Avanzati:** Scegli di esercitarti su una **categoria** specifica o scendi nel dettaglio con le **sottocategorie** per colmare le tue lacune.
- **Feedback Immediato:** Ricevi una risposta visiva istantanea (verde per corretto, rosso per errato) dopo ogni risposta.
- **Timer Integrato:** Tieni d'occhio il tempo per simulare la pressione dell'esame reale.

### 2. Gestione Dati e Statistiche
- **Statistiche Locali:** Il software tiene traccia dei quiz completati e della percentuale di esami superati, salvando tutto nel `localStorage` del tuo browser.
- **Cronologia Recente:** Visualizza gli ultimi risultati per monitorare il tuo miglioramento nel tempo.
- **Backup dei Dati:** Funzionalità di **Salva Dati** e **Importa Dati** tramite file JSON per non perdere mai i tuoi progressi, anche cambiando dispositivo.
- **Reset Totale:** Possibilità di cancellare tutte le statistiche per ricominciare da zero.

### 3. Interfaccia e Personalizzazione
- **Dual Theme (Light & Dark):** Supporta sia una modalità scura profonda che una modalità chiara elegante, adattandosi alle tue preferenze visive.
- **Design Responsive:** Ottimizzato per desktop, tablet e smartphone. Studia dove vuoi, quando vuoi.
- **Animazioni Moderne:** Footer dinamico con gradienti animati e icone SVG interattive per un'esperienza utente premium.

### 4. User Experience (UX) Ottimizzata
- **Scorciatoie da Tastiera:** Per una velocità massima, puoi rispondere senza usare il mouse:
  - `T` o `V`: Risposta **Vera**
  - `F`: Risposta **Falsa**
  - `Spazio`: Resetta/Ricomincia dopo il risultato finale
- **Accessibilità:** Utilizzo di ARIA roles e feedback live per garantire la massima fruibilità.

---

## 🛠️ Tecnologie Utilizzate

Il progetto è costruito interamente con tecnologie web moderne "vanilla", senza dipendenze pesanti:
- **HTML5:** Struttura semantica e interfacce pulite.
- **CSS3:** Variabili CSS (Custom Properties) per il supporto ai temi e Flexbox/Grid per il layout.
- **JavaScript (ES6+):** Logica asincrona per il caricamento dati (`fetch`), gestione file (`FileReader`) e persistenza dati.

---

## 📥 Installazione e Utilizzo

PandaQuiz è "portable" e non richiede installazione:
1. Scarica il file `panda_quizer.html` e il relativo `quizbase.json`.
2. Apri il file `.html` in qualsiasi browser moderno (Chrome, Firefox, Edge, Safari).
3. Seleziona la categoria e inizia a esercitarti!

---

## 📂 Struttura del Progetto

- `panda_quizer.html`: Il cuore dell'applicazione (struttura, stili e logica).
- `quizbase.json`: Il database contenente le domande (Vero/Falso), le immagini e le categorie.

---

## 🤝 Contribuire (Open Source)

Questo progetto è **Open Source**. Se desideri migliorarlo, aggiungere nuove funzionalità o correggere bug:
1. Fai un Fork del repository.
2. Crea un branch per la tua feature (`git checkout -b feature/NuovaCaratteristica`).
3. Fai il commit delle tue modifiche.
4. Apri una Pull Request.

---

## 👤 Autore

Creato con ❤️ da **zMykerd**.

---

## 📄 Licenza

Questo progetto è rilasciato sotto licenza Open Source. Sentiti libero di usarlo, modificarlo e distribuirlo.
