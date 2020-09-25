# COVID2020-viaDBG-runs

## Datasets

	* SRR1190502 - k-mer size 30
	* SRR1191915 - k-mer size 80
	* SRR1191991 - k-mer size 80 (pending to repeat running, k-mer selected was far from optimal and alignment has some inconsistences)

For each dataset:

	* SAM report against MERS reference
	* Contigs report by viaDBG (only for forward strain, the ones that were predicted for the reverse complement were transcripted into their complementaries)
	* Report.txt - statistical information of the alignment using 'metaquast'
