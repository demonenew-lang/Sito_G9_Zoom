# Istruzioni di Sviluppo e Storico Progetto - Sito G9 Zoom Studio Hub

> [!IMPORTANT]
> **DIRETTIVA CRITICA PER ANTIGRAVITY / AGENTI AI:**
> All'avvio di ogni sessione di lavoro o accesso a questa cartella, l'agente Antigravity **DEVE leggere questo file** per comprendere lo stato del progetto `Sito_G9_Zoom`, la sua architettura e le regole di documentazione obbligatorie.

---

## 1. Regole di Condotta per gli Agenti AI (Antigravity)

Ogni volta che Antigravity accede a questa cartella e apporta delle modifiche, deve attenersi alle seguenti regole:
1. **Aggiornamento del Registro Modifiche**: Ogni modifica apportata al codice, allo stile, ai manuali o alla struttura deve essere registrata e documentata in fondo a questo file nella sezione **"Registro delle Modifiche ed Evoluzione"**.
2. **Integrità della Struttura**: Tutti i file di questo progetto devono risiedere esclusivamente all'interno della cartella `Sito_G9_Zoom`. La radice del workspace principale non deve essere inquinata da file sparsi.
3. **Mantenimento dello Stile**: Lo stile scuro personalizzato ("G9 & Zoom H5 Studio Hub") basato su font `Bebas Neue` e `Inter` deve essere preservato in caso di modifiche al design.

---

## 2. Storico del Progetto e Passaggi Effettuati

Questo sotto-sito è stato strutturato come un portale hub offline ("Studio Hub") per consultare rapidamente la documentazione e i manuali ufficiali dei dispositivi hardware principali di registrazione audio e video di Salvatore Costanzo: la fotocamera **Panasonic Lumix G9** e il registratore **Zoom H5**.

### Passaggi Eseguiti per la Creazione:
1. **Creazione della Struttura Hub**: 
   * Impostazione di un indice centrale responsive `index.html` con un layout a griglia scura diviso in due sezioni principali (giallo/arancione per Lumix G9 e azzurro per Zoom H5).
2. **Integrazione della Sezione G9**:
   * Creazione della sotto-cartella `g9`.
   * Posizionamento del manuale d'uso completo in lingua italiana in formato PDF: `DC-G9_DVQP1409ZE_full_ita.pdf`.
   * Creazione del file `g9/index.html` dedicato per la navigazione specifica delle funzionalità Lumix.
3. **Integrazione della Sezione Zoom H5**:
   * Creazione della sotto-cartella `zoom`.
   * Posizionamento del manuale ufficiale Zoom H5: `Manuale_Ufficiale_Zoom_H5.pdf`.
   * Posizionamento della guida rapida: `I_H5studio_QuickTour.pdf`.
   * Creazione del file `zoom/index.html` per l'interfaccia di consultazione rapida del registratore audio.

---

## 3. Struttura dei File del Progetto

* [index.html](file:///c:/I_Miei_ProgettiAntigravity/Sito_G9_Zoom/index.html) - Hub principale di navigazione.
* `g9/` - Risorse Panasonic Lumix G9.
  * [g9/index.html](file:///c:/I_Miei_ProgettiAntigravity/Sito_G9_Zoom/g9/index.html) - Pagina secondaria della fotocamera.
  * [g9/DC-G9_DVQP1409ZE_full_ita.pdf](file:///c:/I_Miei_ProgettiAntigravity/Sito_G9_Zoom/g9/DC-G9_DVQP1409ZE_full_ita.pdf) - Manuale PDF ufficiale.
* `zoom/` - Risorse Zoom H5.
  * [zoom/index.html](file:///c:/I_Miei_ProgettiAntigravity/Sito_G9_Zoom/zoom/index.html) - Pagina secondaria del registratore audio.
  * [zoom/Manuale_Ufficiale_Zoom_H5.pdf](file:///c:/I_Miei_ProgettiAntigravity/Sito_G9_Zoom/zoom/Manuale_Ufficiale_Zoom_H5.pdf) - Manuale PDF ufficiale Zoom.
  * [zoom/I_H5studio_QuickTour.pdf](file:///c:/I_Miei_ProgettiAntigravity/Sito_G9_Zoom/zoom/I_H5studio_QuickTour.pdf) - Guida rapida in PDF.

---

## 4. Registro delle Modifiche ed Evoluzione

*Qualsiasi agente AI che effettua modifiche in futuro deve aggiungere una riga a questa lista seguendo il formato: Data, Autore, Descrizione Modifica.*

* **13 Giugno 2026** - *Antigravity 2.0* - Creazione del file README e configurazione iniziale delle direttive per la conservazione e tracciamento delle modifiche del portale hardware.
* **17 Giugno 2026** - *Antigravity* - Pulizia della struttura tramite rimozione dei file PDF duplicati scaricati per errore e verifica dell'integrità dei link interni.
* **22 Giugno 2026** - *Antigravity* - Deploy del sito sul Server VPS Hetzner all'indirizzo https://49.12.190.86.nip.io/g9_zoom/ configurato tramite Nginx.

