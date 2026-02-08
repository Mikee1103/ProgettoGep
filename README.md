# ProgettoGep

# TITOLO
    Subly


# DESCRIZIONE
  "Applicazione che ti permette di inserire tutti i tuoi abbonamenti attivi e controllare per ognuno tutti i dati
  ( costi, costi dall'attivazione, scadenza etc ).
  Da essa puoi direttamente accedere ai siti degli abbonamenti per rinnovarli o disdirli."


# PROBLEMA
  "Risolve il problema di abbonamenti 
  dimenticati e della gestione dei soldi, 
  problemi abbatstanza comuni tra le persone"



# TARGET
  "Individui che fanno grande
   uso di abbonamenti"



# COMPETITORS
  Rocket Money
  TrackMySubs
  Dyme



# TAGLINE
  "Basta abbonamenti 
  dimenticati, gestiscili tutti 
  da una singola interfaccia"
  
  


# TIMESTAMP JWT
  1758872755



# UML USE CASE
<img width="1096" height="649" alt="image" src="https://github.com/user-attachments/assets/2572b666-921b-444f-b695-6156142677ff" />




# SITO LOVABLE

https://id-preview--08ce3a4d-8e12-454f-9c39-525dedd9f096.lovable.app/?__lovable_token=eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoiaGMzTzNGR0dtMlA5SExHYXlBZ2JjbE1pVjcxMyIsInByb2plY3RfaWQiOiIwOGNlM2E0ZC04ZTEyLTQ1NGYtOWMzOS01MjVkZWRkOWYwOTYiLCJhY2Nlc3NfdHlwZSI6InByb2plY3QiLCJpc3MiOiJsb3ZhYmxlLWFwaSIsInN1YiI6IjA4Y2UzYTRkLThlMTItNDU0Zi05YzM5LTUyNWRlZGQ5ZjA5NiIsImF1ZCI6WyJsb3ZhYmxlLWFwcCJdLCJleHAiOjE3NzExODQ4NDQsIm5iZiI6MTc3MDU4MDA0NCwiaWF0IjoxNzcwNTgwMDQ0fQ.RSj3RhHiGUGy9LDWou1jDTUBlKtOwLLE_Ie4y45R4GiCInlBrRS7TdHa4Ki7Ug5C1A_NvB2wi0-Ehp5l4jtLgD2GKfiNJjrX2_vLady4WllCPqdzZLRUAj2rAtXLOTxJoYW3I4tv-mNndnBo3ky4Rgkv6nPUc0vF8f80j00e6Ow0GTkL6-tkQ17hORDq8s9Lnv_p3cBNRZGVX2Tgdx4dELGBdIgFjA5hATy8Ay10qeAqYNhojfASmZ1HR2zbxx7k8DaiwG1xRPKvIf7qsQ3pC0T_aJ-CVNrpFM5jZnMclyv7VLMjAGtizFyBG457qgBwo3t3_ITtS-LBKXBiAbstVP5lWoGHbz0NOP1gm1suQL2Gl4NTcqRHwFS8xrGp_AVL33zevzgPNt03xb1vYptJWqy7WGYnlfe9Znrcdgj3nKUf-EXuxmNrWwjDlPoSVC5L_UQ75ENteYxIeajgr8bjC_qzXbFpOwjnLbYop5-RrgJ_giJQUHMOWf5g9OYly6PJnUYFJXD0BJEIDpaH-ouhoZjkYol36_O-VDoEWREkofqjickvpAplW1N_j-VhkWC66QmwOEFrUi8ltJqdAFl80mzvr3WksvKB2le53DfzZTJ9QYRm4tkOQC37dZIxXgPpyZK7dedAC6PU7DVlNC27P7yXQZ7Dcz3CAYggHIkeCds


# ELEVATOR PITCH

sono Michele, fondatore di Subly, un’applicazione pensata per risolvere un problema sempre più diffuso: la gestione disordinata degli abbonamenti digitali. Oggi ognuno di noi paga più servizi in abbonamento (streaming, musica, software, palestre, utility)  ma spesso perdiamo il controllo delle scadenze e del costo totale mensile, finendo per spendere soldi inutilmente. Subly nasce per centralizzare tutto in un’unica dashboard semplice e intuitiva, dove l’utente può inserire i propri abbonamenti, visualizzare i costi periodici, monitorare le date di rinnovo e accedere rapidamente ai siti ufficiali per gestire o disdire il servizio. Operiamo nel mercato in forte crescita della gestione finanziaria personale digitale, trainato dall’aumento costante dei servizi in abbonamento e dalla crescente attenzione al risparmio. Il nostro modello di business prevede una versione gratuita per la gestione base e una versione Premium con funzionalità avanzate di analisi delle spese, notifiche intelligenti e possibili partnership o affiliazioni con servizi terzi. Dal punto di vista tecnologico, Subly è sviluppata con un’architettura scalabile e un’interfaccia user-friendly, progettata per offrire semplicità, chiarezza e controllo totale all’utente. Rispetto ai competitor come Rocket Money o altre app di subscription tracking, Subly si distingue per la sua immediatezza, la centralizzazione completa e il focus sull’esperienza utente. Il nostro obiettivo è crescere progressivamente introducendo funzionalità sempre più evolute. Subly vuole trasformare il modo in cui le persone gestiscono i propri abbonamenti, rendendo il controllo delle spese più semplice, trasparente e intelligente.


# WBS

```mermaid
    graph TD
    A["Subly - Gestione Abbonamenti (60k - 5 Mesi)"] --> B["Pianificazione e Analisi (3 sett.)"]
    A --> C["Design UI/UX (4 sett.)"]
    A --> D["Sviluppo Frontend (6 sett.)"]
    A --> E["Sviluppo Backend (6 sett.)"]
    A --> F["Pagamenti e Sicurezza (3 sett.)"]
    A --> G["Testing e QA (3 sett.)"]
    A --> H["Marketing e Lancio (2 sett.)"]
    A --> I["Supporto e Manutenzione (2 sett.)"]

    B --> B1["Analisi Requisiti"]
    B --> B2["Analisi Competitor"]
    B --> B3["Definizione MVP"]
    B --> B4["Pianificazione Tecnica"]

    C --> C1["Wireframe Dashboard"]
    C --> C2["Prototipo Gestione Abbonamenti"]
    C --> C3["User Testing"]

    D --> D1["Login e Registrazione"]
    D --> D2["Dashboard Abbonamenti"]
    D --> D3["CRUD Abbonamenti"]
    D --> D4["Responsive Design"]

    E --> E1["API Utenti"]
    E --> E2["API Abbonamenti"]
    E --> E3["Database"]
    E --> E4["Sistema Notifiche"]

    F --> F1["Gateway Bancario"]
    F --> F2["Autentic]()
```
