---
Title: Huan Fan::Research
layout: home
---

<h1 class="sitename">Huan Fan</h1>
  <ul class="nav pills">
  <li><a href="/"><i class="fa fa-home fa-fw"></i> Home</a></li>
  <li><a href="resume.html" title="Curriculumn Vitae"><i class="fa fa-book fa-fw"></i> Resume</a></li>
  <li class="active"><a href="research.html" title="Research"><i class="fa fa-flask fa-fw"></i> Research</a></li>
  <li><a href="links.html" title="Useful links"><i class="fa fa-suitcase fa-fw"></i> Links</a></li>
  <li><a href="/en/"><i class="fa fa-sitemap fa-fw"></i> Blog</a></li>
  <li><a href="README.html"><i class="fa fa-info-circle fa-fw"></i> </a></li>
</ul>


## Assembly and alignment-free Phylogenomics
The major project I was working on is to develop this Alignment and Assembly Free (AAF) method to reconstruct phylogeny from raw sequencing data. You can find the software package with detailed documentation and tutorial  [here](http://sourceforge.net/projects/aaf-phylogeny/).

## Assembly and alignment-free for RADseq data
This paper is still under review but you're welcome to try the package [phyloRAD](https://github.com/fanhuan/phyloRAD). It is still assembly and alignment-free but tailored for RADseq, or any other reduced representation sequencing data. 

## Assembly and alignment-free for GWAS
This is the actual thing I wanted to do, with the previous two as a fundation. Being able to do genome-wide association studies (GWAS) for any organism without a reference genome has been my ultimate goal. The idea is that we could use k-mers, instead of SNPs, as our unit in GWAS. The paper is still in preparation and the package only makes sense to myself at this point. More to come later this year! Check out [this package](https://aldro61.github.io/kover/doc_example.html) though, for it has the same idea but used SVM instead of regression.

## Host - Microbiome Association
Microbiome has been recognized to have played an important role in shaping the evolution of their hosts. For my postdoc work, I've been mining microbial reads from whole-genome sequencing projects and tieing them back to the differences in their hosts. It's been very exciting to work with microbes. Easy to grow, sequence, assemble, and analyze! Feel bad for species with big genomes...