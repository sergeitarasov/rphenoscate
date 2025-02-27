# README for data archive from: "Automated Integration of Trees and Traits: A Case Study Using Paired Fin Loss Across Teleost Fishes" 

L.M. Jackson,  P.C. Fernando, J.S. Hanscom, J.P. Balhoff,  P.M. Mabee.



Data for these supplementary files is generated by scripts or SPARQL queries found within the following sources:



* [“VTO_to_opentree_pipeline” github repository](https://github.com/pasanfernando/VTO_to_opentree_pipeline/tree/v2.0.0)

* [Ontotrace source repository](https://github.com/phenoscape/ontotrace)



Data used in the manuscript were generated using a copy of the Phenoscape Knowledgebase from 2017-6-08.



The following ontologies relevant to this study are used within the Phenoscape Knowledgebase:



* [Uberon anatomy ontology](http://purl.obolibrary.org/obo/uberon/ext.owl), version http://purl.obolibrary.org/obo/uberon/releases/2017-05-29/uberon.owl

* [Biospatial ontology](http://purl.obolibrary.org/obo/bspo.owl), version http://purl.obolibrary.org/obo/bspo/releases/2014-02-03/bspo.owl

* [Phenotype and trait ontology](http://purl.obolibrary.org/obo/pato.owl), version http://purl.obolibrary.org/obo/pato/releases/2017-07-10/pato.owl

* [OBO relations ontology](http://purl.obolibrary.org/obo/ro.owl), version http://purl.obolibrary.org/obo/ro/releases/2017-05-29/ro.owl

* [Vertebrate taxonomy ontology](http://purl.obolibrary.org/obo/vto.owl), version http://purl.obolibrary.org/obo/vto/2016-10-17/vto.owl



## `Supplementary Materials Table 1`. 

Supplementary Materials Table 1. List of 87 publications used in constructing the synthetic supermatrix, including the number of taxa, pectoral and pelvic fin characters, and states. Studies that were specifically curated for the purpose of more fully representing the distribution of pelvic and pectoral fins and girdles conditions across teleosts are denoted by an asterisk.



## `Supplementary Materials Table 2`.

Comparison of teleost families between the Vertebrate Taxonomy Ontology (VTO), Open Tree, and Catalog of Fishes (CoF). Dash indicates family name that is not recognized within a particular source.  


## `Supplementary Materials Table 3`.

Statistics for reconciliation between Vertebrate Taxonomy Ontology (VTO) and Open Tree taxa. This file lists the species with data that were mismatched during the reconciliation step, and they are separated based on the reason for the mismatch (due to species being extinct, unconventional naming, etc.).



## `Supplementary Materials Table 4`.

List of VTO teleost families that show pectoral fin absence, pelvic fin absence, or the absence of both paired fins. Families with pelvic fin absence were compared to previously documented families (Nelson 1990), and details given in footnotes.



## `Supplementary Materials Table 5`.

Ancestral state reconstruction across Anguilliformes Open Tree phylogeny (Supplementary Materials File 4) for pectoral fin gain and loss (Fig. 7).



## `Supplementary Materials Matrix 1`.

OntoTrace generated NeXML synthetic morphological supermatrix for pectoral fin and pelvic fin presence and absence, including metadata for supporting states and publication information.



## `Supplementary Materials Matrix 2`.

The tab-delimited character matrix generated after pre-processing the OntoTrace matrix (Supplementary Materials Matrix 1) by converting from NeXML format. 



## `Supplementary Materials Matrix 3`.

Resulting matrix after the propagation step. The taxon names are based on the VTO, and this matrix is the input for the taxon name reconciliation step.



## `Supplementary Materials Matrix 4`.

Final output matrix of the pipeline. This tab-delimited file was read into Mesquite v3.10 for mapping onto the Teleostei species-level tree (Supplementary Materials File 1).



## `Supplementary Materials File 1`.

Teleostei species-level tree from Open Tree. Tree file (Newick) from Open Tree synthesis used as the input into Mesquite.



## `Supplementary Materials File 2`.

Output files of synthesis tree build from Open Tree. Archive files of the output directory for each step in the synthesis tree build. 



## `Supplementary Materials File 3`.

Merged tree matrix. NEXUS-formatted translation of the final output matrix (Supplementary Materials Matrix 4) merged with the Teleostei species-level tree from Open Tree (Supplementary Materials File 1). This combined matrix and tree file was used for ancestral state reconstruction in Mesquite.



## `Supplementary Materials File 4`.

Anguilliformes species-level trees based on subset from Teleostei species-level tree from Open Tree (Supplementary Materials File 1) merged with the final output matrix (Supplementary Materials Matrix 4). File includes 1,000 trees each with randomly resolved polytomies performed using the APE package in R. 














