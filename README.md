# Tesis CIC

Este repositorio contiene el código fuente en LaTeX de mi tesis de maestría en el Centro de Investigación en Computación (CIC) del Instituto Politécnico Nacional.

## Estructura del proyecto

- `main.tex`: Archivo principal que compila toda la tesis.
- `frontmater.tex`: Material preliminar (resumen, agradecimientos, índice, etc.).
- `chapter1.tex` a `chapter6.tex`: Capítulos de la tesis.
- `portada.tex`: Portada de la tesis.
- `bibliography.bib`: Archivo de referencias bibliográficas en formato BibTeX.
- `splncs04.bst`, `UNAMstyle.sty`: Estilos y plantillas para formato y bibliografía.
- `Images/`: Carpeta con imágenes organizadas por experimentos y subcarpetas.

## Compilación

Para compilar la tesis, se recomienda utilizar una distribución de LaTeX completa (por ejemplo, TeX Live). Puedes compilar el documento ejecutando:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Esto generará el archivo `main.pdf` con la versión final de la tesis.

## Requisitos

- [LaTeX](https://www.latex-project.org/)
- [BibTeX](http://www.bibtex.org/)
- Paquetes recomendados: `graphicx`, `amsmath`, `hyperref`, `babel`, entre otros.

## Organización de imágenes

Las imágenes de los experimentos están organizadas en subcarpetas dentro de `Images/expN/`, donde `N` es el número del experimento.

## Licencia

Este proyecto es de uso académico. Para cualquier uso distinto, contactar al autor.
