# NUMBERS

Biz maģlıwmatlar túrleri ne ekenligi haqqında bilip aldıq. Endi, aldın sanap ótken hár bir maģlıwmat túrin bólek-bólek úyrenemiz. Búgingi úyrenetuģın maģlıwmat túrimiz, sanlı maģlıwmatlar boladı.

Sanlı maģlıwmat túrleri óz gezeginde pútin san, bólshek san hám kompleks san bolıp 3 túrge bólinedi. Programmalastırıw tillerinde bolsa pútin sanlar `integer`, bólshek sanlar `float` hám kompleks sanlar `complex` dep júritiledi. `integer` sózin qısqarıp `int` deymiz, `float` hám `complex` qısqartılmaydı.

Bul úsh tip haqqında matematika sabaqlıģınan jaqsı tanıs bolsaq kerek. Sonda da azģana maģlıwmat berip ótemen. Integer tipi, olar minus pútin sanlardı (-23, -5, -1,,,), nóldi (0) hám oń pútin sanlardı (1, 2, 55,,,) óz ishine aladı. Float tipi, ózine bólshek sanlardı (1.5, 2.7,,,) aladı. Complex tip bolsa ózinde kompleks sanlardı sáwlelendiredi.

```python
x = 18    # int
y = 64.5  # float
z = 1j    # complex
```

## INTEGERS - PÚTIN SANLAR

Pútin sanlardı da ózgeriwshilerde saqlaw, olardıń ústinde arifmetik ámellerdi orınlaw múmkin:

```python
a = 20  # Sanlar oń yamasa
b = -30 # teris bolıwı múmkin
c = a + b
print(c)
```

Nátije: `-10`&#x20;

{% hint style="info" %}
Python - operatorlar arasındaģı boslıqlardı inabatqa almaydı. Oqıwģa qolay bolıwı ushın joqardaģı sıyaqlı (boslıqlar menen) jazıw múmkin.
{% endhint %}

## FLOATS - BÓLSHEK SANLAR

Pythonda bólshek sanlar **floating point numbers** yamasa qısqa qılıp **floats** delinedi. "_Floating point numbers_" atamasın qaraqalpaq tiline "_júziwshi noqatlı sanlar_" dep awdarmalaw múmkin. Inglis tilinde bólshek sanlardı jazıw ushın útir (`,`) emes noqat (`.`) belgisi isletiledi, hám noqat sannıń úlken kishiligine qarap ornı ózgergeni ushın "floating" (júziwshi) delinedi.

```python
pi = 3.14159 # bólshek san (float)
radius = 10  # butun son (integer)
diametr = 2*radius
print("Sheńberdiń uzınlıģı ", pi*diametr, " ģa teń.")
```

Nátije: `Sheńberdiń uzınlıģı 4.712384999999999 ģa teń.`

Sonıń menen birge pútin hám bólshek sanlar ortasındaǵı hár qanday arifmetik ámellerdiń nátiyjesi de bólshek san boladı.

```
a = 2
b = 3.0
# Tómendegi arifmetik ámellerdiń nátiyjesi bólshek san payda etedi
print(a+b) 
print(a*b)
print(a**b)
print(2*(a+b))
```

Nátije:

`2.0`

`6.0`

`8.0`

`10.0`

## UZÍN SANLARDÍ KIRITIW

Uzın sanlardı kiritiwde, qolaylıq ushın, xanalardı tómengi sızıq (`_`) járdeminde gruppalaw múmkin. Python - sanlar arasındaģı tómengi sızıqlardı (`_`) inabatqa almaydı.

```python
world_population = 8_016_378_020
print("Jer planetasınıń xalıq sanı:", world_populatin)
```

Nátije: `Jer planetasınıń xalıq sanı: 8016378020`

## KONSTANTA

Bazı programmalastırıw tillerinde konstanta túsinigi bar. Konstantalar ózgermes boladı (mısal ushın _π_ diń mánisi konstanta, ózgermes mánis). Pythonda konstanta túsinigi joq, sonıń ushın programmistler bunday ózgeriwshilerdiń atın úlken háripler menen jazadı (_eskertiw esabında_). Álbette bul qatań qaģıyda emes, bıraq keleshekte ózgeriwshiler arasında konstanta mánisti ajratıw ushın jaqsı usıl.

```python
PI = 3.14159
```

## BIR NESHE ÓZGERIWSHIGE MÁNIS BERIW

Birdegende bir neshe ózgeriwshilerge mánis beriw ushın ózgeriwshiler hám olarģa sáykes mánisler útir (`,`) menen ajratıladı:

```python
x, y, z = 10, -17, 2.4
```

Joqardaģı kod nátijesinde `a` ģa `10`, `b` ģa `-17`, `c` ģa `2.4` mánisleri beriledi.

## ÓZGERIWSHI TÚRIN ANÍQLAW

Ózgeriwshi saqlap turģan maģlıwmat qaysı tipte ekenligin anıqlaw ushın `type()` funkciyasınan paydalanamız:

```python
print(type(x))
print(type(y))
print(type(z))
```

Nátije:

`<class 'int'>`

`<class 'int'>`

`<class 'float'>`

## TYPECASTING

Python tilinde tekst (string) hám san (int, float) túrdegi ózgeriwshilerdi bir birine qosıwģa bolmaydı. Mısal ushın:

```python
name = 'Elbrus'
age = 18
message = name + ' ' + birth + 'jasta'
print(message)
```

Nátije: **`TypeError: can only concatenate str (not "int") to str`**

Bizler `Elbrus 18 jasta` degen nátijeni kútken edik, bıraq onday bolmadı. Eger qáteni inglis tilden awdarmalasaq, tekst (str) hám sandı (int)  jámlewge bolmaydı degen máni shıģadı.

Bul mashqalaģa sheshim beriw ushın tómendegi usıldan paydalanamız.

Pythonda bir túrdegi ózgeriwshini basqa túrge ótkeriw múmkin, bul inglis tilinde typecasting delinedi. Bunıń ushın Pythonda arnawlı funkciyalar bar, keliń olar menen tanısamız:

* `str()` — int yamasa float túrdegi sanlardı tekstke ózgertedi.
* `int()` — tekst yamasa float kórinistegi mánistlerdi pútin sanģa ózgertedi. Bunıń ushın tekst pútin san kórinisinde bolıwı kerek.
* `float()` — tekst yamasa int kórinistegi mánislerdi bólshek sanģa ózgertedi.

Demek, joqardaģı kod tuwrı islewi ushın 3-qatardı tómendegishe ózgertemiz:

```python
name = 'Elbrus'
age = 18
message = name + ' ' + str(birth) + 'jasta'
print(message)
```

Nátije: `Elbrus 18 jasta`

{% hint style="danger" %}
`str(age)` kodı `age` degen ózgeriwshiniń mánisin tekst kórinisinde kórsetedi. Negizgi ózgeriwshiniń mánisi san bolıp qalaberedi. `int()` hám `float()` da usınday isleydi.
{% endhint %}

## INPUT() HÁM SANLAR

Aldınǵı sabaǵımızda paydalanıwshıdan maǵlıwmat alıw ushın `input()` funktciyasınan paydalanıwdı úyrendik. Keliń endi sol funkciya járdeminde paydalanıwshıdan san alıwdı kóreyik. Tómendegi kod paydalanıwshınıń tuwılǵan jılın soraydı hám onıń jasın esaplab beredi:

```python
#1 paydalanıwshınıń tuwılǵan jılın soraymız
birth = input("Tuwılǵan jılıńızdı kiritiń: ")
#2 paydalanıwshıń jasın esaplaymız
age = 2023 - birth # 
#3 paydalanıwshı jasın konsolge shıǵaramız 
print (" Siz " + age + " jasta ekansiz")
```

Nátije: **`TypeError: unsupported operand type(s) for -: 'int' and 'str'`** &#x20;

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption><p>IDLE Console</p></figcaption></figure>

Kútilgen nátije ornına qátelik shıqtı. Programma tuwılģan jıldı sorģan waqtında `1998` dep kirgizdim, sol waqıtta qátelik júz berdi hám programma toqtadı. Qáteni awdarmalasaq san (int) hám tekst (str) arasında alıw (`-`) ámelin orınlawģa bolmaydı degen mánis shıģadı.

Qáteliktiń sebebi, `input()` funkciyası hár qanday kirgizilgen mánisti tekst (string) kórinisinde qabıl etedi (eger san kirgizgen bolsaqta), nátijede `birth` ózgeriwshisiniń mánisi string tipinde bolıp qaladı. Joqarda aytqanımızday "san hám tekst arasında alıw ámelin orınlawģa bolmaydı".

Qátelikti saplastırıw ushın 2 hám 6-qatarlardı ózgertemiz:

```python
#1 paydalanıwshınıń tuwılǵan jılın soraymız
birth = int(input("Tuwılǵan jılıńızdı kiritiń: "))
#2 paydalanıwshıń jasın esaplaymız
age = 2023 - birth # 
#3 paydalanıwshı jasın konsolge shıǵaramız 
print (" Siz " + str(age) + " jasta ekansiz")
```

Nátije:

`Tuwılǵan jılıńızdı kiritiń: 1998`&#x20;

`Siz 24 jasta ekansiz`

## ÁMELIYAT

Tómendegi programmalardıń hár birin bólek fayl kórinisinde jazıń hám orınlań:

1. Paydalanıwshı kirgizgen sannıń kvadratın hám kubın konsolģa shıģarıwshı programma
2. Paydalanıwshınıń jasın sorap, onıń tuwılģan jılın esaplap, konsolģa shıģarıwshı programma
3. Paydalanıwshıdan eki san kirgiziwin sorap, kirgizilgen sanlardıń qosındısın, ayırmasın, kóbeymesin hám tıyıdısın shıģarıwshı programma

