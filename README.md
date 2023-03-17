#ProyectoFinal_WBDS-LA

**Brenda Torres Huerta**

El **objetivo** de este proyecto fue analizar el genoma de la bacteria gram negativa *Serratia marcescens*, un patógeno oportunista de insectos que causa bacteriemia en la hemolinfa y genera una muerte rápida. 

A partir de la predicción de genes, realicé una búsqueda de las secuencias que codifican el factor de virulencia llamado **serralisina**, que tiene actividad insecticida al degradar los factores inmunes en insectos, en específico, degradan e inactivan diversas proteínas y péptidos antimicrobianos. 

La **serralisina** es una metaloproteasa conservada en varias especies de bacterias, que se caracteriza por un motivo de unión al zin (HEXXHXXGXXHZ).

Este proyecto abarca la:

1) Predicción de genes en un genoma bacteriano
2) Búsqueda de secuencias de proteínas de referencia relacionadas con serralisinas en la base de datos UniprotKB
3) Análisis de homología con BLASTp
4) Visualización de resultados de anotación con pyCirclize
5) Análisis funcionales con InterPro
6) Análisis filogenéticos


**Paquetes requeridos para ejecutar el código:**

1) *pyCirclize*: para visualizar nuestros datos genómicos
2) *pyrodigal*: para la predicción de genes codificantes
3) *requests*: para interactuar con las APIs de NCBI, UniProt e InterProScan
4) *seaborn*: para visualizar algunas de las propiedades genómicas obtenidas
5) *subprocess*: ejecutar comandos fuera del entorno de python
6) *BioPython*: para el manejo de secuencias
7) *io*: para conectar las entradas y salidas de los distintos programas
8) *pandas*:para el manejo general de datos

**2. Programas adicionales**

1) blast-2.3.0: ftp://ftp.ncbi.nlm.nih.gov/blast/executables/LATEST/ncbi-blast-2.3.0+-x64-linux.tar.gz
2) MAFFT: https://mafft.cbrc.jp/alignment/server/
3) Aliview: https://ormbunkar.se/aliview/
4) ModelTest-NG: https://github.com/ddarriba/modeltest
5) beast2: http://www.beast2.org/
6) iTOL: https://itol.embl.de/

**3. Corrida:**

Toda la información requerida para la ejecución del código se encuentra en el archivo **BrendaTorresHuerta_ProyectoFinal.ipynb**. En este notebook encontrarán la información necesaria para reproducir los diferentes análisis. Como mencioné, se utilizaron programas adicionales, los cuáles también se encuentran específicados en BrendaTorresHuerta_ProyectoFinal.ipynb
