---
layout: post2
permalink: /informatics_for_high-throughput_data_sequencing_2016/
title: Informatics for High-Throughput Sequencing Data 2016 Student Page
header1: Informatics for High-Throughput Sequencing Data 2016
header2: Workshop pages for students
image: CBW_High-throughput_icon.jpg
---

<ul id="navmenu">
  <li><a id="back_to_top">Contents</a>
     <ul class="sub1">
     <li><a href="#course_schedule">Course Schedule</a></li>
     <li><a href="#q_a_forum">Workshop Q/A Forum</a></li>
     <li><a href="#laptop_setup">Laptop Setup Instructions</a></li>
     <li><a href="#pre_tutorials">Pre-Workshop Tutorials</a></li>
     <li><a href="#pre_readings">Pre-Workshop Readings</a></li>
     <li><a href="#amazon_cloud">Amazon Cloud</a></li>
      <li><a href="#day1">Day 1</a>
         <ul class="sub2">  
           <li><a href="#welcome">Welcome</a></li>
           <li><a href="#module_1">Module 1</a></li>
           <li><a href="#module_2">Module 2</a></li>
           <li><a href="#module_3">Module 3</a></li>
           <li><a href="#module_4">Module 4</a></li>
           <li><a href="#assignment">Integrated Assignment</a></li>
        </ul>
      </li>
       <li><a href="#day_2">Day 2</a>
          <ul class="sub2">
             <li><a href="#module_5">Module 5</a></li>
            <li><a href="#module_6">Module 6</a></li>
            <li><a href="#module_7">Module 7</a></li>
           </ul>
       </li>
    </ul>
  </li>
</ul>  

<br>

###  Course Schedule  <a id="course_schedule"></a>

  <a href="http://bioinformatics-ca.github.io/2016_workshops/ht-seq/HT-Seq_2016_Schedule_v1.pdf">Schedule for June 9 to June 10, 2016</a>

[&uarr;](#back_to_top)

###  Workshop Q/A Forum <a id="q_a_forum"></a>

  Post your workshop questions <a href="http://todaysmeet.com/HTSeq2016">here</a>!

[&uarr;](#back_to_top)

###  Laptop Setup Instructions <a id="laptop_setup"></a>

  Instructions to setup your laptop can be found <a href="http://bioinformatics-ca.github.io/2016_workshops/ht-seq/laptop_setup_instructions.pdf">here</a>.

[&uarr;](#back_to_top)

###  Pre-workshop Tutorials <a id="pre_tutorials"></a>

  1) **R Preparation tutorials**: You are expected to have completed the following tutorials in **R** beforehand. The tutorial should be very accessible even if you have never used **R** before.

* The [CBW R tutorial](http://bioinformatics-ca.github.io/CBW_R_Tutorial/)
* [Quick and Dirty Guide to **R**](http://ww2.coastal.edu/kingw/statistics/R-tutorials/text/quick&dirty_R_revised_080715.txt)
* The [R command cheat sheet](../../resources/R_Short-refcard.pdf)

2) **UNIX Preparation tutorials**: Please complete tutorials #1-3 on UNIX at http://www.ee.surrey.ac.uk/Teaching/Unix/

* [Unix Cheat sheet](http://www.rain.org/~mkummel/unix.html) 

3) **IGV Tutorial**: Review how to use IGV Genome Browser if you have not used this tool before.

* [IGV tutorial](../../resources/IGV_Tutorial.pdf)
* link to datasets

[&uarr;](#back_to_top)

###  Pre-workshop Readings <a id="pre_readings"></a>

  Before coming to the workshop, read these.
  
  * [Using cloud computing infrastructure with CloudBioLinux, CloudMan, and Galaxy](http://www.ncbi.nlm.nih.gov/pubmed/22700313)
  
  * [Integrative Genomics Viewer (IGV): high-performance genomics data visualization and exploration](http://www.ncbi.nlm.nih.gov/pubmed/22517427)
  
  * [Genome structural variation discovery and genotyping](http://www.ncbi.nlm.nih.gov/pubmed/21358748)
  
  * [A survey of sequence alignment algorithms for next-generation sequencing](http://www.ncbi.nlm.nih.gov/pubmed/20460430)
  
  * [Genotype and SNP calling from next-generation sequencing data](http://www.ncbi.nlm.nih.gov/pubmed/21587300)
  
[&uarr;](#back_to_top)
  
### Logging into the Amazon Cloud <a id="amazon_cloud"></a>

Instructions can be found [here](http://bioinformatics-ca.github.io/logging_into_the_Amazon_cloud/).

* These instructions will **ONLY** be relevant in class, as the Cloud will not be accessible from home in advance of the class.
 
* We have set up 30 instances on the Amazon cloud - one for each student. In order to log in to your instance, you will need a security certificate. If you plan on using Linux or Mac OS X, please download this **link certificate here**. Otherwise if you plan on using Windows (with Putty and Winscp), please download this **link certificate here**.

[&uarr;](#back_to_top)

***

##  Day 1 <a id="day_1"></a>

###  Welcome <a id="welcome"></a>

  *<font color="#827e9c">Ann Meyer</font>* 
<br>

[&uarr;](#back_to_top)

***

###  Module 1: Introduction to HT-sequencing and Cloud Computing <a id="module_1"></a>

  *<font color="#827e9c">Francis Ouellette</font>*
  
  Lecture:
  
  Lab practical:

[&uarr;](#back_to_top)

***

###  Module 2: Genome Alignment <a id="module_2"></a>

  *<font color="#827e9c">Jared Simpson</font>*
  
  Lecture:
  
  Lab practical:
  
  Programs:
  
 * [samtools](http://samtools.sourceforge.net/) 
 * [BWA](http://bio-bwa.sourceforge.net/) 
 * [Bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml) 
 * [Picard](http://broadinstitute.github.io/picard/index.html) 
 * [GATK](http://www.broadinstitute.org/gsa/wiki/index.php/The_Genome_Analysis_Toolkit) 
 * [FastQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/) 
 * [SeqTK](https://github.com/lh3/seqtk) 
 * [IGV](http://www.broadinstitute.org/igv/) 
 
 Additional Resources:
 
 * [SEQanswers bioinformatics forum](http://seqanswers.com/forums/forumdisplay.php?f=18) 
 * [SAM/BAM file format specification](http://samtools.sourceforge.net/SAM1.pdf) 
 * [Base qualities vs mapping qualities](http://maq.sourceforge.net/qual.shtml)
 * [The decoy genome](http://www.cureffi.org/2013/02/01/the-decoy-genome/) 
 * [FastQC Good/Bad Examples](http://www.slideshare.net/cursoNGS/ngs-qc-granadajun2011) 

[&uarr;](#back_to_top)

***

###  Module 3: Genome Visualization <a id="module_3"></a>

  *<font color="#827e9c">TBA</font>*
  
  Lecture:
  
  Lab practical:

[&uarr;](#back_to_top)

***

###  Module 4: *De Novo* Assembly <a id="module_4"></a>

  *<font color="#827e9c">Jared Simpson</font>*
  
  Lecture:

[&uarr;](#back_to_top)
  
***

### Integrated Assignment <a id="assignment"></a>

*<font color="#827e9c">TBA</font>*

```bash
Files are in the following directory of the cloud instance: ~/CourseData/HT_data/Module2/
 * NA12891_CBW_chr1_R1.fastq.gz
 * NA12891_CBW_chr1_R2.fastq.gz
 * NA12892_CBW_chr1_R1.fastq.gz
 * NA12892_CBW_chr1_R2.fastq.gz
```

```bash
 # Create a directory to work in
 # this is where we'll place all of our output files
 
 mkdir -p ~/workspace/Integrated_assignment
 cd ~/workspace/Integrated_assignment
 
 # Erase any files that might already be there</b>
 
 rm *
 
 # Create symbolic links for all of the files contained in the Module2 directory
 # this includes the hg19 genome, the FASTQ files, and dbSNP annotation
 
 ln -s ~/CourseData/HT_data/Module2/* .
 ls
```


Task list:

1. Align the raw data to the human reference genome.
2. Sort the reads and perform duplicate removal.
3. Index the sorted bam file.
4. Perform indel cleaning.
5. Visualize the alignments.


Discussion/Questions:

1. Explain the purpose of each step.
2. Which software tool can be used for each step. 


Integrated Assignment: 

[&uarr;](#back_to_top)

***

##  Day 2 <a id="day_2"></a>


###  Module 5: Genome Variation <a id="module_5"></a>

  *<font color="#827e9c">Guillaume Bourque</font>*
  
  Lecture:
  
  Lab practical:
  
  [VCF format](https://samtools.github.io/hts-specs/VCFv4.2.pdf)
  
**Pro-tip**: A great resource for putting together a GATK-based variant calling pipeline is the [GATK Best practices](http://www.broadinstitute.org/gatk/guide/topic?name=best-practices) page. This page will guide you in your quest to produce the best variant calls possible using GATK.

**Pro-tip 2**: Another useful program for generating summary statistics on vcf files, filtering vcf files, and comparing multiple vcf files is [vcftools](http://vcftools.sourceforge.net/). 

Data set:

Programs:

 * [GATK](http://www.broadinstitute.org/gsa/wiki/index.php/The_Genome_Analysis_Toolkit) 
 * [snpEFF](http://snpeff.sourceforge.net/) 
 * [IGV](http://www.broadinstitute.org/igv/) 

[&uarr;](#back_to_top)

***

###  Module 6: Genome Structural Variation  <a id="module_6"></a>

  *<font color="#827e9c">Guillaume Bourque</font>*
  
  Lecture:
  
  Lab practical:
  
  Data set:
  
  Programs:
  
  * [lumpy-SV](https://github.com/arq5x/lumpy-sv)
  * [IGV](http://www.broadinstitute.org/igv/)
  
[&uarr;](#back_to_top)

***

###  Module 7: Bringing it Together with Galaxy  <a id="module_7"></a>

  *<font color="#827e9c">Francis Ouellette</font>*
  
  Lecture:
  
  Lab practical:
  
  Data set:
  
```bash
NA12878_CBW_chr1_R1.fastq.gz
http://cbwxx.dyndns.info/module2/NA12878_CBW_chr1_R1.fastq.gz

NA12878_CBW_chr1_R2.fastq.gz
http://cbwxx.dyndns.info/module2/NA12878_CBW_chr1_R2.fastq.gz

hg19_chr1.fa
http://cbwxx.dyndns.info/module7/hg19_chr1.fa

dbSNP_135_chr1.vcf.gz
http://cbwxx.dyndns.info/module2/dbSNP_135_chr1.vcf.gz
```

Note: xx is your student number.

Galaxy workflow part 1 (cloud): 

Galaxy workflow part 2 (main instance):

What you need for the lab:

* [Galaxy public server](https://usegalaxy.org/)
* An account on Galaxy to run tools in their environment.

Galaxy Resources:
* [Galaxy home page](http://galaxyproject.org/)
* [Galaxy public server](http://usegalaxy.org/)
* [Source for installing local Galaxy](http://getgalaxy.org/)
* [Galaxy in the Cloud](http://usegalaxy.org/cloud)

* Example of Galaxy pipeline **put example here**
* [Galaxy 101 worked example](https://main.g2.bx.psu.edu/u/aun1/p/galaxy101)
* [Galaxy servers throughout the world](http://wiki.galaxyproject.org/PublicGalaxyServers)
* [Published pages](https://main.g2.bx.psu.edu/page/list_published)

[&uarr;](#back_to_top)

***
