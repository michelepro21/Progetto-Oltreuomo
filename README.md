# Progetto Oltreuomo — Milestone 1.4

Aggiunge la schermata Trofei alla Milestone 1.3.

Avvio locale:

```powershell
npx serve .
```

Poi apri `http://127.0.0.1:3000` e, dopo un aggiornamento, usa Ctrl+Shift+R.

La chiave localStorage resta `oltreuomo-state-v1`, quindi i progressi delle milestone precedenti vengono mantenuti nello stesso browser/origine.


## Milestone 1.5
Aggiunge Gestione > Task: creazione, modifica, sospensione/riattivazione ed eliminazione delle configurazioni Task.


## Milestone 1.5.3
Correzione: una Task a scadenza completata resta visibile nel Giorno Oltreuomo di completamento e viene rimossa dalla Home dai giorni successivi, mantenendo storico e XP.

## Milestone 1.7
Aggiunge Gestione > Regole di gioco: ricompense base, valutazioni, difficoltà, Skip e curva livelli. Corregge inoltre l'etichetta della ricompensa Salute mentale distinguendo XP base e XP risultanti dalla difficoltà.


## Milestone 1.7.1
Corretto il conteggio degli Skip consecutivi di Studio: dal 4° Skip si applica la stessa penalità progressiva delle altre categorie; completamento resetta la streak, Esonero la congela.

## Milestone 1.7.2
Correzione: il riepilogo Nuovo Giorno mostra la ricompensa Salute mentale solo nel Giorno Oltreuomo in cui la sfida è stata completata.

## Milestone 1.7.4
Aggiunge ANNULLA nel Giorno Oltreuomo aperto per completamenti ed Esoneri. Annullare un completamento ripristina XP, statistiche, streak ed eventuali eventi di Level Up/Down prodotti da quell'azione. Dopo la chiusura del giorno il passato resta immutabile.

Milestone 1.7.5: le Task personalizzate a scadenza completate restano visibili nel Giorno Oltreuomo corrente, compaiono nel riepilogo e possono essere annullate prima della chiusura del giorno.


Milestone 1.7.6: Task personalizzate a tempo collegate al riepilogo Nuovo Giorno, valutazione, XP, Skip/Esonero e streak.


Milestone 1.8.2: aggiunto feedback visivo sobrio LEVEL UP / LEVEL DOWN con categoria e livello finale.


## Milestone 1.8.2
- Overlay automatico dedicato a TROFEO OTTENUTO.
- Mostra nome, XP assegnati e categoria.
- Se il Trofeo provoca anche un Level Up, il feedback Level Up viene mostrato subito dopo il Trofeo, senza sovrapporsi.


## Milestone 1.8.2
- Icona ufficiale Progetto Oltreuomo integrata nella PWA.
- Icone PWA 192×192 e 512×512.
- Apple Touch Icon 180×180 per installazione su iPhone.
- Aggiornata cache offline per includere le icone.


## Milestone 1.8.3
Aggiunti Esporta Backup e Importa Backup in Gestione > Regole. Il backup JSON contiene lo stato locale completo; l'importazione valida il file e richiede conferma prima di sostituire i dati correnti.
