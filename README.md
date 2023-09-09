# python_latex
Generación de pruebas parametrizables con python y latex


Instrucciones

1. Abrir en cualquier editor de Python, el archivo code.py.
2. Para generar los archivos .tex descomentar (quitar el #) alguna de las líneas finales
del archivo que están al final y salvar.

m=10 
#ejer1(m)
#ejer2(m)

3. Ejecutar el archivo code.py

4. Para generar los archivos en .pdf, abra la terminal de comandos y ubíquese en la carpeta tex
y ejecute la siguiente línea de comando según el sistema operativo:

# GNU-Linux
# for i in *.tex; do pdflatex $i; done && rm *.aux *.log *.tex

# MS Windows
#  FOR \%i IN (*.tex) DO pdflatex %i &&  DEL *.log *.aux *.out
