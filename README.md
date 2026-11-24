# CV w LaTeXu

Jednostronicowe CV napisane w LaTeXu. Repozytorium zawiera **wyłącznie pliki źródłowe**.
PDF generuje się lokalnie, a pliki wynikowe są wykluczone w `.gitignore`.

## Kompilacja

```sh
pdflatex cv.tex        # albo: latexmk -pdf cv.tex
```

Można też wgrać `cv.tex` do [Overleaf](https://www.overleaf.com) (kompilator pdfLaTeX).

## Informacja o użyciu LLM i szablonów

Zgodnie z zasadami zadania informuję, że przy tworzeniu CV korzystałem z modelu
językowego (LLM, asystent Antigravity). Nie korzystałem z gotowych szablonów CV.

**Co zrobił LLM:** zaproponował kod LaTeX (preambuła, styl nagłówków, makro `\pozycja`,
układ sekcji), zredagował opisy i klauzulę RODO, przygotował `.gitignore` i README.

**Mój wkład:** dane i treść CV (wykształcenie, projekty, umiejętności), wykonanie
projektów opisanych w CV, weryfikacja treści i wyglądu (jedna strona),
kompilacja, założenie i prowadzenie repozytorium na GitHubie.
