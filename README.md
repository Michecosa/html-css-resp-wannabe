# Responsive Layout – Boolean Academy

Questo esercizio non richiedeva lo sviluppo del sito da zero, ma l’aggiunta della **responsività** al layout già fornito, **senza modificare l’HTML o il CSS esistente**.  
Il lavoro si è concentrato esclusivamente sull’uso delle **media query**.

🌐 [Check it out!](https://michecosa.github.io/html-css-resp-wannabe/)

<br>

## Obiettivi raggiunti

- **Tablet (≤ 768px)**  
  - Le colonne (`.col`) diventano a larghezza piena.  
  - Le sezioni *Lessons* e *Steps* vengono mostrate una card per riga.  
  - Nella sezione *Why Us* immagine e testo si dispongono verticalmente (immagine sopra, testo sotto).  

- **Smartphone (≤ 480px)**  
  - Forzato layout a colonna con `flex-direction: column`.  
  - Ogni elemento va uno sotto l’altro.  
  - Ridimensionati titoli (`h1`, `h2`, `h3`) per una migliore leggibilità.  
  - Aggiunte spaziature extra tra gli elementi.  

- **Intervallo tra 769px e 1160px**  
  - Risolto il problema del layout troppo rigido.  
  - Eliminata la scrollbar orizzontale ridimensionando `.container` a `width: 100%` con padding laterale.  
