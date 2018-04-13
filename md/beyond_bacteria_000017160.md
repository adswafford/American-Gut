<img style="float: right" height="50%" width="50%" src="img/logo.png">

### Your Beyond Bacteria Sample Deep Shotgun Metagenomics Report

Thank you for your participation in the American Gut Project though the Beyond
Bacteria Perk and we appreciate your patience while we transitioned the sample
processing for this perk from out collaborators to our in-house team at UC San
Diego.

DISCLAIMER: The following report is intended FOR RESEARCH USE ONLY and is not a diagnostic test of
any kind. It should NOT be used to inform any clinical, medical, or otherwise health- or 
lifestyle-related decision-making, behavior, or activity. As scientists we do our best to
vet our data, ensure data integrity and provide the latest and best tools and analyses
available, but we do not provide any medical or clinical information or advice and no
information on specific organism found in the sample you provided is intended to be used
for this purpose.

In the Knight Lab, part of the Center for Microbiome Innovation at UC San Diego, 
we extracted DNA from your sample using the Earth Microbiome Project(EMP) standardized
protocol that was recently published in the November 2017 edition of Nature [https://www.nature.com/articles/nature24621],
and is available on the EMP website [http://www.earthmicrobiome.org/protocols-and-standards/dna-extraction-protocol/] for easy reference. The extracted metgenomic DNA was
then prepared for sequencing using our state-of-the art shotgun library preparation
and sequenced on a HiSeq4000.

<img style="float: right" height="50%" width="50%" src="img/Shotgun_overview.png">

Following sequencing, your samples were processed using the Oecophylla sequencing analysis
pipeline under development in the Knight Lab [https://github.com/biocore/oecophylla] using our supercomputing cluster
'Barnacle', which is housed in the SDSC data center and managed by Knight Lab systems administrators. The Barnacle cluster includes 1024 Intel Ivy-bridge compute cores as well as 384 AMD compute cores, 12TB of total Ram with a 10GbE compute
network. Storage includes 250TB of primary storage with equal amounts of dedicated backup for the different file systems. Unlike the amplicon sequencing data we use for the standard kit processing for the AGP which only detects bacteria whose 16S rRNA gene matches the patterns we commonly look for, deeper shotgun metagenomic sequencing detects all genomic DNA in the sample regardless of the type of organism prsent. This means that not only can we pick up microbes other than bacteria, but we have a lot more data to sort through and we can go beyond the operational taxonomic units (OTUs) reported for our
standard kit assessment to determine species and sometimes even strain-level identity for the microbes in
your sample.

If you would like to access your raw data you can find it here: [link]
This data has been filtered to remove sequences that did not pass our quality control parameters, including
the removal of sequences that matched to the human genome or our sequencing controls so these will not be
present in the data.

In the Oecophylla pipeline, the sequencing reads are matched to phyla, genera, and species using the Kraken
database [https://ccb.jhu.edu/software/kraken/] and functional pathways are identified using HUMANN2[http://huttenhower.sph.harvard.edu/humann2].

###Results

The vast majority of the organisms detected in your sample were bacterial, and although many species were identified in your sample, a few types of organisms tended to dominate most of the stool sample you provided.
<img style="float: right" height="50%" width="50%" src="img/10317.000017160_phylum.png">
<img style="float: right" height="50%" width="50%" src="img/10317.000017160_genera.png">
<img style="float: right" height="50%" width="50%" src="img/10317.000017160_species.png">

Since the whole metagenomic sequencing pipeline is able to capture organisms beyond bacteria we have highlighted the most commonly detected viruses and fungi as well, though verall these were in much lower abundance. 

Compared to the bacteriome, relatively little is known about the rapidly evolving viruses that dwell on the bounadary between life and abiotic existance. This is relfected in the large number of unassigned, putative viral DNA detected:

<img style="float: right" height="50%" width="50%" src="img/10317.000017160_virus_families.png">
<img style="float: right" height="50%" width="50%" src="img/10317.000017160_virus_genera.png">
<img style="float: right" height="50%" width="50%" src="img/10317.000017160_virus_species.png">

The fungal microbiome has been studied in detail primarily through model organisms and the food we consume such as beer, wine, cheese, which often contains fungi, or in the case of mushrooms and truffles entirely fungal. We fond a small amount of fungi in your stool sample and the top organisms are highlighted here:

<img style="float: right" height="50%" width="50%" src="img/10317.000017160_fungi_families.png">
<img style="float: right" height="50%" width="50%" src="img/10317.000017160_fungi_genera.png">
<img style="float: right" height="50%" width="50%" src="img/10317.000017160_fungi_species.png">

To view all of the organisms detected in your sample together please use the following links:
[link to .qzv for each]
[link to .qzv for each]
[link to .qzv for each]

In contrast, the microbes that live in us rely on a huge variety of functional pathways to keep growing, multiplying, 
helping, and sometimes harming, us. The top 10 pathways detected in the provided stool sample are below:
[plot of functional pathway]

[link to .qzv for each]

In our latest round of participation for this perk we had 17 total participants
who all provided stool samples. Your sample was combined for analysis with these
participants and ~500 other AGP participants whose samples have been processed
for deeper shotgun metagenomic sequencing through sponsorship from outside partners.

A visualization of your sample in the context of these indivduals can be found at the following link:
[link to .qzv of PCoA for each]

Please select 'your_sample' from the dropdown menu on the right of that viewer to see your sample highlighted.
Additional information for navigating the Emperor display can be found on the [Emperor website](https://biocore.github.io/emperor/).

A variety of alpha and beta diversity metrics and visualizations for your sample in the context of the other were created and can be accessed at the following links:
[links to each type of output]

Finally your sample was examined to determine which features were differentially abundant in your sample vs the rest of
the sequenced participants:
