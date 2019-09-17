# Car-Rental-System
Mentinerea evidentei clientilor intr-o companie de inchiriat masini, unde fiecare numar de autoturism (i.e. inchiriat) 
va fi asociat cu un nume de persoana (i.e. chirias);
1. aflarea starii unei anumite masini (i.e. inchiriata sau nu)
Operare: se va cauta cheia (i.e. nr. de inmatriculare) in tabela. Daca numarul de inmatriculare exista, masina este inchiriata, iar daca nu, masina poate fi data unui nou client.
2. aflarea chiriasului:
Operare: similar cu cazul anterior, se va cauta cheia. Daca aceasta exista, se va citi valoarea asociata - aceasta din urma fiind numele persoanei ce detine masina.
3. predarea unei masini (de catre un client)
Operare: dupa predarea masinii, se sterge din dictionar perechea (cheie, valoare)
4. adaugarea unui nou client
Operare: la predarea unei masini catre un nou proprietar temporar, se va adauga si in dictionar o pereche (cheie, valoare) corespunzatoare.
5. (optional) aflarea numarului de masini inchiriate
Operare: valoarea va fi egala cu numarul total de perechi din tabela de simboluri.


