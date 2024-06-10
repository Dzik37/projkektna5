Projekt 2 - Wtyczka do QGIS

1.Wtyczka do programu QGIS pozwala obliczyć różnice wysokości pomiędzy punktami, pole powierzchni dowolengo poligonu oraz kilka opcji powiązanych z poprzednimi.

2.Wymagania techniczne:
-system operacyjny windows 10 lub 11
-python 3.11.5
-QGIS 3.36.0

3.Funkcje wtyczki:
-obliczenie różnicy wyskości pomiędzy 2 zaznaczonymi punktami
-obliczenie pola powierzchni poligonu (w jednostkacg wybranych przez użytkownika) zawartego pomiędzy zaznaczonymi punktami i narysowanie go w oddzielnej warstwie
-wczytanie pliku txt ze współrzędnymi punktów w układach 1992 i 2000 i narysowanie ich na nowej wsrstwie
-wyświetlanie numerów punktów, którze brały udział w przeprowadzonych obliczeniach
-czyszczenie konsoli wynikowej

4.Pobieranie i aktywacja wtyczki:
Z repozytorium GitHub należy pobrać folder projekt_2_ig i przenieść go do folderu z wtyczkami QGIS. W programie QGIS należy wejść w opcje wtyczki -> zarządzaj wtyczkami i zaznaczyć wtyczkę o nazwie Projekt 2 IG.

5.Opis funkcjonalności wtyczki:
-w górnym okienku należy wybrać warstwę, na której są punkty, dla których chemy wykonywać obliczenia
-aby obliczyć różnicę wysokości pomiędzy punktami należy zaznaczyć dokładnie 2 punkty i kliknąć przycisk "Oblicz różnicę wyskości"
-aby obliczyć pole powierzchni dowolnego poligonu należy zaznaczyć conajmniej 3 punkty oraz wybrać jednostkę w jakiej chcemy otrzymać wynik (dostępne jednostki: metry kwadratowe, ary, hektary)
-aby narysować poligon na podstwaie zaznacziny punktów należy klinąć przycisk "Utwórz poligon"
-aby wczytać plik txt ze współrzędnymi punktów należy w polu "Wybierz plik" wybrać plik txt z naszymi punktami, następnie wybrać w jakim układzie współrzędnych są nasze punkty i w wypadku wybrania układu 2000 należy dodatkowo wybrać strefę ukłądu. Aby punkty zostały narysowane w oddzielnej warstwie należy kliknąć przycisk "Wgraj punkty"
-aby wyczyścić konsole wynikowe należy kliknąć przycisk "Wyczyść wyniki"

6.Pliki wejściowe ze współrzędnymi punktów:
Pliki ze współrzędnymi punktów powinny mieć format txt a dane w pliku powinny być współrzędnymi X Y oddzielonymi spacją. Separatorem dziesiętnym powinna być kropka. Przykładowy wygląd pliku:

6505557.947008692 5698134.984363967
6494228.235143422 5698070.40673962
6495892.9210715005 5700279.960207025




