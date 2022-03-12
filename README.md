# OOP_Projects
Proiect1- Tema13:
Definiti clasa "persoana", avand:
    - membri privati pentru nume (string), anul nasterii (intreg), sex (caracter);
    - sase metode publice pentru setarea/furnizarea informatiilor din cei trei membri privati.
   Definiti clasa "baza_de_date" avand	
    - ca membri privati un vector la "persoana" declarat dinamic si un intreg reprezentand numarul persoanelor;
    - ca metode publice un constructor care initializeaza vectorul cu NULL pe fiecare componenta, un destructor care dezaloca toate "persoanele" 
   pointate de componentele vectorului, o metoda pentru adaugat o "persoana", trei metode pentru eliminat persoanele avand un anumit  nume, respectiv an al nasterii, 
   respectiv sex (cele trei metode vor  avea acelasi nume, prin supraincarcare), doua metode pentru afisat persoanele continute in baza de date in ordinea alfabetica a numelor, 
   respectiv crescatoare a varstelor.
   
   Cele doua clase de mai sus pot avea si alti membri/metode, dar se va respecta principiul incapsularii datelor (orice setare/furnizare a  informatiilor continute in membrii 
   privati se va face doar prin intermediul unor metode). 
   
   Scrieti un program care sa gestioneze o baza de date folosind clasele de  mai sus. El va afisa un meniu (in mod text), care va oferi functii de adaugat o persoana, 
   eliminat persoanele dupa nume, varsta, sex, afisat
persoanele in ordine alfabetica sau dupa varsta. 
