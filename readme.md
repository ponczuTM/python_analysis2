Plik student-matA.csv zawiera dane o 395 uczniach pewnej portugalskiej szkoły średniej. Opis poszczególnych zmiennych znajduje się w pliku student.txt.
Zmienne G1, G2 oraz G3 odnoszą się do ocen uzyskanych przez tych uczniów na koniec poszczególnych okresów.
Oczywiście są ze sobą ściśle skorelowane. Zmienną celu będzie G3, a wśród wybranych predyktorów nie może znaleźć się ani G1 ani G2.

Wykonaj poniższe polecenia w dowolnie wybranym programie, a następnie przedstaw wyniki swoich analiz w postaci raportu.
Dokonaj wyboru predyktorów. Oceń jakość danych, dokonaj niezbędnych korekt, jeśli to konieczne.
Podziel dane na zbiór uczący i testowy, ustawiając numer indeksu jako ziarno generatora liczb losowych.
Dla danych ze zbioru uczącego wykonaj eksploracyjną analizę danych. Zidentyfikuj, które spośród wybranych zmiennych mogą mieć największy wpływ na ocenę G3. Zbadaj, które zmienne są ze sobą skorelowane.
Potraktuj ocenę G3 jako zmienną jakościową. Na zbiorze uczącym zbuduj dowolny model klasyfikacji i oceń jego jakość na zbiorze testowym. Wyznacz 3 miary jakości modelu: trafność, trafność z dopuszczalnym odstępstwem o 1 (tzn. uznajemy, że model dobrze przewidział jakąś wartość, jeśli odgadł właściwie ocenę lub pomylił się o 1 w dół lub w górę) oraz  średni błąd bezwzględny MAE.
Potraktuj ocenę G3 jako zmienną ilościową. Na zbiorze uczącym zbuduj dowolny model szacowania i oceń jego jakość na zbiorze testowym. Zaokrąglij przewidywane wartości oceny G3 do całości. Następnie wyznacz 3 miary jakości modelu: trafność, trafność z dopuszczalnym odstępstwem o 1 (tzn. uznajemy, że model dobrze przewidział jakąś wartość, jeśli odgadł właściwie ocenę lub pomylił się o 1 w dół lub w górę) oraz średni błąd bezwzględny MAE.
Który ze zbudowanych modeli okazał się lepszy? Które z wybranych zmiennych mają największy wpływ na ocenę G3? Czy potwierdza to Twoje obserwacje z punktu 3.?