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

### PIL, PNL e NFP
Il PIL (GDP) misura l'attività economica di tutti gli attori che hanno sede legale e fiscale entro i confini nazionali; il PNL(GNL) misura l'attività economica che produce output entro i confini nazionali. La differenza viene definita net factor payments from abroad, NFP, o net foreign factor income, NFFI,

$$\text{NFP} := \text{GDP} - \text{GNP}$$

Alcuni fattori che rendono GDP diverso da GNP sono aziende con produzione all'estero o lavoratori emigrati o immigrati che trasferiscono parte del reddito dentro o fuori i confini (rimesse)

(economics-hs:macro:intro:gdp)=
### Composizione del PIL

$$Y = C + I + G + NX$$

Spese totali che formano il PIL, $Y$, sono di 4 tipi:
- $C$ consumi
- $I$ investimenti
- $G$ spesa governativa/pubblica
- $NX$ esportazione netta di beni e servizi all'estero

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

(economics-hs:macro:short-run)=
## Il breve periodo
(economics-hs:macro:short-run:goods-market)=
### Il mercato dei beni
(economics-hs:macro:short-run:financial-market)=
### I mercati finanziari
(economics-hs:macro:short-run:is-lm)=
### Il modello IS-LM
- Modello IS-LM in economoia chiusa e aperta
- Politiche economiche e fiscali
  - Trappola della liquidità

(economics-hs:macro:medium-run)=
## Il medio periodo

(economics-hs:macro:medium-run:jobs-market)=
### Il mercato del lavoro

#### Definizioni e statistiche
- Forza lavoro, occupazione, disoccupazione; ore lavorate;

(economics-hs:macro:medium-run:jobs-market:wages)=
```{dropdown} Determinazione dei salari

$$W = P^e F(u,z)$$

- $W$ livello nominale dei salari aggregati
- $P^e$ livelli di prezzo attesi (vedi [aspettative - prezzi](economics-hs:macro:extra:expectations)), poiché il lavoratore è interessato (o dovrebbe esserlo) alla retribuzione reale e non nominale
- $u$ tasso di disoccupazione
- $z$ variabile "catchall" che include tutti gli altri fattori che possono influenzare i salari

con:
- $\partial_u F < 0$, all'aumentare della disoccupazione diminuisce il potere contrattuale (aggregato) dei lavoratori 
- $\partial_z F > 0$ per definizione
```

```{dropdown} Determinazione dei prezzi

```

(economics-hs:macro:medium-run:as-ad)=
### Offerta e domanda aggregata: il modello AS-AD

(economics-hs:macro:medium-run:unemployment:phillips)=
### Il tasso naturale di disoccupazione e la curva di Phillips


Vedi anche [Introduzione alla curva di Phillips](economics-hs:macro:intro:macro-vars:phillips)

**Tasso naturale di disoccupazione.**

### Inflazione, produzione e crescita della moneta

(economics-hs:macro:long-run)=
## Il lungo periodo
- Storia
- Risparmio, accumulazione di capitale e produzione
- Progresso tecnologico e crescita

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
