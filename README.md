# dati.gov.it

Repo centrale di strutturazione del progetto.

Vedi: https://developers.italia.it/it/datigov/

Questa repository e' il punto di incontro e condivisione di tutti gli sviluppatori e NON che vorranno contribuire
all'evoluzione del portale http://dati.gov.it.

Per il momento contiene esclusicamente questo file di spiegazioni  che evolverá anche
grazie al vostro contributo. Il motivo di questa scelta e' di aprire al contributo da parte di tutti voi fin
dalla partenza del processo di sviluppo.

L'intezione e' che qui troverete la descrizione dello stato del progetto http://dati.gov.it:
- con [link](https://github.com/FormezPA/dkan) al codice sorgente
- allo [stato di avanzamento](https://github.com/italia/dati.gov.it/projects)
- alle [issues](https://github.com/italia/dati.gov.it/issues).

Attualmente dati.gov.it si basa su un modulo di Drupal chiamato [dkan](https://github.com/FormezPA/dkan)  Il sistema e'
composto inoltre da una serie di harvester:

- [Ckan harvester](https://github.com/FormezPA/dkan_harvest_ckan)
- [Dkatap harvester](github.com/FormezPA/dkan_harvest_dcatap)

che vanno a importare i metadati dai vari portali open data delle pubbliche amministrazioni locali e nazionali. I dati vengono
esposti anche attraverso una serie di servizi web basati sullo standard [CKAN](http://docs.ckan.org/en/latest/api/)

Dati.gov.it evolverá da catalogo dei dati aperti a piattaforma di strumenti per l'esposizione dei dati pubblici. In questo contesto
alcuni dei punti che crediamo possano essere punto di rifermento e guida al progetto sono:

- Standardizzare i datasets di interesse nazionale seguendo ontologie predefinite ad esempio [dcat_ap_it](http://guida-pratica-dcat-ap-it.readthedocs.io/en/latest/guida.html)
- Offrire strumenti di interrogazione e visualizatione
- Fare analisi dei dati e utilizzare machine learning sia su dati in tempo reale che statici
- Esporre API pubbliche ben documentate
- Creare una dashboard del cittadino e delle imprese

Una prima bozza documentativa che descrive la metodologia di sviluppo agile e aperto e di architettura si puó trovare al
seguente [link](https://docs.google.com/document/d/1dCfbpwmkl-U2kreykRY8YXJct6GOe-r_3qjism5wI2Y/edit)
