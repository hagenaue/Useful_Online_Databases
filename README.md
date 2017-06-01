# Useful_Online_Databases: a list of useful resources for interpreting brain microarray data:

## *Gene expression omnibus (GEO): A public archive of transcriptomic data (microarray, RNA-Seq, epigenetics...)
### I added example code for downloading from GEO here, but also put it in the folder specific to GEO
### Good for comparing our results to previous results:
#### 1) Can provide validation or confirmation (if the archived experiments address a similar research question)
#### 2) Can provide extra data if we need to increase sample size to see anything (meta-analysis)
#### 3) Can help with interpretation (e.g., comparing the influence of GROV in the brain to the influence of cortisol on cultured neurons)
https://www.ncbi.nlm.nih.gov/geo/

## *dbSNP & dbVar: A searchable database of genetic variants linked to various diseases or phenotypes
### Note: typically, to interpret this information you will need to look up the genes that are thought to have expression regulated by these genetic variants in an eQTL database (see below). 
https://www.ncbi.nlm.nih.gov/projects/SNP/

## *Rat Genome Database: Amongst other things, you can search for genetic variants related to behavioral phenotypes in rats & mice.
http://rgd.mcw.edu
### e.g. anxiety:
http://rgd.mcw.edu/rgdweb/search/qtls.html?term=Anxiety&chr=ALL&start=&stop=&map=360&rs_term=&vt_term=&speciesType=3&obj=qtl
### You can also search for the phenotypes associated with genetic variants near particular genes, e.g. C1qa:
http://rgd.mcw.edu/rgdweb/report/gene/main.html?id=1306716
### I think there is a way to do this in bulk, but I don't remember how.

## *Mouse Genome Informatics: Amongst other things, you can search for genetic variants related to behavioral phenotypes in mice.
http://www.informatics.jax.org
### This website definitely lets you batch query a list of genes for known phenotypes:
http://www.informatics.jax.org/batch_data.shtml

## *GTEx: Database documenting gene expression vs. genotype in various tissues
https://www.gtexportal.org/home/
### Useful for interpreting the genetic variants associated with disease/phenotype in dbGAP or dbVAr databases

## *CommonMind Consortium: documenting gene expression vs. genotype in a large sample of DLPFC tissue
https://www.synapse.org/#!Synapse:syn5585484
### Useful for interpreting the genetic variants associated with disease/phenotype in dbGAP or dbVAr databases

## *Allen Brain Atlas (ABA): Publically searchable & downloadable data related to the brain.
http://www.brain-map.org
## Note - each of these datasets has in depth technical documentation located on the website (white papers). I recommend reading the technical documentation if you are going to work with the data.
## Includes:
### - In situ hybridization data from mouse and human brains - from adults and across development.
#### Note: These in situs were run in bulk, so they tend to be noisy (like most big data).
### - Microarray data from across human brains and primate brains (characterizing regional variation)
### - Single-Cell RNA-Seq data
### - Connectivity data (from mice)
### - fMRI data (human)

## *My curated database of cell type specific genes
https://sites.google.com/a/umich.edu/megan-hastings-hagenauer/home/cell-type-analysis
