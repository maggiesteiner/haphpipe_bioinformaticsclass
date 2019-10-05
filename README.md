# haphpipe_bioinformaticsclass
Github repository for Fall 2019 GW bioinformatics class for working with HAPHPIPE.

Overall for your project, you will be taking viral NGS data throughout two premade pipelines in HAPHPIPE. You will be making a user guide for future undergrads to use, documenting your frequently asked questions, and learning how to implement a pipeline.

A template User Guide can be found [here](https://github.com/kmgibson/haphpipe_bioinformaticsclass/blob/master/Haphpipe_UserGuide_template.md). I have also put a copy for each of you within your relative folder. 


**Tutorials to complete prior to starting:** <br>
This is if you are unfamiliar with bash coding and markdown files.

- [Markdown](https://www.markdowntutorial.com/lesson/1/)
- [Command Line](https://www.codecademy.com/learn/learn-the-command-line)
- [Bash scripting](https://www.codecademy.com/learn/learn-the-command-line/modules/bash-scripting)

**Prior to starting, please read:**

1. Your manuscript associated with your data.
2. General guidlines to HAPHPIPE [here](https://github.com/gwcbi/haphpipe).
3. Use [bedtools](https://bedtools.readthedocs.io/en/latest/content/tools/annotate.html) as your inspiration for describing the modules.


## HIV

**Pipelines to compare:** <br>
Freddie - [IVA](https://github.com/sanger-pathogens/iva) <br>
Shane - [PASeq](PASeq.org)

**Helpful links for your project:**

1. [HIV Sequence Database](https://www.hiv.lanl.gov/content/sequence/HIV/MAP/landmark.html)
2. [Manuscript](https://www.biorxiv.org/content/biorxiv/early/2018/09/12/414995.full.pdf)
3. [SRA BioProject](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA486832)

## HCV
**Pipelines to compare:** <br>
Uzma - [V-pipe](https://github.com/cbg-ethz/V-pipe) <br>
Dhatri - [Viral-NGS](https://github.com/broadinstitute/viral-ngs)

**Helpful links for your project:**

1. [HCV Sequence Database](https://hcv.lanl.gov/content/sequence/HCV/MAP/landmark.html)
2. [Manuscript](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4067308/)
3. [SRA BioProject](https://www.ncbi.nlm.nih.gov/bioproject?LinkName=sra_bioproject&from_uid=651945)


## Influenza
**Pipelines to compare:** <br>
Jack - pick one:<br>

1. [FluLINE](https://umasangumathi.github.io/FluLINE/)
2. [Instaflu](https://insaflu.insa.pt)
3. [Glue](http://tools.glue.cvr.ac.uk/#/home)

**Helpful links for your project:**

1. BioSamples SAMN01095441 to SAMN01095495 for H1N1/2009 and SAMN01095144 to SAMN01095190 for H3N2
2. [Manuscript](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4731279/)
3. [SRA BioProject](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA486832)
4. [Influenza references](https://www.ncbi.nlm.nih.gov/genome?LinkName=assembly_genome&from_uid=4784198)
	- Reference genomes:  Influenza A virus (A/California/07/2009(H1N1)) and Influenza A virus (A/New York/392/2004(H3N2))

For your references, we concatenated the 8 segments:

	For H3N2: NC_007373, NC_007372, NC_007371, NC_007366, NC_007369, NC_007368, NC_007367, NC_007370
	For H1N1: NC_026438, NC_026435, NC_026437, NC_026433, NC_026436, NC_026434, NC_026431, NC_026432