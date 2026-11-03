# Filmsamling

Et konsolprogram, der holder styr på en samling film (opret, vis, søg, redigér og slet).

## Gruppe

 Navn 
Amin Mosawi
Suleiman Mohamud
## Sådan kører du programmet

- JDK: skriv den version, I bruger (fx 21)
- Klassen med `main`: `Main`
- Kør `Main` i IntelliJ.
- Tests ligger i `src/test/java` og køres med JUnit 5.

## User stories

Færdige: skriv numrene (fx US1, US2, US3)

Ikke nået: skriv numrene og vær ærlige (fx US7, US8, US18)

## Dokumentation

- Klassediagram: [docs/klassediagram.md](docs/klassediagram.md)
- FURPS-krav: [docs/furps.md](docs/furps.md)

KRAV:

# FURPS-krav til Filmsamling

Mindst ét krav pr. bogstav. Ret kravene, så de passer til jeres program.

## F – Functionality (funktionalitet)

- Brugeren kan oprette, vise, søge, redigere og slette film i samlingen.
- Brugeren kan søge efter en film på en del af titlen.

## U – Usability (brugervenlighed)

- Menuen og alle beskeder til brugeren er på dansk.
- Menuen vises igen efter hver handling, så brugeren altid kan se sine valg.

## R – Reliability (pålidelighed)

- Programmet går ikke ned, hvis brugeren skriver tekst, hvor der skal stå et tal.
- Samlingen gemmes i en fil, så filmene ikke forsvinder, når programmet lukkes.

## P – Performance (ydeevne)

- Visning og søgning i samlingen sker uden mærkbar ventetid ved op til 1000 film.

## S – Supportability (vedligeholdelse)

- Koden er delt i UserInterface, Controller, MovieCollection og Movie, så hver klasse har ét ansvar.
- Der er JUnit-tests, så fejl bliver fundet, når koden ændres.





