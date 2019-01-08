# Postgres
- Coneixeu què és una Plataforma de Servei( Paas) al núvol ? Expliqueu breument el concepte i la utilitat:
  - En aquest model, el proveïdor ofereix la xarxa, els servidors, l'emmagatzematge, aplicacions, repositoris, i en definitiva tot el que calgui per a poder hostetjar les aplicacions i serveis creats per als clients.
- Ens centrarem en la Plataforma Heroku ja que té un pla gratuït que només cal registar-se i és una de les plataformes més utilitzades darrere de AWS i Google App Engine. A més te suport per les bases de dades Postgres. Expliqueu característiques i beneficis de la plataforma Heroku.
  - Permet crear bases de dades compatibles amb postgres.
- Creem la nostra base de dades amb heroku
  
  ![](imatges/1.PNG) 

-Instal·lem el pgAdmin3 (amb windows ja ve el 4) i connectem la nostra base de dades amb pgAdmin, posant els credencials de la nostra base de dades al pgadmin
![](imatges/2.PNG) 

## Carregar un Fixter sql

![](imatges/7.PNG)

- Per què seveix la instrucció \! pwd ? Per que pot ser útil ?
  - Serveix per saber en quin directori estas treballant actualment
-   Executeu l’ordre i expliqeu el significat de cada variable.
-   \echo :DBNAME :ENCODING :HOST :PORT :USER ;
  
  ![](imatges/8.PNG)

  Nom de la base de dades, la codificació, el host, el port i l'usuari.

  - Mitjançant ordre \o: indicant la sortida de sentències d’ara endavant. ( tornar a
executar \o per la sortida estandar)

![](imatges/9.PNG)

- Especificar formats de sortida amb l’ordre pset. Els formats de sortida són aligned,
unaligned, html i làtex ( especial interès aquests dos darrers).

![](imatges/10.PNG)

- Combinar els apartats anteriors. Canviant format de sortida i
sortida.

![](imatges/11.PNG)

- Per que serveixen les orders ( des de consola de postgres):
\l: serveix per llistar totes les bases de dades
![](imatges/12.PNG)
\d : Ficar només \d i \d nom_taula ( ex: proveidors).L 'ordre \d és útil per
mostrar informació sobre l'SGBD: taules, índexs,

![](imatges/13.PNG)
- Creeu una base de dades nova : provaAlmata.

  ![](imatges/14.PNG)
- Us podeu conectar des de consola a la nova base de dades.
\c provaAlmata
![](imatges/15.PNG)
- Mireu els usuaris : \du. Quin son ? Tenen alguna similitut amb els
vostres usuaris de la vostra base de dades

![](imatges/16.PNG)

- Torneu a la vostra base de dades
  
![](imatges/ultima.PNG)

1 – En un entorn Windows ( ja sigui el vostre ordinador o una màquina virtual amb qualsevol
sistema Windows ): Aneu a la secció Downloads i seguiu les instruccions. Un cop instal.lat
connecteu a la vostra Base de Dades Heroku. Mirar les taules i executeu algún script.
![](imatges/3.PNG)
![](imatges/4.PNG)
I ens connectem a la nostra base de dades heroku
 ![](imatges/2.PNG) 

Aqui ja pordem veure la nostra base de dades

![](imatges/5.PNG)

Creem un script

![](imatges/6.PNG)