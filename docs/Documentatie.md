# Booklated Library Management System

## 1. Prezentarea generală a sistemului

Booklated Library Management System este un sistem destinat gestionării activităților unei biblioteci. Acesta permite organizarea informațiilor despre cărți și membri, precum și evidența împrumuturilor și returnărilor.

Proiectul prezintă un prototip interactiv realizat în Figma, care ilustrează principalele interfețe și funcționalități ale sistemului.

## 2. Arhitectura modulară

Sistemul Booklated Library Management System este proiectat pe baza unei arhitecturi modulare, organizată în trei straturi principale. Această structură permite separarea interfeței grafice de logica aplicației și de gestionarea datelor.

### 2.1. Stratul de prezentare (Presentation Layer)

Acest strat reprezintă partea vizuală a aplicației, prin intermediul căreia utilizatorii interacționează cu sistemul. Acesta include pagina principală, pagina de întâmpinare, autentificarea bibliotecarului, înregistrarea membrilor, panoul de administrare, lista cărților, formularul de adăugare a cărților și interfața pentru evidența cărților împrumutate și returnate.

### 2.2. Stratul logicii aplicației (Business Logic Layer)

Acest strat este responsabil de prelucrarea acțiunilor utilizatorilor și de gestionarea operațiilor principale ale sistemului. Acesta include module pentru autentificare, gestionarea membrilor, gestionarea cărților și gestionarea împrumuturilor și returnărilor.

### 2.3. Stratul de acces la date (Data Access Layer)

Acest strat se ocupă de organizarea, stocarea, preluarea și actualizarea informațiilor utilizate de aplicație. Acesta gestionează datele despre cărți, membri, împrumuturi, returnări și istoricul cărților.

### 2.4. Comunicarea dintre straturi

Stratul de prezentare transmite cererile utilizatorilor către stratul logicii aplicației. Acesta prelucrează solicitările și comunică, atunci când este necesar, cu stratul de acces la date pentru a obține sau actualiza informațiile. Rezultatele sunt apoi transmise înapoi către interfața grafică.

Această organizare modulară contribuie la o structură mai clară a proiectului, facilitează întreținerea și permite dezvoltarea ulterioară a aplicației.

## 3. Diagrame UML

În această secțiune vor fi prezentate diagramele care descriu funcționalitățile și structura sistemului.

### 3.1. Diagrama Use Case

Diagrama Use Case ilustrează actorii care interacționează cu sistemul și principalele acțiuni pe care aceștia le pot realiza.

### 3.2. Diagrama arhitecturii modulare

Diagrama prezintă cele trei straturi ale sistemului și modul în care acestea comunică între ele.
## 4. Prototipul interactiv

Prototipul interactiv al sistemului a fost realizat în Figma și prezintă principalele ecrane și fluxuri de navigare ale aplicației.
