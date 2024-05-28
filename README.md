# Booking-tennis-court-java-app


## Descriere
o	Proiectul pe care l-am ales este o aplicatie pentru calculator tip booking pentru o bază de tenis. În această aplicație, clienții pot închiria un teren de tenis pentru un interval de timp, pot sterge contul, pot edita datele personale și pot vedea ce rezervări au mai făcut.

## Obiective


* o	Gestionarea utilizatorilor și autentificarea
    - O să fie implementat un sistem de autentificare pentru a permite utilizatorilor să-și creeze conturi și să se conecteze în aplicație
* o	Gestionarea programărilor
    - 	Implemetarea funcționalităților pentru rezervarea terenurilor de tenis la date și ore specifice
    - 	Permiterea utilizatorilor sa vizualizeze disponibilitatea terenurilor și să facă programări în funcție de preferințele lor


## Arhitectura


![Screenshot 2023-11-04 010718](https://github.com/AlexandraMoldovan11/My-project/assets/149817008/9af14e37-0b5c-4aaa-ab7d-186bdc4e73f8)


-	Autentificare și Autorizare
	-	Înainte de a procesa o cerere, aplicația verifică autentificarea utilizatorului și autorizațiile acestuia pentru a asigura că are acces la funcționalitatea dorită.
-	Validarea Datelor de Intrare
	-	Aplicația validează datele introduse de utilizator pentru a se asigura că sunt corecte și sigure.
-	Logica de Afaceri
	-	Când un utilizator dorește să facă o rezervare, aplicația verifică disponibilitatea terenului și alocă programarea.
-	Generarea Răspunsului
	-	Aplicația generează un răspuns adecvat pentru utilizator, fie că este vorba despre afișarea unei pagini cu detalii despre o rezervare confirmată, afișarea unei liste de terenuri disponibile sau returnarea unui mesaj de eroare.
 
     Indicatori de performanță propuși
*	Numărul de rezervări pe zi/săptămână/lună
*	Rata de utilizare a terenurilor


## Functionalitati/Exemple utilizare
*	Gestionarea utilizatorilor și autentificarea
	* O să fie implementat un sistem de autentificare pentru a permite utilizatorilor să-și creeze conturi și să se conecteze în aplicație
*	Gestionarea programărilor
	* Implemetarea funcționalităților pentru rezervarea terenurilor de tenis la date și ore specifice
	Permiterea utilizatorilor sa vizualizeze disponibilitatea terenurilor și să facă programări în funcție de preferințe
