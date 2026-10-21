# Nome del progetto

Una riga che dice cosa fa questo progetto. Progetto del corso di Automazione dei sistemi
elettrici di trasporto (Politecnico di Milano), gruppo NN: Nome Cognome, Nome Cognome,
Nome Cognome.

Materiali e istruzioni del corso: https://www.danielemartini.eu/automazione/

## Com'è fatta la cartella

- `CLAUDE.md` e `AGENTS.md` — le regole del gruppo per l'agente di coding, stesso testo con
  due nomi: Claude Code legge il primo, Codex / Gemini CLI / opencode il secondo. Stanno in git.
- `miePersonalizzazioni.md` — le preferenze personali di chi lavora: ogni componente lo crea
  sul proprio PC con la struttura scritta in `CLAUDE.md`. È nel `.gitignore`: resta lì.
- `diario.md` — il diario del progetto: a fine sessione, cosa è stato fatto, cosa è stato
  deciso, da dove si riparte.
- `docs/` — documenti di lavoro: `flussi.md` e `flussi.drawio.png` (i passi del progetto, in
  parole e in un diagramma disegnato con draw.io), appunti, note sulle fonti.
- `relazione/` — la relazione del corso, pronta da compilare: `relazione.tex` (con
  `bibliografia.bib` e `figure/`) oppure `relazione.docx`, stessa struttura. Scegliete uno dei
  due e cancellate l'altro.
- `dati/`, `codice/`, `presentazione/`, `sito/` — vuote oggi, è voluto: ognuna ha un README
  che dice cosa ci va.
- `.gitignore` — quello che non va su GitHub.

## Come si comincia

1. Create `miePersonalizzazioni.md` con la struttura scritta in `CLAUDE.md` e compilatelo.
2. Aprite il terminale **dentro questa cartella** e lanciate il vostro agente. Le regole le
   legge da solo.
