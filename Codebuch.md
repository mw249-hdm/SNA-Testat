# Codebuch

Erhoben wurden die Reichsbürger, die bei einer Razzia durchsucht wurden und ihre Verbindungen untereinander und zu den Organisationen AfD, KSK und NdA.  
Quelle: https://taz.de/Razzia-gegen-Reichsbuerger/!5898636/
https://www.belltower.news/update-reichsbuerger-razzien-das-breite-netzwerk-der-revolutionsbereiten-reichsbuergerinnen-144131/
Grundregeln: keine Sonderzeichen, keine Leerzeichen, etc.

## Edgelist
from = ID des Knoten Mitglied  
to = ID des Knoten Mitgliedschaft  
relationship:  1 = zwischen zwei Personen 2=Person zu Organisation

## Nodelist
id = ID aus der Edgelist
name = Voller Name/Bezeichnung
type = Mensch oder Organisation
sector = 1= Adel
2= Dienstleister
3= Polizei
4= Militär
5= Politik
6= Kultur
7= Juristik
8= Wissenschaft 
