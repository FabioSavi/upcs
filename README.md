# UPO Planner Calendar Sync 📅🤖

UPO Planner Calendar Sync è un bot Telegram sviluppato in Python che permette agli studenti di sincronizzare automaticamente l'orario delle lezioni universitarie direttamente sul proprio account Google Calendar.

🌐 **Sito web e documentazione:** [https://fabiosavi.github.io/upcs](https://fabiosavi.github.io/upcs/)

## 🚀 Come funziona
L'utente interagisce con il bot tramite Telegram per:
1. Selezionare il proprio corso di studi.
2. Effettuare il login in modo sicuro tramite Google OAuth 2.0.
3. Autorizzare il bot ad aggiungere e mantenere aggiornati gli eventi delle lezioni sul proprio calendario.

## 🔒 Sintesi della Privacy Policy
La tutela dei dati è una priorità. Il bot opera secondo il principio del privilegio minimo:
* **Dati raccolti:** Solo l'ID Telegram, le preferenze del corso e i token OAuth necessari per la comunicazione con Google.
* **Permessi limitati:** Il bot crea e aggiorna *esclusivamente* gli eventi relativi alle lezioni universitarie. **Non legge, non modifica e non elimina** eventi personali preesistenti sul calendario dell'utente.
* **Nessuna condivisione:** I dati non vengono mai venduti o condivisi con terze parti.
* **Conformità Google:** L'uso delle API di Google rispetta rigorosamente la *Google API Services User Data Policy* (Limited Use).
* **Revoca:** L'utente può disconnettersi in qualsiasi momento dal bot o dalle impostazioni del proprio account Google, comportando l'eliminazione dei token dal database.

👉 [Leggi l'Informativa sulla Privacy completa](privacy.html)

## ⚖️ Sintesi dei Termini di Servizio
* **Natura del progetto:** Questo è un progetto indipendente, gratuito e open-source. Non è affiliato, sponsorizzato o supportato dall'Università del Piemonte Orientale (UPO), da Google LLC o da Telegram.
* **Limitazione di responsabilità:** Il servizio è fornito "così com'è" (as is). Sebbene sia progettato per essere preciso, l'autore non è responsabile per eventuali inesattezze negli orari, lezioni mancate o temporanei malfunzionamenti derivanti da aggiornamenti delle API. Si consiglia sempre di verificare gli orari sui canali ufficiali.
* **Uso corretto:** Il bot è destinato al solo uso personale. Abusi o tentativi di manomissione comporteranno il blocco dal servizio.

👉 [Leggi i Termini di Servizio completi](terms.html)

## 🛠️ Stack Tecnologico
* Python
* Telegram Bot API
* Google Calendar API (OAuth 2.0)

---
*Per supporto o segnalazioni di bug, contattare: [fabio.savitteri06@gmail.com]*
