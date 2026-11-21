# UteqFit-AI

Repositorio grupal de Ingeniería de Requerimientos (ISR-401), UTEQ, periodo académico 2026-2027 SPA.

## Integrantes

- Aldas Zambrano Alan Andrés
- Briones Solorzano William Adrian
- Lavayen Bone Cristopher Javier
- Monserrate Ochoa Erick Ariel

## Estructura del repositorio

```text
UteqFit-AI/
├── .gitignore
├── README.md
└── PFC/
    └── E1/
        ├── main.tex
        ├── main.pdf
        ├── referencias.bib
        ├── secciones/
        ├── figuras/
        ├── modelos/
        ├── instrumentos/
        └── evidencias/
```

Algunos archivos y carpetas se incorporarán conforme avance la entrega.

## TA-PFC-E1: Proyecto Fin de Curso - Entrega 1

### Archivo principal

`PFC/E1/main.tex`

### Compilador y dependencias

- Compilador: pdfLaTeX (MiKTeX 25.12).
- Bibliografía: BibTeX con el estilo `IEEEtran` (paquete `ieeetran` de MiKTeX); las referencias están en `referencias.bib`.
- Paquetes LaTeX: los declarados en `main.tex`, instalados mediante MiKTeX.

### Orden de compilación

Desde la carpeta `PFC/E1`:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

El resultado es `PFC/E1/main.pdf`.

## Archivos de la entrega

- `secciones/`: archivos LaTeX que forman parte del documento principal.
- `figuras/`: imágenes utilizadas en el informe.
- `modelos/`: archivos editables de los diagramas.
- `instrumentos/`: guion de entrevista, cuestionario y guía de observación.
- `evidencias/`: registros y manifiesto de evidencias.
- `referencias.bib`: referencias bibliográficas.
- `main.pdf`: documento compilado.

## Estado

Entrega en desarrollo. Los archivos pendientes serán incorporados por los integrantes del equipo.