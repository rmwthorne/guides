# Public Data Sources
One problem facing genomic scientists is finding relevent publicly published datasets *effectively*. The [Gene Expression Omnibus (GEO)](https://www.ncbi.nlm.nih.gov/geo/) is the obvious first stop, but navigating and filtering through search results is frequently painful.

here's a couple search options, aside from GEO:
* [ENCODE](https://www.encodeproject.org/search/?type=Experiment)
  - Positives: Decent filtering experience 
  - Example: [TF ChIP-seq data](https://www.encodeproject.org/search/?type=Experiment&assay_title=ChIP-seq&replicates.library.biosample.donor.organism.scientific_name=Homo+sapiens&target.investigated_as=transcription+factor&biosample_type=immortalized+cell+line&replicates.library.biosample.treatments.treatment_term_name=dexamethasone) for cell lines treated with dexamethasone
* [EBI](https://www.ebi.ac.uk/)
  - Positives: Better search functionality than GEO 
  - Example: ["T cell ATAC data"](https://www.ebi.ac.uk/ebisearch/search.ebi?db=nucleotideSequences&query=T%20cell%20ATAC&requestFrom=searchBox)
* [Illumina Basespace](https://basespace.illumina.com/home/index)
  - Positives: Easy download via `basemount`

