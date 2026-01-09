# 🎮 I Primi Programmi - Restaurati

Collezione di giochi vintage degli anni '90, originariamente scritti in DOS Batch e Turbo Pascal, ora completamente restaurati e convertiti in moderne applicazioni web HTML5/JavaScript.

## 🎯 Giochi Disponibili

### 1. 🎈 L'Avventura del Pallone Aerostatico
**File:** `adventure.html`

Un'emozionante avventura testuale interattiva in stile "Choose Your Own Adventure". Viaggia in Francia, affronta tempeste, esplora il deserto del Sahara e scopri misteri nascosti.

- **Tipo:** Avventura Testuale
- **Durata:** 15-30 minuti
- **Nodi narrativi:** 97 scene diverse
- **Finali multipli:** Sì
- **Originale:** DOS Batch (97+ file .bat)

### 2. ⭕ Tris (Tic-Tac-Toe)
**File:** `tris.html`

Il classico gioco del tris con grafica moderna e un'intelligenza artificiale sfidante.

- **Tipo:** Strategia
- **Durata:** 2-5 minuti per partita
- **Giocatori:** 1 vs Computer
- **Punteggio:** Tracciamento vittorie/pareggi
- **Originale:** Turbo Pascal (474 righe)

### 3. 😊 Smile Shooter
**File:** `smile.html`

Un frenetico gioco arcade di tiro al bersaglio con timer di 30 secondi.

- **Tipo:** Arcade
- **Durata:** 30 secondi per partita
- **Controlli:** Mouse
- **Punteggio:** 10 punti per smile
- **Salvataggio:** High score automatico
- **Originale:** Turbo Pascal (278 righe)

## 🚀 Come Giocare

### Metodo 1: Locale
1. Apri `index.html` in un browser moderno (Chrome, Firefox, Edge, Safari)
2. Clicca sul gioco che vuoi provare
3. Divertiti!

### Metodo 2: Ospitare Online
Puoi facilmente mettere questi giochi online:

**GitHub Pages:**
```bash
# Crea un repository GitHub
# Carica tutti i file HTML
# Vai su Settings > Pages > Enable Pages
# Il tuo sito sarà su: username.github.io/repo-name
```

**Netlify/Vercel:**
- Trascina la cartella sul sito
- Deploy automatico in pochi secondi

## 📁 Struttura File

```
primi programmi/
├── index.html          # Pagina principale
├── adventure.html      # Gioco avventura testuale
├── tris.html          # Gioco Tris
├── smile.html         # Gioco Smile Shooter
├── README.md          # Questo file
│
├── parse_adventure.py  # Script per estrarre dati dai .bat
├── embed_story.py     # Script per incorporare JSON in HTML
├── adventure_data.json # Dati dell'avventura (generato)
│
└── [97+ file .bat]    # File originali DOS
    [4 file .pas]      # File originali Turbo Pascal
```

## 🔧 Dettagli Tecnici

### Conversione Effettuata

**Da:**
- DOS Batch files (16-bit)
- Turbo Pascal 7.0
- BGI Graphics Library
- DOS Sound/Keyboard APIs
- Incompatibili con Windows 64-bit moderno

**A:**
- HTML5
- CSS3 con animazioni
- JavaScript ES6+
- Canvas API per grafica
- LocalStorage per salvataggio

### Tecnologie Usate
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla, no framework)
- **Grafica:** Canvas 2D API
- **Storage:** LocalStorage API
- **Responsive:** Media queries CSS
- **Encoding:** UTF-8

### Compatibilità Browser
- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Opera (v76+)
- ✅ Mobile browsers

## 🎨 Caratteristiche

- ✅ **100% Web-Based** - Nessuna installazione richiesta
- ✅ **Responsive Design** - Funziona su desktop, tablet e mobile
- ✅ **Offline Ready** - Funziona senza connessione internet
- ✅ **Salvataggio Automatico** - High scores e progressi salvati localmente
- ✅ **Grafica Moderna** - Animazioni CSS3 fluide
- ✅ **Cross-Platform** - Windows, Mac, Linux, Android, iOS

## 📖 Storia

Questi programmi rappresentano i primi passi nella programmazione di giovani appassionati negli anni '90. Originariamente creati con:

- **Turbo Pascal 7.0** - Per i giochi grafici (Tris, Smile, Fragga, Keysound)
- **DOS Batch** - Per l'avventura testuale interattiva
- **BGI (Borland Graphics Interface)** - Per la grafica DOS
- **PC Speaker** - Per gli effetti sonori

### Programmi Originali non Ancora Restaurati

La collezione originale includeva anche:

1. **Fragga** - Space shooter completo (~1000 righe Pascal)
2. **Keysound** - Applicazione musicale con tasti F1-F10

Questi potrebbero essere restaurati in futuro!

## 🛠️ Script di Utilità

### parse_adventure.py
Estrae la struttura narrativa da tutti i file .bat:
```bash
python parse_adventure.py
# Output: adventure_data.json con 97 nodi narrativi
```

### embed_story.py
Incorpora i dati JSON direttamente nell'HTML:
```bash
python embed_story.py
# Evita problemi CORS con file locali
```

## 💡 Note Tecniche

### Perché Incorporare il JSON?
I browser moderni bloccano il caricamento di file JSON locali per sicurezza (CORS policy). L'incorporamento diretto risolve questo problema senza bisogno di un server web.

### Encoding
I file originali usavano encoding Latin-1 (ISO-8859-1). Durante la conversione sono stati convertiti in UTF-8 per compatibilità web moderna.

### Caratteri Speciali
Alcuni caratteri italiani (è, à, ù, etc.) potrebbero essere visualizzati diversamente dall'originale DOS a causa delle differenze di encoding.

## 🎓 Valore Educativo

Questi giochi mostrano:
- Evoluzione della programmazione (1990s → 2020s)
- Conversione da linguaggi compilati a web
- Preservazione di software legacy
- Storia dell'informatica personale

## 📝 Licenza

Questi programmi sono restaurati a scopo educativo e di preservazione storica.

## 🙏 Credits

- **Programmazione Originale:** Eugenio Ghiglia e amici (anni '90)
- **Restauro e Conversione:** 2026
- **Tool:** VS Code, Python, HTML5, JavaScript

## 📧 Supporto

Per problemi o domande:
- Apri un issue su GitHub
- Controlla la compatibilità del browser
- Verifica che JavaScript sia abilitato

---

**Restaurato con ❤️ nel 2026 | Da DOS alla Web**
