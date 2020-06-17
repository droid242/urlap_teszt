# urlap_teszt
Űrlapok gyakorlás

### Form - ahol az adat kezdődik
Űrlapot a form elem használatával hozhatunk létre.
Az űrlapon belül vannak a beviteli mezők, listák.

### Input és label
Az input elem az adatok kézi bevitelére szolgál.
Az input mezőket címkével láthatjuk el, ez a label elem.

#### Az input elem fontos tulajdonságai:
* name: az adat neve, későbbi azonosításhoz kell.
* type: az adat típusa, lehet text, password, radio stb.

***

A checkbox és a radio szintén adatbevitelre szolgál. Ebben az esetben a felhasználónak nem kell beírnia semmit, csupán választania kell a felkínált lehetőségek közül.

### Checkbox - csekkoljunk be!
Egy input elem, amelynek a típusa: checkbox. A checkbox önálló elem, ha bepipáljuk az azt jelenti, hogy igent mondtunk a kérdésre.

### Radio - egyszerre csak egyet!
Szintén egy input elem, de mindig többet használunk egyszerre. Az alapvető különbség a radio és a checkbox között, hogy a radio esetében több választási lehetőséget kínálunk fel, amelyek közül csak egyet lehet választani. Pl. neme, autó színe. A radio esetén fontos, hogy a name tulajdonság az adott csoportba tartozó öszes radio-nál azonos legyen.

### A value tulajdonság
Value, azaz a mező értéke. Ha beállítjuk a value atrribútumot, alapértelmezett értéket adhatunk az input elemnek.

### A checked tulajdonság
Ha bejelölünk egy radio vagy checkbox elemet, felveszi a checked tulajdonságot. Viszont ezt nem csak automatikusan veheti fel, mi is megadhatjuk, hogy alapból be legyen jelölve. Csak hozzá kell adnunk az elemhez.

***

### fieldset
Két fontos tag, amit a formok kapcsán még érdemes megemlíteni: a fieldset és a legend. A fieldset segítségével csoportosítani tudjuk a logikailag összetartozó űrlapelemeket, a legend segítségével pedig ezekhez a csoportokhoz tudunk feliratot készíteni. A legend mindig a fieldset elemen belül kell hogy legyen!