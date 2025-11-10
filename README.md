# Projekt: Bioróżnorodność i ekosystemy

## Opis projektu

Ten dokument zawiera materiały edukacyjne w formacie reStructuredText (`.rst`) dotyczące **bioróżnorodności i funkcjonowania ekosystemów**, przygotowane do publikacji w formie pliku pdf lub strony HTML przy użyciu **Sphinx** z motywem **Furo**.

Dokument obejmuje trzy rozdziały, które szczegółowo omawiają znaczenie bioróżnorodności, jej poziomy, usługi ekosystemowe oraz zagrożenia i działania ochronne.

---

## Zawartość dokumentu

- `rozdzial1/index.rst` – Znaczenie bioróżnorodności dla funkcjonowania ekosystemów oraz różnorodność biologiczna i jej poziomy.
- `rozdzial2/index.rst` – Znaczenie bioróżnorodności dla stabilności ekosystemów i usługi ekosystemowe wynikające z bioróżnorodności.
- `rozdzial3/index.rst` – Zagrożenia dla bioróżnorodności, ochrona i zachowanie różnorodności biologicznej wraz z tabelą działań ochronnych oraz podsumowaniem.
- `rozdzial2/zdjecie.png` – Przykładowa ilustracja odnośnie bioróżnorodności.
- `conf.py` – Plik konfiguracyjny Sphinx.

---

## Format i użycie

Dokumenty zapisane są w formacie **reStructuredText (`.rst`)**, który jest natywnie wspierany przez Sphinx. Pliki zawierają:

- nagłówki rozdziałów i podrozdziałów,
- akapity opisowe,
- liste numerowaną,
- tabele ilustrujące działania ochronne,
- wstawiony obraz z opcją wyśrodkowania.

**Uwaga:** Do poprawnego zbudowania pliku HTML wymagana jest instalacja motywu **Furo**.
Można go zainstalować w środowisku Python za pomocą:

```bash
pip install furo
```
Po czym w celu zbudowaniu dokumentu HTML należy wywołać komendę:

```bash
make html
```
