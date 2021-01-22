# Restante_Zilnice_Macro_Excel
Restante_Zilnice_Macro_Excel



Restante:
Fisierul cu restante:
Se sterg datele din sheeturile cu rosu, fara primul rand, [pentru a ramane formulele:
“Restante desfasurator”
“Programari”
“Clienti instalati”
“Treceri”

“Restante desfasurator”
Se foloseste subscriptia “Vechime clienti neinstalati detaliat”
Tabelul se prelucreaza: se taie coloanele cu “tichetcadou150””tichetcadou50””tichetcadou250” si “partner”
Dupa se da remove duplicates cu “id address”
Localitati de ramas : 
Dambovita: Baldana, Ghergani, Gulia, Mavrodin, Racari, Tartasesti, Crevedia,Darza
Giurgiu: Bolintin-Deal
Calarasi: Belciugatele, Candeasca, Cojesti, Gostilele, Mariuta, Fundulea

“Programari”
Se folosesc subscriptiile
Liste programari – national neinstalabili si instalabili
Fisierele se prelucreaza astfel
Dupa coloana “televizor” se insereaza o coloanal
Dupa coloana “mininod_montat” se insereaza o coloanal
Dupa coloanal “CAM” se Sterge tot


“Clienti instalati”
Se foloseste subscriptia  “Durata instalare servicii detaliat”
Se da delete la randurile 1 si 2
Se da unmerge la coloanele F si G (se trece nume la col G)
Se insereaza o cloana dupa “Inchis prin”
Se stabileste Rank-ul instalarilor
Se copiaza din restante 2017 septembrie fisierul 18.09 durata
Se sorteaza dupa rank “AV” dupa se da remove dupa “KEY” “AX”
Localitati de ramas : 
CL: Belcigatele, Candeasca, Cojesti, Fundulea, Gostilele, Mariuta
DB: Baldana, Crevedia, Darza, Gamanesti, Ghergani, Gulia, Mavrodin, Racari, Tartasesti
GR: Bolintin-Deal
Bucuresti si ilfov: tot
Ulterior se copiaza datele in restante sheet Clienti instalati”

“Treceri”
Se foloseste subscriptia  “Instalari subcontractori”
Se folosesc date din fisier pana la coloana “telefonie signed date”

Centralizator 1 refreshe all 







PRINT
Sursa 1
Copy F51:G64 paste cablari buisniss toate datele
Copy F8:J23 paste bucuresti toate datele (Dreapta )

Sursa 2
Copy paste nord si sud  BLOC(FTTB) FTTH CASA
De pe mail echipele pentru medie (GPON = casa,BLOC =FTTH)

Sursa 3
Copy paste Treceri FTTH NORD SUD 


Centralizator 2 3
Copy paste fix tabelul Paste special values only

Centralizator 1 
Copy paste table stanga mic fix tabelul Paste special values only
Selec all  unhide  ranmduri 
Trage de mijloc table sa apra ziua anterioara 
Hide sa apara fix totalul

POZE la CENTralizator 1 2 3 
Micsorare poza 
Trimitere pe mail 2 3 1
