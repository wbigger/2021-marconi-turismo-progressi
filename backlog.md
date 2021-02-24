# Backlog

Di seguito, tutte le storie (circa) fino alla fine del progetto.

Vi ricordo che quando fate la vostra pianificazione, potete (dovete) spacchettare queste storie in delle vostre storie più piccole.

## Packet tracer
Come amministratore, voglio avere su packet tracer uno schema funzionante dell'architettura di rete, per verificare che la connessione sia corretta.
- il tablet deve poter pingare il server
- il piano di indirizzamento di internet deve essere con IP pubblici
Nota: il server o ha un indirizzo IP pubblico (in una sottorete /30) oppure è sotto NAT con port-forwarding.

Come amministratore, voglio poter testare la pagina web su packet tracer, in modo da poter fare delle verifiche in simulazione.
- il server deve avere il servizio HTTP/HTTPS attivo
- il server deve poter essere raggiunto tramite dominio (servizio DNS)

## Front-end
Come amministratore, voglio avere una sitemap del sito per avere una visione di inseme di tutto il progetto
- mi interessa solo la parte fruibile da tablet
- opzionale una eventuale parte da fruire a casa prima della visita
- specificare se alcune azioni sono svolte dall'operatore dell'infopoint

Come utente, voglio visualizzare una pagina con i dettagli del PoI in cui mi trovo, per poter avere informazioni aggiuntive di tipo turistico
- nella pagina deve essere presente un video di presentazione con più informazioni
- ci devono essere delle immagini (max 3) per poter vedere il punto di interesse al volo
- le immagini devono avere una didascalia

## Back-end
Come amministratore, voglio che la pagina sia dinamica, in modo da poterla aggiornare più facilmente.
- i video, le foto ed i testi devono essere presi da un server attraverso chiamate HTTP
- il server deve prendere le informazioni da un database
- il database salva solo l'URL delle immagini, del video, che dovranno essere salvati su un server HTTP dedicato

Nota: valuteremo insieme se per la parte di backend non implementare la soluzione in packet tracer ma usare direttamente un'architettura reale.
