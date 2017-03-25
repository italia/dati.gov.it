# dati.gov.it

Questo repository e' il punto di incontro e condivisione di tutti gli sviluppatori e NON che vorranno contribuire
all'evoluzione del portale [dati.gov.it](http://dati.gov.it).

Per il momento contiene esclusivamente questo file di spiegazioni che evolverà anche
grazie al vostro contributo. Il motivo di questa scelta è di aprire al contributo da parte di tutti voi fin
dalla partenza del processo di sviluppo.

## STATO ATTUALE DEL PROGETTO

Qui troverete la descrizione dello stato del progetto [dati.gov.it](http://dati.gov.it):
- con [link](https://github.com/FormezPA/dkan) al codice sorgente
- allo [stato di avanzamento](https://github.com/italia/dati.gov.it/projects)
- alle [issues](https://github.com/italia/dati.gov.it/issues).

Attualmente [dati.gov.it](http://dati.gov.it) si basa su un profilo di Drupal chiamato [dkan](https://github.com/FormezPA/dkan).  Il sistema include inoltre da una serie di harvester:

- [Ckan harvester](https://github.com/FormezPA/dkan_harvest_ckan)
- [DCAT-AP harvester](https://github.com/FormezPA/dkan_harvest_dcatap)

che importano i metadati da vari portali open data delle pubbliche amministrazioni italiane. Per una lista completa delle fonti attualmente importate si veda [la lista delle fonti dati](http://www.dati.gov.it/admin/harvest-sources-export) (aggiornata in tempo reale).
I dati vengono esposti anche attraverso una serie di servizi web basati sullo standard [CKAN](http://docs.ckan.org/en/latest/api/)

## EVOLUZIONE

[dati.gov.it](http://dati.gov.it) evolverá da catalogo dei dati aperti a piattaforma di strumenti per l'esposizione dei dati pubblici. In questo contesto
alcuni dei punti che crediamo possano essere punto di rifermento e guida al progetto sono:

- Standardizzare i datasets di interesse nazionale seguendo ontologie predefinite ad esempio [DCAT-AP_IT](http://guida-pratica-dcat-ap-it.readthedocs.io/en/latest/guida.html)
- Offrire strumenti di interrogazione e visualizzazione
- Fare analisi dei dati e utilizzare machine learning sia su dati in tempo reale che statici
- Esporre API pubbliche ben documentate
- Creare una dashboard del cittadino e delle imprese

## DOCUMENTAZIONE & INFO

Una prima bozza di documentazione che descrive la metodologia di sviluppo agile e di architettura si può trovare al
seguente [link](https://docs.google.com/document/d/1dCfbpwmkl-U2kreykRY8YXJct6GOe-r_3qjism5wI2Y/edit)

Trovate maggiori informazioni riguardo a questo progetto su [developers.italia.it](https://developers.italia.it/it/datigov/)
