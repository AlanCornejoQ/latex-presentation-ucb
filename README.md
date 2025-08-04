# Beamer Theme UCB (Modo Claro)

Plantilla Beamer en LaTeX para presentaciones académicas de la  
Universidad Católica Boliviana San Pablo, en estilo claro y colores institucionales.

## Características

- Modo claro con fondo blanco y texto oscuro.
- Colores configurables según carrera:
  - IMT (Mecatrónica): #5576A1
  - SIS (Sistemas): #3CA5CF
  - INB (Biomédica): #2DB6A8
- Portada con diseño dividido: título a la izquierda, logo opcional a la derecha.
- Admite correo electrónico del autor.
- Integración con bibliografía BibTeX.
- Compatible con Overleaf y compiladores LaTeX locales.

## Uso

1. Cargar el tema y definir la carrera:

   ```latex
   \usepackage{beamerthemeucb}
   \setcarrera{IMT} % Opciones válidas: IMT, SIS, INB
   ```
2. Completar los datos de la presentación:
```latex
\title{Título de la presentación}
\author{Nombre del autor}
\email{correo@ucb.edu.bo}
\institute{Facultad o unidad académica}
```
3. Compilar

### Licencia
Este proyecto se distribuye bajo la licencia MIT.