## Bionode intro

<p style="float: left;"><a href="//bmpvieira.com/allbio14" target="_blank">bmpvieira.com/wurmlab-meeting15a</a></p>
<br>

<a href="http://bionode.io" target="_blank"><img style="padding-left: 5%; width: 50%; float: left;" alt="bionode" src="img/bionode-logo.svg" /></a>

---

### Bionode

**[Bionode.io](http://bionode.io)** <span class="fragment" style="font-size: .8em;"> - *Modular and universal bioinformatics*</span>
<img style="width: 20%;float: right; padding-right: 1em;" alt="bionode" src="img/bionode-logo.svg" />

<span class="fragment" style="font-size: .7em; line-height:10%;">Pipeable UNIX command line tools and JavaScript / Node.js APIs for bioinformatic analysis workflows on the server and browser.
<a class="fragment" href="http://irccloud.com/#!/ircs://irc.freenode.net:6697/%23bionode">#bionode</a>
<br>
<a class="fragment" href="http://gitter.im/bionode/bionode">gitter.im/bionode/bionode</a>

<div style="padding-bottom:1em;"></div>

---

### Problem: Too much data

<a href="http://nstoler.com/img/sequencingcosts.jpg" target="_blank"><img style="padding-left: 5%; width: 45%; float: left;" alt="sequencingcosts" src="img/sequencingcosts.jpg" /></a>

<a href="http://www.nature.com/nature/journal/v498/n7453/pdf/498255a.pdf" target="_blank"><img style="padding-left: 5%; width: 35%; float: left;" alt="datadeluge" src="img/datadeluge.png" /></a>

---

### Reproducibility crisis

<a href="http://cnx.org/resources/e268f3f73eb57c4ad741e45dd7c5cdd5/30.jpg" target="_blank"><img style="padding-left: 5%; width: 70%; float: left;" alt="reproducibility" src="img/reproducibility.jpg" /></a>

---

### Reproducibility layers

<div style="float: left; width: 30%;">
<a href="https://octodex.github.com/labtocat" target="_blank"><img style="padding-left: 5%; " alt="labtocat" src="img/labtocat.png" class="" /></a>
<br>
Code
</div>

<div style="float: left; width: 20%;">
<a href="http://dat-data.com" target="_blank"><img style="" alt="dat" src="img/dat.png" class="" /></a>
<br>
Data
</div>

<br>

<div style="float: left; width: 40%;">
<a href="http://bionode.io" target="_blank"><img style="" alt="bionode" src="img/bionode-logo.svg" /></a>
<br>
Workflow
</div>

<div style="float: left; width: 30%;">
<a target="_blank" href="http://docker.io"><img class="" style="" alt="docker" src="img/docker.png" /></a>
<br>
Environment
</div>

---

<a href="http://bionode.io" target="_blank"><img style="padding-left: 5%; width: 100%; float: left;" alt="bionode-team" src="img/bionodeteam.png" /></a>
<small>
<a href="https://github.com/bionode/bionode/issues/9">Bionode also collaborates with BioJS</a>
</small>

---

### Bionode - list of modules

| Name                   | Type           | Status          | People                                              |
|------------------------|----------------|-----------------------------|-----------------------------------------------------------------------|
| [ncbi]                 | Data access    | ![production][production]   |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [![maxogden][maxogden-img]][maxogden-url] [![mafintosh][mafintosh-img]][mafintosh-url] [![olgabot][olgabot-img]][olgabot-url] [![mlovci][mlovci-img]][mlovci-url] |
| [fasta]                | Parser         | ![request][production]      |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [seq]                  | Wrangling      | ![request][production]      |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [IM][IsmailM-url] [![yeban][yeban-img]][yeban-url] |
| [ensembl]              | Data access    | ![request][production]         |  [![nerdstrike][nerdstrike-img]][nerdstrike-url] [![emepyc][emepyc-img]][emepyc-url] [![daviddao][daviddao-img]][daviddao-url] |
| [blast-parser]         | Parser         | ![request][production]         |  [![greenify][greenify-img]][greenify-url]                         |

---

### Bionode - list of modules

| Name                   | Type           | Status          | People                                              |
|------------------------|----------------|-----------------------------|-----------------------------------------------------------------------|
| [template]             | Documentation  | ![request][production]      |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [JS pipeline]          | Documentation  | ![request][production]      |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [Gasket pipeline]      | Documentation  | ![request][production]      |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [Dat/Bionode workshop] | Documentation  | ![request][production]      |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |

---

### Bionode - list of modules

| Name                   | Type           | Status          | People                                              |
|------------------------|----------------|-----------------------------|-----------------------------------------------------------------------|
| [sra]                  | Wrappers       | ![development][development] |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [![olgabot][olgabot-img]][olgabot-url] [![mlovci][mlovci-img]][mlovci-url] |
| [bwa]                  | Wrappers       | ![development][development] |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [sam]                  | Wrappers       | ![development][development] |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [![ekg][ekg-img]][ekg-url] |
| [bbi]                  | Parser         | ![development][development] |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [![dasmoth][dasmoth-img]][dasmoth-url] |

---

### Bionode - list of modules

![request][request]

| Name                   | Type            | People                                              |
|------------------------|---------------------|-----------------------------------------------------------------------|
| [ebi]                  | Data access         |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [![olgabot][olgabot-img]][olgabot-url] [![mlovci][mlovci-img]][mlovci-url] [![arq5x][arq5x-img]][arq5x-url] |
| [semantic]             | Data access         |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [![ktym][ktym-img]][ktym-url] |
| [vcf]                  | Parser              |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [gff]                  | Parser              |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [bowtie]               | Wrappers            |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [sge]                  | Wrappers            |  [![bmpvieira][bmpvieira-img]][bmpvieira-url] [![maxogden][maxogden-img]][maxogden-url] [![ekg][ekg-img]][ekg-url] [![gawbul][gawbul-img]][gawbul-url] [![mkuzak][mkuzak-img]][mkuzak-url] [badryan][badryan-url] |
| [blast]                | Wrappers            |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |

---

### Bionode - list of modules

| Name                   | Type            | People                                              |
|------------------------|---------------------|-----------------------------------------------------------------------|
| [vsearch]              | Wrappers            |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [khmer]                | Wrappers            |  [![bmpvieira][bmpvieira-img]][bmpvieira-url]                         |
| [rsem]                 | Wrappers            |  [![olgabot][olgabot-img]][olgabot-url]                               |
| [gmap]                 | Wrappers            |  [![olgabot][olgabot-img]][olgabot-url]                               |
| [star]                 | Wrappers            |  [![olgabot][olgabot-img]][olgabot-url]                               |
| [go]                   | Wrappers            |  [badryan][badryan-url]                               |


[ncbi]: https://github.com/bionode/bionode-ncbi
[NCBI API (e-utils)]: http://www.ncbi.nlm.nih.gov/books/NBK25501/
[fasta]: https://github.com/bionode/bionode-fasta
[seq]: https://github.com/bionode/bionode-seq
[template]: https://github.com/bionode/bionode-template
[JS pipeline]: https://github.com/bionode/bionode-examples
[Gasket pipeline]: https://github.com/bionode/bionode-example-dat-gasket
[Dat/Bionode workshop]: http://maxogden.github.io/get-dat
[Mozfest 2014]: http://schedule.mozillafestival.org/#session/-1I0CKguyr
[Gasket]: https://github.com/datproject/gasket
[sra]: https://github.com/bionode/bionode-sra
[SRA Toolkit]: http://www.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=toolkit_doc
[bwa]: https://github.com/bionode/bionode-bwa
[Burrows-Wheeler Aligner]: http://bio-bwa.sourceforge.net
[sam]: https://github.com/bionode/bionode-sam
[Sequence Alignment/Map tools]: http://www.htslib.org
[bbi]: https://github.com/bionode/bionode-bbi
[BBI (bigWig and bigBed)]: http://genome.ucsc.edu/FAQ/FAQformat.html
[ebi]: https://github.com/bionode/bionode-ebi
[EBI API]: http://www.ebi.ac.uk/Tools/webservices/
[ensembl]: https://github.com/daviddao/biojs-rest-ensembl
[ENSEMBL API]: http://rest.ensembl.org
[semantic]: https://github.com/bionode/bionode-semantic
[vcf]: https://github.com/bionode/bionode-vcf
[Variant Call Format]: http://samtools.github.io/hts-specs/VCFv4.2.pdf
[gff]: https://github.com/bionode/bionode-gff
[General Feature Format]: https://www.sanger.ac.uk/resources/software/gff/spec.html
[bowtie]: https://github.com/bionode/bionode-bowtie
[Bowtie aligner]: http://bowtie-bio.sourceforge.net/index.shtml
[sge]: https://github.com/bionode/bionode-sge
[SUN Grid Engine]: https://arc.liv.ac.uk/trac/SGE
[blast]: https://github.com/bionode/bionode-blast
[blast-parser]: https://github.com/greenify/biojs-io-blast
[Basic Local Alignment Search Tool]: http://www.ncbi.nlm.nih.gov/books/NBK1763/
[vsearch]: https://github.com/bionode/bionode-vsearch
[Search and clustering]: https://github.com/torognes/vsearch
[khmer]: https://github.com/bionode/bionode-khmer
[k-mer counting & filtering]: http://khmer.readthedocs.org/en/v1.1/
[rsem]: https://github.com/bionode/bionode-rsem
[RNA-Seq by Expectation-Maximization]: https://github.com/bli25wisc/RSEM
[gmap]: https://github.com/bionode/bionode-gmap
[Genomic Mapping and Alignment Program]: http://research-pub.gene.com/gmap/
[star]: https://github.com/bionode/bionode-star
[Spliced Transcripts Alignment to a Reference]: https://github.com/alexdobin/STAR
[go]: https://github.com/bionode/bionode-go
[Gene ontology]: http://en.wikipedia.org/wiki/Gene_ontology

[production]:https://img.shields.io/badge/status-production-green.svg?style=flat-square
[development]:https://img.shields.io/badge/status-development-orange.svg?style=flat-square
[request]:https://img.shields.io/badge/status-request-blue.svg?style=flat-square

[bmpvieira-img]: https://avatars3.githubusercontent.com/u/263386?v=3&s=40
[bmpvieira-url]: https://github.com/bmpvieira
[maxogden-img]: https://avatars3.githubusercontent.com/u/39759?v=3&s=40
[maxogden-url]: https://github.com/maxogden
[mafintosh-img]: https://avatars3.githubusercontent.com/u/376661?v=3&s=40
[mafintosh-url]: https://github.com/mafintosh
[olgabot-img]: https://avatars3.githubusercontent.com/u/806256?v=3&s=40
[olgabot-url]: https://github.com/olgabot
[mlovci-img]: https://avatars3.githubusercontent.com/u/909047?v=3&s=40
[mlovci-url]: https://github.com/mlovci
[arq5x-img]: https://avatars3.githubusercontent.com/u/72291?v=3&s=40
[arq5x-url]: https://github.com/arq5x
[ktym-img]: https://pbs.twimg.com/profile_images/1124266319/ktym_normal.jpg
[ktym-url]: https://github.com/ktym
[ekg-img]: https://avatars3.githubusercontent.com/u/145425?v=3&s=40
[ekg-url]: https://github.com/ekg
[badryan-img]: https://avatars3.githubusercontent.com/u/6317446?v=3&s=40
[badryan-url]: https://github.com/badryan
[gawbul-img]: https://avatars3.githubusercontent.com/u/321291?v=3&s=40
[gawbul-url]: https://github.com/gawbul
[mkuzak-img]: https://avatars3.githubusercontent.com/u/208443?v=3&s=40
[mkuzak-url]: https://github.com/mkuzak
[dasmoth-img]: https://avatars3.githubusercontent.com/u/209047?v=3&s=40
[dasmoth-url]: https://github.com/dasmoth
[IsmailM-img]: https://avatars3.githubusercontent.com/u/5578375?v=3&s=40
[IsmailM-url]: https://github.com/IsmailM
[yeban-img]: https://avatars3.githubusercontent.com/u/90373?v=3&s=40
[yeban-url]: https://github.com/yeban
[nerdstrike-img]: https://avatars3.githubusercontent.com/u/5434501?v=3&s=40
[nerdstrike-url]: https://github.com/nerdstrike
[emepyc-img]: https://avatars3.githubusercontent.com/u/473962?v=3&s=40
[emepyc-url]: https://github.com/emepyc
[daviddao-img]: https://avatars0.githubusercontent.com/u/1241240?v=3&s=40
[daviddao-url]: https://github.com/daviddao
[greenify-img]: https://avatars1.githubusercontent.com/u/4370550?v=3&s=40
[greenify-url]: https://github.com/greenify

---

### Dat workshop

[maxogden.github.io/get-dat](http://maxogden.github.io/get-dat)

<a href="http://maxogden.github.io/get-dat" target="_blank"><img style="padding-left: 5%; width: 100%; float: left;" alt="get-dat" src="img/datworkshop.png" /></a>

---

### Bionode

<code class="fragment">npm install -g bionode</code><br>
<code class="fragment">bionode ncbi download gff bacteria</code>
<code class="fragment">bionode ncbi download sra arthropoda | bionode sra fastq-dump</code><br>
<code class="fragment">npm install -g bionode-ncbi</code><br>
<code class="fragment">bionode-ncbi search assembly formicidae | dat import --json</code><br>

---


### Some problems I faced during my research:

<ul>
<li class="fragment">For web projects, needed to implement the same functionality on browser and server</li>

<li class="fragment"> Difficulty getting relevant descriptions and datasets from NCBI API using bio\* libs</li>

<li class="fragment">Difficulty writing scalable, reproducible and complex bioinformatic pipelines</li>
</ul>

---

** Need to reimplement the same code on browser and server. **

Solution: JavaScript everywhere

* [Afra](http://afra.sbcs.qmul.ac.uk) <span class="">-> [bionode-seq]() </span>
* [GeneValidator](http://genevalidator.sbcs.qmul.ac.uk) <span class="">-> [seq](https://github.com/bionode/bionode-seq), [fasta](https://github.com/bionode/bionode-fasta)</span>
* [SequenceServer](http://www.sequenceserver.com)
* [BioJS](http://biojs.net) <span class=""> -> [collaborating for code reuse](http://github.com/bionode/bionode/issues/9)</span>
* [Biodalliance](http://www.biodalliance.org) <span class="">-> [converting to bionode](https://github.com/bionode/bionode-bbi)</span>

---

** Difficulty getting relevant description and datasets from NCBI API using bio* libs **

<div class="fragment">
<p><strong>Python example:</strong> URL for the Achromyrmex assembly?</p>
<a href="ftp://ftp.ncbi.nlm.nih.gov/genomes/all/GCA_000188075.1_Si_gnG"><pre>ftp://ftp.ncbi.nlm.nih.gov/genomes/all/GCA_000188075.1_Si_gnG</pre></a>
</div>

<pre class="fragment">
<span class="fragment">import xml.etree.ElementTree as ET</span>
<span class="fragment">from Bio import Entrez</span>
<span class="fragment">Entrez.email = "mail@bmpvieira.com"</span>
<span class="fragment">esearch_handle = Entrez.esearch(db="assembly", term="Achromyrmex")</span>
<span class="fragment">esearch_record = Entrez.read(esearch_handle)</span>
<span class="fragment">for id in esearch_record['IdList']:</span>
<span class="fragment">  esummary_handle = Entrez.esummary(db="assembly", id=id)</span>
<span class="fragment">  esummary_record = Entrez.read(esummary_handle)</span>
<span class="fragment">  documentSummarySet = esummary_record['DocumentSummarySet']</span>
<span class="fragment">  document = documentSummarySet['DocumentSummary'][0]</span>
<span class="fragment">  metadata_XML = document['Meta'].encode('utf-8')</span>
<span class="fragment">  metadata = ET.fromstring('<root>' + metadata_XML + '</root>')</span>
<span class="fragment">  for entry in Metadata[1]:</span>
<span class="fragment">    print entry.text</span>
</pre>

<span class="fragment">
Solution: <a href="http://github.com/bionode/bionode-ncbi">bionode-ncbi</a>
</span>

---

** Difficulty getting relevant description and datasets from NCBI API using bio* libs **

<div class="fragment">
<p><strong>Example:</strong> URL for the Achromyrmex assembly?</p>
<a href="http://ftp.ncbi.nlm.nih.gov/genomes/all/GCA_000204515.1_Aech_3.9/GCA_000204515.1_Aech_3.9_genomic.fna.gz"><pre>http://ftp.ncbi.nlm.nih.gov/genomes/all/GCA_000204515.1_Aech_3.9/GCA_000204515.1_Aech_3.9_genomic.fna.gz</pre></a>
</div>

<p class="fragment">JavaScript</p>
<pre class="fragment">
<span class="fragment">var bio = require('bionode')</span>
<span class="fragment">bio.ncbi.urls('assembly', 'Acromyrmex', function(urls) {</span>
<span class="fragment">  console.log(urls[0].genomic.fna)</span>
<span class="fragment">})</span>
</pre>

<pre class="fragment">
<span class="fragment">bio.ncbi.urls('assembly', 'Acromyrmex').on('data', printGenomeURL)</span>
<span class="fragment">function printGenomeURL(urls) {</span>
<span class="fragment">  console.log(urls[0].genomic.fna)</span>
<span class="fragment">})</span>
</pre>

---

** Difficulty getting relevant description and datasets from NCBI API using bio* libs **

<div class="fragment">
<p><strong>Example:</strong> URL for the Achromyrmex assembly?</p>
<a href="http://ftp.ncbi.nlm.nih.gov/genomes/all/GCA_000204515.1_Aech_3.9/GCA_000204515.1_Aech_3.9_genomic.fna.gz"><pre>http://ftp.ncbi.nlm.nih.gov/genomes/all/GCA_000204515.1_Aech_3.9/GCA_000204515.1_Aech_3.9_genomic.fna.gz</pre></a>
</div>

<p class="fragment">JavaScript</p>
<pre class="fragment">
<span class="fragment">var ncbi = require('bionode-ncbi')</span>
<span class="fragment">var ndjson = require('ndjson')</span>
<span class="fragment">ncbi.urls('assembly', 'Acromyrmex')</span>
<span class="fragment">.pipe(ndjson.stringify())</span>
<span class="fragment">.pipe(process.stdout)</span>
</pre>

<p class="fragment">BASH</p>
<pre class="fragment">
<span class="fragment">bionode-ncbi urls assembly Acromyrmex |
tool-stream extractProperty genomic.fna
</span>
</pre>

---

**Difficulty writing scalable, reproducible and complex bioinformatic pipelines.**

Solution: Node.js Streams everywhere

<pre>
var ncbi = require('bionode-ncbi')
var tool = require('tool-stream')
var through = require('through2')
var fork1 = through.obj()
var fork2 = through.obj()
</pre>

---

**Difficulty writing scalable, reproducible and complex bioinformatic pipelines.**

Solution: Node.js Streams everywhere

<pre>
<span class="fragment">ncbi</span>
<span class="fragment">.search('sra', 'Solenopsis invicta')</span>
<span class="fragment">.pipe(fork1)</span>
<span class="fragment">.pipe(dat.reads)</span>

<span class="fragment">fork1</span>
<span class="fragment">.pipe(tool.extractProperty('expxml.Biosample.id'))</span>
<span class="fragment">.pipe(ncbi.search('biosample'))</span>
<span class="fragment">.pipe(dat.samples)</span>

<span class="fragment">fork1</span>
<span class="fragment">.pipe(tool.extractProperty('uid'))</span>
<span class="fragment">.pipe(ncbi.link('sra', 'pubmed'))</span>
<span class="fragment">.pipe(ncbi.search('pubmed'))</span>
<span class="fragment">.pipe(fork2)</span>
<span class="fragment">.pipe(dat.papers)</span>
</pre>

---

<img style="float: left; padding-right:.5em; width:100%;" alt="streams" src="img/streams2.gif" />

---

**Difficulty writing scalable, reproducible and complex bioinformatic pipelines.**

<pre>
<span class="fragment">bionode-ncbi search genome Guillardia theta |</span>
<span class="fragment">tool-stream extractProperty assemblyid |</span>
<span class="fragment">bionode-ncbi download assembly |</span>
<span class="fragment">tool-stream collectMatch status completed |</span>
<span class="fragment">tool-stream extractProperty uid|</span>
<span class="fragment">bionode-ncbi link assembly bioproject |</span>
<span class="fragment">tool-stream extractProperty destUID |</span>
<span class="fragment">bionode-ncbi link bioproject sra |</span>
<span class="fragment">tool-stream extractProperty destUID |</span>
<span class="fragment">bionode-ncbi download sra |</span>
<span class="fragment">bionode-sra fastq-dump |</span>
<span class="fragment">tool-stream extractProperty destFile |</span>
<span class="fragment">bionode-bwa mem 503988/GCA_000315625.1_Guith1_genomic.fna.gz |</span>
<span class="fragment">tool-stream collectMatch status finished|</span>
<span class="fragment">tool-stream extractProperty sam|</span>
<span class="fragment">bionode-sam</span>
</pre>

---

**Difficulty writing scalable, reproducible and complex bioinformatic pipelines.**

* [bionode-example-dat-gasket](https://github.com/bionode/bionode-example-dat-gasket)
* [get-dat workshop](http://maxogden.github.io/get-dat/)
* [get-dat bionode gasket example](https://github.com/maxogden/get-dat/blob/master/markdown/08-extra-credit.md)

---

**Difficulty writing scalable, reproducible and complex bioinformatic pipelines.**

<pre>
<span class="fragment"> { </span>
<span class="fragment">   "import-data": [ </span>
<span class="fragment">     "bionode-ncbi search genome eukaryota", </span>
<span class="fragment">     "dat import --json --primary=uid" </span>
<span class="fragment">   ], </span>
<span class="fragment">   "search-ncbi": [ </span>
<span class="fragment">     "dat cat", </span>
<span class="fragment">     "grep Guillardia", </span>
<span class="fragment">     "tool-stream extractProperty assemblyid", </span>
<span class="fragment">     "bionode-ncbi download assembly -", </span>
<span class="fragment">     "tool-stream collectMatch status completed", </span>
<span class="fragment">     "tool-stream extractProperty uid", </span>
<span class="fragment">     "bionode-ncbi link assembly bioproject -", </span>
<span class="fragment">     "tool-stream extractProperty destUID", </span>
<span class="fragment">     "bionode-ncbi link bioproject sra -", </span>
<span class="fragment">     "tool-stream extractProperty destUID", </span>
<span class="fragment">     "grep 35526", </span>
<span class="fragment">     "bionode-ncbi download sra -", </span>
<span class="fragment">     "tool-stream collectMatch status completed", </span>
<span class="fragment">     "tee > metadata.json" </span>
<span class="fragment">   ], </span>
</pre>

---

**Difficulty writing scalable, reproducible and complex bioinformatic pipelines.**

<pre>
<span class="fragment">   "index-and-align": [ </span>
<span class="fragment">     "cat metadata.json", </span>
<span class="fragment">     "bionode-sra fastq-dump -", </span>
<span class="fragment">     "tool-stream extractProperty destFile", </span>
<span class="fragment">     "bionode-bwa mem **/*fna.gz" </span>
<span class="fragment">   ], </span>
<span class="fragment">   "convert-to-bam": [ </span>
<span class="fragment">     "bionode-sam 35526/SRR070675.sam" </span>
<span class="fragment">   ] </span>
<span class="fragment"> } </span>

</pre>


---

**Difficulty writing scalable, reproducible and complex bioinformatic pipelines.**

<span class="fragment">[datscript](https://github.com/datproject/datscript)</span>
<pre class="fragment">
pipeline main
run pipeline import

pipeline import
run foobar | run dat import --json
</pre>
<span class="fragment"><p class="fragment">[bmpvieira example](https://github.com/datproject/datscript/blob/master/example.ds)</p></span>
<span class="fragment"><p class="fragment">[ekg example](https://github.com/ekg/datscriptish/blob/master/example.dsh)</p></span>

---


## Extra slides

---

### Bionode - Why wrappers?

* Same interface between modules (Streams and NDJSON)
* Easy installation with NPM
* Semantic versioning
* Add tests
* Abstract complexity / More user friendly

---

### Bionode - Why Node.js?

Same code client/server side

<img style="padding-left: 5%; width: 80%; float: left;" alt="client-server" src="img/client-server.png" />
<a href="http://browserify.org/" target="_blank"><img style="padding-left: 5%; width: 25%; float: left;" alt="browserify" src="img/browserify.png" /></a>

---

### Bionode - Why Node.js?

<a href="https://nodei.co/#bionode-ncbi" target="_blank"><img style="padding-left: 5%; width: 50%; float: left;" alt="bionode-nci" src="img/bionode-ncbi.png" class="fragment"/></a>
<a href="http://www.modulecounts.com/" target="_blank"><img style="padding-left: 5%; width: 80%; float: left;" alt="modules" src="img/modules.png" class="fragment"/></a>

---

### Reusable, small and tested modules

![badges](img/badges.png)

---

### Benefit from other JS projects

<div class="fragment" style="float: left; padding-right:2em; width:20%;">
<a href="http://dat-data.com" target="_blank">Dat</a>
<img style="width:100%;" alt="dat" src="img/dat.png" />
</div>

<div class="fragment" style="float: left; padding-right:2em; width:20%;">
<a href="http://biojs.net" target="_blank">BioJS</a>
<img style="width:100%;" alt="biojs" src="img/biojs.png" />
</div>

<div class="fragment" style="float: left; padding-right:2em; width:20%;">
<a href="http://noflojs.org" target="_blank">NoFlo</a>
<img style="width:100%;" alt="noflo" src="img/noflo.jpg" />
</div>

---

<section data-background="img/noflo.png"></section>

---

<section data-background="img/bionode-pipeline.png"></section>

---

<a href="http://nodered.org/" target="_blank"><img style="padding-left: 5%; width: 90%; float: left;" alt="nodered" src="img/nodered.png" /></a>

<a href="https://usegalaxy.org/" target="_blank"><img style="padding-left: 5%; width: 90%; float: left;" alt="bionode-galaxy" src="img/bionode-galaxy.png" class="fragment" /></a>

---
