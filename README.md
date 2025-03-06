### Comanditos utiles
1. copiar un archivo de un directorio a otro
   - cp archivo_R2.fastq.gz /home/prince/enterovirus/carpeta_donde_copia_archivo
     
2. eliminar un archivo
   - rm nombre_del_archivo.fasta
3. Contar el número de secuencias (lecturas) en un archivo FASTQ comprimido.
   - zcat xxxxxx_R1.fastq.gz | grep "^@" | wc -l
4. eliminar los archivos de un directorio
   - rm -rf * 


### Analisis data
## Instalar FastQC
1. Ir a https://www.bioinformatics.babraham.ac.uk/projects/fastqc/
   - Darle Download Now
   - Selecionar el programa que desee instalar en este caso FastQC
   - Anticlick y copiar URL (puede ser para linux o windons)
   - usar wget https://www.bioinformatics.babraham.ac.uk/projects/fastqc/fastqc_v0.12.1.zip (en la terminal)
   - ls (observamos que estea nustro fichero fastqc_v0.12.1.zip)
   - unzip fastqc_v0.12.1.zip
   - ls
   - cd FastQC
   - chmod 777 fastqc
   - fastqc *.fastq.gz (todos los archivos)
   - fastqc 16157AADMX_S2_L001_R1_001_paired.fastq.gz 16157AADMX_S2_L001_R2_001_paired.fastq.gz (archivo por archivo)

2. Si tiene buena calidad continuamos , sino hay que hacer una limpieza de los datos
## Instalar trimomatic 
- conda install -c bioconda trimmomatic
- trimmomatic
- 
