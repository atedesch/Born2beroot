# Born2beroot

## Hostname - atedesch42

In Linux, l'hostname è il nome assegnato a un computer all'interno di una rete. È un identificatore univoco che consente agli altri dispositivi sulla rete di identificare e comunicare con quel computer.
L'hostname può essere configurato per rappresentare il nome dell'organizzazione, il tipo di dispositivo o qualsiasi altra convenzione desiderata. Di solito è composto da una serie di caratteri alfanumerici, trattini e punti.
Il comando hostname in Linux viene utilizzato per visualizzare o impostare il nome host del sistema. Ecco alcuni utilizzi comuni:
1. Visualizzare l'hostname: Puoi utilizzare il comando hostname senza alcun argomento per visualizzare semplicemente il nome host corrente del sistema.
2. Impostare l'hostname: Puoi utilizzare il comando hostname con l'opzione -b o --set seguita dal nuovo nome host per cambiarlo temporaneamente. Tuttavia, questa modifica non sarà permanente dopo il riavvio del sistema.
```bash
sudo hostname nuovo_hostname
```


## su
Il comando su su Linux (e su altri sistemi Unix-like) è utilizzato per acquisire temporaneamente i privilegi di un altro utente. Di solito, viene utilizzato per diventare l'utente "root", che ha accesso completo a tutti i file di sistema e alle operazioni di amministrazione.


## apt install sudo
apt install sudo non è un comando comune in Linux, ma è una combinazione di due comandi distinti: apt install e sudo:
- apt è un gestore dei pacchetti per distribuzioni basate su Debian e derivate come Ubuntu. Il comando apt viene utilizzato per gestire l'installazione, la rimozione e l'aggiornamento dei pacchetti software nel sistema operativo.
- install è un argomento del comando apt che specifica che si desidera installare un pacchetto software nel sistema.
- sudo è un comando che consente agli utenti di eseguire altri comandi con i privilegi di un altro utente, comunemente l'utente "root" che ha accesso completo al sistema. È spesso richiesto per eseguire operazioni di amministrazione, come l'installazione di nuovi pacchetti software.
Quindi, apt install sudo verrebbe utilizzato per installare il programma sudo, che a sua volta consente agli utenti di eseguire comandi con privilegi di amministratore. Tuttavia, è importante notare che sudo di solito è già preinstallato in molte distribuzioni Linux, quindi non sarebbe necessario installarlo manualmente nella maggior parte dei casi.


## OpenSSH
OpenSSH è un'implementazione open source del protocollo SSH (Secure Shell), che fornisce un metodo sicuro per accedere e gestire in remoto i dispositivi e i server su una rete. Il protocollo SSH cifra tutti i dati scambiati tra il client SSH (il programma utilizzato per connettersi al server) e il server SSH, fornendo così una connessione sicura su una rete non affidabile, come ad esempio Internet.
OpenSSH offre diverse funzionalità, tra cui:
1. Accesso remoto sicuro: Gli utenti possono connettersi a un server SSH in remoto da qualsiasi luogo e interagire con il sistema come se fossero fisicamente presenti davanti ad esso. La connessione è protetta da cifratura per proteggere i dati sensibili scambiati tra il client e il server.
2. Trasferimento sicuro dei file: OpenSSH include anche strumenti come scp (Secure Copy Protocol) e sftp (Secure File Transfer Protocol) per il trasferimento sicuro di file tra il client e il server SSH. Anche queste operazioni sono protette da crittografia per garantire la sicurezza dei dati.
3. Tunneling: OpenSSH consente di creare tunnel crittografati tra il client e il server per instradare altre connessioni attraverso di esso. Questo è utile per accedere a servizi interni di una rete remota in modo sicuro.

OpenSSH è ampiamente utilizzato in sistemi operativi Unix-like (come Linux e BSD) e viene fornito di default in molte distribuzioni Linux. È una componente essenziale per gestire in modo sicuro i server e gli altri dispositivi remoti su una rete.


# port 4242
Le "porte da ascoltare" si riferiscono alle porte su un computer che sono aperte e in ascolto per le connessioni in entrata. Le porte sono numeri di identificazione numerica associati a un servizio specifico o a un'applicazione su un host di rete.

Nel contesto di un server, come ad esempio un server web o un server SSH, le porte da ascoltare rappresentano i canali attraverso i quali altri computer possono comunicare con quel server. Ogni servizio o applicazione ha una porta specifica a cui è associato di default. Ad esempio:

- Il servizio web di default (HTTP) ascolta sulla porta 80 o sulla porta 443 per le connessioni non sicure e sicure, rispettivamente.
- Il servizio SSH ascolta di default sulla porta 22.
- Il servizio FTP ascolta sulla porta 21.

Le porte da ascoltare sono essenziali per consentire ai client di comunicare con i server e di accedere ai servizi offerti da questi ultimi. Tuttavia, è importante comprendere che le porte possono essere cambiate o personalizzate per adattarsi alle esigenze specifiche dell'ambiente di rete o per aumentare la sicurezza. Ad esempio, per motivi di sicurezza, potresti voler cambiare la porta predefinita di un servizio noto per una porta meno nota per ridurre il rischio di attacchi da parte di hacker.





