# Transizione controllata: Dreamweaver + GitHub Desktop → Visual Studio + Copilot

## 🧭 Introduzione
Questa Page documenta la transizione evolutiva del flusso di sviluppo del portale Calapso Serale, passando da Dreamweaver + GitHub Desktop a Visual Studio + GitHub Copilot.

## 📁 Mappa delle cartelle locali

- `C:\CalapsoSerale\gagini-serale-official\` → Flusso DW + GitHub Desktop  
- `C:\Users\marco\source\repos\calapsoserale\gagini-serale-workspace-VS\` → Flusso VS + Copilot

## 🔁 Flussi operativi a confronto

| Attività         | DW + GitHub Desktop | VS + Copilot     |
|----------------  |---------------------|------------------|
| Editing layout   | ✅                  | ⚠️ Limitato     |
| Refactoring      | ❌                  | ✅ AI assistito |
| Commit Git       | ✅ Manuale          | ✅ Integrato    |
| Branch tematici  | ✅                  | ✅              |
| Debug            | ❌                  | ✅              |
| Documentazione   | Manuale             | ✅ Integrabile   |

## 📜 Rubrica dei commit tematici

- `fix-layout-BES`  
- `update-navbar-accessibility`  
- `copilot-suggestion-refactor`  
- `debug-footer-responsive`

## ✅ Checklist sincronizzazione sicura

- [ ] Modifiche non simultanee su cartelle parallele  
- [ ] Commit descrittivi e coerenti  
- [ ] Pull prima di ogni nuova sessione  
- [ ] Push immediato dopo commit  
- [ ] Backup settimanale dei repository

## 🧠 Valutazione evolutiva

- Vantaggi riscontrati: assistenza AI, refactoring, commit integrati  
- Limiti da mitigare: preview layout, familiarità IDE  
- Proposta: estensione al repository ufficiale  
- Considerazioni: possibile dismissione di GitHub Desktop
## 📝 Aggiornamento cartella locale (27/09/2025)

La cartella clonata da Visual Studio è stata rinominata per distinguere chiaramente il flusso VS + Copilot da quello DW + GitHub Desktop.

- **Da**: `gagini-serale-workspace`
- **A**: `gagini-serale-workspace-VS`
- **Motivo**: separazione funzionale tra ambienti di sviluppo
- **Effetto**: nessun conflitto con il flusso Dreamweaver; commit e sincronizzazione gestiti in modo indipendente