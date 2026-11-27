# Autovalutazione AILit per docenti

Strumento di autovalutazione per docenti sulle 19 competenze del framework AILit (OCSE e Commissione europea, 2026). Per ogni competenza il docente indica quanto la padroneggia («Io, nel mio lavoro») e quanto la fa sviluppare ai suoi studenti («Con i miei studenti»). Una ragnatela confronta le due risposte e suggerisce i prossimi passi.

A cura di Emilia Sera.

## Come funziona

- È un'unica pagina HTML (`index.html`), senza server e senza raccolta di dati.
- Le risposte non vengono conservate né inviate: a ogni apertura il test riparte da zero.
- Per il confronto nel tempo il docente scarica il risultato (un file `.txt` con resoconto e codice) e lo ricarica quando ripete l'autovalutazione. In alternativa può incollare il codice risultato di 38 cifre.

## Pubblicazione con GitHub Pages

1. Crea un repository pubblico, per esempio `ailit-autovalutazione`.
2. Carica `index.html` e questo `README.md` (Add file → Upload files → Commit changes).
3. Vai in Settings → Pages, scegli Deploy from a branch, branch `main`, cartella `/ (root)` e salva.
4. Dopo un paio di minuti la pagina è online all'indirizzo `https://NOMEUTENTE.github.io/ailit-autovalutazione/`.

Per incorporarla nel blog:

```html
<iframe src="https://NOMEUTENTE.github.io/ailit-autovalutazione/" title="Autovalutazione AILit per docenti" width="100%" height="900" style="border:1px solid #ccc;border-radius:8px" allow="clipboard-write"></iframe>
```

## Fonte e licenza

OECD / Unione europea (2026), *Preparare gli studenti all'era dell'IA. Un framework per l'alfabetizzazione all'Intelligenza Artificiale per l'istruzione primaria e secondaria*, CC BY 4.0, https://doi.org/10.1787/65cd27d4-en.

Questo strumento è un adattamento di un'opera originale dell'OCSE e dell'Unione europea. Le opinioni espresse e le argomentazioni utilizzate in questo adattamento non devono essere riportate come rappresentative delle posizioni ufficiali dell'OCSE, dei suoi paesi membri o dell'Unione europea.
