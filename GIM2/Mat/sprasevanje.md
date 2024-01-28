# Vprasanja in odgovori a spraševanje iz matematike 2024


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
