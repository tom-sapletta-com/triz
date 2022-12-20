# triz
triz python


import pandas as pd
from triz import *

# tworzymy ramkę danych z danymi wejściowymi
df = pd.DataFrame([
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
])

# tworzymy algorytm TRIZ
t = TrizAlgorithm()

# wykonujemy algorytm TRIZ i zapisujemy wynik do zmiennej
result = t.run(df)

# wyświetlamy wynik
print(result)
