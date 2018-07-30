# Description
The original dataset is available from Datalad: http://datasets.datalad.org/
	-datalad install ///
	-datalad install ///abide

File: Phenotypic_V1_0b.csv = ABIDE phenotype will with summary assessment data
File: nidm.ttl = NIDM-Experiment conversion of /datasets.datalad.org/abide/RawDataBIDS/CMU_a/ joined with assessment informaiton from Phenotypic_V1_0b.csv
	-Created with: 
	-- /PyNIDM/nidm/experiment/tools/BIDSMRI2NIDM.py -d /datasets.datalad.org/abide/RawDataBIDS/CMU_a/
	--/PyNIDM/nidm/experiment/tools/CSV2NIDM.py -csv Phenotypic_V1_0b.csv -ilxkey [my interlex key]  -github dbkeator [my github access token] -json_map abide_phenotypic_v1_0b_vars_to_terms.json -nidm /datasets.datalad.org/abide/RawDataBIDS/CMU_a/nidm.ttl

File: nidm.ttl.png = PNG image of the NIDM.ttl file graph

File: abide_phenotypic_v1_0b_vars_to_terms.json = Example JSON dictionary file mapping variable names in Phenotypic_V1_0b.csv to terms from Interlex and custom-defined in github
