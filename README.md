# Projekt-studia
⚽ Football Simulator (Unity + C++ Engine)
Projekt zaawansowanego symulatora rzutów karnych, w którym logika decyzyjna i obliczeniowa została przeniesiona do natywnej biblioteki DLL napisanej w C++.
🚀 Główne Funkcje
Natywny Silnik C++: Obliczanie siły strzału oraz logika AI bramkarza odbywa się poza środowiskiem Unity (C#).

System Celowania: Dynamiczne celowanie za pomocą strzałek z wykorzystaniem normalizacji wektorów, co zapewnia stałą siłę strzału niezależnie od kierunku.

Fizyka Siatki: Zastosowanie materiałów fizycznych (Physic Materials) sprawiających, że piłka realistycznie zatrzymuje się w siatce.

System Detekcji Goli: Skrypt GoalDetector monitoruje strefę bramki, aktywując efekty dźwiękowe i UI (TextMeshPro).

🛠 Technologie
Silnik: Unity 6 (6000.0.4f1)

Języki: C# (skrypty Unity), C++ (silnik logiczny)

Środowisko: Visual Studio 2022

Komunikacja: DllImport (P/Invoke)

🎮 Instrukcja Sterowania
Strzałki (Lewo/Prawo): Celowanie przed strzałem.

Spacja: Oddanie strzału (pobiera moc z DLL).

Klawisz R: Pełny reset sceny (piłka, bramkarz, dźwięki i napisy).

📂 Struktura Projektu
/Assets - Zasoby Unity (skrypty C#, modele, dźwięki).

/Plugins - Skompilowana biblioteka Football_project.dll.

/CPP_Source - Kod źródłowy silnika w C++ (dllmain.cpp, pch.cpp, logika AI).
