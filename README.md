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
   - fastqc *.fasta.gz
2. Si tiene buena calidad continuamos , sino hay que hacer una limpieza de los datos
## Instalar trimomatic 
- conda install -c bioconda trimmomatic
- trimmomatic
