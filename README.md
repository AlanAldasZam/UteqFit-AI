# UteqFit-AI

Repositorio grupal de Ingeniería de Requerimientos (ISR-401), UTEQ, periodo académico 2026-2027 SPA.

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
- Bibliografía: Biber 2.21, cuando se configure `biblatex`.
- Paquetes LaTeX: los declarados en `main.tex`, instalados mediante MiKTeX.

### Orden de compilación

Desde la carpeta `PFC/E1`:

```bash
pdflatex main.tex
pdflatex main.tex
```

Cuando se incorporen las referencias mediante `biblatex` y Biber:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado será `PFC/E1/main.pdf`.

**Nota:** los comandos deberán comprobarse con la versión definitiva de `main.tex`.

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