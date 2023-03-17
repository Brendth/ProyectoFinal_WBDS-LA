# ProyectoFinal_WBDS-LA
Brenda Torres Huerta

El objetivo de este proyecto fue analizar el genoma de la bacteria gram negativa "Serratia marcescens", un patógeno oportunista de insectos que causa bacteriemia en la hemolinfa y genera una muerte rápida. 

A partir de la predicción de genes, realicé una búsqueda de las secuencias que codifican el factor de virulencia llamado serralisina, que tiene actividad insecticida al degradar los factores inmunes en insectos, en específico, degradan e inactivan diversas proteínas y péptidos antimicrobianos. 

La serralisina es una metaloproteasa conservada en varias especies de bacterias, que se caracteriza por un motivo de unión al zin (HEXXHXXGXXHZ).

Este proyecto abarca la:

1) Predicción de genes en un genoma bacteriano
2) Búsqueda de secuencias de proteínas de referencia relacionadas con serralisinas en la base de datos UniprotKB
3) Análisis de homología con BLASTp
4) Visualización de resultados de anotación con pyCirclize
5) Análisis funcionales con InterPro
6) Análisis filogenéticos


1. Paquetes requeridos para ejecutar el código:

pyCirclize: para visualizar nuestros datos genómicos
pyrodigal: para la predicción de genes codificantes
requests: para interactuar con las APIs de NCBI, UniProt e InterProScan
seaborn: para visualizar algunas de las propiedades genómicas obtenidas
subprocess: ejecutar comandos fuera del entorno de python
BioPython: para el manejo de secuencias
io: para conectar las entradas y salidas de los distintos programas
pandas:para el manejo general de datos

2. Programas adicionales

- blast-2.3.0
ftp://ftp.ncbi.nlm.nih.gov/blast/executables/LATEST/ncbi-blast-2.3.0+-x64-linux.tar.gz
- MAFFT
https://mafft.cbrc.jp/alignment/server/
-Aliview
https://ormbunkar.se/aliview/
-ModelTest-NG
https://github.com/ddarriba/modeltest
-beast2
http://www.beast2.org/
-iTOL
https://itol.embl.de/

3. Corrida: 
Toda la información requerida para la ejecución del código se encuentra en el archivo BrendaTorresHuerta_ProyectoFinal.ipynb.
En este notebook encontrarán la información necesaria para reproducir los diferentes análisis.
Como mencioné, se utilizaron programas adicionales, los cuáles también se encuentran específicados en BrendaTorresHuerta_ProyectoFinal.ipynb
