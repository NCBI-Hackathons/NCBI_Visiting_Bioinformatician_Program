# NCBI Visiting Bioinformatician Program
Postdocs and Graduate Students Visit NCBI for 4 to 6 weeks for Training in Bioinformatics, Computational Biology, Data Science, Project Management and Product Management

## Training Objectives for the Visiting Bioinformatician Program

### Bioinformatics
  While most visitors are already bioinformaticians in some capacity, novel data types and datasets are explored, typically from public datasets.  
### Computational Biology
  Statistical methods and data visualization are also explored 
### Data Science
  Visitors improve their skills in data streaming, data management, statistical analysis and visualization.  
### Project Management
  Typically, visitors are put in charge of a team of bioinformaticians during the last week of their stay at NCBI.  
### Product Management
  Visitors leverage their own use cases, the use cases of their colleagues, and reach out to others in government, academia and industry to find other suitable use cases for their bioinformatics products.  
### Communication
  For the most part, coding and research are done live -- primarily on github -- which is a distinct departure from antiquated scientific communication practices.  

## Large-scale ongoing projects

#### Polygenic SNP Search Tool (PSST)
Pipeline that identifies multiple SNPs that are associated with diseases or disease phenotypes. This pipeline identifies
asserted pathogenic SNPs. in addition, the pipeline uses SNPs identified in Genome-wide Association Studies (GWAS), crossed with databases such as ClinVar and dbSNP to construct a report describing multiple genetic variants associated with diseases.

- Project page: https://github.com/NCBI-Hackathons/PSST

![Workflow](/images/smallPSST.png?raw=true "PSST.png")

#### VirusFrankenstein

An agglomeration of hackathon-virus seach strategies for discovering new viruses from metaviromic and metagenomic data.  

## Current projects

#### [Complex Pheno/Geno](https://github.com/NCBI-Hackathons/Complex_Phenogeno)

There has now been more than ten years, and thousands of publications referencing GWAS (and other) studies, which resulted in the discovery of hunderds of thousands of single nucleotide polymorphisms. Taking advantage of this existing (and growing) knowledge generated in the lab, Complex Pheno/Geno restricts the genome space to be used in predictive models for the disease, potentially lowering the costs of personilized medicine. At the same time it explores the involvement or rsIDs that have been linked together in the literature, exploring the role of interacting pathways in an agnostic way. Moreover, it models the observed pathology taking into consideration the various diagnostic measurements without the need for binary diagnostic outcomes. Finally it incorporates data on known environmental modulators to further refine the modelling process. The outcome of Complex Pheno/Geno is the fine-grain categorization of patients within a cohort.
![Flow diagram](https://github.com/NCBI-Hackathons/Complex_Phenogeno/blob/master/Images/FlowDiagram.jpeg)

#### [Tryptase_Duplication](https://github.com/NCBI-Hackathons/Tryptase_Duplication) 

There are a number of genes within the Tryptase family all of which are closely related. The two main genes within the family are the TPSAB1 and TPSB2 known as alpha and beta respectively.
There is evidence that duplication of the TPSAB1 gene is linked to certain phenotypic traits. For example susceptibility to infection [1,2,3]
<br />
Duplication of the TPSAB1 locus is associated with a number of SNPs at the 5' prime end of the transcript. These SNPs allow the duplicated TPSAB1 and wild-type TPSAB1 to be distinguished from each other.
<br />
The Tryptase_Duplication project uses these SNPs to look for expression of the wild-type and duplicated TPSAB1 in publicly available RNA Seq data from the Sequence Read Archive (SRA).
<br />
![Flow diagram](https://github.com/NCBI-Hackathons/Tryptase_Duplication/blob/master/analysis/figs/expression_per_group.png)

#### [EndoVir](https://github.com/NCBI-Hackathons/EndoVir) 

A implementation of [ViruSpy](https://github.com/NCBI-Hackathons/ViruSpy)  in modern Python (3.6) to facilitate on-the-fly adjustments of pipeline parameters and integration of different external tools.   

Endogenous Viral Elements (EVEs) are part of the host genome and allow horizontal transmission within a host but the underlying evolutionary mechanisms are still unclear. Currently, virology is entering a ‘discovery phrase’ due to new and cheaper sequencing technologies which result in a deluge of metagenomic data from a wide range of organisms. These sequence data provide information on the organisms of interest as well as contain a record of all the expressed microbial parasites that infect that host, including viruses. This makes such data set especially valuable for the analysis of EVEs.

#### PubRunner

A framework for keeping text mining up-to-date. Many text mining tools and results become stale because they aren't updated with the latest publications. This framework manages the download of required corpora (e.g. PubMed), execution of tools, uploading results to somewhere public and updating the status of the tool on the PubRunner website. The VB program is being used to productize PubRunner and create a flexible and easy-to-use Python package.

- Website: http://pubrunner.org/
- F1000 paper: https://f1000research.com/articles/6-612/v1
- Hackathon project: https://github.com/NCBI-Hackathons/PubRunner
- New Python package: https://github.com/jakelever/pubrunner

#### AutoDenovo

Pipeline for finding denovo mutations related to neurodevelopmental disorders using family study designs, similar to pipelines previously developed for cancer research. It combines different types of variants by multiple callers, and uses both chip and exome sequencing data. The end goal is to compare annotated variants to public databases (dbVar, ClinVar), possibly indicating further sequencing or mechanistic avenues.

- Project page: https://github.com/gsudre/autodenovo

#### [LabPype](https://github.com/NCBI-Hackathons/LabPype)

LabPype provides a solution for rapid development of pipeline and workflow management software. A visualized pipeline software provides features such as reusability of workflows, user-friendly interface, and highly integrated functionalities. LabPype accelerates the making of such software for developers. It also helps the scientists become the developers to meet their increasing and diverging needs.

- Project page: https://github.com/NCBI-Hackathons/LabPype
- Demo: https://ncbi-hackathons.github.io/LabPype/

## Former Projects and Past Participants

```
VBs will place links to their repos and other product deliverables here 
Example:  Celeste S:  https://www.youtube.com/watch?v=fC9rYghqUTo&feature=youtu.be
```
