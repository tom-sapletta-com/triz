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





Stwórz implementację w języku python algorytmu  ARIZ składającego się z etapów:

    Analizy problemu
    Analizy modelu sytuacji początkowej
    Sformułowania idealnego rozwiązania końcowego, jak i sprzeczności fizycznych
    Zastosowania zasobów teorii wepola (patrz: niżej)
    Zastosowania bazy danych metody TRIZ
    Finalizacji w proponowaniu i zastępowaniu problemu
    W szacowaniu jakości rozwiązania w trybów zażegnywania sprzeczności technicznych
    Maksymalnie możliwego użycia zasobów, walorów otrzymanego rozwiązania
    Nadzoru nad etapem rozwiązania wdrażanego na poziomie przedsiębiorstwa

# importujemy potrzebne biblioteki
import pandas as pd
from triz import *

# tworzymy ramkę danych z danymi wejściowymi
df = pd.DataFrame([
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
])
    
# tworzymy algorytm ARIZ
a = ArizAlgorithm()

# wykonujemy algorytm ARIZ i zapisujemy wynik do zmiennej
result = a.run(df)

# wyświetlamy wynik
print(result)

# analizujemy problem
problem_analysis = a.analyze_problem(df)

# analizujemy model sytuacji początkowej
initial_model_analysis = a.analyze_initial_model(df)

# sformułowujemy idealne rozwiązanie końcowe oraz sprzeczności fizyczne
ideal_final_solution_and_contradictions = a.formulate_ideal_final_solution_and_contradictions(df)

# zastosowanie zasobów teorii wepola
wepola_theory_resources = a.apply_wepola_theory_resources(df)

# zastosowanie bazy danych metody TRIZ
triz_database = a.apply_triz_database(df)

# finalizacja w proponowaniu i zastępowaniu problemu
finalize_problem_proposal_and_replacement = a.finalize_problem_proposal_and_replacement(df)

# szacowanie jakości rozwiązania w trybach zażegnywania sprzeczności technicznych
estimate_quality_of_solution_in_conflict_resolution_modes = a.estimate_quality_of_solution_in_conflict_resolution_modes(df)

# maksymalne wykorzystanie zasobów, walorów otrzymanego rozwiązania
maximize_resource_and_value_utilization_of_obtained_solution = a.maximize_resource_and_value_utilization_of_obtained_solution(df)

# nadzór nad etapem rozwiązania wdrażanego na poziomie przedsiębiorstwa
supervise_implementation_of_solution_at_enterprise_level = a.supervise_implementation_of_solution_at_enterprise_level(df)
