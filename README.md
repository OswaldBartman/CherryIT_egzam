# README.md

README.md is now an example file.  

## Tytuł: Automatron - Nie działająca funkcja "Send Key" z "calc.exe" 

Środowisko testowe: Komputer z systemem Windows 10, wersja 1909 Program: Automatron 

### Autor przypadku testowego: Oswald Bartman 

#### Kroki do wykonania: 

1. Uruchom jako administrator program Automatron.exe 
2. Naciśnij przycisk "+ Add Next Step" i wybierz funkcję "Run Command" 3. W białym pustym polu wpisz "calc.exe" 
4. Naciśnij przycisk "+ Add Next Step" i wybierz funkcję "Delay", w polu "Delay" wpisz wartość np. 3000 
5. Naciśnij przycisk "+ Add Next Step" i wybierz funkcję "Send Key", kliknij na pole "Type Keys to Send Here" i wybierz dowolną cyfrę na klawiatury, np. "1" (powinno się wyświetlić "D1") 
6. Kliknij na przycisk "Select Process From List" i wybierz proces o nazwie "kalkulator", (może być o nazwie Calculator, calc.exe, Kalkulator), wymaż dane z wiersza "id", jeśli taki proces nie występuje w wierszu o nazwie "Name" wpisz "Calculator". 7. Naciśnij przycisk "START" w lewym górnym rogu okna aplikacji.
 
##### Oczekiwany rezultat: 

Po wykonaniu wszystkich kroków z powyższych punktów w aplikacji "Kalkulator" wyświetla się cyfra "1".
