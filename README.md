# globi-taxon-names
list of manual taxonomic name mappings and taxonomic stop words 

 * [non-taxon-names.txt](./non-taxon-names.txt) is a list of non taxon words (aka taxon stop words) that are found in taxonomic name descriptions. They may contains words associated with lifestages (e.g., larva) or habitat (e.g., benthic). 

 * [taxon-name-mapping.csv](./taxon-name-mapping.csv) is a best effort list to map funky names to their likely taxonomic or functional counter part. 

 Both files have been introduced as an attempt to match names from datasets appearing in https://globalbioticinteractions.org and make them more easily accessible by mapping them to existing name sources.

 These files are used by [Nomer](https://github.com/globalbioticinteractions/nomer) as part of the globi-correct matcher. 
