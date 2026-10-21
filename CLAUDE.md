# CLAUDE.md - Nome del progetto

## Cos'è questo progetto

Due o tre frasi: cosa vogliamo ottenere e per chi. Esempio: "Studio di un sistema di
ricarica condominiale con load balancing: normativa, requisiti, modello di ripartizione
dei costi fra i condomini."

Progetto del corso di Automazione dei sistemi elettrici di trasporto, Politecnico di
Milano, gruppo NN.

## Chi ci lavora

Nome Cognome, Nome Cognome, Nome Cognome. Nessuno di noi programma di mestiere: spiega le
scelte in italiano semplice e non dare per scontato niente.

## Preferenze personali

Se nella radice del progetto esiste `miePersonalizzazioni.md`, leggilo prima di iniziare e
segui le sue indicazioni: sono le preferenze di chi sta lavorando in questa sessione.
Non modificarlo e non metterlo mai in un commit.

Ogni componente del gruppo lo crea sul proprio PC (è nel `.gitignore`, non va su GitHub)
con questa struttura:

    # Le mie personalizzazioni
    ## Chi sono
    Nome, sistema operativo, editor, agente che uso.
    ## Come voglio che mi parli
    Lingua, lunghezza delle spiegazioni, quando chiedermi conferma.
    ## Cosa so fare e cosa no
    Terminale, git, programmazione: sì / no / un po'.
    ## Note di lavoro
    Comandi che uso spesso, errori già visti, cose che ho capito.

## Com'è fatta la cartella

- `docs/` - documenti di lavoro: `flussi.md` e `flussi.drawio.png` (i passi del progetto, in parole e in un diagramma; il diagramma lo disegniamo noi), appunti, note sulle fonti.
- `relazione/` - la relazione del corso, in LaTeX e in Word. Non toccarla mai senza che te lo chieda esplicitamente.
- `dati/` - i dati raccolti. Ogni file è registrato nella tabella di `dati/README.md` con la sua provenienza.
- `codice/` - il codice: script, modello, grafici. Ogni script dice in testa cosa fa, cosa legge e cosa produce.
- `presentazione/` - le slide finali. `sito/` - la pagina di presentazione.
- `diario.md` - il diario del progetto: avanzamento e decisioni. Lo scriviamo noi, non tu.
- `README.md` - cos'è il progetto, per chi arriva da fuori.
- Ogni cartella ha un README.md che dice cosa ci va: leggilo prima di scriverci. Nuove cartelle solo dopo averlo proposto e avuto l'ok.

## Regole di lavoro

- Un passo alla volta. Fai quello che ti ho chiesto, poi fermati e dimmi cosa hai fatto.
- Prima di creare un file nuovo, dimmi quale e perché.
- Se non ti riesce qualcosa, dillo. Non inventare numeri, fonti, nomi di pacchetti o risultati.
- Codice semplice e commentato in italiano: lo dobbiamo leggere noi.
- Niente librerie in più senza chiedermelo prima.
- Non modificare `relazione/` e `diario.md`.
- Niente commit e niente push da solo: li facciamo noi, dopo aver letto le modifiche.

## Come si scrive

Italiano. I numeri hanno sempre l'unità di misura. Ogni affermazione non ovvia ha una
fonte. Niente emoji.
