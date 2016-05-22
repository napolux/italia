# Italia

In questo repository potrete trovare una serie di file utili a costruire elenchi, endpoint JSON, `<select>` html, tabelle MySQL, ecc... Basati su comuni, province e regioni italiane.

### Contenuto del repository

* File JSON per comuni, province, regioni contenenti tutti i dati presenti nei file originali ISTAT
* File XML per comuni, province, regioni
* Dump MySQL composto da tre tabelle: `comuni`, `province`, `regioni`. Le tabelle sono relazionate tra loro tramite i campi `ID_regione`, `ID_provincia`, `ID_comune`, rispettivamente 
* Dump SQLite3 composto da tre tabelle: `comuni`, `province`, `regioni`. Le tabelle sono relazionate tra loro tramite i campi `ID_regione`, `ID_provincia`, `ID_comune`, rispettivamente

### Italiano o inglese?

Essendo un repository ad uso prettamente autarchico, per le label di campi, oggetti, ecc... Ho preferito mantenere la variante italiana. Eventualmente in futuro sarà possibile aggiungere lingue differenti. 

### Alcune precisazioni

* I dati sono "ottimizzati" per l'uso "tipico" fatto da sviluppatori software (menù di selezione, archiviazione dati, ecc...). I codici di "associazione"" tra regione/provincia/comune potrebbe non coincidere
 con quelli indicati dall'ISTAT.
* Le coordinate dei comuni sono presi dal sito [geonames.org](http://www.geonames.org/)
* Il tutto è "salvo errori e/o omissioni"

### Come posso contribuire?

Puoi contribuire aggiungendo:

* Correzioni / Variazioni
* Nuovi formati dati ([partendo dagli originali ISTAT](http://www.istat.it/it/archivio/6789), e non dai file che trovi qui)

### Aggiornamento dati

I dati sono basati sui [file originali ISTAT](http://www.istat.it/it/archivio/6789) aggiornati al **23 Aprile 2016**. Verranno aggiornati ogni volta che ISTAT rilascerà nuovi dati.

### LEGAL STUFF

THE FILES (FROM NOW, "THE SOFTWARE") ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.