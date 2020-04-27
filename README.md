# vmi_duomenu_masyvas
#
# VMI sukurtas duomenų masyvas. Masyvo data 2020-04-22
Valstybinė mokesčių inspekcija bendradarbiaudama su VšĮ "Europos viešosios politikos institutas", atrinko duomenis į duomenų masyvą, kurie leistų suinteresuotai visuomenei analizuoti ekonomikos esamą situaciją, jos tendencijas, kurti bei testuoti įvairius paramos modelius ir jų kainas. VMI leidus, pateikiame duomenis plačiąjai visuomenei.

Pastabas ar priekaištus rašykite EVPI, EVPinstitutas@gmail.com, Rimantas Žylius

# Duomenų imtis
Šiame masyve pateikiamos tik įmonės, įregistruotos PVM mokėtojais.
Šis masyvas sugeneruotas ~2020-04-20, tad ne visos įmonės tuo metu buvo pateikusios 2020 kovo mėn duomenis (deklaravimo data yra iki 25 dienos). 


# Duomenų laukų paaiškinimai
# ID
dirbtinis įmonės kodas, skirtas susieti įmonės duomenis šioje lentelėje ir jos atnaujinimuose, tačiau neturintis nieko bendro su jokiais įmonės juridinių asmenų ar PVM registro numeriais.

# MMR reg metai
Kuriais metasi įmonė registruota mokesčių mokėtojų registre.

# PVM reg metai
Kuriais metasi įmonė registruota PVM  mokėtoju.

# Statusas
"0. Teisinis statusas neįregistruotas" yra statusas rodantis normaliai veikiančią įmonę. 

# "Mokėjimai"
tai faktiškai sumokėta visų mokesčių suma tą mėnesį (t.y. tai nėra mokėtini mokesčiai už tą mėnesį, o faktiškai sumokėtų mokesčių suma), balansas, t.y. įskaitant atliktus grąžinimus.

# PVMD 
PVM deklaracijoje FR0600v2 deklaruota prekių ir paslaugų sandorių suma (be PVM). Imama formos šių laukelių suma:

11. "PVM apmokestinami sandoriai”

12. “PVM apmokestinami sandoriai, kai PVM išskaito pirkėjas (96 str. nustatytais atvejais)”

13. “PVM neapmokestinami sandoriai”

16. “Sandorių, kuriems taikoma spec. apmokestinimo schema, marža”

17. “Prekių eksportas (0 proc.)”

18. “ES PVM mokėtojams patiektos prekės (0 proc.)”

19. “Kiti PVM apmokestinami sandoriai (0 proc.)”

20. “Už Lietuvos ribų įvykę sandoriai (ne PVM objektas Lietuvoje)”

Ši suma nebūtinai sutampa su tą mėnesį išrašytų sąskaitų suma (kai kurie sandoriai nematomi PSF pvz. yra tiekimai į ES; eksportas ir pan.; taip pat gali skirtis PVM apmokestinimo momentas (avansiniai mokėjimai ir kai kurios išimtys).
 
# PVM Prievolė 
tą mėnesį mokėtino į VMI sąskaitą PVM suma. 
Duomenys pateikiami iš PVM deklaracijos (FR0600v2) 36 laukelio “Mokėtinas į biudžetą arba grąžintinas iš biudžeto (-) PVM (27+29+30+31+32+33+34-35)”.
 
# Darbo apmokėjimo suma 2019
įmonės išlaidos darbo užmokesčiui, įskaitant mokesčius. Atkreiptinas dėmesys, kad kai kurios gaunamos pajamos nepatenka į šią sumą (komandiruotės, įvairios SODRA neapmokestinamos pajamos ir pan.).

# EV kodas, pavadinimas, skyrius, sekcija, skyriaus kodas, sekcijos kodas
Pagal ekonominių veiklų klasifikatorių https://osp.stat.gov.lt/600 įmonės nurodytos veiklos kodai ir jų iššifravimai.
Pastebėtina, kad EC kodus įmonės priskiria sau pačios, o jų tikslumas ir patikimumas nėra kontroliuojamas.


