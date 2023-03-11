---
description: syntax - sintaksis, comments - túsindirme
---

# SYNTAX, COMMENTS

## SYNTAX

Sintaksis penen mekteptegi ana tili sabaqlıģında tanısqan edik, "Sintaksiste sóz dizbegi, gáplerdiń dúzilisi hám túrleri, gáp aģzaları úyreniledi. Sóz dizbekleri de, gápler de sózlerden jasaladı, bıraq sózler qalay bolsa solay gáp dúze bermeydi..." - muģallimlerimiz usıģan uqsas gápler menen túsindirgen edi (bunıń ushın olarģa raxmet). Eger joqardaģı anıqlamanı túsinbegen bolsańız ziyanı joq, elede ápiwayıraq etip túsindiremen. Bıraq onnan aldın meniń bir buyrıģımdı orınlań. Buyrıq tómendegishe**:** aldırıp márte al kózińdi bir jaqsılap dem.

Úlken itimal menen siz ele buyrıqtı orınlamadıńız. Sebebi bergen buyrıģım sintaksis normaları boyınsha jazılmaģan. Negezinde buyrıq, "kózińdi bir márte jaqsılap dem aldırıp al" bolıwı kerek edi. Kórip turģanıńızday gápler mánige iye bolıwı ushın sintaksiske ámel etken xalda dúziliwi kerek. Sintaksiske ámel etilmese ne bolatuģınlıģın kórdińiz.

Programmalastırıw tilleri de, bir til. Onıńda ózine jarasa nısamları bar. Programmalastırıw tilinen paydalanıp kompyuterge buyrıq beriwdi qáleseńiz, tildiń nızamlarına ámel etken xalda kod jazıwıńızģa tuwrı keledi. Eger nızamdı buzatuģın bolsańız kompyuter siz bergen buyrıqtı orınlamastan, **SyntaxError** xabarın jiberedi.

Mısal ushın, tómendegi kod arqalı biz kompyuterge "_`Sálem, Álem` sózin ekranģa shıģar_" degen buyrıqtı berip atırmız.

```python
print("Sálem, Álem")
```

Nátije: `Sálem, Álem`

Kodımızdı sintaksis nızamların buzbaģan xalda jazģanımız ushın Python bizdiń buyrıģımızdı orınladı. Eger tómendegi sıyaqlı nızamdı buzatuģın bolsaq, kompyuter biz kútken nátijeni bermeydi.

```python
print("Sálem, Álem)
```

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Nátije: `SyntaxError: incomplete input`

Hár dayım sintaksisti buzģan waqtımızda **SyntaxError** qáteligi kórsetiledi. Mısal ushın, kereksiz jerge qoyılģan noqat, vergul yamasa bos orın (пробел), sonıń menen birge belgili funkciyalar atın qáte jazıw (`print()` ornına `prit()`), ashılmay yamasa jawılmay qalģan qawsırmalar, qalıp ketken gilt sóz (keyword) sıyaqlılar da SyntaxError esaplanadı.

SyntaxError eń kóp ushraytuģın qátelik bolıp, Python bunday qáteligi bar programmalardı orınlamaydı. Biz sabaqlarımız dawamında, ornı kelgende basqada sintaksis nızamları haqqında aytıp ótemiz!

## COMMENTS

Túsindirme, orıssha aytqanda комментарии. Programmalastırıwda túsindirmeler biz jazģan kodımızdıń itibarģa alınbay ketetuģın bólegi bolıp esaplanadı yaģıniy túsindirmelerdi kompyuter oqımaydı. Olar bizge yaģıniy programmistlerge bir nárseni túsindiriw yamasa esletip turıw ushın isletiledi.&#x20;

Python tilinde túsindirmeler hash (`#`) simbolı arqalı jaratıladı. Pyhon, hash simbolı qoyılģan jerden baslap qatar aqırına deyingi hámme nárseni itibarsız qaldıradı. Mısal ushın:

```python
# Tómendegi kod, Sálem Álem sózin konsolge shıģaradı.
print("Sálem Álem")
print(12 * 8) # 12ni 8ge kóbeytiwden payda bolģan nátijeni konsolge shıģaradı.
# print("Python")     
```

```python
"""
Usılay etipte
kóp qatarlı túsindirmelerdi
jazıw múmkin.

Qaysı usıl sizge qolay bolsa, sonnan paydalansańız boladı.
"""
print("Sálem Álem")
```

## ÁMELIYAT

Tómendegi kodlardıń nátijesi qanday bolıwın, programmanı iske túsirmey turıp oylanıp kóriń:

```python
print "Assalawma aleykum"
```

```python
print("Assalawma aleykum")
```

```
print('Assalawma aleykum')
```

```python
print('Assalawma aleykum")
```

```python
print.('Assalawma aleykum')
```

```python
print("Sálem")
# print("Hello World")
print("Álem")
```
