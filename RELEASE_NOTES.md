# GefinApp 0.1.1 beta

Aggiornamento della beta Windows x64.

## Novità 0.1.1

- Sincronizzazione automatica in background dell'intero universo visibile.
- Dieci anni di prezzi OHLCV e azioni societarie al primo caricamento.
- Aggiornamenti successivi limitati agli ultimi tre mesi.
- Coda controllata con due richieste concorrenti, retry e isolamento degli errori per simbolo.
- Nuovo ciclo ogni sei ore mentre GefinApp è aperta.
- Stato dettagliato disponibile in `/api/system/sync` e avvio manuale tramite `POST`.

## Contenuto

- Home Mercati con più orizzonti temporali, notizie e calendario.
- Universo di azioni, ETF, indici e materie prime organizzato per geografia e settore.
- Analisi del singolo titolo con prezzi, volumi, fondamentali e bilanci.
- Sentiment storico e contestuale basato su fonti pubbliche.
- Dieci modelli previsionali mensili con validazione walk-forward e metodologia integrata.
- Portafoglio e profitti/perdite separati tra operazioni reali e simulate.
- Database SQLite creato e conservato esclusivamente in locale.

## Installazione

Scarica lo ZIP, estrailo e avvia `Avvia GefinApp.cmd`. Node.js non deve essere installato.

## Nota beta

Il pacchetto non è firmato digitalmente; Windows può mostrare un avviso per un file scaricato da Internet.
