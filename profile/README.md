# 📌 Come segnalare bug, feature ed epiche

**OndaFactory** è il punto di raccolta unico per tutte le segnalazioni.

Se hai un problema, un’idea o una richiesta, **[apri una issue qui](https://github.com/ondafactory/triage/issues/new)**.  
Può essere un bug, una nuova funzionalità, un miglioramento o un progetto strategico.

---

## 🚨 Cosa segnalare

Quando apri una **issue** su questo repository, puoi scegliere tra:

- **🐞 Bug** → un problema tecnico che blocca o limita l’uso della piattaforma.  
- **✨ Feature / Miglioramento** → una piccola nuova funzionalità o un’ottimizzazione a qualcosa di esistente.  
- **🚀 Epic** → un progetto ampio e prioritario (settimane/mesi).  

---

## 📝 Come inserire una issue

1. Vai su **[New Issue](https://github.com/ondafactory/triage/issues/new)**.  
2. Scegli il **template**:  
   - Bug report  
   - Feature / Miglioramento  
   - Epic strategica  
3. Compila i campi richiesti.  
4. Salva la issue.  

👉 Sarà il team di sviluppo a spostarla nel backlog corretto.

---

## 📦 Repository

| Repository                                                   | Contenuto                                                | Destinatari |
| ------------------------------------------------------------ | -------------------------------------------------------- | ----------- |
| [`triage`](https://github.com/ondafactory/triage/issues)     | Tutte le segnalazioni iniziali.                          | Tutti       |
| [`bugs`](https://github.com/ondafactory/bugs/issues)         | Problemi tecnici da risolvere.                           | Dev         |
| [`features`](https://github.com/ondafactory/features/issues) | Piccole funzionalità o miglioramenti (1–2 giorni).       | Dev · PO    |
| [`epics`](https://github.com/ondafactory/epics/issues)       | Progetti strategici (settimane/mesi).                    | Dev · PO    |

> Apri *sempre* le segnalazioni in **triage** → il team le instraderà poi nel backlog corretto.  
> *(Gli altri repo hanno l’accesso in scrittura limitato).*

---

## 🔄 Flusso

```mermaid
flowchart TD
  triage((Triage))

  %% Bugs
  triage --> bugs_backlog[Bugs]
  bugs_backlog --> bugs_done((Done))

  %% Features
  triage --> feat_backlog[Features backlog]
  feat_backlog --> feat_todo[To do]
  feat_todo --> feat_doing[Doing]
  feat_doing --> feat_done((Done))

  %% Epics
  triage --> epic_backlog[Epics backlog]
  epic_backlog --> epic_todo[To do]
  epic_todo --> epic_doing[Doing]
  epic_doing --> epic_done((Done))
```

---

<div align="center">
  Realizzato con ☕🍪🍵 dal team Onda
</div>
