# tis-klein-gordon-solitons

Komplexná štúdia statických, **radiálne symetrických solitónov** v nelineárnom Klein–Gordonovom modeli s exponenciálnou nelinearitou.  
Repozitár obsahuje:

* kompletný LaTeX zdroj článku,  
* numerické skripty a vstupné dáta,  
* finálny PDF preprint.

---

## Hlavný článok

**PDF:** [`docs/Klein-Gordon_Solitons_Working_Paper_v1.0.pdf`](./docs/Klein-Gordon_Solitons_Working_Paper_v1.0.pdf)  
**Dátum:** 2. augusta 2025  
**Autori:** Kamil Vargovský, Mária Vargovská  

---

## Abstrakt

Predkladáme kompletnú analýzu statických, energeticky konečných riešení nelineárnej Klein–Gordonovej rovnice v ℝ³ s exponenciálnou nelinearitou.  
Numerickými metódami (_shooting_) určujeme rodinu solitónov, mapujeme jej parametrické vlastnosti, testujeme lineárnu aj plnú dynamickú stabilitu a aplikujeme metódu posúvajúcich sa rovín na dôkaz jedinečnosti a radiálnej symetrie riešenia. Výsledky preukazujú existenciu stabilných, lokalizovaných riešení pre parametre spĺňajúce podmienku **γ > 2 |α| / β** a potvrdzujú ich robustnosť voči poruchám.

---

## Štruktúra repozitára

| Súbor / priečinok | Popis                                                     |
|-------------------|-----------------------------------------------------------|
| `main.tex`        | Hlavný LaTeX súbor článku                                 |
| `sec_*.tex`       | Jednotlivé kapitoly (model, numerika, dynamika, …)        |
| `soliton_refs.bib`| Bibliografia                                              |
| `fig/`            | Obrázky a grafy (PDF)                                     |
| `scripts/`        | Python notebooky a skripty (shooting, dynamika, spektrum) |
| `docs/`           | Vygenerovaný PDF článok                                   |

---

## Reprodukcia výsledkov

```bash
# 1 | Klonuj repozitár
git clone https://github.com/kamilvargovsky-cmd/tis-klein-gordon-solitons.git
cd tis-klein-gordon-solitons

# 2 | Kompiluj PDF (vyžaduje TeX distribúciu s latexmk)
latexmk -pdf main.tex
```

Numerické simulácie a spektrálnu analýzu zreprodukuješ spustením Jupyter notebookov alebo skriptov v priečinku `scripts/`.

---

## Ako citovať

```bibtex
@misc{vargovsky2025kleingordon,
  author       = {Kamil Vargovský and Mária Vargovská},
  title        = {Radiálne symetrické solitóny v nelineárnom Klein--Gordonovom modeli:
                   Numerika, dynamika a dôkaz prísnej jedinečnosti},
  year         = {2025},
  howpublished = {\url{https://github.com/kamilvargovsky-cmd/tis-klein-gordon-solitons}},
  note         = {Version 1.0}
}
```

---

## Licencia

Copyright © 2025 Kamil Vargovský  
Distribuované pod licenciou **MIT** (viď súbor `LICENSE`).

---

## Kontakt

E-mail: **kamil.vargovsky@gmail.com**  

Otázky, bug-reporty napíšte priamo na uvedený e-mail.
