Tara_corail
================
2024-10-08

## **1) Get Data**

Permet la création d’un nouveau répertoire qui contiendra les fichiers
fastq.

``` r
# Créer un dossier
dir.create("Total_data_file_corail")
```

Ensuite, je télécharge la totalité des fichiers dans mon nouveau dossier
Total_data_file_corail

``` r
# Télécharger les fichiers en utilisant wget
system("wget -i Tara_link -P Total_data_file_corail")
```

- wget : Outil en ligne de commande pour télécharger des fichiers à
  partir du Web.

- -i : Fichier d’entrée contenant les liens URLs de téléchargement des
  données fastq.

- -P : Dossier où les fichiers sont enregistrés.
