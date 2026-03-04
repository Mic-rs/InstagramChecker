# Instagram Non-Followers Checker

Strumento web per scoprire **chi segui su Instagram ma non ti segue indietro** utilizzando i dati ufficiali esportati da Instagram.

Il tool funziona **completamente nel browser**: nessun dato viene caricato su server.

## Demo

🚀 Apri il sito:

https://mic-rs.github.io/InstagramChecker/

## Come funziona

1. Esporta i tuoi dati da Instagram
2. Carica i file `following.json` e `followers.json`
3. Il tool confronta le liste e mostra gli account che **non ti seguono**

## Come ottenere i file JSON da Instagram

Instagram → Impostazioni → Centro gestione account → Le tue informazioni e autorizzazioni → Esporta le tue informazioni → Esporta sul dispositivo → Clicca su "personalizza informazioni" e seleziona solo "Follower e persone/Pagine seguite"

## Limitazioni e accuratezza

Il risultato non è garantito al 100%.

- Instagram può esportare i dati in formati diversi o incompleti a seconda dell’account e del periodo.
- Alcuni account possono apparire come “non ti seguono” anche se ti seguono (es. dati non aggiornati nell’export, differenze di maiuscole/minuscole, duplicati o voci anomale nei file).

Per ridurre errori: usa export recenti, carica i file corretti e verifica manualmente i casi dubbi.

## Autore

Realizzato da _Mic_
  
[@_michelecast_](https://instagram.com/_michelecast_)
