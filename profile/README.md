# 📌 Come segnalare bug, feature o un progetto strategico

**OndaFactory** è il punto di raccolta unico per tutte le segnalazioni.

Se hai un problema, un’idea o una richiesta, **[apri una issue qui](https://github.com/ondafactory/work/issues/new)**.  
Può essere un bug, una nuova funzionalità, un miglioramento o un progetto strategico.

---

## 🚨 Cosa segnalare

Quando apri una **issue** su questo repository, puoi scegliere tra:

- **🐞 Bug** → un problema che blocca o limita l’uso della piattaforma.  
- **✨ Feature** → una nuova funzionalità o un miglioramento a qualcosa di esistente.  
- **🚀 Strategic** → un progetto o una funzionalità strategica.  

---

## 📝 Come inserire una issue

1. Vai su **[New Issue](https://github.com/ondafactory/work/issues/new)**.  
2. Scegli la tipologia di issue: Bug, Feature o Strategic.
3. Compila i campi richiesti.  
4. Salva la issue.  

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

  %% Strategic
  triage --> epic_backlog[Epics backlog]
  epic_backlog --> epic_todo[To do]
  epic_todo --> epic_doing[Doing]
  epic_doing --> epic_done((Done))
```

---

<div align="center">
  Realizzato con ☕🍪🍵 dal team Onda
</div>
