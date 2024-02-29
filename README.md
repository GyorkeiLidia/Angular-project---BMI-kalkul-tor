A PROJECT EGYBEN LETÖLTHETŐ A GOOGLE DRIVE-RÓL: https://drive.google.com/file/d/1n5c-Fmkv6kT1PDRRyyr1wZLVRcKcMIho/view?usp=drive_link

# Angular-project---BMI-kalkul-tor
AngularJs project, BMI kalkulátor

Az alábbi feladat leírás alapján készítettem el a projectet:

BMI kalkulátor. Készítsünk egyszerű BMI kalkulátort AngularJs keretrendszerben. A feladat megoldása során kövesse
a pontosan a megadott instrukciókat.
1) Hozzon létre új AngularJs projektet WP4_HF_004 néven!
2) Hozzon létre új komponenst bmi néven! A komponenshez tartozó selector neve legyen: app-bmi-calculator!
3) Helyezze fel a létrehozott komponenst az app komponensben! A felületen csak ez a komponens jelenjen meg.
4) A komponenshez tartozó osztályban vegye fel az alábbi attribútumokat a megfelelő adattípussal:
• weight, ebben fogjuk tárolni a súlyt kilogrammban kifejezve (numerikus)
• height, ebben fogjuk tárolni a magasságot méterben kifejezve (numerikus)
5) Készítsünk paraméter nélküli konstruktort az osztályban, amely a weight attribútum értékét 50-ra, a height
attribútum értékét 1,6-ra állítja.
6) Jelenítse meg a súly és magasság értékeket a sablonban!
7) A felületen jelenjen meg négy gomb az alábbiak szerint!
• "Súly csökkentése" felirattal, amely gombra kattintva meghívja a komponensosztályban definiált,
decWeight paraméter nélküli metódust!
• "Súly növelése" felirattal, amely gombra kattintva meghívja a komponensosztályban definiált, incWeight
paraméter nélküli metódust!
• "Magasság csökkentése" felirattal, amely gombra kattintva meghívja a komponensosztályban definiált,
decHeight paraméter nélküli metódust!
• "Súly növelése" felirattal, amely gombra kattintva meghívja a komponensosztályban definiált, incHeight
paraméter nélküli metódust!
8) Definiáljuk az komponensosztályban a szükséges metódusokat az alábbi implementációkkal.
• decWeight: Csökkentsük az aktuális weight értéket 1-gyel.
• incWeight: Növeljük az aktuális weight értéket 1-gyel.
• decHeight: Csökkentsük a height attribútum értéket 0,1-gyel.
• incHeight: Növeljük a height attribútum értéket 0,1-gyel.
9) Készítsünk egy attribútumot a komponensosztályban bmi néven, amely numerikus értéket vehet fel, de az
attribútum értéke lehet definiálatlan is.
10) Készítsünk új gombot a sablonban "Számol" néven, amely meghívja a komponensosztályban definiált
calculateBmi paraméter nélküli metódust!
11) Definiáljuk a komponensosztályban a calculateBmi paraméter nélküli metódust az alábbi megvalósítással: a
bmi attribútum értéke legyen egyenlő a kilogrammban mért súly és a méterben mért magasság négyzetének
hányadosával (bmi = súly / magasság2
).
12) Jelenítsük meg a bmi értéket a sablonban!
13) Jelenítsük meg a testsúlyosztályt a számított bmi érték alapján a sablonban (tilos új attribútumot felvenni). A
testsúlyosztály meghatározása során az alábbi értéket kell megjeleníteni a bmi érték alapján:
- nem definiált (azaz nem kattintottunk a gombra) esetén "nem számítható"
- 16 alatt érték esetén "kóros soványság"
- 16 – 17 értékek között esetén "mérsékelt soványság"
- 17 – 18,5 értékek között esetén "enyhe soványság"
- 18,5 – 25 értékek között esetén "normális testsúly"
- 25 – 30 értékek között esetén "túlsúly"
- 30 – 35 értékek között esetén "elhízás"
- 35 – 40 értékek között esetén "túlzott elhízás"
- 40 fölötti érték esetén "extrém elhízás"
