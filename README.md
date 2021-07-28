# GPS Position per SMS-Anfrage versenden

Bei diesem Projekt geht es um die Möglichkeit per Versenden einer SMS an ein Android Smartphone, die GPS-Position dessen als Antwort-SMS zu erhalten. 

Dazu sind zwei Skripte notwendig, die für die Android App Automate erstellt wurden.

- Automate_Script-SMS_Send_Request

Dieses Skript stellt die SMS-Anfrage an über eine Mobilfunknummer an ein anderes Android Gerät 

- Automate_Script-SMS_Send_Position_SMS

Dieses Skript verarbeitet die SMS-Anfrage aus dem vorherigen Skript und retouniert entsprechend die aktuelle GPS-Position. Dieses Skript läuft im Hintergrund und benötigt keinerlei Interaktion durch den Benutzer.

Für weitere Informationen siehe meinen Blogbeitrag https://www.andreas-voit.at/2021/07/28/automateGPSSMS
