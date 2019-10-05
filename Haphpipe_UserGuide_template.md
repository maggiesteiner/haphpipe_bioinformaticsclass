# Haphpipe User Guide

---
Directions from Keylie and Maggie to help guide you:

It's mostly just an explanation of what you did + your notes on how to get it to work. Below is an outline to guide you in your note taking and such. Write down every question you have or google - nothing is "stupid." Also, try googling your question first, then reaching out to us or bringing it to haphpipe hours. It may be helpful to take screenshots of any error messages, if applicable. If google helped you - document the link or sources that helped answer your question. 

To begin, please read your associated paper, and give us a paragraph about their study and a paragraph about their NGS technique.

Inspiration: https://bedtools.readthedocs.io/en/latest/content/bedtools-suite.html

Emails: kmgibson@gwu.edu and steinerm@gwu.edu 

HAPHPIPE Hours: Tuesday and Thursday (Time TBA)

---

## Basics:

*Made by:*

*My virus is:*

*My links are:*

*Associated paper pararaphs.*
*Paragraph about study:*

*Paragraph abut NGS technique and data:*

## Questions to answer in your own words
Do not feel like you need a "perfect answer" - that is not what we're going for. Explain things in your own words and as if you're explaining them to your peers or another undergrad you "tutor". We're trying to make this approachable not perfect, scientific explainations. Also, you don't have to answer these *prior* to starting, just eventually or throughout your work on this.

1. What is a directory structure? Please explain and create a diagram / picture to accompany your explaination.
2. What is the difference between next-generation sequencing and Sanger sequencing?
3. What is the difference between the two pipelines, hp01 and hp02? Explain what each step of the pipelines accomplishes and why that step is necessary.
4. Did you need to learn how to bash script for this? What do you feel like you weren't prepared for after reading the introduction part we provided you with?



## Installing HAPHPIPE

Insert instructions in your own words and code.

## Activating HAPHPIPE

Insert how you activate HAPHPIPE and use it in your own words and provide your code.


## HAPHPIPE suite
Please explain what the haphpipe suite is. What is it's purpose how do you use it? What is it good for?

For each of the stages below, please explain the stage. List the files needed for the command, what the command does. The options for the command. An example of how to execute the command.

### hp_reads
        sample_reads
        trim_reads
        join_reads
        ec_reads
### hp_assemble
        assemble_denovo
        assemble_amplicons
        assemble_scaffold
        align_reads
        call_variants
        vcf_to_consensus
        refine_assembly
        finalize_assembly
### hp_haplotype
        predict_haplo
        ph_parser
### hp_annotate
        pairwise_align
        extract_pairwise
        annotate_from_ref
        
## Example usage
Your virus with both pipelines. Document all code and explanation.  

## Helpful resources
List all helpful topics you think or did address here with links / explainations you felt were helpful. Use bullet points.

- introduction to NGS
	- https://learn.gencore.bio.nyu.edu
- inroduction to bash
	- (add)
- helpful tips for command line
	- https://github.com/gwcbi/HPC/blob/master/commandline.md
- how to run interactive jobs *(do this to run all haphpipe modules and pipelines!)*
	- https://github.com/gwcbi/HPC/blob/master/interactive_jobs.md
- intro to github
	- https://github.com/gwcbi/HPC/blob/master/github.md
- markdown tutorial
	- https://www.markdowntutorial.com
	
## FAQ
List all questions you had and provide links / explainations you felt were helpful to answer these questions. Use topics and numbering.
