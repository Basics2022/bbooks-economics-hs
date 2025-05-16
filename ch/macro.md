(economics-hs:macro)=
# Introduzione alla macroeconomia

(economics-hs:macro:intro)=
## Introduzione
```{dropdown} Soggetti economici:
  individui, aziende, settore finanziario, governo, estero (five-sector **circular flow model**)

  I -> A: risorse (tempo, capacità) in cambio di reddito, spesa per prodotti
  I <- A: reddito per risorse, prodotti in cambio di denaro
  I -> F: risparmi
  I -> G: tasse
  I -> E: import
  A <- F: investimenti
  A <- G: spesa pubblica (parte, poiché parte rimane per spese dipendenti pubblici?)
  A <- E: export 

  Astrazione utile per misura PIL, riassunto dipendenze tra settori,...
```
```{dropdown} Misura dell'economia
- In termini di cosa si misura l'economia? In beni e servizi (no a illusioni monetaristiche)
```
```{dropdown} Moneta
- Con cosa si misura? Con un valuta (no a illusioni monetaristiche, caratteristiche valuta - il BTC ha queste caratteristiche?,...)
```
```{dropdown} ... 
```
```{dropdown} Storia del pensiero e delle teorie economiche
  - ...
  - classici del XVIII e XIX secolo:
    - A.Smith
    - Positivismo e utilitarismo: J.Bentham, D.Ricardo, J.Stuart Mill
    - ...
    - LSE
  - neoclassici:
    - anglo-american
    - ...
    - scuola di Vienna: von Hayek,...
    - ...
  - XX secolo:
    - Keynes
    - Chicago, M.Friedman
```

(economics-hs:macro:intro:econ-measure:gdp)=
### Misurazione dell'attività economica, PIL e PNL
Esistono 3 possibili definizioni equivalenti con 3 approcci differenti del PIL/PNL, come misura dell'attività economica in un determinato intervallo di tempo in una determinata zona:
1. produzione: valore aggiunto di tutto l'output (beni più servizi) prodotto 
2. reddito: reddito ottenuto dai produttori dell'output
3. spesa: spesa totale dei compratori dell'output

L'equivalenza dei 3 approcci viene rappresentata dall'**identità fondamentale della contabilità del reddito nazionale**

$$ \text{valore aggiunto totale} = \text{ricavo totale} = \text{spesa totale} $$

**todo** Differenze? Difficoltà di misura secondo i diversi approcci? Cosa non viene misurato

(economics-hs:macro:intro:econ-measure:gdp-gnp)=
### PIL, PNL e NFP
Il PIL (GDP) misura l'attività economica di tutti gli attori che hanno sede legale e fiscale entro i confini nazionali; il PNL(GNL) misura l'attività economica che produce output entro i confini nazionali. La differenza viene definita net factor payments from abroad, NFP, o net foreign factor income, NFFI,

$$\text{NFP} := \text{GDP} - \text{GNP}$$

Alcuni fattori che rendono GDP diverso da GNP sono aziende con produzione all'estero o lavoratori emigrati o immigrati che trasferiscono parte del reddito dentro o fuori i confini (rimesse)

(economics-hs:macro:intro:gdp)=
### Composizione del PIL

$$Y = C + I + G + NX + In$$ (eq:gdp:expenses)

Spese totali che formano il PIL, $Y$, sono di 4 tipi:
- $C$ consumi
- $I$ investimenti
- $G$ spesa governativa/pubblica
- $NX$ esportazione netta di beni e servizi all'estero
- $In$ scorte

```{admonition} Esportazione netta, $\ NX$
:class: tip

Nell'identità contabile {eq}`eq:gdp:expenses` del PIL tramite i consumi, il termine di bilancia commerciale $NX = X - M$, saldo tra esportazione $X$ e importazioni $M$, considera i consumi esteri $X$ dei prodotti nazionali e rimuove il termine di importazioni $M$, già considerato in termini di consumi $C$ e investimenti $I$, per non contarlo due volte.

Ad esempio, il ruolo del termine $-M$ nell'identità contabile {eq}`eq:gdp:expenses` viene discusso nell'[articolo](https://lavoce.info/archives/107719/le-importazioni-il-pil-e-gli-errori-di-misurazione/) abbastanza recente - 02/05/2025 - di T.Monacelli e R.Trezzi su lavoce.info, come chiarimento necessario per molti giornalisti o sedicenti esperti che si sono lanciati nel commento degli effetti dell'aumento di importazioni sul PIL negli Stati Uniti d'America, in seguito agli annunci di dazi.

```

```{note} Com'è composto il PIL nei diversi stati? Come si è evoluto negli anni?
```

(economics-hs:macro:intro:macro-vars)=
### Altre variabili macroeconomiche: PIL, tasso di disoccupazione, tasso di inflazione; legge di Okun e curva di Phillips

(economics-hs:macro:intro:macro-vars:inflation)=
#### Inflazione
**Price level.** Il livello dei prezzi traccia l'andamento di prezzo di un bene o servizio (o beni e servizi equivalenti) nel tempo. L'Inflazione è definita come l'aumento percentuale del livello dei prezzi. Esistono principalmente due misure del livello dei prezzi: il deflatore del PIL e il CPI. Non è detto che i due indici corrispondano: poiché il deflatore del PIL traccia l'andamento dei prezzi dei beni prodotti nell'economia, mentre il CPI traccia l'andamento dei prezzi dei beni acquistati dai consumatori in un'economia.

**Deflatore del PIL.** Nel periodo $t$, il deflatore del PIL è definito come il rapporto tra il PIL nominale e il PIL reale,

$$P_t = \frac{\$ Y_t}{Y_t} \ .$$

**CPI, Consumer Price Index.**

(economics-hs:macro:intro:macro-vars:okun)=
#### Legge di Okun
Relazione tra variazione percentuale dell'output e variazione percentuale della disoccupazione,

$$\frac{\bar{Y} - Y}{\bar{Y}} = c ( u - \bar{u} ) \ ,$$

con:
- $\bar{Y}$ output potenziale
- $Y$ output misurato
- $c$ costante di proporzionalità positiva. 
- $u$ tasso di disoccupazione
- $\bar{u}$ [tasso di disoccupazione naturale](economics-hs:macro:medium-run:unemployment:phillips)

$$\frac{\Delta Y}{Y} = k - c \Delta u \ .$$

Valori plausibili della retta di regressione sono $k \simeq 0.03$, $c \simeq -0.4$ (per quale economia in quale istante? US oggi?)

(economics-hs:macro:intro:macro-vars:phillips)=
#### Curva di Phillips

Vedi anche curva di Phillips nell'ambito del [mercato del lavoro nel medio periodo](economics-hs:macro:medium-run:unemployment:phillips).

(economics-hs:macro:intro:comparisons)=
### Confronti

(economics-hs:macro:intro:comparisons:time)=
#### Andamenti temporali

**Valori**
- **nominali**
- **reali**, inlfation-adjusted

**Variazioni**
- **congiunturale**: variazione rispetto al periodo precedende
- **tendenziale**: variazione rispetto allo stesso periodo dell'anno precedente

**Componenti di una time series.** Vengono riconosciute diverse componenti di una *time series*:
- $T$: *trend*
- $C$: *cyclical*, durata variabile e non nota, tipicamente più lenta e più ampia della variabilità stagionale (?)
- $S$: *seasonal*, durata fissa e nota
- $E$: *error*, o *irregular*

A seconda del fenomeno si possono utilizzare modelli additivi, $Y_t = T_t + C_t + S_t + E_t$, o moltiplicativa $Y_t = T_t \, C_t \, S_t \, E_t$

**Correzioni**
- effetti di calendario: numero di giorni lavorati, festività variabili, anno bisestile,...
- effetti di stagione:

(economics-hs:macro:intro:comparisons:space)=
#### Confronto di diverse regioni

**PPI**,...

(economics-hs:macro:short-run)=
## Il breve periodo
(economics-hs:macro:short-run:goods-market)=
### Il mercato dei beni

(economics-hs:macro:short-run:goods-market:y-z)=
#### Produzione = Domanda
Domanda di beni $Z$, offerta di beni $Y$

$$Z = C + I + G + \text{NX} - \text{In}$$

- Consumo $C$.
  - Dipende dal reddito disponibile $Y_d$, cioè del reddito al netto delle tasse $T$, $Y_d = Y - T$,
    
    $$C(Y_d)$$

  - $\partial_{Y_d} C > 0$

- Investimenti $I$, esclude inventario $\text{In}$ trattato a parte
- Spesa pubblica $G$, esclude trasferimenti poiché non sono acquisto di beni/servizi (ma fanno parte del reddito di altri attori economici)
- Export netto $\text{NX} = \text{Ex} - \text{Im}$
- Inventario $\text{In}$

**Equilibrio.** All'equilibrio di domanda e offerta di beni, $Y^* = Z(Y^*)$,

$$Y^* = C(Y-T) + I(Y^*,i) + G + \text{NX}$$ (eq:goods:zy)

**Approssimazioni.** Nel caso di funzione di consumo lineare con il reddito disponibili, $C = c_0 + c_1 (Y- T)$,

$$Z = c_0 + c_1 (Y-T) + I + G = \underbrace{c_0 + I + G - c_1 T}_{\text{autonomous spending}} + c_1 Y \ ,$$

si può ricavare in maniera esplicita l'output in funzione della tassazione, degli investimenti e della spesa pubblica, in condizioni di equilibrio $Y = Z$

$$Y^* = \frac{1}{1-c_1} \left[ c_0 + I + G - c_1 T \right] \ ,$$

e valutare le sensibilità di $Y$ a questi parametri/variabili. **todo** *bla bla sui moltiplicatori*

(economics-hs:macro:short-run:goods-market:i-s)=
#### Investimento = Risparmio

- Risparmio privato, $S = Y_d - C = Y - T - C$
- Risparmio pubblico, $S_{pub} = T - G$

al netto dell'import/export e dell'inventario, esplicitando il contributo degli investimenti $I$ dalla relazione produzione=domanda del PIL {eq}`eq:goods:zy`, si ottiene la relazione 

$$\begin{aligned}
  I & = Y - C - G = \\
    & = Y - C -  T + ( T - G ) = \\
    & = S + S_{pub} 
\end{aligned}$$ (eq:goods:is)

che prevede l'uguaglianza tra investimenti e risparmio (somma di privato e pubblico) in condizioni di equilibrio.

**Osservazione.** La decisione di consumo è la stessa decisione di risparmio, poiché $Y - T =: Y_d = C + S$

**Approssimazioni.** Nel caso di consumo lineare con il reddito disponibile,

$$S = Y - T - C = Y - T - c_0 - c_1 (Y - T) = - c_0 + (1 - c_1)(Y-T)$$

(economics-hs:macro:short-run:financial-market)=
### I mercati finanziari

Nell'ipotesi che ci siano solo due scelte possibili di impiego del patrimonio, liquidità (moneta in varie forme) e obbligazioni (che pagano interessi $i$). In quale proporzione conviene avere liquidità e obbligazioni? Dipende da: livello di transazioni (quanto denaro serve per le spese) e interessi sulle obbligazioni (quanto conviene avere bond, per godere di interessi).

#### Domanda di moneta
La domanda di moneta è la quantità di moneta necessaria principalmente per le transazioni all'interno di un'economia. E' ragionevole quindi assumere che la domanda di moneta $M^d$ sia proporzionale al reddito nominale $\$Y$ e sia funzione dei tassi di interesse $i$

$$M^d = \$ Y L(i) \ ,$$

con $L_{/i} < 0$ poiché risulta più conveniente avere 

**Osservazione.** [Ruolo delle aspettative sui tassi di interesse](economics-hs:macro:extra:expectations).

L'offerta di moneta $M^s$ è controllata dalla banca centrale della zona di interesse. All'**equilibrio**, l'offerta di moneta uguaglia la domanda di moneta, 

$\begin{aligned}
  M^s & = M^d \\
  M^s & = \$ Y L(i) \\
  M^s & = P Y L(i) \ ,
\end{aligned}$$

avendo indicato $Y$ l'output reale, $\$ Y$ l'output nominale e $P$ l'indice dei prezzi.

$$\frac{M}{P} = Y L(i)$$

### Determinazione del tasso di interesse
- politica monetaria, e opearazioni open-market
- economia con moneta nella forma di contanti e depositi: il ruolo delle banche come *intermediari finanziari*
  - Cosa fanno le banche: bilancio di CB e di B
    - B: ricevono soldi da risparmiatori; mantengono riserve (in liquidità e presso CB), per transazioni e per vincoli richiesti per solidità (reserve ratio); il resto può essere usato per prestiti (circa 70\% in quali paesi) e altri investimenti, tipicamente bond (30\%)

**todo**...

(economics-hs:macro:short-run:is-lm)=
### Il modello IS-LM
- Modello IS-LM in economoia chiusa e aperta
- Politiche economiche e fiscali
  - Trappola della liquidità

(economics-hs:macro:medium-run)=
## Il medio periodo

(economics-hs:macro:medium-run:jobs-market)=
### Il mercato del lavoro

(economics-hs:macro:medium-run:jobs-market:stats)=
```{dropdown} Misure nel mercato del lavoro
- Forza lavoro $L$, occupazione $N$, disoccupazione, $U$, tasso di disoccupazione $u$; ore lavorate;...

$$L = N + U$$

$$u := \frac{U}{L} = 1 - \frac{N}{L}$$

$$N = L (1 - u)$$

```

(economics-hs:macro:medium-run:jobs-market:wages)=
```{dropdown} Determinazione dei salari

$$W = P^e F(u,z)$$ (eq:wages-prices)

- $W$ livello nominale dei salari aggregati
- $P^e$ livelli di prezzo attesi (vedi [aspettative - prezzi](economics-hs:macro:extra:expectations)), poiché il lavoratore è interessato (o dovrebbe esserlo) alla retribuzione reale e non nominale
- $u$ tasso di disoccupazione
- $z$ variabile "catchall" che include tutti gli altri fattori che possono influenzare i salari; ad esempio protezione sociale per disoccupazione, inoccupazione

con:
- $\partial_u F < 0$, all'aumentare della disoccupazione diminuisce il potere contrattuale (aggregato) dei lavoratori 
- $\partial_z F > 0$ per definizione
```

```{dropdown} Determinazione dei prezzi

$$Y = A N$$

- $Y$ output, $\left[\$\right]$
- $N$ occupazione, $\left[\text{n. ore lavorate}\right]$ o altre [misure del lavoro](economics-hs:macro:medium-run:jobs-market:stats)
- $A$ produttività, $\left[\frac{\$}{\text{n. ore lavorate}}\right]$, o riferito a altre misure del lavoro; dipende dallo [sviluppo tecnologico](economics-hs:macro:long-run:progress) e influenza la crescita economica

Prezzi, in funzione del livello dei salari, del numero di dipendenti, del costo della materia prima, e del markup $m$ dell'azienda $\frac{\text{prezzo}}{\text{cost}}$, che dipende dal potere dell'azienda di fare il prezzo nel mercato. Nell'ipotesi che il costo della materia prima possa essere incorporato nel markup $m$, si può (*sì? in quali condizioni? ha senso nascondere il costo della materia prima nel markup? In generale non è detto che questo sia un effetto lineare con i salari...*)

$$P = (1+m) W$$ (eq:prices-wages)

```

Usando le due relazioni {eq}`eq:wages-prices`, {eq}`eq:prices-wages` si può determinare il punto di equilibrio in cui il valore del rapporto $\left(\frac{W}{P} \right)$ è uguale nella formazione dei salari e dei prezzi,

$$\begin{aligned}
 \left( \frac{W}{P} \right)_{\text{wages}} & = \left( \frac{W}{P} \right)_{{prices}} \\
 \frac{P^e}{P} F(u, z) & = \frac{1}{1+m} \\
\end{aligned}$$ (eq:wages-prices:equil)

da cui si ricava la definizione di **tasso di disoccupazione naturale**, $u_n$, come il tasso di disoccupazione per il quale è valida la condizione di equilibrio {eq}`eq:wages-prices:equil`, a condizioni fissate di $z$, $\frac{P^e}{P}$ (legata all'inflazione attesa), $m$.

**Influenza di $z$, $\pi$, $m$ sui salari reali $\frac{W}{P}$ e su tasso di disoccupazione naturale.**
...**todo**...

(economics-hs:macro:medium-run:as-ad)=
### Offerta e domanda aggregata: il modello AS-AD

**AS, Aggregate Supply.** Dalle relazioni per la formazione dei salari {eq}`eq:wages-prices` e dei prezzi {eq}`eq:prices-wages`, eliminando la variabile dei salari, $W$, ed usando la relazione tra tasso di disoccupazione e output

$$P = P^e (1+m) F(u,z) = P^e (1+m) \left( 1-\frac{Y}{A L}, z \right)$$ (eq:as)

Influenza dei parametri:
- $\partial_{P^e} P = (1+m) F(u,z) > 0$
- $\partial_{m} P = P^e F(u,z) > 0$
- $\partial_{z} P = P^e (1+m) \partial_z F > 0$
- $\partial_{Y} u = - \frac{1}{A L} < 0$, e quindi $\partial_Y P = - P^e (1+m) \frac{1}{AL} \partial_u F > 0$
- $\partial_{A} u = \frac{Y}{A^2 L} > 0$, e quindi $\partial_Y P = P^e (1+m) \frac{1}{A^2 L} \partial_u F < 0$

**AD, Aggregate Demand.** Dal [mercato dei beni](economics-hs:macro:short-run:goods-market), l'output dipende dal consumo (che a sua volta dipende dal reddito disponibile, $Y- T$), dagli investimenti (che dipendono dall'output e dai tassi di interesse) e dalla spesa pubblica, $Y = C(Y-T) + I(Y,i) + G + NX$. Dal [mercato finanziario](economics-hs:macro:short-run:financial-market), $\frac{M}{P} = Y L(i)$. Assumendo trascurabile il contributo dell'export netto, **todo**...

$$Y = Y\left(\frac{M}{P}, G, T \right)$$ (eq:ad)

Influenza dei parametri:
- ...

**Equilibrio nel corto e medio periodo.**



(economics-hs:macro:medium-run:unemployment:phillips)=
### Il tasso naturale di disoccupazione e la curva di Phillips


Vedi anche [Introduzione alla curva di Phillips](economics-hs:macro:intro:macro-vars:phillips)

**Tasso naturale di disoccupazione.**

### Inflazione, produzione e crescita della moneta

(economics-hs:macro:long-run)=
## Il lungo periodo
- Storia
(economics-hs:macro:long-run:savings)=
### Risparmio, accumulazione di capitale e produzione

(economics-hs:macro:long-run:progress)=
### Progresso tecnologico e crescita

L'output $Y$ risulta funzione dei capitali $K$ e del lavoro (nell'effetto combinato di occupazione, $N$, e produttività, $A$)

$$Y = Y(K,N,A) = Y(K, NA)$$ (eq:progress-output)

Il progresso tecnologico fa aumentare $A$. Si può riscrivere la relazione {eq}`eq:progress-output` in funzione di output e capitali per *lavoratore "effettivo"*, $AN$,

$$\frac{Y}{AN} = y \left( \frac{K}{NA} \right)$$

Se gli investimenti uguagliano i risparmi dei privati e il tasso di risparmio è costante, allora $I = S = s Y$. Dividendo per $AN$ si ottiene

$$\frac{I}{AN} = s \frac{Y}{AN}$$


(economics-hs:macro:extra)=
## Altro
(economics-hs:macro:extra:expectations)=
### Aspettative
- Tassi di interesse
- Mercati finanziari
- Consumo e investimento
- Produzione e politica economica
- [Salari](economics-hs:macro:medium-run:jobs-market:wages), il livello di prezzi attesi influenza la determinazione del livello dei salari,

  $$W = P^e F(u,z)$$

(economics-hs:macro:extra:open)=
### Economia aperta
- Domanda interna o estera
- Deprezzamento, bilancia commerciale e produzione
- Risparmio, investimento e disavanzo
- Politica economica in economia aperta
- Regimi di cambio: fissi o flessibili
(economics-hs:macro:extra:issues)=
### Patologie: crisi, elevato debito, iperinflazione
(economics-hs:macro:extra:policy)=
### Politica economica, monetaria e fiscale

## Basi
### Storia: dalla necessità nel commercio e la partita doppia agli strumenti attualmente presenti
### Concetti fondamentali e definizioni
- Moneta:
- Rimesse
- Variazione congiunturale (rispetto al periodo precendente), tendenziale (rispetto allo stesso periodo dell'anno precedente)

## Attualità
- Storia recente: Italia, Europa, US,...
- Dati della situazione attuale

## Riferimenti
- O.Blanchard, Macroeconomics
- O.Blanchard, A.Amighini, F.Giavazzi, Macroeconomia - Una prospettiva europea
- ...
