# Trabajo Práctico - Legislación

**Evolución del Sistema de Derechos en la Sociedad de la Información: Protección de Menores en Redes Sociales**

Este repositorio contiene un trabajo académico desarrollado en LaTeX.

## Cómo generar el PDF

### Windows

1. **Instalar LaTeX**:
   - Descargar MiKTeX desde https://miktex.org/download
   - Instalar con las opciones por defecto

2. **Compilar el documento**:
   ```cmd
   pdflatex main.tex
   pdflatex main.tex
   ```
   (Ejecutar dos veces para generar correctamente la tabla de contenidos)

3. **Alternativa con editor**:
   - Instalar TeXstudio desde https://www.texstudio.org/
   - Abrir `main.tex` y presionar F5 para compilar

### Linux

1. **Instalar LaTeX**:
   ```bash
   # Debian
   sudo apt update && sudo apt install texlive-full
   
   # Arch
   sudo pacman -S texlive-most texlive-lang
   
   # Fedora
   sudo dnf install texlive-scheme-full
   ```

2. **Compilar el documento**:
   ```bash
   pdflatex main.tex
   pdflatex main.tex
   ```
   (Ejecutar dos veces para generar correctamente la tabla de contenidos)

## Resultado

El archivo `main.pdf` se generará con el trabajo completo listo para presentación.

## Autor

Lucas Eduardo Ramirez Bonch  
Técnico Superior en Análisis de Sistemas - 3er año  
Ciclo Lectivo: 2025  

## Repositorio

https://github.com/Lubonch/TP-Legislacion