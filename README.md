To repozytorium jest forkiem kursowego projektu źródłowego: [ArtuDitu/AnalizaDanychPythonKurs](https://github.com/ArtuDitu/AnalizaDanychPythonKurs), rozwijanym lokalnie na potrzeby prowadzenia zajęć z analizy danych w Pythonie. Zawiera materiały dydaktyczne, ćwiczenia i dane robocze do pracy krok po kroku podczas laboratoriów.

Celem repozytorium jest przeprowadzenie studentów przez praktyczny workflow: od poprawnego importu danych, przez czyszczenie i podstawową analizę w `pandas`, po organizację pracy w `Git/GitHub`. 

## Praktyczne informacje

### Dla studentów
- Uruchom środowisko zgodnie z instrukcją w notatniku (`python3 -m venv .venv`, aktywacja, instalacja pakietów) lub przez `uv`.

## Opcjonalnie: uv

Repozytorium wspiera także `uv` (alternatywa dla ręcznego `venv + pip`):

```bash
uv sync
uv run jupyter notebook
```

Jeśli chcesz uruchamiać pojedyncze skrypty/testy:

```bash
uv run python skrypt.py
```
Jeśli kiedykolwiek launcher `jupyter` się rozjedzie, awaryjnie działa też:

```bash
uv run python -m notebook
```
