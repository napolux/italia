# Italia

In questo repository potrete trovare una serie di file utili a costruire elenchi, endpoint JSON, `<select>` html, tabelle MySQL, ecc... Basati su comuni, province e regioni italiane.

### Contenuto del repository

* File JSON per comuni, province, regioni contenenti tutti i dati presenti nei file originali ISTAT
* File JSON semplificati per comuni, province, regioni
* File XML per comuni, province, regioni
* Dump MySQL composto da tre tabelle: `comuni`, `province`, `regioni`. Le tabelle sono relazionate tra loro tramite i campi `ID_regione`, `ID_provincia`, `ID_comune`, rispettivamente 

### Italiano o inglese?

Essendo un repository ad uso prettamente autarchico, per le label di campi, oggetti, ecc... Ho preferito mantenere la variante italiana. Eventualmente in futuro sarà possibile aggiungere lingue differenti. 

### Come posso contribuire?

Puoi contribuire aggiungendo:

* Correzioni / Variazioni
* Nuovi formati dati ([partendo dagli originali ISTAT](http://www.istat.it/it/archivio/6789), e non dai file che trovi qui)

### Aggiornamento dati

I dati sono basati sui [file originali ISTAT](http://www.istat.it/it/archivio/6789) aggiornati al **23 Aprile 2016**. Verranno aggiornati ogni volta che ISTAT rilascerà nuovi dati.
