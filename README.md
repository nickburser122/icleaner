# iCleaner

Turns pasted tabular text into a table. It detects the delimiter, finds the table inside the surrounding text, infers each column type and shows what it will do before anything is saved. Results copy as TSV or download as `.tsv` or `.csv`.

## Limits

- Data is stored in the browser (IndexedDB); clearing site data removes it.

## Network and install

No network calls after load; loads Google Fonts from a CDN. Not installable; no service worker.
