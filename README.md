# R_klasyfikacja

1. Wybrany zbiór danych powinien być dostosowany albo do zadania regresji albo klasyfikacji.
Powinien zawierać przynajmniej 100 obserwacji, a ze względu na użycie sieci neuronowych tak
naprawdę zbiór powinien być znacznie większy. Górnego ograniczenia wielkości zbioru nie ma,
chociaż warto zauważyć że przy zbiorach mających więcej niż kilka tysięcy obserwacji, modele
pewnie będą dość długo się liczyć. Na początku projektu należy opisać, czego dotyczy zbiór
(temat i cel projektu), jakie zawiera cechy, jaka obróbka danych została wykonana (np.
oczyszczanie braków danych, dodanie nowej kolumny, usunięcie kolumny itp.). Przed budową
modeli powinien się znajdować krótki opis podstawowych statystyk dla cech w zbiorze, ze
szczególnym naciskiem na zmienną zależną. Na końcu projektu powinno znajdować się
podsumowanie/wnioski.
2. Budowa modeli klasyfikacji lub regresji: podział zbioru na uczący i testowy, wytrenowanie co
najmniej 4 różnych modeli (dobór parametrów, predykcja na zbiorze testowym, określenie
najistotniejszych cech, obliczenie metryk jakości działania). Modele porównać na koniec tego
rozdziału lub w podsumowaniu/wnioskach. Porównanie powinno być na podstawie dwóch różnych
metryk jeśli jest to możliwe (w przypadku regresji np. R^2 i RMSE lub MAE, w przypadku
klasyfikacji accuracy i F1 lub AUC).
3. Model sztucznej sieci neuronowej odpowiedni do regresji lub klasyfikacji (zależnie od
wybranego zbioru) – dobór parametrów, ocena jakości działania, porównanie z wcześniej
zbudowanymi modelami uczenia maszynowego (również można porównać albo w tym miejscu
albo w podsumowaniu).
4. Zaprezentowanie i porównanie co najmniej dwóch wybranych metod redukcji wymiarów oraz
dwóch wybranych metod grupowania (clustering) obserwacji (może to być „bez związku” ze
wcześniejszymi analizami, nie każdy zbiór będzie taki że wymaga redukcji wymiarów, więc
bardziej chodzi o zaprezentowanie że grupa umie takie metody zastosować, niż żeby osiągnąć tutaj
sensowny wynik)
