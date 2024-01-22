# V.2
1.. Charakterystyka oprogramowania. 
Nazwa: Webscrapping portali streamingowych.
Opis: Webbscrapping portali streamingowych to narzędzie, które pozwala na sprawdzenie swoich  ulubionych filmów do obejrzenia pod kątem dostępności na różnych  portalach  streamingowych. Działa na zasadzie porównania danych z bazy  oraz docelowej „watchlisty”. Projekt zostały wykonany w środowisku R, przy pomocy programu Rstudio Deskop oraz biblioteki „rvest”.

2.. Prawa autorskie:
Autorzy: Maksymilian Umiński, Przemysław Wałkuski
Licencje: 
RStudio Desktop w wersji darmowej jest ogólnie dostępne do pobrania, instalacji i użytkowania bezpłatnie. Darmowa wersja jest objęta licencją otwartego oprogramowania GPL (General Public License). Warunki licencji GPL umożliwiają swobodne używanie, modyfikowanie i rozpowszechnianie oprogramowania, pod warunkiem zachowania pewnych zasad, takich jak udzielanie innym użytkownikom tych samych swobód. Oznacza to, że stworzony kod jest udostępniony do powszechnego użytkowania.

Licencja - CC BY-NC-SA 4.0

Pakiet rvest jest udostępniany na licencji MIT. Licencja MIT to liberalna licencja typu open source, która umożliwia używanie, modyfikowanie i rozpowszechnianie oprogramowania pod warunkiem dołączenia oryginalnych informacji o prawach autorskich i zastrzeżeń.

3.. Specyfikacja wymagań:
Stałe zaciąganie danych z bazy, tzw. „monitorowanie” portalu w celu odnajdywania i aktualizacji informacji o dostępności poszczególnych filmów.
Porównywanie watch listy z bazą filmów, gdzie otrzymany wynik jest informacją - JAKI film oraz na JAKIEJ platformie się znajduje.

4.. Architektura środowiska
- Rstudio - RStudio to środowisko programistyczne do języka programowania R. Język R jest używany do analizy danych, statystyki, wizualizacji danych i innych zastosowań związanych z analizą danych. RStudio zapewnia rozbudowane narzędzia, które ułatwiają pracę z językiem R, zarządzanie projektem, analizę danych i tworzenie raportów.
  
- Rvest package - Biblioteka programu R, która służy do web scrapingu, czyli ekstrakcji danych z stron internetowych. Pozwala na łatwe pobieranie i analizowanie danych z witryn online.
  
- Upflix.pl  - strona, z której zaciągane są filmy. Jest to strona internetowa, która na bieżąco śledzi zmiany w polskiej ofercie najpopularniejszych platform VOD w Polsce: Netflix, Disney+, HBO Max, SkyShowtime, Amazon Prime Video, Cineman, Polsat Box Go, Rakuten, iTunes, Player, VOD.pl, TVP VOD, Apple TV+, PLAY NOW, Canal+, CDA Premium, Ninateka, E-Kino Pod Baranami, MOJEeKINO, Nowe Horyzonty, FilmBox+, Pięć Smaków, VOD.MDAG.PL, Katoflix, Outfilm, Viaplay, Loomi, 35mm.online, FlixClassic, VOD Warszawa, CHILI, RED GO, Megogo, ARTE po polsku, TVSmart.
  
- IMBD – strona, z której zaciągana jest „watchlista”. Jest to popularna witryna internetowa zawierająca obszerne informacje na temat filmów, programów telewizyjnych, aktorów, reżyserów, scenarzystów, producentów i innych osób związanych z przemysłem filmowym. W celu wykonania takiej listy, użytkownik musi stworzyć swoje, własne prywatne konto.

5.. Scenariusz testów:
1. Nastapi zmiana adresu portalu.
2. Na portalu nastąpi awaria.
