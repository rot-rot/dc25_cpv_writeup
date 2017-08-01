# DEF CON 25 Crypto and Privacy Village Contest
Won by team rot(rot(λ)):
[CryptoK](https://twitter.com/0xF0unD)
[elegin](https://twitter.com/aaronsteimle)
[Jabroni](https://twitter.com)
[llamaprincess](https://twitter.com/_llamaprincess)
[pseudoku](https://twitter.com/_pseudoku)
[zevlag](https://twitter.com/zevlag)

## Write-up
WIP

[Original Contest Website](http://goldbug.cryptovillage.org/tgbr/)

### iOS
tl;dr flag= SQUIDS

#### The Puzzle
```
1. JK EJRN☆U. I☆T G☆ NRFJNUC QJ QTLU NUEJNC UVUNY 
   QNTI☆TQDTIQGE QUDULSJIU EJIVUN☆TQGJI. FTYHU QSUY'C 
   NUEJNCUC QSG☆ ☆U☆☆GJI.
2. WO HJIBSJP HNIY MPO☆TOIUBOQ. WO GBQSOI NGWNYQ. UNHO 
   N VJBUO, JTS JM SCO ENEOG JM SJIATOQ, QKONFBIA SJ 
   TQ. BS KGNYOR TQ N HBACSY RTE.
3. IUIMYFCI WTP PIEMIQP. DQ'P ASPQ T BTQQIM FR RDCGDCL 
   F☆Q VWTQ QWIY TMI.
4. SHB ☆GMKPSLJS SH☆JO LIKUS QBTUP☆SY QYQSBGQ ☆QJ'S 
   HKW SHBY WKPD, ☆S'Q HKW SHBY RL☆F.
5. MGV DGFN ☆G XGS VCFQ QMTLT ETLLCNTL QG KTECIF 
   LTYKTQ? ... I VCFQ QMTE QG KTECIF LTYKTQ OGK CL 
   DGFN CL ETF CKT YCHCRDT GO TUID.
6. OH XDQ VNCP PD RGGJ N ☆GELGP, XDQ BQ☆P NA☆D FOTG 
   OP HLDB XDQL☆GAH.
```
#### Solution
This puzzle was a classic substitution cipher with a twist.
1. A ☆ is used instead of a character.
2. Each line does not share the same substitution.

Solving the substitution yields
```
1. OF COURSE. NSA IS RUMORED TO TAPE RECORD EVERY 
   TRANSATLANTIC TELEPHONE CONVERSATION. MAYBE THEY'D 
   RECORDED THIS SESSION.
2. WE MONITOR MANY FREQUENCIES. WE LISTEN ALWAYS. CAME 
   A VOICE, OUT OF THE BABEL OF TONGUES, SPEAKING TO 
   US. IT PLAYED US A MIGHTY DUB.
3. EVERYONE HAS SECRETS. IT'S JUST A MATTER OF FINDING 
   OUT WHAT THEY ARE.
4. THE IMPORTANT THING ABOUT SECURITY SYSTEMS ISN'T 
   HOW THEY WORK, IT'S HOW THEY FAIL.
5. HOW LONG DO YOU WANT THESE MESSAGES TO REMAIN 
   SECRET? ... I WANT THEM TO REMAIN SECRET FOR AS 
   LONG AS MEN ARE CAPABLE OF EVIL.
6. IF YOU WANT TO KEEP A SECRET, YOU MUST ALSO HIDE 
   IT FROM YOURSELF.
```

Take what each ☆ represents and putting them all together yields the flag **SQUIDS**

### ColecoVision
tl;dr flag= LADYBUG

#### The Puzzle
<img src="colecovisionpuzz.png" width="200">

#### Solution
This puzzle was a straightforward usage of [ITA2 (Baudot) code](https://en.wikipedia.org/wiki/Baudot_code#ITA2) in the 543.21 format.

Decoding the image yields the flag **LADYBUG**

### ZXSpectrum
tl;dr flag= WRIGGLER

#### The Puzzle
<img src="ZXSpectrum.png" width="400">

#### Solution
            3 TREA cMXuQ=CHE RYO
66T =FIM vfAGES tA8PAINT
KERSL p76 ASTN X AMEAL B7hLCAPS
Ceci n’est pas un labyrinthe.
                                                                                        http://aesencryption.net/


### Atari 2600
tl;dr flag= CENTIPEDE

Find 3 of each:
Countries
Countries’ capital cities
Dog breeds
Elements
Pasta shapes
Plants or trees
Semi-precious stones
US states
Vegetables

Find 3 of each:
Countries [R]
Oman - RMAN
Rwanda - RWANDA
Timor-Leste - RIMOR LESTE
Countries’ capital cities [V]
Ottowa - VTTAWA
Riyadh - VIYADH
Tbilisi - VBILISI
Dog breeds [C]
Otter Hound - CTTER HOUND
Rottweiler - COTTWEILER
Terrier - CERRIER
Elements [P]
Oxygen - PXYGEN
Radium - PADIUM
Titanium - PITANIUM
Pasta shapes [G]
Orecchiette - GROCCHIETTE
Rigatoni - GIGATONI
Tagliatelli - GAGLIATELLI
Plants or trees [A]
Oleander - ALEANDER
Rhododendron - AHODODENDRON
Teak - AEAK
Semi-precious stones [R]
Onyx - RNYX
Ruby - RUBY
Topaz - ROPAZ
US states [R]
Oklahoma - RKLAHOMA
Rhode Island - RHODE ISLAND
Texas - REXAS
Vegetables [Q]
Onion = QNION
Rutabega - QUTABEGA
Turnip - QURNIP
	

“ORDER TRIOS ALPHABETICALLY BY FIRST ITEM”

PRAVGCRQR

Rot13 → CENTIPEDE

Solution: CENTIPEDE

### Nintendo 64
tl;dr flag= BUCKBUMBLE

### Apple II
tl;dr flag= DUNGBEETLES

### Game Boy
tl;dr flag= YARS'REVENGE

### Playstation 2
tl;dr flag= EXTERMINATION

### META puzzle
tl;dr flag= QUINCUNX
Solutions:
SQUIDS
LADYBUG
WRIGGLER
CENTIPEDE
BUCKBUMBLE
DUNGBEETLES
YARS’REVENGE
EXTERMINATION

Key: 2 6 3 3 3 2 10 2 < Check this > checked

Meta-Solution: QUINCUNX
