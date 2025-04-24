# Onda Factory

> Segnala problemi, proponi idee e contribuisci allo sviluppo di Onda — che tu sia Redattore, Designer o Sviluppatore, inizia da qui.

---

## 📝 Come aprire una issue

1. Vai a **[`triage`](https://github.com/ondafactory/triage/issues/new)**.
2. Scegli un titolo e compila una descrizione chiara del problema.
3. Invia: ci penseremo noi.

---

## 📦 Repository

| Repository | Contenuto | Destinatari |
|------------|-----------|-------------|
| [`triage`](https://github.com/ondafactory/triage/issues) | Bug, idee o domande in forma grezza. **Nessun filtro**. | Tutti |
| [`proposals`](https://github.com/ondafactory/proposals/issues) | Idee e proposte da discutere e validare. | Tutti |
| [`issues`](https://github.com/ondafactory/issues/issues) | Task a breve termine: bug‑fix, piccoli miglioramenti, hot‑patch. | Dev |
| [`roadmap`](https://github.com/ondafactory/roadmap/issues) | Funzionalità più importanti che richiedono più tempo. | PM · Dev |

> Apri *sempre* in **triage** → poi saremo noi a spostare la issue in **proposals**, **issues** o **roadmap** a seconda dei casi.
> *(Per favore **non** aprire direttamente ticket negli altri repo: l'accesso in scrittura è limitato).*

---

## 🔄 Flusso

```mermaid
flowchart LR
  triage((Triage)) --> proposals{{Proposals}}
  proposals --> roadmap[Roadmap]
  triage --> issues[Issues]
  issues --> done1((Done))
  roadmap --> done2((Done))
  issues --> roadmap
```

---

<div align="center">
  Realizzato con ☕ &nbsp;dal team Onda Factory
</div>

