---
layout: page
redirect_to:
 - https://genomon-project.github.io/GenomonPagesR/
image:
  feature: genomon-8fps-1100px-once.gif
headline: Genomon 
subtitle: The Zen of Cancer Genome Sequence Analysis 
search_omit: true
---

Genomon is a suite of bioinformatics tools for analyzing cancer genome and RNA sequencing data.

<style type="text/css">

.frame {
  border-collapse: separate;
  border-spacing: 0px 10px;
  display: table;
  width: 100%;
}
.box {
  display: table-cell;
  vertical-align: middle;
  background-color: #EFEFEF;
  padding: 10px;
}
</style>

<div class="frame">
<div class="box" style="width:200px">
<center><h2>Easy to use!</h2></center>
<div align="center"><img src="images/iconmonstr-laptop-4-96.png"></div>
<br>
</div>

<div class="box">
Genomon is now easier than ever to use.<br>
You just need to prepare list of input sequence data paths and just type:
<pre style="margin: 15px; padding: 5px; background-color: #FFFFFF;">
genomon_pipeline dna input.csv output_dir config.cfg
</pre>
</div>
</div>

<div class="frame">
<div class="box" style="width:200px">
<center><h2>Large scale!</h2></center>
<div align="center"><img src="images/iconmonstr-server-7-96.png"></div>
<br>
</div>
<div class="box">
Genomon is now highly optimized and equipped with efficient job scheduling framework. <br>
Several hundreds of genomic and transcriptome sequencing data can be analized simultaneously.
</div>
</div>

<div class="frame">
<div class="box" style="width:200px">
<center><h2>Flexible!</h2></center>
<div align="center"><img src="images/iconmonstr-control-panel-11-96.png"></div>
<br>
</div>
<div class="box">
Genomon is extensible. So you can easily incorporate your favorite modules into Genomon. <br>
Also you can easily deploy Genomon to your own cluster. 
</div>
</div>

# Overview

Genomon enables us to perform sensitive and accurate detection of most types of genomic variants
(single nucleotide variants, short indels, mid-size (20bp - 300bp) indels and large scale structural variations),
and transcriptomic changes (gene fusions, aberrant splicing patterns),
and fairly good performance is demonstrated 
through [a large number of important cancer genome projects](http://www.ncbi.nlm.nih.gov/pubmed?term=(Ogawa%2C%20Seishi%5BAuthor%5D)%20AND%20Miyano%2C%20Satoru%5BAuthor%5D).


Genomon adopts efficient job scheduling framework that enables us easily analyzing several hundreds of 
genome and transcriptome sequencing data simultaneously.
Genomon is easy to install and after installing, 
users can start analysis just preparing simple sample configuration files.

Also, Genomon can be easily extensible and developers can freely re-distribute throught GPLv3 license,

