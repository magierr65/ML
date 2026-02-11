**ML — Machine Learning Sandbox**

Repozytorium dedykowane eksperymentom, analizie danych oraz wdrażaniu modeli uczenia maszynowego. Projekt jest zoptymalizowany pod kątem szybkości i powtarzalności środowiska dzięki wykorzystaniu narzędzia uv.

**O projekcie**

Projekt służy jako baza do codziennej pracy z danymi, obejmując:

    Eksploracyjną analizę danych (EDA) przy użyciu pandas, seaborn i matplotlib.
    Modelowanie ML z wykorzystaniem scikit-learn.
    Interactive Development w środowisku Jupyter.
    Automatyzację jakości kodu dzięki ruff (linting & formatting).

**Tech Stack**

    Język: Python 3.10+
    Zarządzanie pakietami: uv
    Główne biblioteki: numpy, pandas, scikit-learn, matplotlib, tqdm.

**Szybki Start**

Zapomnij o pip install -r requirements.txt. Dzięki uv postawienie środowiska zajmuje sekundy.

    Klonowanie repozytorium:
    Bash

    git clone https://github.com/twoj-uzytkownik/ML.git
    cd ML

    Instalacja środowiska i zależności:
    Bash

    # uv automatycznie stworzy .venv i zainstaluje pakiety z uv.lock
    uv sync

    Aktywacja środowiska:

        Windows: .venv\Scripts\activate
        Linux/macOS: source .venv/bin/activate

**Jakość kodu i rozwój**

W projekcie skonfigurowany jest Ruff, który pilnuje porządku w kodzie.

    Formatowanie i sprawdzanie błędów:
    Bash

    uv run ruff check --fix
    uv run ruff format

    Pre-commit: Jeśli chcesz, aby błędy były sprawdzane automatycznie przed każdym git commit, uruchom:
    Bash

    uv run pre-commit install

**Autor**

Jakub Magierski