## MSI CALLERS

|Caller|PubYear|Specialty|From|Study|Source|
|------|-------|---------|----|-----|------|
|msisensor|2014|Microsatellite Instability(MSI)|Memorial Sloan Kettering Cancer Center|[study](http://ascopubs.org/doi/pdf/10.1200/PO.17.00084)|[source](https://github.com/ding-lab/msisensor)|
|msings|2014|MSI|University of Washington, Seattle|[study](https://www.ncbi.nlm.nih.gov/pubmed/24987110)|[source](https://bitbucket.org/uwlabmed/msings)|[study](http://www.sciencedirect.com/science/article/pii/S1525157815001531)|
|msiseq|2015|MSI|National Cancer Center Singapore|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4549793/)|[source](https://cran.r-project.org/web/packages/MSIseq/index.html)|
|mirmmr|2017|MSI with methylation and mutation|Siteman Cancer Center, Wash U in St. Louis|[study](https://www.ncbi.nlm.nih.gov/pubmed/28961932)|[source](https://github.com/ding-lab/MIRMMR)|
|mantis|2017|MSI|The Ohio State University|[study](https://www.ncbi.nlm.nih.gov/pubmed/27980218)|[source](https://github.com/OSU-SRLab/MANTIS)|
|no name|2017|MSI classification|Harvard Medical School|[study](https://www.nature.com/articles/ncomms15180)|contact authors|


## STR Callers
|caller|orig pub|class|study|source|
|------|--------|-----|-----|------|
|hipSTR|2016|STR|[study](http://www.biorxiv.org/content/early/2016/09/27/077727)|[source](https://hipstr-tool.github.io/HipSTR/)|


## Ion Torrent/454

|caller|orig pub|class|input|study|source|
|------|--------|-----|-----|-----|------|
|otg-snpcaller|2014|SNV|torrent|[study](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0097507)|available?|
R453Plus1toolbox|2011|SNV|454|[study](https://academic.oup.com/bioinformatics/article/27/8/1162/228803/R453Plus1Toolbox-an-R-Bioconductor-package-for)|[source](http://www.bioconductor.org/packages/2.10/bioc/html/R453Plus1Toolbox.html)|
|pyroHMMsnp|2013|SNV|torrent/454|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3711422/)|[source](https://github.com/homopolymer/PyroTools/)|
|pyroHMMvar|2013|indel|torrent/454|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3888126/)|[source](https://github.com/homopolymer/PyroTools/)|


## Nanopore
|caller|orig pub|class|input|study|source|
|------|--------|-----|-----|-----|------|
|graphmap|2016|SNV|nanopore|[study](http://www.nature.com/articles/ncomms11307)|[source](https://github.com/benedictpaten/marginAlign/blob/master/src/margin/marginCaller.py)|
marginAlign|2015|SNV|nanopore|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4907500/)| [source](https://github.com/benedictpaten/marginAlign)|


## PacBio
|caller|orig pub|class|input|study|source|
|------|--------|-----|-----|-----|------|
|SMRT-SV|2016|SV|pacbio|[study](http://genome.cshlp.org/content/early/2017/03/31/gr.214007.116)|[source](https://github.com/EichlerLab/pacbio_variant_caller)|
|HySA|2017|SV/indel|pacbio+illumina|[study](http://genome.cshlp.org/content/early/2017/01/19/gr.214767.116.abstract#corresp-1)|[source](https://bitbucket.org/xianfan/hybridassemblysv)|
|Multibreak-SV|2014|SV|PacBio|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4253835/)|[source](https://github.com/raphael-group/multibreak-sv)|
|PBHoney|2014|SV|PacBio|[study](http://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-15-180)|[source](https://sourceforge.net/projects/pb-jelly/)|


## Bio Nano
|caller|orig pub|class|input|study|source|
|------|--------|-----|-----|-----|------|
|Parliament|2015|SV|bio nano|Illumina/PacBio/BioNano|[study](https://www.ncbi.nlm.nih.gov/pubmed/25886820)|[source](https://sourceforge.net/projects/parliamentsv/)|


## RNA
|caller|orig pub|class|input|study|source|
|------|--------|-----|-----|-----|------|
|eSNV-Detect|2014|eSNV|rna|[study](https://academic.oup.com/nar/article/42/22/e172/2410988/The-eSNV-detect-a-computational-system-to-identify)|[source](http://bioinformaticstools.mayo.edu/research/esnv-detect/)|
|radia|2014|SNV/indel|rna+dna|[study](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0111516)|[source](https://github.com/aradenbaugh/radia/)|
|UNCeqR|2014|SNV/indel|rna+dna|[study](https://academic.oup.com/nar/article/42/13/e107/1277201/Integrated-RNA-and-DNA-sequencing-improves)|[source](http://lbg.med.unc.edu/~mwilkers/unceqr_dist/)|
|BreakTrans|2013|SV|wgs+rna|[study](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-8-r87)|[source](http://bioinformatics.mdanderson.org/main/BreakTrans)|


## de novo Filters

|caller|orig pub|class|input|type|study|source|
|------|--------|-----|-----|----|-----|------|
|denovolyzer|2015|SNV/indel|vcf|de novo|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4606471/)||
|Triodenovo|2015|SNV|vcfs|germ|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4410659/)|[source](http://genome.sph.umich.edu/wiki/Triodenovo#Download)|
|MendelScan|2014|SNV/indel|vcfs exome|germ|[study](https://www.ncbi.nlm.nih.gov/pubmed/24560519)|[source](https://github.com/genome/mendelscan)|
|trioCaller|2013|SNV|vcfs|denovo|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3530674/)|[source](http://genome.sph.umich.edu/wiki/TrioCaller)|
|FamSeq|2012|SNV/indel|vcf|denovo|[study](http://www.pnas.org/content/110/10/3985.long)|[source](http://odin.mdacc.tmc.edu/~wwang7/FamSeqIndex.html)|
|ForestDNM|2012|SNV/indel|vcf|denovo|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3712641/)|[source](http://sebatlab.ucsd.edu/index.php/software-data)|
|Var-MD|2012|SNV/indel|vcfs exome|denovo|[study](https://www.ncbi.nlm.nih.gov/pubmed/22290570)|[source](https://research.nhgri.nih.gov/software/Var-MD/)|
|kggseq|2012|SNV|mendel filter|[study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3326332/)||

## UNPUBLISHED CALLERS

|caller|release|caller class|input type|study|source|
|------|--------|------------|----------|-----|------|
|concod|2016|sv||[conf.](http://ieeexplore.ieee.org/abstract/document/7822495/)||
|cnndel|2016|sv||[conf.](http://ieeexplore.ieee.org/abstract/document/7822793/)||
|needlestack|2016|SNVs and indels| multi-sample BAMs||[source](https://github.com/IARCbioinfo/needlestack)|
|svmod|2016|sv||[open](http://link.springer.com/article/10.1007/s00180-016-0674-2)||
|UPS-indel|2016|indel||[conf.](http://ieeexplore.ieee.org/document/7802793/)|[source](https://sourceforge.net/projects/ups-indel/)|
|BreakDown|2015|SV/VAF||[thesis](https://scholarship.rice.edu/handle/1911/87870)||
|excaliburSMD|2014||||[source](https://github.com/cribioinfo/ExScaliburSMD)|
|takeabreak|2014|inv breakpoints||[conf.](http://link.springer.com/chapter/10.1007%2F978-3-319-07953-0_10)|[source](https://colibread.inria.fr/software/takeabreak/)|
|QuadGT|2013|SNV|exome trio|[conf.](http://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-S5-S3)|[source](http://www.iro.umontreal.ca/~csuros/quadgt/)|
|SoapSNV|2013|multi|||[source](http://soap.genomics.org.cn/SOAPsnv.html)|
|CNValidator|2012|CNV|||[source](https://code.google.com/archive/p/cnvalidator/)|
|mogul|2012|||[conf.](https://link.springer.com/chapter/10.1007/978-3-642-12683-3_23)||
|SeqCNVCBS|2012|CNV|||[source](http://www.mybiosoftware.com/seqcnvcbs-1-0-scan-statistics-cnv-detection-cbs.html)|
|bassovac|2011||||[source](http://tvap.genome.wustl.edu/tools/bassovac/)|
|kissnp|2010|||[open](https://hal.inria.fr/inria-00514887/)||
|glfTools|2010|SNV|||[source](http://genome.sph.umich.edu/wiki/GlfSingle)|
|BREPA||SV|||[source](https://bitbucket.org/xianfan/brepa)|
|snippy|||||[source](http://www.vicbioinformatics.com/software.snippy.shtml)|
|copycat|||||[source](https://github.com/chrisamiller/copyCat)|


## Unsorted Callers

|caller|orig pub|caller class|input type|study|source|
|------|--------|------------|----------|-----|------|
|sprites|2016|sv||https://academic.oup.com/bioinformatics/article/32/12/1788/1743630/Sprites-detection-of-deletions-from-sequencing|||sv-m|2012|indel||[study](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-14-132)|[source](https://www.bsse.ethz.ch/mlcb/research/bioinformatics-and-computational-biology/structural-variant-machine--sv-m-.html)|
|splazers|2012|indel||https://academic.oup.com/bioinformatics/article/28/5/619/248213/Detecting-genomic-indel-variants-with-exact|||Sentieon||||https://peerj.com/preprints/1672.pdf|http://www.sentieon.com/products.html|
|MindTheGap|2014|insertions|c elegans|https://academic.oup.com/bioinformatics/article/30/24/3451/2422179/MindTheGap-integrated-detection-and-assembly-of|http://gatb.inria.fr/software/mind-the-gap/|
|Factera|2015|SV/fusion||https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4296148/|https://factera.stanford.edu/|
|dindel|2011|indels|Sanger, slow|http://europepmc.org/abstract/MED/20980555|N/A|
|piCALL|2011|indel|scripps, exon|https://www.ncbi.nlm.nih.gov/pubmed/21653520||
|svseq 1 & 2|2011|SV|split-read|https://www.ncbi.nlm.nih.gov/pubmed/21994222||
|Spanner|2011|SV||https://www.ncbi.nlm.nih.gov/pubmed/21293372||
|SPLINTER|2010|SNV|SNPSeeker + indels|https://www.ncbi.nlm.nih.gov/pubmed/21041413/||
|bam2mpg|2010|SNV||https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2945191/||
|svmerge|2010|
|snvmix|2010|SNV|early cancer-specific, with low purity expectations|https://academic.oup.com/bioinformatics/article/26/6/730/245170/SNVMix-predicting-single-nucleotide-variants-from||
|cnD|2010|cnv||https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2820678/||
|dna sudoku|2009|SNV|overlapping pooling design|https://www.ncbi.nlm.nih.gov/pubmed/19447965/||
|breseq|2009|SNV|binomial model|https://www.researchgate.net/publication/232776704_Genome_evolution_and_adaptation_in_a_long-term_experiment_with_Escherichia_coli||
|maq|2009|SNV|bayesian model includes sequencing errors|https://www.ncbi.nlm.nih.gov/pubmed/18714091||
|SNPSeeker|2009|SNV|pooling. compares observed allele frequencies against the distribution of sequencing errors as measured by the Kullback Leibler (KL) distance|https://www.ncbi.nlm.nih.gov/pubmed/19252504/||
|modil|2009|indels||http://www.nature.com/nmeth/journal/v6/n7/full/nmeth.f.256.html||
|VariationHunter|2009|SV||http://genome.cshlp.org/content/19/7/1270.short||
|mrcanavar|2009|cnv||https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2875196/||
|maq|2008|SNV||https://www.ncbi.nlm.nih.gov/pubmed/18714091||
|PEM|2007|SV |paired-end|http://science.sciencemag.org/content/318/5849/420||
|PolyPhred|2006|SNV||https://www.ncbi.nlm.nih.gov/pubmed/16493422/||
|SNPDetector|2005|SNV||https://www.ncbi.nlm.nih.gov/pubmed/16261194/||
|novoSNP|2005|SNV||https://www.ncbi.nlm.nih.gov/pubmed/15741513/||
|ssahaSNP|2001|SNV||https://www.ncbi.nlm.nih.gov/pubmed/11591649/||
|polybayes|1999|SNV||https://www.ncbi.nlm.nih.gov/pubmed/10581034/||

