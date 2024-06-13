Questo progetto è un applicazione desktop che permette di chattare su Telegram tramite un bot.

***
Funzionalità principali:
*1.Selezione di una chat da una lista predefinita
*2.Invio di messaggi alla chat selezionata
*3.Visualizzazione in tempo reale dei messaggi inviati e ricevuti

***
Prerequisiti:
*1.Python 3 installato sul sistema
*2.Accesso a Internet per l'utilizzo dell'API di Telegram
*3.Token API valido per il bot Telegram

***
Installazione e utilizzo:
*1.Clonare il repository
*2.installare e dipendenze (pip install -r requirements.txt)

Configurazione del file chats.txt:

![image](https://github.com/Framework8/Messaggi-via-bot_Telegram/assets/109827575/d38e08b2-fb35-477c-8e72-c27082b79450)

Inserire manualmente nel file il nome e il chat id separandoli solo con ":" come mostrato in foto.

Ottenere il chat id:
![image](https://github.com/Framework8/Messaggi-via-bot_Telegram/assets/109827575/697e2765-4df3-45c3-b594-dc5fbfeb84f1)

Un modo per ottenere il chat id di un utente con il bot è collegarlo ad uno script come quello indicato sopra in immagine (in allegato come "chat_id_bot.py") e far inviare all'utente con cui si vuole chattare il comando "/chat_id". Una volta che il bot gli avrà risposto con il chat id basterà aggiungerlo al file chats.txt
