### Pirmas laboratorinis

## Tools & stuff

- [BPMN Editor](https://demo.bpmn.io/s/start)
- [BPMN Reference](https://camunda.com/bpmn/reference/)

## Consultation 2024-09-16

Bendri komentarai:

Mūsų atveju nelabai realistiška pasirašyti sutarti po 4 procesų ("Jūs ieškote durnių klientų").
Reikėtų pasirašyti sutartį iš anksto.

Klaidų taisymus modeliuoti paprasčiau/atskirai nuo SCRUM ciklo.

Demo time/partial delivery beveik tas pats

Aprašyti QA procesą (pavadinti konkrečiau), ar sprendžiame tokius klausimus "ar spėjame pagal grafiką" ir t.t. ar tik testavimas ir *pamiršau*.

Fig 1. vietoje Figure 1:

## Bendri pastebėjimai apie pirmą laboratorinį darbą

- Labai aiškiai parašyti, kokią apimtį modeliuojam (visą įmonę ar tik kažokį tai padalinį, mūsų atveju tai tikriausiai bus tik IT padalinys)
- Aiškiai apibrėžtos rolės ir atsakomybės
- Nedaryti ankstyvų exitu veiklose
- Būtinai paminėti, kad scope yra nusprendžiamas prieš pasirašant sutartį ir yra vienas iš dalykų, ką mes išsiaiškinam su klientu
- Galim įsivaizduoti, kad pvz. dirbam su Jira, tada galim aiškiai aprašyti task'ų hierarchiją (epic (projektas) -> story (feature arba infrastruktūros darbai) -> task (atomiška užduotis)).
- [optional] Flow diagramos procesų veikloms

## Gretos komentarai

- Paskirtis/tikslas turi būti lakoniškas "purpose" (client engagement falim braukti viską po pirmo sakinio)
- jam nepatinka, kai kartojasi sinonimai
- Activities būtinai turi būti kaip stepsai kurie seka vienas po kito
- Labai aiškiai in Activities nurodyti, kas atsitinka, jei pvz klientas nesutinka toliau vykdyti projekto.
- Trinti lauk PRO/blabla
- Jei rašome kažkokius produktus skliaustuose, tai reikia ir ne skliaustuose juos rašyti lygiai taip pat

## Galutinis review checklistas

### Turinys

- [ ] Procesas turi diagramą (neprivaloma)
- [ ] Procesų tikslai aprašyti trumpai ir aiškiai
- [ ] Procesų veiklos aprašytos detaliai
- [ ] Procesų veiklos tarpusavyje naudoja/kuria informaciją arba darbo produktus kuriuos kuria/naudoja kitos veiklos tame procese (tas atvejis kai identified stakeholders, bet kas iš to?)
- [ ] Darbo produktų sąraše yra aprašyti visi apibrėžti darbo produktai

### Formatavimas

- [x] Visi procesai aprašyti lentelėse be išorinių šonų
- [x] Procesų lentelių pirmos eilutės laukelių tekstas yra paryškinti su `\textbf`
- [x] Procesų lentelių skyrių pavadinimai (visas pirmas stulpelis be pirmos eilutės) sutampa tarp procesų (Tikslas, Panaudoti darbo produktai, Sukurti darbo produktai, Veiklos)

## \#1 lab atsiskaitymo pastabos [2024-10-07]

- [X] versija naujoj eikutej
- [ ] dar kažką minėjo apie titulinį, bet i forgor

imones aprasymas:
- jis keltu “modeliuojame departamenta” aukščiau

Procesų aprašymas:
- [nesupratau] išmesti rodykle

KI:
- scope’as ir funkcionalumas - vos ne sinonimai
- klientas nenori sakyti savo biudžeto

Darbo produktu sarašas:
- dalis darbo produkto aprašymai turi būti procesuose
- Darbo produktai turi buti rikiuojami arba tik atsaradimi tvarka arba abezeliškai
- PNI:
    - mes per griežti, pvz: sistema turi veikti ir ivedus blogus duomenis t.t.
- GRR:
    - Negali dokumentas aprašyti visų pokyčių

KI:
- apimtis kaip priedas prie sutarties
- zmogiskuju istekliu nelabai reikia
- apimtis ir sutartis, lyg ir ta pati nusako

galetu busi proceselis kuris paplanuotu kiek uztrunka darbai

RA:
- keistas speendimas apjungti reikalavimus ir projektavima
- nezinom nei kiek laiko ir zmoniu galima skirti reikalavimu analizei 
- nera review ir neparodyta uzsakovui

UR:
- “Panaudos atvejai” - blogas terminas, “naudojimo atvejai”, “panaudojimo atvejai” - geresni terminai
- Reikalavimai: is darbo produktu - atskleidziami, is proceso - nuoroda i reikalavimas.
- “surušiuodami” - keista veikla, “sakot, kad sugebesit, jas vidas išrušiuoti?!”, taip dažniausiai nebūna, bet jeigu musu įnone sugeba - all g


Sprinti planavimas
- pirmine prioritezacija, “isrusiavimas” - blogas terminas geriau “surikiavimas”. geriau naudot vienodus terminus
- ka reiskia kad komandos nariai gali atnaujinti prioritetus
- “kad tilptų į intervalą”, blogai nes 5 į 50 ir techniškai telpa

Igyvendinimas:
- klaidu apraše negalima pažymėti, kad programuotojas sutaise klaida
- “vientu testai” -> “moduliu testai”
- “komentuoja koda” galima suprasti, kad rašo kodo komentarus //

Testavimas:
- KA galimas ir nuo pirmo sprinto
- Neaisku ar pagal aprasyma (jais pasitiki) ar bega tikrinti FR ir NFR
- Testuotojai _gali nuspręsti_ - no, jie daro tai ką reikia daryti, gerai butu nuspresti kad mes nusprestumem ka jie daro

PAS:
- nieks nezino kas padaryta, nes nera sprinto uzduosiu sarašo
- SŠ labai toli vienas nuo kito ir retai naudojama, gali pasimiršti
- per daug pasižadam - viską aptarti

KG:
- “staiga” atbėga IS
- Įvertinimų nėra, nes niekas nepildo [ikalbejom, kad pildo]

Notes:
- Uzduoties aprasymai ir FR, NFR stuff

8.5 - įvertinimas


