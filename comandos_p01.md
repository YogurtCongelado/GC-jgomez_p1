# Comandos de la Práctica 01
## Nombre(s) Apellido(s)

# Parte I. 

**Respuesta 1:**


/usr/bin/bash

**Respuesta 2:**


mkdir data filtered raw_data meta scripts figures archive


**Respuesta 3:**

mv filtered data ; mv raw_data data

**Respuesta 4:**

- "data" es la carpeta guarda todos los tipos de datos que utilizamos
- "meta" contiene info que describe la info del proyecto
- "scripts" es para guardar codigo fuente 
- "figures" guarda las figuras o graficas
- "archives" contiene informacion privada 

# Parte II.

**Respuesta 1:**

chmod +x delay.sh

**Respuesta 2:**

ls -l

**Respuesta 3:**

sleep 30

**Respuesta 4:**

./delay.sh &
kill pid

# Parte III.
**Respuesta 1:**
touch SarsCov-2.txt

nano SarsCov-2.txt

**Respuesta 2:**


mv sequence.fasta x_sequence.fasta
mv sequence.gff3 x_sequence.gff3
                 .
                 .
                 .
mv sarscov2_assembly.fasta.gz Dir/raw_data 


# Parte IV.

**Respuesta 1:**

ln -s ../raw_data/splike_x.faa

**Respuesta 2:**

touch glycoproteins.faa


**Respuesta 3.**

head -1 splike_a.faa
>pdb|6VXX|A Chain A, SARS-CoV-2 spike glycoprotein

head -1 splike_b.faa
>pdb|6VXX|B Chain B, SARS-CoV-2 spike glycoprotein

head -1 splike_c.faa
>pdb|6VXX|C Chain C, SARS-CoV-2 spike glycoprotein

**Respuesta 4.** 

cat splike_a.faa > cat splike_b.faa > splike_c.faa > glycoproteins.faa

