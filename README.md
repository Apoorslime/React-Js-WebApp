# Guida introduttiva alla creazione di una React-App su Termux

Questo progetto è stato avviato con [Create React App](https://github.com/facebook/create-react-app).

## Script disponibili

Nella directory del progetto `my-app`, puoi eseguire:

### `npm start`

Esegue l'app in modalità sviluppo.\
Apri [http://localhost:3000](http://localhost:3000) per visualizzarlo nel tuo browser.

Appena eseguirai `npm start` Termux potrebbe già proporti di aprire un browser


La pagina si ricaricherà quando apporti modifiche.\
Potresti anche vedere eventuali errori di lanugine nella console.
### `npm test`

Avvia il test runner nella modalità orologio interattivo.\
Per ulteriori informazioni, vedere la sezione sui [test di esecuzione](https://facebook.github.io/create-react-app/docs/running-tests).


### `npm run build`

Crea l'app per la produzione nella cartella `build`.\
 Raggruppa correttamente React in modalità produzione e ottimizza la build per le migliori prestazioni.

 La build viene minimizzata e i nomi dei file includono gli hash.\
 La tua app è pronta per essere distribuita!


Vedi la sezione su [deployment](https://facebook.github.io/create-react-app/docs/deployment) per maggiori informazioni.

### `npm run eject`

**Nota: questa è un'operazione a senso unico.  Una volta "espulso", non puoi tornare indietro!**

 Se non sei soddisfatto dello strumento di compilazione e delle scelte di configurazione, puoi 'espellere' in qualsiasi momento.  Questo comando rimuoverà la singola dipendenza di build dal tuo progetto.

 Invece, copierà tutti i file di configurazione e le dipendenze transitive (webpack, Babel, ESLint, ecc.) direttamente nel tuo progetto in modo da avere il pieno controllo su di essi.  Tutti i comandi tranne "espelli" continueranno a funzionare, ma punteranno agli script copiati in modo da poterli modificare.  A questo punto sei da solo.

 Non devi mai usare `eject`.  Il set di funzionalità curato è adatto per distribuzioni di piccole e medie dimensioni e non dovresti sentirti obbligato a utilizzare questa funzionalità.  Tuttavia, comprendiamo che questo strumento non sarebbe utile se non potessi personalizzarlo quando sei pronto per questo.

## Boostrap Deprecato
a tutti gli sviluppatori che utilizzano boostrap all'interno di ReactJs, Questo pacchetto è stato Deprecato a causa di vulnerabilità con npm, il pacchetto è stato ritirato.

**package.json**

```json
{
  "name": "boostrap",
  "version": "2.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/npm/deprecate-holder.git"
  },
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/npm/deprecate-holder/issues"
  },
  "homepage": "https://github.com/npm/deprecate-holder#readme",
  "dependencies": {}
}
```

Per impostare boostrap nell'app ReactJs, installa il package React-Boostrap
`npm install react-bootstrap bootstrap`
e importa boostrap all'interno di [App.js](src/App.js), inserisci nella prima riga

```js
import 'bootstrap/dist/css/bootstrap.min.css';
```



