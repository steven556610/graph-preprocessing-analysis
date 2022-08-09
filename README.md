# preprocessing


## network and pathway database
Material: STRING PPI networ (https://string-db.org), KEGG, MSigDB, REACTOME, NCI

package: powerlaw, mygene, network,numpy pandas

In the Set2gaussian document, we need to send input which include network and pathway database information (gene set).

In the preprocessing step, we will introduce how we address and do what operat on the materials.

In the file named MSigDB_REACTOME_KEGG_C6HallMark_gmt_file_address_and_GeneSet_output, we address and make output file for pathway database gene-set.

In the file named STRINGv11_network_process and string physical network link preprocess, we address STRING PPI network.

In the STRINGv11_network_process, we present the network in different confidence score, and calculate power-law attribution for the PPI network.

In the string physica networ link preprocess, we transfer PPI's node from ENSEMBL protei ID to gene symbol to ensure following experiment conduct well.

## disease gene set


## drug gene set








