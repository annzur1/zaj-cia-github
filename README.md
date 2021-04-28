# zaj-cia-github


def rownowaznosc(zmiennaP, zmiennaQ):
    if (zmiennaP== 0 and zmiennaQ == 0) or (zmiennaP== 1 and zmiennaQ == 1):
        return "True"
    elif (zmiennaP== 0 and zmiennaQ == 1) or (zmiennaP== 1 and zmiennaQ == 0):
        return "False"
    else:
        return "Funkcja pobiera tylko wartosci 0 i 1!"

#Prezentuje działanie funkcji dla wszystkich możliwych kombinacji:

liczba_g = 1
liczba_h = 1
wynik = rownowaznosc(liczba_g,liczba_h)
print(wynik)

liczba_a = 1
liczba_b = 0
wynik = rownowaznosc(liczba_a,liczba_b)
print(wynik)

liczba_c = 0
liczba_d = 1
wynik = rownowaznosc(liczba_c,liczba_d)
print(wynik)

liczba_e = 0
liczba_f = 0
wynik = rownowaznosc(liczba_e,liczba_f)
print(wynik)

