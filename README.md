# ParkingLot

Aplicație web realizată în Java pentru gestionarea mașinilor,
a proprietarilor și a locurilor de parcare.

## Funcționalități

- Adăugarea, afișarea, editarea și ștergerea mașinilor.
- Asocierea mașinilor cu proprietari și locuri de parcare.
- Încărcarea fotografiilor pentru mașini.
- Adăugarea și afișarea utilizatorilor.
- Autentificare și deconectare.
- API REST pentru consultarea mașinilor.

## Tehnologii

Java 21, Jakarta EE 10, Servlets, JSP, JPA, EJB și Gradle.

## Rulare

1. Deschide proiectul într-un IDE cu suport pentru Java și Gradle.
2. Configurează un server compatibil cu Jakarta EE 10 și Java 21.
3. Configurează conexiunea la baza de date prin resursa
   `jdbc/ParkingLotResource` și autentificarea prin
   `jdbcRealmParkingLot`.
4. Generează fișierul WAR folosind `./gradlew war`
   sau `gradlew.bat war` pe Windows.
5. Publică fișierul WAR din `build/libs` pe server
   și accesează aplicația în browser.
