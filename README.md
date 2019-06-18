# ExploreData
Data package for "Explore Data" group project of RaukR 2019.

The datasets are in raw format, you will have to figure out how to parse them.
You can find the datasets from within R using:

```
system.file("extdata", "visby_ais.log",package="ExploreData", mustWork = T)
system.file("extdata", "visby_adsb.log",package="ExploreData", mustWork = T)
system.file("extdata", "geno_data_raw.rdat",package="ExploreData", mustWork = T)
```

`geno_data_raw.rdat` requires the R packages `GenABEL` and `GenABEL.data` to work.
