# JMBAG
0036483027


#Pitanje 1:
Pojavile su se datoteke ClassLibrary1.pdb i ClassLibrary1.dll.
Nakon što obrišemo .dll datoteku, dogodi se pogreška pri pokretanju .exe datoteke (Unhandled Exception: System.IO.FileNotFoundException) jer nam nedostaje referenca do ClassLibrary datoteke.
Poslat ću KonzolnaAplikacija.exe i ClassLibrary1.dll.


#Pitanje 2:
Prikazala je stari string jer projekt nije buildan, dakle nije generirana nova .dll datoteka nego se koriste podaci iz starog class library asemblija.


#Pitanje 3:
Ispisalo se "Pero: Hello World".

#Pitanje 4:
Dodana je datoteka PeroClassLibrary.dll.


#Pitanje 5:
Aplikacija radi jer je u bin/Debug folderu dodana nova .dll datoteka i sada se Pero-ClassLibrary traži tamo.

#Pitanje 6:
Build proces se normalno izvršio, a u packages diektorij vratio se NodaTime.
