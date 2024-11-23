# Aplikacja Paint by CatDeveloper

<img src="Paint_ico.png" align="right" width="128">

Ta aplikacja to prosty program do rysowania, stworzony przy użyciu Python, Tkinter i Matplotlib.  Umożliwia ona tworzenie rysunków za pomocą myszki, z możliwością wyboru koloru i grubości linii.  Zapisuje rysunki w formatach PNG i JPG.


## Funkcjonalność:

* **Rysowanie:** Tworzenie rysunków za pomocą myszki.
* **Wybór koloru:**  Duża paleta kolorów do wyboru.
* **Grubość linii:**  Regulacja grubości linii rysowania.
* **Zapisywanie:**  Zapisywanie rysunków do plików PNG i JPG.
* **Czyszczenie obrazu:**  Przycisk do czyszczenia całego obszaru rysowania.
* **Prosty interfejs:**  Intuicyjny i łatwy w użyciu interfejs użytkownika.


## Ważne informacje:

* **Plik `kolory.json`:** Aplikacja korzysta z pliku `kolory.json` do przechowywania palety kolorów.  **Każda, nawet najmniejsza, modyfikacja tego pliku ręcznie może spowodować uszkodzenie aplikacji.** Jeśli wystąpią problemy, usuń plik `kolory.json` – aplikacja automatycznie wygeneruje nowy plik z domyślną paletą kolorów podczas kolejnego uruchomienia.

## Instalacja:

1.  Upewnij się, że masz zainstalowane Pythona (wersja 3.7 lub nowsza) oraz biblioteki:
    ```bash
    pip install matplotlib numpy Pillow
    ```
2.  Pobierz pliki aplikacji (main.py, gui.py, logic.py, Paint.ico).
3.  Uruchom plik `main.py`.


## Utworzenie pliku wykonywalnego (EXE):

Do utworzenia pliku wykonywalnego (EXE) użyj PyInstaller:

1. Zainstaluj PyInstaller:  `pip install pyinstaller`
2. Uruchom w konsoli: `pyinstaller --onefile --icon=Paint.ico main.py gui.py logic.py`


## Autor:

CatDeveloper


---
<div align="right">
  <small>v1.0</small>
</div>
