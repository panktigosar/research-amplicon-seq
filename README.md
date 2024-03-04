# research-template

The data is download from ```PRJNA723064```.
# Instructions of data download
The data is downloaded with the help for [SRA toolkit] (https://www.ncbi.nlm.nih.gov/sra/docs/toolkitsoft/).
1. Download the meta data and fastq files in ```.sra``` format using following code:
```prefetch PRJNA723064```

2. Use the ```fastq-dump``` command to extract the FASTQ files from the downloaded data: 
```fastq-dump --split-files --gzip PRJNA723064```
Ensure the files are in correct paths. You will need about 4.5 GB disk space.
