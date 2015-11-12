##Database including the most abundant OTUs (at 97% clustering) from pyroreads from the BioMarKs survey

	Database name: BM_V4
	Version: 5775 | November 2015
	Ramon Massana : ramonm at icm.csic.es


### DESCRIPTION

	-The most abundant OTUs (at 97%) from pyroreads from the BioMarKs survey
	-Classified to class-level using several reference databases and Blast searches
	-5775 sequences, about 380 bp in size
	-The codes are: OTU number - Class - Supergroup - Number of reads
	               [   114    Apicomplexa Alveolata         819 ]	


### SOURCE 

	- Based on the sequences presented in Massana et al. 2015. EM 17:4035–4049 	(http://dx.doi.org/10.1111/1462-2920.12955)


### HISTORY OF THE DATASET

	Initially there were 15295 OTUs at 97% from several sites, planktonic size fractions and sediments. These were carefully classified. They corresponded to 840,498 reads

	- Remove OTUs to keep the most abundant and the better classified
	- Remove singletons (9827 OTUs left)
	- Remove OTUs less than 10 reads appearing in 1 place (8081 left)
	- Remove OTUs less than 10 reads appearing in 2 places (6094 left)
	- Remove OTUs less than 10 reads appearing in >2 places and an evalue >0 (5331 left)
	- Remove OTUs appearing in 1 place and with an evalue >0(5284 left)
	- Remove OTUs appearing in 2 places and with an evalue >e-150(5232 left)

	The final 5232 OTUs were 34.2% of the initial OTU number and 97.3% of the reads	(817,485)

	We did the same process with the list of metazoans and OTUs
	- Initial: 1497 OTUs (249,563 reads)
	
	The final 543 OTUs were 36.3% of the initial OTU number and 98.2% of the reads (245,048)

