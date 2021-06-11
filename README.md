# ExploreData
Data package for "Explore Data" group project of RaukR.

The datasets are in raw format, you will have to figure out how to parse them.
You can find the datasets from within R using:

```
system.file("extdata", "visby_ais.log",package="ExploreData", mustWork = T)
system.file("extdata", "visby_adsb.log",package="ExploreData", mustWork = T)
system.file("extdata", "chr22.1000g.vcf",package="ExploreData", mustWork = T)
```

## Chr22.1000g.vcf

File downloaded from the IGSR https://www.internationalgenome.org/data FTP site.
Originally named ALL.chr22.phase3_shapeit2_mvncall_integrated_v5b.20130502.genotypes.vcf it is a VCF format file with population allele frequencies of variants on chromosome 22. For size purposes the file supplied in RaukR has been filtered to 20000 random variants across chromosome 22.
Data is from 2504 individuals. 

