Wearables Health‑Score Prediction

Cel projektu: Zbudowanie modeli regresyjnych, które na podstawie danych z urządzeń wearable (krokomierz, puls, sen itp.) przewidują ciągły wskaźnik Health_Score opisujący ogólną kondycję użytkownika.

Opis projektu:

Projekt demonstruje kompletny pipeline ML — od pobrania danych, ich czyszczenia i eksploracji, przez inżynierię cech, aż po budowę i ewaluację kilku modeli regresji.  Głównym plikiem jest notatnik projekt.ipynb, w którym kolejno:

pobieramy publiczny zbiór Wearables Dataset za pomocą biblioteki kagglehub,

łączymy i porządkujemy źródła („activity”, „sleep”, „nutrition” …​),

konstruujemy zmienną celu Health_Score (średnia wybranych metryk),

przygotowujemy macierz cech (m.in. Steps, Heart_Rate, Calories_Burned, Sleep_Duration, Body_Fat_Percentage, …​),

trenujemy i porównujemy modele: LinearRegression, Lasso, RandomForestRegressor,

szacujemy MSE i R² oraz analizujemy ważność cech.

Repozytorium może służyć jako punkt wyjścia do własnych eksperymentów z danymi noszonymi (wearables) — np. przewidywania spalonych kalorii, personalizacji treningów czy wczesnego wykrywania anomalii zdrowotnych.

