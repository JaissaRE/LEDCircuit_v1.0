# LEDCircuit_v1.0

## Descrizione
Circuito elettrico in serie, alimentato da una batteria da 9V.\
L'obiettivo principale di questo progetto è calcolare la resistenza necessaria per limitare il flusso di corrente elettrica che attraversa il LED, garantendone così il corretto funzionamento e prevenendo eventuali danni. 

**Legge di Ohm**
La Legge di Ohm descrive la relazione che c'è tra tensione, corrente e resistenza all'interno di un circuito elettrico.

**V= I⋅R**
dove: V è la tensione misurata in Volt (V), I è la corrente misurata in Ampere (A), R è la resistenza misurata in Ohm (Ω).

Per questo circuito c'è bisogno di calcolare la resistenza, dunque **R= V/I**.\
La tensione V si ottiene sottraendo alla tensione della sorgente la caduta di tensione sul LED\
**9-2= 7V**.\
Questo risultato va diviso per la corrente desiderara **I** di 20mA o 0,02A (valore scelto arbitrariamente poichè non in possesso di specifiche tecniche relative al LED)\
**7/0,02= 350Ω**


## Componenti Utilizzati
* LED rosso
* Batteria da 9V
* Connettore per batteria
* Breadboard
* Resistore da 330Ω
* 2 Resistori da 10Ω
   
## Schema Elettrico
![Schema Elettrico](https://github.com/JaissaRE/LEDCircuit_v1.0/blob/main/Images/Schematics.jpg?raw=true)

## Istruzioni per l'Assemblaggio
* Collegare il connettore ai poli della batteria ![step 1](https://github.com/JaissaRE/LEDCircuit_v1.0/blob/main/Images/Step_1.jpg?raw=true)
* Connettere in serie i 3 resistori ![step 2](https://github.com/JaissaRE/LEDCircuit_v1.0/blob/main/Images/Step_2.jpg?raw=true)
* Connettere il LED avendo cura di inserire l'anodo (polo positivo) e il catodo (polo poositivo) nei fori collegati rispettivamente ai poli positivo e negativo della batteria ![step 3](https://github.com/JaissaRE/LEDCircuit_v1.0/blob/main/Images/Step_3.jpg?raw=true)

## Risultati
![circuito in funzione](https://github.com/JaissaRE/LEDCircuit_v1.0/blob/main/Images/circuit.gif?raw=true)
## Link Utili
Per la parte teorica, mi sono basata sulle informazioni reperibili a questo link (https://www.progettiarduino.com/legge-di-ohm-tensione-corrente-e-resistenza.html) mentre per la realizzazione del circuito ho seguito questo tutorial (https://www.instructables.com/Basic-Electronics/)

## Conclusioni
