# Vprasanja in odgovori za spraševanje iz matematike 2024


## Osnovna raven

### 1. Izjavni račun

#### Kaj je izjava?
Je smiselna poved, kateri lahko določimo logično vrednost (0 ali 1).

#### Kaj je negacija dane izjave? Kdaj je negacija pravilna (resnična) in kdaj nepravilna (neresnična)?
Je nasprotna trditev dane izjave; negacija je pravilna, kadar je izjava, kki jo zanika nepravilna, in obratno.

#### Kaj je konjunkcija izjav? Napišite pravilnostno (resničnostno) tabelo za konjunkcijo.
Konjunkcija je operacija med dvema izjavama, ki je pravilna samo kadar sta obe izjavi pravilni.

A | B | A∧B
---|---|---
1 | 1 | 1
1 | 0 | 0
0 | 1 | 0
0 | 0 | 0

#### Kaj je disjunkcija izjav? Napišite pravilnostno (resničnostno) tabelo za disjunkcijo.
Disjunkcija je operacija med dvema izjavama, ki je pravilna kadar je vsaj ena izjava pravilna

A | B | A∨B
---|---|---
1 | 1 | 1
1 | 0 | 1
0 | 1 | 1
0 | 0 | 0

***
### 2. Izjavni račun

#### Kaj je tavtologija?
Tavtologija je izjava, ki je, vedno pravilna *(p ∨ ¬p)*.

#### Kaj je implikacija izjav? Napišite pravilnostno (resničnostno) tabelo za implikacijo.
Implikacija je operacija med dvema izjavama, ki je nepravilna samo kadar je prva vhodna izjava pravilna, druga pa nepravilna.

A | B | A=>∨B
---|---|---
1 | 1 | 1
1 | 0 | 0
0 | 1 | 1
0 | 0 | 1

#### Kaj je ekvivalenca izjav? Napišite pravilnostno (resničnostno) tabelo za ekvivalenco.
Ekvivalenca je operacija med izjavama, ki je pravilna samo kadar imata obe vhodni izjavi enako logično vrednost.

A | B | A<=>B
---|---|---
1 | 1 | 1
1 | 0 | 0
0 | 1 | 0
0 | 0 | 1

#### Povejte primer dveh izjav in ugotovite pravilnost (resničnost) njune ekvivalence.
**A: Nebo je modro.**
**B: Sonce je rumeno.**

A | B | A<=>B
---|---|---
1 | 1 | 1

***
### 3. Množice

#### Kaj je prazna množica in kaj univerzalna množica? w
Prazna množica je množica, ki ne vsebuje nobenega elementa, univezalna množica je množica vseh elementov s katerimi delamo. Moč množice nam pove koliko elementov vsebuje neka množica.

#### Kaj je razlika dveh množic? Kaj je komplement množice?
Razlika dveh množic *(A-B)* je množica, ki vsebuje elemente množice A, brez skupnih elementov množice B
Komplement množice *(A^c)* je množica, ki vsebuje vse elemente univerzalne množice, brez elementov množice A
Komplement množice je razlika med Univerzalno množico in množico A

#### Kaj je potenčna množica dane množice? Izberite množico z močjo 3 in zapišite njeno potenčno množico. 
Potenčna množica neke množice je množica, ki vsebuje vse njene podmnožice, vključno z množico samo ter prazno množico.
```
A = {1, 2, 3}
P(A) = {{}, {1}, {2}, {3}, {1, 2}, {1, 3}, {2, 3}, {1, 2, 3}}
```

***
### 4. Množice

#### Kdaj je množica A podmnožica množice ?B Kdaj sta množici enaki?
Množica A je podmnožica množice B, če je vsak element množice A hkrati tudi element množice B

#### Kaj je presek dveh množic? Kdaj sta množici disjunktni?
Presek dveh množic je množica, katere elementi so hkrati elementi množice A in množice B.
Množici sta disjunktni, če nimata skupnih elementov; njun prejek je enak 0.

#### Kaj je unija dveh množic? Kako izračunamo moč unije dveh množic?
Unija dveh množic je množica, katere elementi so elementi množice A ali množice B.
<br>
Moč unije dveh množic izračunamo tako, da od vsote moči obeh množic odštejemo moč njunega preseka.
<br>
***∣A∪B∣=∣A∣+∣B∣−∣A∩B∣***

#### Izberite taki množici A in B da je *m(A)=3* in *m(B)=2* Zapišite njun kartezični produkt.
```
A = {a, b, c}
B = {1, 2}
A×B={(a,1),(a,2),(b,1),(b,2),(c,1),(c,2)}
```

***
### 5. Naravna in cela števila

#### Opišite množici N in C in ju predstavite na številski premici.
Naravna števila so števila s katerimi štejemo, Cela števila so naravna št. z njihovimi nasprotnimi vrednostmi in 0.

#### Naštejte računske operacije v množici N.
Seštevanje – a + b = c
Množenje – a*b = c

#### Definirajte odštevanje v množici Z.
`a – b = a + (-b) = c`; prištevanje nasprotne vrednosti
####
* Komutativnost
* Distributivnost
    `a⋅(b+c)=(a⋅b)+(a⋅c)`
* Asociativnost
    `a+(b+c)=(a+b)+c`

***
### 6. Liha in soda tevila

#### Definirajte soda in liha števila.
Število je sodo kadar je deljivo s 2; Število je liho kadar ni sodo

#### Pokažite, da je vsota dveh lihih števil sodo število.
```
(2n+1)+(2n+3)= 2n+2n+1+3= 4n+4= 2-(2n + 2)
```

#### Pokažite, da je kvadrat lihega števila liho število.
```
(2n+1)² = 4n² + 4 + 1 = 2(2n² + 2)+1
```

***
### 7. Praštevila

#### Definirajte praštevila in sestavljena števila. Zapišite množico vseh praštevil, ki so manjša od 20.
Praštevila so števila, ki imajo natanko 2 delitelja, 1 in samega sebe; sestavljena števila so števila, ki imajo več 
deliteljev
```
Praštevila manjša od 20:
{2, 3, 5, 7, 11, 13, 17, 19}
```

#### Kaj je razcep naravnega števila na prafaktorje? Ali je razcep na prafaktorje enoličen? Koliko je praštevil?
Razcep števila na prafaktorje je postopek v katerem neko (sestavljeno) število zapišemo kot produkt praštevil.
<br>
Ja, razep na prafaktorje je enoličem
<br>
Prašteil je neskončno mnogo

#### Opišite enega izmed postopkov za preverjanje, ali je dano število praštevilo.

***
### 8. Deljivost

#### Kdaj je naravno število a večkratnik naravnega števila b?
Kadar obstaja N število `k`, da velja `b = a * k`

#### Definirajte relacijo deljivosti v množici N.
a deli b natank, če obsatja tako naravo število `k`, da velja a je enako b krat k
`a∣b∃k∈N:a=b⋅k`
#### Opišite tri lastnosti relacije deljivosti.

* Refleksivnost: `a | a`; a deli a
* Tranzitivnost: `a | b & b | c => a | c`; če a dei b in b deli c, potem a deli c
* Antisimetričnost: `a | b & b | a => a = b` če a deli b in b deli a, sta a in b enaka

#### Zapišite tri naravna števila a, b in c, večja od 10, da bo veljalo: a deli b in b ne deli c.
```
A = 12
B = 24
C = 11
```

***
### 9. Večkratniki in deljitelji

#### Definirajte največji skupni delitelj dveh naravnih števil. Razložite metodo za izračun največjega skupnega delitelja dveh naravnih števil. Kdaj sta si dve naravni števili tuji?
* Največji skupni delitelj - je največje naravno število, ki deli obe števili brez ostanka
* Metoda za izračun NSD: Evklidov algoritem
    ```
    1. Za števili a in b izračunamo ostanek pri deljenju a/b, označimo ga z r
    2. Zamenjamo a z b in b z r.
    3. Postopek ponavljamo dokler r ni enak 0
    4. Ko je r=0, je b največji skupni delitelj števil a in b.
    ```
* Števili sta si tuji če je njun največji skupni delitelj 1

#### Definirajte najmanjši skupni večkratnik dveh naravnih števil. Razložite metodo za izračun najmanjšega skupnega večkratnika dveh naravnih števil.
* Najmanjši skupni večkratnik dveh naravnih števil a in b je najmanjše naravno število, ki je deljivo tako z a kot tudi z b.
* izračun najmanjšega skupnega večkratnika:
    ```
    1. Števili a in b razcepimo na prafaktorje
    2. zapišemo vsak faktor z najvišjo potenco, s katero se število pojavi v enem od faktoriziranih števil
    3. Najmanjši skupni večkratnik je produkt teh faktorjev
    ```

#### Izberite različni naravni števili med 20 in 50. Določite njun največji skupni delitelj in najmanjši skupni večkratnik.
```
a = 24
b = 35
D = 1
v = 1680
```


***
### 10. Deljenje naravnih števil

#### Povejte osnovni izrek o deljenju naravnih števil.
`a=k⋅b+r`

#### Izberite naravno število med 5 in 10 ter naštejte elemente množice vseh ostankov pri deljenju z izbranim naravnim številom.

```
6
r₆ = {0, 1, 2, 3, 4, 5}
```

#### Naj bo `k` naravno število. Opišite množico vseh ostankov pri deljenju z naravnim številom `k`.
Moč množice je enaka `k`
Največji možen ostanek pri deljenju s številom `k` je `k-1`

***
### 11. Kriterij deljivosti

#### Za vsako izmed števil 2, 4, 8 navedite kriterij deljivosti s tem številom.
```
2: Število je sodo; zadnja števka števila je soda
4; Zadnji 2 števki števila sta deljivi s 4
8: Zadnje 3 Števke so deljive s 8
```

#### Navedite kriterij deljivosti s številom 3.
Vsota števk števila je deljiv s 3


#### Navedite kriterij deljivosti s številom 6.
Število je hkrati deljiv s 2 in s 3

#### Poiščite primer štirimestnega naravnega števila, ki je deljivo s 6.
`6000`

***
### 12. Ulomki in racionalna števila

#### Kaj je ulomek? Kdaj dva ulomka predstavljata isto racionalno število?
Ulomek je zapis števila oblike `a/b`; kjer sta `a` in `b` celi števili in`b≠0`

#### Pojasnite, kako ulomke seštevamo, odštevamo, množimo in delimo.
* Seštevamo: dva ulomka seštejemo tako, da ju razširimo na skupni imenovalec, števca seštejemo.
* Odštevamo: dva ulomka odštejemo tako, da ju razširimo na skupni imenovalec, števca odštejemo.
* Množimo: dva ulomka zmnožimo tako, da med sabo zmnožimo imenovalcca in števca.
* Delimo: dva ulomka delimo tako, da zmnožimo prvi ulomek z obratno vrednostjo dugega ulomka.

***
### 13. Ulomki in decimalni zapis

#### Kako iz decimalnega zapisa števila prepoznamo, da lahko to število zapišemo z ulomkom? Kako poljubnemu ulomku priredimo njegov decimalni zapis?

#### Kateri ulomki imajo končen decimalni zapis? Povejte primer ulomka, ki nima končnega decimalnega zapisa.
Končen decimalni zapis imajo tisit, katerih imenovalec je sestavljen iz prafaktorjev 2 in 5 <br>
Primer ulomka s neskončnim decimalnim zapisom: `1/3`

#### Povejte primer periodičnega decimalnega števila (z dolžino periode vsaj dva) in ga zapišite kot ulomek.
0.363636...
```
x = 0.363636... /*100
100x = 36.363636...
100x - x = 36.363636... - 0.363636...
99x = 36 /:99
x = 36/99
x = 4/11
```
***
### 14. Realna števila

#### Kdaj je realno število racionalno in kdaj iracionalno? Kako se razlikujeta njuna decimalna zapisa?
* Racionalno: število je racionalno, če ga lahko zapišemo kot ulomek `a/b`
* Irracionalno: število je ittacionalno, če ima neskončen, neperiodičen decimalni zapis
#### Povejte primer racionalnega števila in dva primera iracionalnih števil.
* Racionalno: 3.1
* Iracionalno: pi koren iz 2

#### Opišite konstrukcijo točke na številski premici, ki predstavlja vrednost ulomka `m/n`, `m<n`, kjer sta m in n naravni števili in je `n>2`.

***
### 15 Absolutna vrednost

#### Definirajte absolutno vrednost realnega števila in pojasnite njen geometrijski pomen.
Je razdalja med točko in koordinatnim izhodiščem.

#### Naj bosta a in b realni števili. Kaj predstavlja število `|b-a|`?
predstavlja absolutno vrednost razlike; predstavlja razdaljo med dvema točkama; oz. razdaljo med njunima projekcija.

#### Na številski premici pojasnite rešitev enačbe `|x| = a` kjer je a pozitivno realno število. Odgovor ponazorite s primerom.
`|x| = a` na številski premici predstavlja oddaljenost `x`-a od koordinatnega središča, torej `x = +- 3`

#### Naj bosta a in b realni števili. Primerjajte izraza `|a|+|b|` ter `|a+b|` Odgovor ponazorite s primeri.
Izraz `|a|+|b|` predstavlja skupno razdaljo med a in 0 in b in 0 <br>
izraz `|a+b|` pa meri razdaljo med vsoto a in ter 0

```
a = 2
b = -3
|a| + |b| = |2| + |-3| = 2 + 3 = 5
|a + b| = |2 + (-3)| = |2 - 3| = |-1| = 1
```

***
### 16. Kompleksna števila

#### Definirajte množico kompleksnih števil. Kako grafično upodobimo (predstavimo) kompleksna števila?
Množica kompleksnih števil se označuje s simbolom C in vključuje vsa števila oblike `a+bi`, kjer sta `a` in `b` realni števili, ter `i` imaginarna enota, za katero velja `i²=−1`. Tu je `a` realni del kompleksnega števila, `b` pa imaginarni del.

Kompleksna števila grafično predstavljamo na kompleksni ravnini, kjer je horizontalna os `(X)` realna os in vertikalna os `(Y)` imaginarna os.

#### Definirajte operacijo seštevanja v množici C. Opišite geometrijski pomen seštevanja kompleksnih števil.
z₁ + z₂ = (a₁ + a₂) + (b₁ + b₂)i

#### V kompleksni ravnini predstavite podmnožici kompleksnih števil `A = {z ∈ C; Im(z)= 2}` in `B = {z ∈ C; Im(z) = Re(z)}`
```
A = horizontalna črta pri Im = 2
B = črta pod kotom 45° v I. kvadrantu
```

***
### 17. Množenje kompleksih števil

#### Definirajte operacijo množenja v množici C. Zapišite primer

#### Opišite geometrijski pomen množenja kompleksnega števila s številom `-1` in geometrijski pomen množenja kompleksnega števila s pozitivnim realnim številom.

#### Naj bo `n` naravno število. Izračunajte i^n, kjer je n letošnja letnica.

#### Izberite kompleksno število `z = a + bi`, kjer sta `a` in `b` od nič različni realni števili, in izračunajte `z²`
***
### 18. Absolutna vrednost kompleksnega števila

#### Definirajte absolutno vrednost kompleksnega števila. Na primeru pokažite izračun absolutne vrednosti kompleksnega števila..

#### Na primeru izbranega števila `z = a + bi`, kjer je `a != 0` in `b != 0`, pokažite, da je `|2z| = 2|z|`

#### 

#### V kompleksni ravnini predstavite množico točk `{z ∈ C; |z| =< 3}`. Zapišite primer kompleksnega števila `z = a + bi` z te množice, kjer je `a` pozitivno, `b` pa negativno realno število.
***
### 19. Konjugirana vrednost kompleksnega števila

#### Definirajte konjugirano vrednostkompleksnega števila in razložite njen geometrijski pomen.

#### Dokažite, da je konjugirana vrednost vsote dveh kompleksnih števil enaka vsoti njunih konjugiranih vrednosti

#### Izberite kompleksno število `z = a + bi`, kjer sta `a` in `b` od nič različni realni števili, in izračunajte `z⁻¹`

***
### 20. Enačbe

#### Kaj je enačba in kaj je rešitev enačbe? Kdaj sta dve enačbi ekvivalentni (enakovredni)?

#### Opišite postopke, ki dano enačbo prevedejo v ekvivalentno enačbo

#### Kako rešimo sistem dveh linearnih enačb z dvema neznankama? Zapišite primer takega sistema in ga rešite.
 
***
### 21. Potence s celimi eksponenti

#### Definirajte potenco z naravnim in potenco s celim eksponentom.

#### Naštejte tri pravila za računanje s potencami s celimi eksponenti

#### Na primerih potenc s celii eksponeti pokažite uporabo dveh izmed zgornjih pravil

***
### 22. Koreni

#### Definirajte `n-ti √x` za poljubno naravno število `n`. Zakaj je pomembno, ali je `n` sodo ali liho število

#### Kako množimo korene z enakima in kako z različnima korenskima eksponentoma?

#### Kako korenimo produkt? Kako korenimo korene?

#### Racionlizirajte imenovalec ulomka `a/(a√b)`.

***
### 23. Potence z racionalnimi eksponenti

#### Definirajte potenco s pozitivnoosnovo in arcionalnim eksponntom.

#### Povejte tri pravila za računanje s takimi potencami.

#### Podajte primera dveh potenc z enakima osnovama in različnima pozitivnima racionalnima eksponentoma (ki nista celi števili) in izračunajte njun produkt. Izrazire ti dve potenci še kot korena in izračunajte njun produkt.

***
***
***
### 24. Premice

#### Definirajte vzporednost premic v ravnini.

#### Naštejte vse možne medsebojne lege dveh premic v ravnini.

#### aštejte dve lastnosti relacije vzporednosti premic v ravnini.

#### Povejte aksiom o vzporednici.
***
### 25. Koti

#### Pojasnite pojme ničelni, pravi, iztegnjeni in polni kot.

#### Poasnite pojma sokota in sovršna kota.

#### Kdaj je dani kot oster in kdaj top?

#### Kdaj sta kota komplementarna in kdaj suplementarna?
***
### 26. Koti

#### Definirajte kotno stopinjo, kotno minuto in kotno sekundo.

#### Definirajte radian.

#### Zapišite zvezo med stopinjami in radiani.

#### Koliko stopinj meri en radian?

#### oliko radianov merijo koti 30°, 45°, 60° in 90°?

#### Kdaj sta kota skladna?

***
### 27. Trikotnik

#### Definirajte trikotnik

#### Definirajte notranji in zunanji kot trikotnika

#### Kolikšna je vsota notranjih kotov trikotnika? Triditev dokažite.

#### Kolikšna je vsota zunanjih kotov trikotnika?

***
### 28. Zamenite točke trikotnika

#### Opišite konstrukcijo simetrale daljice in simetrale kota.

#### Kako poiščemo težišče trikotnika, središče trikotniku očrtane krožnice, središče trikotniku včrtane krožnice in višinsko točko?

***
### 29. Skladnost likov

#### Definirajte skladnost likov

#### Povejte štiri izreke o skladnosti triotnikov.

#### V paralelogramu narišemo obe diagonali. Koliko parov skladnih reikotnikov dobimo?

***
### 30. Podobnost likov

#### Definirajte podobnost likov.

#### Povejte tri izreke o podobnosti likov.

#### Trikotnika `ABC` in `A'B'C'` sta podobna. Stranica `AB` prvega trikotnika meri `c`, stranica `A'B'` drugega trikotnika pa meri `k⋅c`. Kolikšna sta obseg in ploščina trikotnika `A'B'C'`, če je `o` obseg trikotnika `ABC` in `S` ploščina trikotnika `ABC`?
