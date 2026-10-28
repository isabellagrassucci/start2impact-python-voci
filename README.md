# L'archivio di Voci

Progetto del **modulo Python** del master di [start2impact](https://www.start2impact.it/): un sistema di gestione degli elementi scritto in Python su Jupyter Notebook.

## Il tema

**Voci** è un media brand (ipotetico, dalla consegna del progetto) che racconta le storie delle donne su blog, social e YouTube.
Anche online le donne hanno ancora poca voce: nei media digitali italiani sono solo il **39% delle persone esperte citate** e firmano il **29% dei contenuti** (GMMP 2025).
Voci non cerca solo la parità: vuole **compensare**, dando alle donne più spazio del solito.

## La soluzione

L'archivio dei contenuti di Voci, con una regola editoriale scritta nel codice.

- **La redazione** registra video, interviste e articoli. Un contenuto entra solo se le voci maschili dell'**intero archivio** restano entro il **30%**; altrimenti scatta un errore creato su misura, `VociSbilanciate`.
- **L'utente** consulta l'archivio da un menu: ricerca per parola, filtri con più criteri insieme e statistiche (con pandas), compreso il tema su cui la redazione deve impegnarsi di più.
- **Struttura a oggetti**: `ArchivioVoci` contiene i `Contenuto`, da cui ereditano `Video`, `Intervista` e `Articolo`.

## Come eseguirlo

1. Installa pandas: `pip install pandas`
2. Apri `IsabellaGrassucci_Python.ipynb` ed esegui tutte le celle.
3. Per provare il menu interattivo, togli il `#` dall'ultima cella di codice (`menu_utente(archivio)`).

## Fonti

- Osservatorio di Pavia, [Global Media Monitoring Project 2025 – Italia](https://www.osservatorio.it/wp-content/uploads/2016/03/GMMP25-_IT_EN.pdf)
- [Obiettivo 5 dell'Agenda ONU 2030 – Parità di genere](https://unric.org/it/obiettivo-5-raggiungere-luguaglianza-di-genere-ed-emancipare-tutte-le-donne-e-le-ragazze/)

---
Isabella Grassucci · 2026
