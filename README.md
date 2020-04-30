# PRF1
Supplementary material for the manuscript "Frequent birth-and-death events throughout perforin-1 evolution". Contains data from the manual annotation work and from the preliminary phylogenetic analyses.
# Annotation
The *Annotation* folder contains the output of the [*BATI* algorithm](http://degradome.uniovi.es/downloads.html). Each species folder includes as many folders as annotated genes and pseudogenes. Each of these subfolders will display:

* A `tbn` file with the `tblastn` hits used in the annotation process. If no genes were annotated in the project, this will be the only file.
* A `seq` file with the annotated coding sequence, one exon per line.
* An `aa` file with the protein translation of the `seq` sequence.
* A `gff` and an `xml` file with the coordinates of the annotation.
* A `_contig.seq` file with the genomic sequence containing the annotated gene.
* A `warnings.txt` file with custom warnings about the annotation.
* A `map.html` file with a map of the `_contig.seq` sequence.

Some folders also contain `pdf` files showing alignments of the project sequences with the human PRF1 protein as reference.

# Phylogenetics
There are three folders with the analyses of mammalian PRF1 sequences (`mammals`), fish PRF1 sequences (`flfish`) and fish c2PRF1 sequences (`C2`). Each of those folders contain the input and output files of `MrBayes`, plus a subfolder with the input and output of `protpars`.

# Species symbols and assemblies


|Annotation project | Species | Assembly|
|---|---|
|allMis4 | Alligator mississippiensis | GCA_000281125.4|
|allSin1 | Alligator sinensis | GCA_000455745.1 |
|anaPla1.5 | Anas platyrhynchos | GCA_003850225.1|
|andRos1 | Anguilla rostrata | GCA_001606085.1 |
|anoCar2.0 | Anolis carolinensis | GCA_000090745.2|
|aptFor1 | Aptenodytes forsteri  | GCA_000699145.1|
|astMex2.0 | Astyanax mexicanus | GCA_000372685.2|
|balBon1 | Balaenoptera bonaerensis | GCA_000978805.1 |
|balReg1 | Balearica regulorum | GCA_000709895.1|
|bosTau1.2 | Bos Taurus | GCA_002263795.2|
|braFlo2 | Branchiostoma floridae | GCA_000003815.1|
|bucRhi1 | Buceros rhinoceros | GCA_000710305.1|
|calPeg1 | Calidris pugnax | GCA_001431845.1 |
|calMil6.1.3 | Callorhinchus milii | GCA_000165045.2|
|calAnn1 | Calypte anna  | GCA_003957555.2|
|catAur1 | Cathartes aura | GCA_000699945.1|
|chiPla1 | Chiloscyllium plagiosum | GCA_004010195.1|
|chrPic3.0.3 | Chrysemys picta | GCA_000241765.2|
|cioIntKH | Ciona intestinalis | GCA_000224145.2|
|cluHar1 | Clupea harengus | GCA_900323705.1|
|colLiv1.0 | Columba livia | GCA_000337935.1|
|ConCri1.0 | Condylura cristata | GCA_000260355.1|
|corAlt1 | Corapipo altera  | GCA_003945725.1|
|corBra1 | Corvus brachyrhynchos  | GCA_000691975.1|
|croPor1 | Crocodylus porosus | GCA_001723895.1|
|cucCan1 | Cuculus canorus | GCA_000709325.1|
|cynSem1.0 | Cynoglossus semilaevis | GCA_000523025.1|
|cypCar | Cyprinus carpio | GCA_000951615.2|
|danRer11 | Danio rerio | GCA_000002035.4|
|dasNov3 | Dasypus novemcinctus | GCA_000208655.2|
|delLeu2 | Delphinapterus leucas | GCA_002288925.3|
|egrGar1 | Egretta garzetta | GCA_000687185.1|
|Efet.01 | Eisenia fetida | GCA_003999395.1|
|EleEdw1.0 | Elephantulus edwardii | GCA_000299155.1|
|equCab3.0 | Equus caballus | GCA_002863925.1|
|eriEur2 | Erinaceus europaeus | GCA_000296755.1|
|esoLuc3 | Esox lucius | GCA_000721915.3|
|eurHel1 | Eurypyga helias  | GCA_000690775.1 |
|galGal6a | Gallus gallus | GCA_000002315.5|
|gavGan1 | Gavialis gangeticus | GCA_001723915.1|
|gekJap1.1 | Gekko japonicus | GCA_001447785.1|
|halLeu4.0 | Haliaeetus leucocephalus  | GCA_000737465.1|
|hetGla2 | Heterocephalus glaber  | GCA_000247695.1|
|hipCam1 | Hippocampus comes | GCA_001891065.1|
|lagObl1 | Lagenorhynchus obliquidens | GCA_003676395.1|
|lipVex1 | Lipotes vexillifer  | GCA_000442215.1|
|loxAfr3 | Loxodonta Africana | GCA_000001905.1|
|melGall5.0 | Meleagris gallopavo | GCA_000146605.4|
|melUnd6.3 | Melopsittacus undulatus | GCA_000238935.1|
|merNub1 | Merops nubicus | GCA_000691845.1|
|nsch1 | Neomonachus schauinslandi | GCA_002201575.1|
|notScu2 | Notechis scutatus | GCA_900518725.1|
|numMel1.0 | Numida meleagris  | GCA_002078875.2|
|opiTho1 | Opisthocomus hoazin | GCA_000692075.1 |
|OfaDov1 | Orbicella faveolata | GCA_002042975.1|
|orcOrc1.1 | Orcinus orca  | GCA_000331955.2|
|ornAna1.p.v1 | Ornithorhynchus anatinus | GCA_004115215.2|
|OryAfe1.0 | Orycteropus afer afer | GCA_000298275.1|
|oryLat1 | Oryzias latipes | GCA_002234675.1 |
|parMaj1.1 | Parus major | GCA_001522545.3|
|pelCri1 | Pelecanus crispus | GCA_000687375.1|
|pelSin1.0 | Pelodiscus sinensis | GCA_000230535.1|
|petMar1.0 | Petromyzon marinus | GCA_002833325.1|
|phaCar1 | Phalacrocorax carbo | GCA_000708925.1|
|phaCin4.1 | Phascolarctos cinereus | GCA_002099425.1|
|phoRub1 | Phoenicopterus ruber | GCA_000687265.1|
|phyCat1 | Physeter catodon | GCA_002837175.2|
|podCri1 | Podiceps cristatus | GCA_000699545.1|
|pomCan1 | Pomacea canaliculate | GCA_003073045.1|
|proCap1 | Procavia capensis | GCA_004026925.2|
|pseNaj2 | Pseudonaja textilis | GCA_900518735.1|
|pytBiv5.0.2 | Python bivittatus | GCA_000186305.2|
|ramVar4.0 | Ramazzottius varieornatus | GCA_001949185.1|
|rhiTyp2 | Rhincodon typus | GCA_001642345.2|
|salSal2 | Salmo salar | GCA_000233375.4|
|strCam1 | Struthio camelus | GCA_000698965.1|
|susScr11.1 | Sus scrofa | GCA_000003025.6|
|tauEry1 | Tauraco erythrolophus | GCA_000709365.1|
|thaSir1 | Thamnophis sirtalis | GCA_001077635.2|
|tinGut2 | Tinamus guttatus | GCA_000705375.2|
|turTru1 | Tursiops truncatus | GCA_001922835.1|
|tytAlb1 | Tyto alba  | GCA_000687205.1|
|aRhiBiv1.1 | Rhinatrema bivittatum | GCA_901001135.1|
|nanPar1 | Nanorana parkeri | GCA_000935625.1|
|RCv2.1 | Lithobates catesbeianus | GCA_002284835.2|
|xenTro10 | Xenopus tropicalis | GCA_000004195.4|
|bTaeGut1_v1 | Zebra finch | GCA_003957565.2|
