# **Lucrare 1**

**1. Ce este un sistem embedded. Dati exemplu de un sistem embedded cu justificarea caracteristicilor definitorii.**

`
Un sistem embedded este un sistem informatic specializat, conceput pentru a efectua o serie de sarcini specifice, spre deosebire de un calculator generalist care poate efectua mai multe sarcini. De exemplu, un termostat inteligent este un sistem embedded pentru că este proiectat să monitorizeze și să controleze temperatura unei case, având hardware și software dedicat pentru aceasta.
`

**2. Explicati de ce majoritatea pinilor la un circuit de tip microcontroller au functionalitate multipla. Dati exemple.**
   
`
Pinii cu funcționalitate multiplă permit unui microcontroller să fie mai versatil și să se adapteze la diferite aplicații, economisind spațiu și reducând costurile. De exemplu, un pin pe un microcontroller Atmega poate funcționa ca intrare digitală, ieșire digitală sau poate avea funcții speciale, cum ar fi comunicarea SPI sau măsurarea PWM.
`

**3. Ce este un sistem de intreruperi? Ce avantaje aduce sistemul de intreruperi in functionarea unui sistem de calcul?**
   
`
Un sistem de întreruperi permite unui microcontroller să întrerupă procesul curent pentru a răspunde unui eveniment extern sau intern printr-o rutină de service de întrerupere (ISR). Acest lucru face ca sistemele să fie mai eficiente și responsabile, permițând un răspuns rapid la evenimentele critice.
`

**4. Cum influenteaza alegerea arhitecturii sistemului de memorie proiectarea hardware a unui sistem embedded?**
   
`
Arhitectura sistemului de memorie influențează capacitatea, performanța și costul sistemului embedded. De exemplu, alegerea între memoria volatilă și cea nevolatilă determină cum vor fi stocate și recuperate datele în diferite stări de alimentare și operare.
`

**5. Explicati de ce circuitele de tip microcontroller sunt utilizate preferential in cadrul sistemelor embedded?**
   
`
Microcontrolerele sunt preferate în sistemele embedded datorită dimensiunii reduse, costului scăzut, consumului mic de energie și funcționalității integrate, care le fac ideale pentru controlul aplicațiilor specifice.
`
   
**6. Ce avantaje/dezavantaje ofera oscilatorul intern la un microcontroller?**

`
Avantajele includ costuri reduse și simplitatea designului, deoarece nu sunt necesare componente externe. Dezavantajele includ o precizie și o stabilitate scăzută comparativ cu oscilatoarele externe și limitări în gama de frecvențe posibile.
`
   
**7. Care este rolul mecanismelor de tip timer la un microcontroller?**
   
`
Timerele sunt folosite pentru a măsura intervalele de timp, a genera întârzieri, a controla evenimentele bazate pe timp și a produce semnale de modulație a lățimii de puls (PWM) pentru controlul motoarelor sau reglarea intensității LED-urilor.
`

**8. Ce efect are asupra registrelor interne ale microcontrollerului interactiuena pinMode din mediul Arduino IDE?**
   
`
Funcția pinMode() din Arduino IDE setează modul în care un pin specificat va funcționa - ca intrare (INPUT) sau ieșire (OUTPUT) - prin modificarea registrelor de direcție ale portului asociat pinului.
`

**9.  Care sunt avantajele utilizarii afisaelor de tip LED?**
    
`
Afisajele LED sunt durabile, au un consum redus de energie, sunt vizibile în lumina puternică și au o durată de viață lungă, făcându-le o opțiune populară pentru multe aplicații.
`

**10.  Argumentati afirmatia ca un sistem de calcul de uz general este o colectie de sisteme specializate.**
    
`
Sistemele de calcul de uz general sunt proiectate să ruleze o gamă largă de aplicații și, prin urmare, sunt compuse din subsisteme specializate cum ar fi unitatea de procesare grafică (GPU), procesorul central (CPU) și alte circuite specializate pentru rețea, stocare etc.
`

**11.  Ce este un microcontroller (microprocesor integrat) ? Prin ce se deosebeste un circuit de tip microcontroller de un micropocesor de uz general?**

`
Un microcontroller este un circuit integrat care include un procesor, memorie și periferice de intrare/ieșire într-un singur cip. Se deosebește de un procesor de uz general, care necesită componente externe separate pentru a forma un sistem complet.
`

**12.  La ce sunt utilizati pinii I/O la un circuit de tip microcontroller?**
    
`
Pinii I/O la microcontrolere sunt folosiți pentru a conecta cipul la lumea exterioară, permițându-i să interacționeze cu senzori, actuatori și alte dispozitive.
`

**13.  Ce se intelege printr-un mecanism de tip watchdog?**
    
`
Un mecanism watchdog este un temporizator care resetează sistemul dacă software-ul funcționează anormal și nu reîmprospătează watchdog-ul într-un timp prestabilit, ajutând astfel la recuperarea de la blocările de software.
`

**14.  Cum explicati diversitatea mare de circuite din cadrul aceleiasi familii de microcontrollere? Dati Exemple de familii.**
    
`
Diversitatea în familia microcontrolerelor este datorată nevoii de a servi o gamă largă de aplicații cu cerințe diferite de memorie, viteze de procesare și capacități I/O. Exemple de familii includ AVR de la Atmel și MSP430 de la Texas Instruments.
`

**15.  Ce avantaje aduce organizarea memoriei in memorie program si memorie de date in cazul circuitelor de tip microcontroller?**
    
`
Separarea memoriei de program de memoria de date permite o gestionare mai eficientă a resurselor și o securitate îmbunătățită, protejând codul programului de corupere accidentală sau intenționată.
`

**16.  Dati exemplu de un protocol serial intercircuit si exemplificati pe scurt functionarea acestuia.**
    
`
I2C este un protocol serial care folosește două linii: una pentru ceas (SCL) și una pentru date (SDA). Permite comunicația între multiple circuite pe aceeași pereche de fire, folosind adrese unice atribuite fiecărui dispozitiv.
`

**17.  Ce efect are asupra registrelor interne ale microcontrollerului interactiunea digitalWrite din mediul Arduino IDE?**
    
`
Funcția digitalWrite() schimbă starea unui pin I/O la înalt sau jos, afectând direct registrul de ieșire al portului asociat pinului în microcontroller.
`

**18.  De ce este necesara organizarea matriceala a elementelor interfetei utilizator? Dati un exemplu.**
    
`
Organizarea matriceală permite controlul unui număr mare de butoane sau leduri folosind un număr redus de pini I/O, cum ar fi în cazul tastaturilor sau afișajelor LED matriceale.
`

**19.  De ce afisasele de tip LED sunt denumite pasive?**
    
`
Afișajele LED sunt considerate pasive pentru că fiecare pixel individual trebuie să fie activat de un curent pentru a emite lumină, spre deosebire de afișajele active, care conțin elemente care emit lumină independent.
`

**20.  Pot exista sisteme embedded la care sa lipseasca interfata utilizator? Argumentati.**

`
Da, multe sisteme embedded funcționează fără interfață directă cu utilizatorul, de exemplu, modulele senzorilor în aplicații industriale sau dispozitivele IoT care comunică datele printr-o rețea fără interacțiune umană directă.
`

**21.  Dati exemplu de un protocol de comnicatie/de retea/fara fir si explicati modul de functionare a acestuia.**
    
`
Bluetooth este un protocol de comunicație fără fir care facilitează transferul de date între dispozitive printr-un schimb de frecvențe radio pe distanțe scurte, folosind un proces numit "frequency hopping" pentru securitate și reducerea interferențelor.
`

**22.  Care sunt metodele de sistematizare a specificatilor de functionare in vederea implementarii software?**
    
`
Specificațiile de funcționare pot fi sistematizate în documentații funcționale, diagramă de cazuri de utilizare, diagramă de activitate și alte forme de documentație tehnică care detaliază funcționalitatea sistemului și cerințele software.
`

**23.  Care sunt factorii care permit alegerea uni sistem de operare specializat?**
    
`
Factorii includ cerințele specifice de timp real, resursele hardware limitate, necesitatea optimizării performanței și a consumului de energie, și cerințele de securitate și fiabilitate specifice aplicației.
`

**24.  Care sunt principalele arhitecturi de program in cadrul sistemelor embedded?**
    
`
Arhitecturile de program includ structura monolitică, bazată pe întreruperi, cu mașini de stare finită și programarea bazată pe evenimente sau pe task-uri și procese în sistemele de operare în timp real (RTOS).
`

**25.  Caracteristici ale sistemelor embedded. Comparatie cu sistemele de uz general.**
    
`
Sistemele embedded sunt specializate, compacte și eficiente în energie, cu hardware și software dedicat, în timp ce sistemele de uz general sunt versatile, mai puternice și proiectate pentru a executa o varietate largă de aplicații.
`

**26.  Dati exemple de componenta hardware ce permite construirea interfetei utilizator. Explicatia functionarea acesteia.**
    
`
O componentă hardware cum ar fi un touchscreen permite interacțiunea utilizatorului cu sistemul prin detectarea contactului fizic pe o suprafață sensibilă, care apoi transmite coordonatele punctului de contact către procesor pentru a răspunde la comandă.
`

**27.  Ce se intelege prin SoC?**
    
`
SoC (System on Chip) se referă la integrarea tuturor componentelor necesare unui calculator sau sistem electronic într-un singur cip, inclusiv procesorul, memoria, perifericele de I/O și alte funcții necesare sistemului.
`

**28.  Dati exemplu de o tehnica de proiectare hardware care sa permita cresterea numarului de elemente componente pentru interfata utilizator.**
    
`
Multiplexarea este o tehnică care permite controlul mai multor elemente de interfață utilizator (cum ar fi afișajele sau LED-urile) folosind un număr mai mic de pini prin activarea lor secvențială.
`

**29.  Care este diferenta dintre sarcina uni analist si cea a unui programator?**
    
`
Analistul de sisteme se concentrează pe înțelegerea și modelarea cerințelor sistemului, în timp ce programatorul implementează soluțiile tehnice prin scrierea codului necesar pentru a îndeplini aceste cerințe.
`

**30.  Cand este necesara utilizarea uni SO in cazul unui sistem embedded?**
    
`
Un sistem de operare este necesar în sistemele embedded complexe care necesită multitasking, gestionarea avansată a memoriei sau interacțiuni rețea în timp real, oferind o platformă standardizată pentru dezvoltarea aplicațiilor.
`

**31.  Dati exemplu pertinent cand un PC poate inlocui un sistem embedded.**
    
`
Un PC poate înlocui un sistem embedded în aplicațiile de testare și prototipare unde flexibilitatea și puterea de procesare sunt mai importante decât dimensiunea, consumul de energie sau costul.
`

**32.  Care sunt principalele caracteristici a sistemelor industriale de tip PC?**
    
`
Sistemele industriale de tip PC sunt robuste, fiabile, extensibile și capabile să ruleze o gamă largă de software, cu interfețe standardizate pentru conectarea la echipamentele industriale.
`

**33.  Enumerati si explicati pe scurt etapele de proiectare a unui sistem embedded.**
    

Proiectarea unui sistem embedded implică mai multe etape esențiale:

- Definirea cerințelor: Înțelegerea nevoilor și limitărilor pentru care sistemul este proiectat.
- Proiectare și arhitectură: Crearea unui plan detaliat al sistemului, inclusiv selectarea hardware-ului și structurarea software-ului.
- Dezvoltarea hardware: Designul și construcția plăcii de circuit, inclusiv microcontrollerul și alte componente necesare.
- Dezvoltarea software: Scrierea codului sursă care va rula pe hardware-ul dezvoltat.
- Integrare și testare: Asamblarea sistemului și testarea funcționalității acestuia pentru a se asigura că îndeplinește specificațiile inițiale.
- Dezvoltare și implementare: Îmbunătățirea și modificarea sistemului pe baza feedback-ului primit în urma testării.
- Producție: Producerea în masă a sistemului după finalizarea și validarea designului.
- Mentenanță și suport: Oferirea de suport tehnic și actualizări pentru produsul final.


**34.  Enumerati si explicati rolul perifericelor (cel mai des) intalnite in cazul circuitelor de tip microcontroller.**


Perifericele în cadrul unui microcontroller sunt folosite pentru a extinde funcționalitatea și a permite interacțiunea cu lumea externă, precum:

  - Porturi I/O: Pentru a controla dispozitivele externe, cum ar fi LED-uri, motoare, senzori.
  - Timere: Pentru a măsura timpul sau a genera întârzieri.
  - Comunicare serială: Pentru a transfera date între microcontrolere sau alte dispozitive, cum ar fi PC-urile, utilizând protocoale cum ar fi UART, SPI sau I2C.
  - Convertoare Analog-Digital (ADC): Pentru a converti semnalele analogice de la senzori în valori digitale ce pot fi procesate.
  - Watchdog Timer: Pentru a reseta sistemul în caz de blocare a software-ului.

    
**35. Ce rol au specificatiile de sistem/functionale in cadrul proiectarii unui sistem?**
    
`
Specificațiile de sistem descriu scopul și funcțiile generale ale unui sistem, în timp ce specificațiile funcționale traduc aceste cerințe în parametri tehnici detaliate, stabilind o fundație pentru proiectarea tehnică și dezvoltarea software.
`
    
**36.  Ce rol au specificatiile de testare in cadrul realizarii unui proiect?**
    
`
Specificațiile de testare definisesc criteriile și procedurile de verificare a conformității produsului cu cerințele stabilite, asigurând calitatea și funcționarea corectă a sistemului înainte de lansarea acestuia.
`

**37.  Ce se intelege printr-o arhitectura de microcontroller pe 8/16/32 de biti?**
    
`
Arhitectura unui microcontroller pe 8, 16 sau 32 de biți se referă la lățimea de bandă a busului de date și la dimensiunea cuvântului pe care microcontrollerul îl poate procesa într-o singură instrucțiune, influențând performanța și capacitatea de procesare.
`

**38.  Ce rol are procesul de calibrare in cazul achizitiei de date?**
    
`
Calibrarea este procesul prin care se asigură că răspunsul instrumentului de măsurare corespunde precis cu valoarea adevărată a mărimii măsurate, reducând erorile de măsurare și îmbunătățind acuratețea datelor.
`
    
**39.  Ce legatura exista intre plaja de variatia a parametrului masurat si precizie in cazul procesului de conversie analog numerica?**
    
`
Plaja de variație a parametrului măsurat și precizia sunt interconectate; pe măsură ce plaja de variație crește, pentru a menține aceeași precizie, este necesară o rezoluție mai mare a conversiei (mai mulți biți).
`
    
**40.  Care sunt elementele ce trebuie precizate in cazul unui proces de conversie analog numerica?**
    

În procesul de conversie analog-numerică trebuie specificate:

  - Plaja de intrare: Intervalul de tensiuni sau curent care va fi convertit.
  - Rezoluția: Numărul de biți utilizați pentru conversie, care determină cât de fin poate fi împărțit intervalul de intrare.
  - Frecvența de eșantionare: Cât de des se face conversia semnalului analogic în digital.
  - Precizia și acuratețea: Erorile inerente sistemului și cum pot fi acestea minimizate prin calibrare și alte tehnici.


**41.  Cum se explica existenta la Atmega 328 8 pini ADC in situatia in care exista un singur CAN intern?**
    
`
Sunt 8 canale multiplexate care se folosesc pe rand, deci sunt mai multe canale in acelasi CAN.
Un singur CAN poate fi partajat între mai multi pini ADC. 
`

**42.  Ce se intelege prin izolare galvanica?**
    
`
Izolarea galvanica presupune separarea din punct de vedere electric a elementului de control de cel de comanda. Masa comuna (GND) duce la anularea izolarii galvanice. Izolarea galvanica se poate realiza cu ajutorul unor elemente precum relee, optocuploare.
`