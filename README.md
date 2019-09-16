# Arvutivorgud
Ott Kuulme: Võrgu testid
```
Lesson 1*    
   
printf --> Võimaldab sisestada teksti ning suudab eristada mõnda käsku - näiteks '\n', et tekst hakkaks (või läheks edasi) järgmiselt realt.  
nc --> Võimaldab internetiühenduste vahel andmete edastamise.  
Ctrl + D --> Disconnectib netcati portist. 
-l --> Suunab netcat-i kindlat port-i kuulama. 
Ping --> Annab võimaluse näha ühenduse võimalikkust sinu ja teise hosti vahel.  
| (pipe) --> Võimaldab outputi teise kohta paigaldada.   
> --> Võimaldab netcat-i käsu vastuse faili saata.  
```  
```  
Lesson 2*

dig --> Sarnaneb host-ile, kuid informatsiooni väljastab rohkem.
Ctrl + C --> Võimaldab lõpetada kindla protsessi, nagu näiteks ping, käsu.
host --> Sarnaneb DNS-ile, kuid tõlgib selle veebilehe sisse kirjutamisel IP-ks. 
```  
```  
Lesson 3*

Otsesed käsud puudusid. Märgin, mis meelde jäi - kokkuvõtvalt ei ole maailmas iga isiku jaoks IP aadresseid piisavalt, kuid sellele on juba lahendus olemas. 
Selleks on NAT-süsteem - ruuteril on privaatne IP aadress, mis jaotub kogu majapeale.
```  
```  
Lesson 4*

tcpdump --> Võimaldab DNS-i liiklust jälgida.
Samuti rääkis packetite vajalikkusest ning lähemalt, et kuidas need töötavad.
Pärast x aja möödumist katkeb ühendus juhul, kui üks pool teiselt vastust ei saa.
```  
```  
Lesson 5*

traceroute --> Näitab ette kõik enne läbitud IP-aadressid, milleni jõuti enne soovitud aadressile jõudmist.
Ruuterid ei ole suutelised (või võimelised?) suurtes kogustes packeteid korraga läbi laskma ning räägiti selle lahendusest.
Samuti oli jutt, et seadmetel on firewall, mis filtreerib seadme ja võrgu vahel toimuvat tegevust - vältides süsteemitõrkeid ning pahavara.
```  
```  
# Mida ma huvitavat teada sain:

- Kuidas timeout tekib.

- Juhul kui inimesed on NAT-iga eraldatud, saab neil olla sama IP-aadress.

- Lõpmatute loopide vältimiseks on packetitel limiteeritud eluaeg.

- Et eksisteerivad reserveeritud port-id (port-id 0-1023)
```  
