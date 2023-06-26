# STRINGS

**STRING** (tekst) - Pythondaģı eń kóp qollanılatuģın maģlıwmat túrlerinen biri. Ózgeriwshige tekstlerdi saqlaw ushın tekst qostırnaq (`" "`)yamasa apostrof (`' '`) ishinde jazılıwı kerek.\\

```python
city = 'Nukus'
nation = "Karakalpak"
```

## KÓP QATARLÍ STRING

Saqlanıwı kerek bolģan tekst bir neshe qatardan ibarat bolsa úsh qostırnaq yamasa úsh apostroftan paydalanıladı.

```python
text = """
Ana tilim, júregiseń anamnıń.
Júrek ana, men ózińnen jaraldım,
Qásiyetli tilim barda sayrap turǵan,
Babalardıń quwaman keyingi ármanın.

Ana tili millettiń tili, qádirlim,
Tilsiz jerde, el sońında súrindim.
Til bolmasa tirishiliktiń joqdur mánisi,
Tilim barda aytılar sır kewlimdegi.
"""
```

## STRING ÚTINDE ÁMELLER

#### Tekstlerdi birlestiriw (`+`)

Tekstlerdi qosıw ushın `+` operatorınan paydalanamız:

```python
name = 'Rasul'
print("Meniń atım " + name)
```

Nátije: `Meniń atım Rasul`

```python
name = "Ibrayım"
l_name = "Yusupov"
print(name + l_name)
```

Nátije: `IbrayımYusupov`

Joqardaǵı kodımızda atı hám familiyası birigip jazılıp qaldı, olardı ajratıp jazıw ushın arasına boslıq belgisin qosıp ketemiz. Úshinshi qatardaǵı kodtı tómendegishe ózgertemiz:

```python
name = "Ibrayım"
l_name = "Yusupov"
print(name + " " + l_name)
```

Nátije: `Ibrayım Yusupov`

### f-string

Eki hám odan kóp ózgeriwshilerdi tekstke biriktiriw ushın f-string usılınan paydalanamız:

```python
name = 'Ibrayım'
l_name = 'Yusupov'
full_name = f'{name} {l_name}'
print(full_name)
```

Bul usıl járdeminde uzın tekstlerdi de jasaw múmkin.

```python
name = "Elbrus"
lastname = "Sársenbaev"
print(f"Sálem, meniń atım {name} familiyam {lastname}.")
```

Nátije: `Sálem, meniń atım Elbrus familiyam Sársenbaev.`

### &#x20;Arnawlı belgiler

Tekske boslıq qosıw ushın `\t` belgisinen, taza qatardan baslaw ushın `\n` belgisinen paydalanamız:

```python
print('Hello Wordl!')
print('Hello \tWorld!')
print('Hello \nWorld!')
```

Nátije:

`Hello World!`&#x20;

`Hello    World!`&#x20;

`Hello`&#x20;

`World!`

## STRING METODLARÍ

Pythonda tekstler ústinde orınlaw múmkin bolǵan tayyar ámeller toplamı bar. Bunday ámeller toplamı **metodlar** dep ataladı

Metodlardı qollaw ushın atı tekstten soń `.metod_atı()` kórinisinde jazıladı. Keliń usınday metodlardıń bazıları menen tanısamız.

### `upper()` hám `lower()` metodları

`upper()` metodı teksttiń hár bir háribin úlken háripke ózgertedi.

```python
name = 'Karamatdin'
l_name = 'Joldasbaev'
full_name = f'{name} {l_name}'
print(full_name.upper())
```

Nátije: `KARAMATDIN JOLDASBAEV`

`lower()` metodı bolsa kerisinshe, hár bir háripti kishi háripke ózgertedi.

```python
name = 'Karamatdin'
l_name = 'Joldasbaev'
full_name = f'{name} {l_name}'
print(full_name.upper())
```

Nátije: `karamatdin joldasbaev`

### `title()` hám `capitlize()` metodları

`title()` metodı teksttegi hár bir sózdiń birinshi háribin úlken hárip penen jazadı.

```python
fullname = 'elbrus sársenbaev'
print(fullname.title())
```

Nátije: `Elbrus Sársenbaev`

`capitalize()` bolsa tekǵana eń birinshi sózdiń birinshi háribin úlken hárip penen jazadı.

```python
fullname = 'elbrus sársenbaev'
print(fullname.capitalize())
```

Metodlardı tekǵana ózgeriwshilerge emes, bálki tuwrıdan-tuwrı tekstke de qollaw múmkin.

```python
print('karamatdin joldasbaev'.upper())
```

Nátije: `KARAMATDIN JOLDASBAEV`

## INPUT - PAYDALANÍWSHÍ MENEN BAYLANÍS

Usı waqıtqa deyin biz ózgeriwshilerdiń mánisin programmanıń ishinde berip atır edik. cooming soon

