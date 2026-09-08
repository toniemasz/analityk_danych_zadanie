
# Zadanie 1:

## Wyniki

Różnica xG dla każdego stanu meczu dla obu drużyn.

| Drużyna | Remis | Wygrana | Przegrana |
|---|---:|---:|---:|
| Pogoń Grodzisk Mazowiecki | -0.3141 | 0.0379 | -0.0496 |
| Polonia Bytom | 0.3141 | 0.0496 | -0.0379 |

[Kod rozwiązania](./zadanie1.ipynb)
Dane do analizy zapisane lokalnie jako `data.csv`.


# Zadanie 2


## Podejście

Najpierw określiłbym profil zawodnika X.
Następnie porównałbym go z wahadłowymi Pogoni i ocenił według kryteriów wynikających z jego roli.
Skupiłbym się przede wszystkim na:
- progresji piłki poprzez podania i prowadzenie,
- dryblingach i pojedynkach 1 na 1,
- wejściach w ostatnią tercję,
- tworzeniu sytuacji bramkowych,
- dośrodkowaniach,
- pressingu,
- odbiorach i przechwytach,
- skuteczności w pojedynkach defensywnych.
Większość statystyk analizowałbym per 90 minut, biorąc pod uwagę również liczbę rozegranych minut oraz to, czy zawodnik częściej zaczynał mecze w podstawowym składzie, czy wchodził z ławki.
Sprawdziłbym też lokalizacje jego akcji oraz to, czy podobny poziom utrzymywał w kolejnych meczach.

## Gdzie dane mogą zawieść

StatsBomb dobrze pokazuje działania z piłką i część zachowań defensywnych, ale nie daje pełnego obrazu ruchu bez piłki. 
Dane wskazują miejsce, w którym zawodnik wykonał zarejestrowaną akcję, ale nie pokazują jego pełnego ustawienia ani ruchu bez piłki pomiędzy zdarzeniami.
Trudniej więc dokładnie ocenić overlap, underlap, powroty defensywne, sprinty czy intensywność pracy. Dane nie pokażą też, jakie dokładnie zadania taktyczne zawodnik otrzymał od trenera.
