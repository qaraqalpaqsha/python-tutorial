# PRINT, ARITHMETIC OPERATORS

HELLO WORLD sabaģımız aqırında bir neshe kodlardı jazıp kóriwdi waziypa etip bergen edik. Keliń sol kodlardıń nátijesin kóremiz:

```python
print("Assalawma Aleykum")
```

Nátije: `Assalawma Aleykum`

Kútgenimizdey, joqardaģı kod Assalawma Aleykum tekstin konsolde kórsetti. Keliń endi keyingi kod nátijesin kóremiz:

```python
print(Qayırlı tań)
```

Bul rette Qayırlı tań jazıwınıń ornına, **SyntaxError** (sintaksiste qátelik) xabarı shıqtı. Qátelik qay jerde?

`print()` funkciyası tekst yamasa ańlatpalardı konsolge shıģarıw waziypasın atqaradı. Bıraq bul funkciya tuwrı islewi ushın bir neshe qaģıydalarģa ámel qılıw kerek. Atap aytqanda, eger konsolge tekst shıģarajaq bolsaq, tekstimiz tırnaqsha (" ") yamasa apostrof (' ') arasında jazılıwı kerek. Sonday eken Qayırlı tań sózin konsolģa shıģarıw ushın tuwrı kod:

```python
print("Qayırlı tań")
```

yamasa

```python
print('Qayırlı tań')
```

boladı.

Nátije: `Qayırlı tań`

Qostırnaq yamasa birtırnaq isletiwdiń abzallıqlarınan biri, eger siz shıģarıwdı qálegen tekstte ekewinen biri qatnasatuģın bolsa, `print()` funkciyasında ekinshisinen paydalanasız. Keliń tómendegi mısaldı kóremiz:

```python
print('Men "Qaraqalpaqnama" shıģarmasın jaqsı kóremen.')
```

Nátije: `Men "Qaraqalpaqnama" shıģarmasın jaqsı kóremen.`

Joqardaģı tekstte `"Qaraqalpaqnama"` sózin tırnaqshadan ishinde edi. Bul tekstti konsolge shıģarıw ushın bolsa, print() funkciyasında tekstti apostrof ishine aldıq.

Eger tekstti bir neshe qatarģa bólip jazıwģa tuwrı kelip qalsa, úshewlik tırnaqsha (""" """) yamasa apostroftan (''' ''') paydalanıwımız múmkin:

```python
print('''Aqılı kámil ilimi zor,
Bilimli el bolmaydı xor.''')
```

Nátije:

`Aqılı kámil ilimi zor,`&#x20;

`Bilimli el bolmaydı xor.`

Jáne bir mısal kóreyik, biz dúzgen programma `"My name is Turdıbek, I'm a student"` sózin konsolge shıģarsın. Bıraq abaylı bolıw kerek, eger biz `print()` funkciyasında apostroftan paydalanatuģın bolsaq qátelik shıģıwı múmkin. Sebebi, `I'm` sózinde apostrof bar. Joqarda da aytılģan edi, eger shıģarlıwı kerek bolģan tekstte apostrof yamasa qostırnaq, ekewiniń biri bar bolsa `print()` funkciyasında ekinshisinen paydalanıwımız degen edik.&#x20;

Bıraq bizde jáne bir usıl bar, eger teksttegi apostroflar aldına `\` belgisin qoysaq. Biz qáteliktiń aldın alamız:

```python
print('My name is Turdıbek, I\'m a student')
```

Nátije: `My name is Turdıbek, I'm a student`

Joqardaģı kodımızģa itibar bergen bolsańız "I'm" sózi `I\'m` kóriniste jazılģan jazılģan. Ulıwma alģanda `\` belgisi hár qanday arnawlı belgiler aldına qoyıladı.

Keliń bir eki arnawlı belgilerdi kórip shıģamız:

| Kod  | Nátije    | Mısal                   |
| ---- | --------- | ----------------------- |
| \n   | New line  | print("Hello \nWorld")  |
| \t   | Tab       | print("\tGood morning") |
| \b   | Backspace | print("Hello, \bWorld") |
| \\\\ | Backslash | print("A \\\ B")        |

## ARIFMETIK ÁMELLER

`print()` funkciyası tek ģana tekstlerdi emes, hár túrli ańlatpalardı da konsolģa shıģaradı. Máselen:

```python
print(2+2*2)
```

Nátije: `6`

&#x20;Python arifmetik ámellerdi orınlawda Matematika qaģıydalarına ámel etedi:

* Qawsırma ishindegi ámeller qawsırma sırtındaģılardan aldın orınlanadı
* Dárejege kóteriw (koren shıģarıw), kóbeytiw hám bóliw aldın orınlanadı
* Kóbeytiw hám bóliw, qosıw hám alıwdan aldın orınlanadı
* Basqa jaģdaylarda ańlatpalar shepten ońģa qaray orınlanadı

Joqardaģı mısalda da aldın kóbeytiw (`2*2=4`), keyin qosıw ámeli (`4+2=6`) orınlanadı.

```python
print(10/4)
```

Nátije: `0.25`

Kórip turģanıńızday `/` belgisi bóliw ámelin orınlaydı hám nátije hár dayım bólshek san kórinisinde boladı (eger bóliw nátijesinde pútin san payda bolsa da):

```python
print(12/4)
```

Nátije: `3.0`

Bóliw ámelinen pútin san kórinisindegi nátije alıw ushın `//` belgisinen paydalanamız:

```python
print(12//4)
```

Nátije: `3`

Dawam etemiz...

```python
print(5**2)
```

Nátije: `25`

Joqardaģı `**` belgisi dárejege kóteriwdi ańlatadı, yaģıniy `5**2` ańlatpası 5 tiń 2-dárejesin beredi.

Pythondaģı ápiwayı arifmetik ámeller tómendegi kestede berilgen:

| Operator | Xarekteristika                | Mısal        |
| -------- | ----------------------------- | ------------ |
| +        | Qosıw                         | 4+3=7        |
| -        | Alıw                          | 7-3=4        |
| \*       | Kóbeytiw                      | 2\*3=6       |
| /        | Bóliw                         | 10/2=5.0     |
| //       | Bóliw hám pútin bólegin alıw  | 5//6=0       |
| %        | Bóliw hám qaldıq bólegin alıw | 10%3=1       |
| \*\*     | Exponenta (dáreje/koren)      | 2\*\*10=1024 |

`print()` járdeminde tekst hám ańlatpanı birge shıģarıwģa da boladı. Bunıń ushın hár bir ańlatpa hám tekst vergul (`,`) menen ajratıladı:

```python
print("Tórttiń kvadratı", 4**2, "ģa teń")
```

Nátije: `Tórttiń kvadratı 16 ģa teń`

## ÁMELIYAT

Tómendegi mısallardı Python járdeminde shıģarıń. Hár bir másele tekstin túsindirme kórinsinde jazıp qoyıń:

Juwaplar tómendegishe bolıwı kerek:

1. 5 tiń 4-dárejesin esaplań
2. 99 dı 4 ge bólgende neshe qaldıq qalatuģınlıģın esaplań
3. 3 tiń kvadratı hám 4 tiń kubınıń qosındısın esaplań
4. 144 ten koren neshe shıģatuģınlıģın esaplań
5. 2 niń 4-dárejesinen alınģan korendi esaplań

Kodıńızdı tómendegishe jazıń hám saqlap qoyıń:

```python
# 5 tiń 4-dárejesin esaplań
print(5**4)
```

Juwaplar tómendegishe bolıwı kerek:

<figure><img src="../../../.gitbook/assets/image (1) (3).png" alt=""><figcaption></figcaption></figure>
