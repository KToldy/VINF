# VINF
Python PageRank Solution
V tomto repozitári nájdete riešenie na predmet Vyhľadávanie Informácií.

Zadanie: Vypočítanie page ranku stránok, štatistika uzlov (Python)

Príprava na spustenie softvéru:

* Inštalácia Jupyter Nooteboku z https://jupyter.org/install
* Spustenie JupyterNooteboku
* Skopírovanie riešenia z public github repozitáru: https://github.com/KToldy/VINF
* V prípade potreby, doinštalovanie chýbajúcich knižníc pomocou: pip install nazov_kniznice
* Použitie algoritmu

Použitie softvéru:

* Načítanie súboru: parser.parse(Path_to_file)
* Spustenie Spracovania linkov, sparse matici a pageranku
* Spustenie vytvorenie indexovania
* Následne nad indexom môžeme hľadať pomocou funkcie hladaj(search_term)