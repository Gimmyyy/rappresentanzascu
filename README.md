# 🇮🇹 Rappresentanza SCU – Regione Campania

> Sito istituzionale della Rappresentanza degli Operatori Volontari del Servizio Civile Universale in Regione Campania.

🌐 **[Visita il sito](https://gimmyyy.github.io/rappresentanzascu)**

---

## 📌 Descrizione

Spazio digitale dedicato agli operatori volontari del SCU in Campania: tavoli di lavoro tematici, composizione della rappresentanza, documenti istituzionali e canali di contatto con la delegazione regionale.

---

## 📄 Pagine

| Pagina | Descrizione |
|---|---|
| **Home** | Presentazione della rappresentanza e dei sei pilastri fondamentali |
| **Rappresentanza** | Delegati e rappresentanti regionali con selezione per anno |
| **Tavoli** | I 9 tavoli tematici attivi con descrizione delle attività |
| **Contatti** | Modulo di contatto, email, Instagram e canale WhatsApp |

---

## ⚙️ Tecnologie

- **HTML5** / **CSS3** / **JavaScript** vanilla — nessun framework esterno
- **Font:** [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- **Hosting:** GitHub Pages
- **Dati delegati:** file `delegati.json` aggiornabile ogni anno senza toccare l'HTML

---

## 🗂️ Struttura del progetto

```
├── index.html          # Unico file HTML (SPA multi-pagina via JS)
├── delegati.json       # Dati delegati per anno — aggiorna solo questo!
├── assets/
│   ├── logo.jpg        # Logo SCU Campania
│   └── favicon.ico     # Favicon
└── README.md
```

---

## 🔄 Aggiornamento Annuale

Per aggiornare i delegati ogni anno è sufficiente modificare **solo** il file `delegati.json`:

```json
{
  "2027": [
    {
      "nome": "Nome Cognome",
      "ruolo": "Delegato Regionale",
      "badge": "green",
      "email": null,
    }
  ]
}
```

I valori possibili per `badge` sono:
- `"blue"` → Rappresentanti nazionali/regionali
- `"green"` → Delegati regionali
- `"gray"` → Anni storici / non applicabile

---

## 🧭 Funzionalità principali

- ☀️ **Tema chiaro/scuro** con persistenza via `localStorage`
- 📱 **Responsive** — ottimizzato per mobile, tablet e desktop
- ♿ **Accessibile** — skip link, `aria-label`, `role` semantici, `:focus-visible`
- 🔗 **Open Graph** — anteprima ottimizzata per WhatsApp e social
- 📋 **Form Contatti** integrato
- ⏰ **Anno Footer** — aggiorna automaticamente l'anno corrente nel footer

---

## 🏛️ Riferimenti istituzionali

- [Servizio Civile – Regione Campania](https://www.regione.campania.it/regione/it/tematiche/servizio-civile)
- [Rappresentanza SCU – Dipartimento Politiche Giovanili](http://www.politichegiovanili.gov.it/servizio-civile/operatori-volontari/rappresentanza)
- [Linee guida Rappresentanza SCU (PDF)](https://www.politichegiovanili.gov.it/media/khqivwkp/allegato-b-linee-guida.pdf)

---

## 👤 Autore

Sviluppato con ❤️ da Gianmarco Luciano aka **laky**  
Delegato Regionale SCU – Campania 2026
