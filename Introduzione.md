# Segnali
## Cos'è un segnale
E' una **variazione** di grandezze fisiche nel dominio di rifermento, per esempio:
- radiazioni elettromagnetiche
- onde di pressione
- composti chimici volatili

## Obiettivo
L'obiettivo di un segnale è il **trasferimento di informazioni**, per questo le variazioni sono **imprevedibili** (stocastici), altrimenti quella trasmessa non sarebbe una vera informazione in quanto già nota

## Disturbi
Durante la propagazione al segnale si possono sommare altri segnali di disturbo causati da vari fenomeni, si dividono in:
- **rumori**: disturbi aleatori
- **interferenze**: causate da altre sorgenti di segnale
- **distorsioni**: alterazioni sistematiche (quindi prevedibili) causate dai sistemi fisici

## Elaborazione
I segnali possono appartenere a molti domini diversi, risulta pratico convertirli in grandezze elettriche
L'elaborazione si svolge in 3 fasi
1) Conversione attraverso l'uso di un **trasduttore** ($D\to E$)
2) Elaborazione con apparati elettrici ed elettronici ($E\to E$)
3) Opzionalmente conversione inversa ($E\to D$)

L'elaborazione **digitale** può sfruttare hardware general purpose e risultare quindi più economica
## Sistemi di elaborazione
I sistemi sono catene di elaborazione, possono estendere i segnali oltre ad alcune limitazioni fisiche

## Tipologie
Un segnale può essere:
- **scalare**: per ogni punto del dominio restituisce un unico valore
- **vettoriale**: restituisce più valori
- **monodimensionale**
- **multidimensionale**: più variabili
<div class="page-break" style="page-break-before: always;"></div>

Un segnale viene classificato secondo:
- **dominio**
	- continuo
	- discreto
- **ampiezza**, valore restituito per ogni punto del dominio
	- continua
	- discreta
- **periodicità**
	- periodico: $x(t)=x(t+kT),\;k\in \mathbb{N},\;T:\text{periodo}$
	- aperiodico: a durata limitata, smorzato, finestrato o impulso
	- pseudo-periodico
- **aleatorietà**
	- deterministico: definito a priori, generato o proveniente da una registrazione, utilizzato per valutare le prestazioni di un sistema
	- aleatorio: imprevedibile (stocastico), si può conoscere solo in modo statistico da una sua **realizzazione** (istanza del processo)


| Ampiezza\Dominio | Continuo                                       | Discreto                                    |
| ---------------- | ---------------------------------------------- | ------------------------------------------- |
| **Continua**     | Analogico<br>![analogico](analogico.png)       | Campionato<br>![campionato](campionato.png) |
| **Discreta**     | Quantizzato<br>![quantizzato](quantizzato.png) | Digitale<br>![digitale](digitale.png)       |
