# Sequencing-Cheetsheet
Source: [https://emea.illumina.com/techniques/sequencing/ngs-library-prep/library-prep-methods.html](https://emea.illumina.com/techniques/sequencing/ngs-library-prep/library-prep-methods.html)

## Sequencing methods

**[DNA sequencing methods](https://github.com/lemonbases/Sequencing-Cheetsheet/blob/master/for-all-you-seq-dna.pdf)**:

- DNA variants
- Low levels of DNA
- Epigenetics
- DNA–protein interactions
- Protein–protein interactions

**[RNA sequencing methods](https://github.com/lemonbases/Sequencing-Cheetsheet/blob/master/for-all-you-seq-rna.pdf)**:

- RNA transcription
- RNA–protein interactions
- Low levels of RNA
- RNA modifications
- RNA structure

**[Single-Cell methods](https://github.com/lemonbases/Sequencing-Cheetsheet/blob/master/for-all-you-seq-single-cell.pdf)**:

- Low-level RNA detection
- Low-level DNA detection
- Integrated DNA and RNA analysis

## Comparison

**[DNA methods overview](https://github.com/lemonbases/Sequencing-Cheetsheet/blob/master/dna-sequencing-methods-review-web.pdf)**

**[RNA methods overview](https://github.com/lemonbases/Sequencing-Cheetsheet/blob/master/rna-sequencing-methods-review-web.pdf)**

### Genomics

#### DNA breaking mapping

<h5>BLESS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bless.png"></p>

<p>BLESS is a genome-wide approach to map DSBs at nucleotide resolution. BLESS is able to detect telomere ends, Sce endonuclease–induced DSBs, and complex genome-wide DSB landscapes. In this method, DSBs are ligated <i>in situ</i> to a proximal linker covalently linked to biotin. The gDNA is extracted and fragmented, and the labeled fragments are captured on streptavidin beads. Next, a distal linker is ligated to the free end of the captured fragments. The fragments are released by linker digestion with I-SceI and PCR-amplified.</p>
<h6>Pros:</h6>
<ul>
<li>Detects DSBs at nucleotide resolution</li>
<li>Does not depend on proteins that bind to DSBs—a source of bias</li>
<li>Does not depend on single-stranded DNA (ssDNA)—a source of bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>High background; only maps unjoined ends<sup>1</sup></li>
<li>Susceptible to artifacts associated with cell fixation<sup>2</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23503052">BLESS: Crosetto N., Mitra A., Silva M. J., Bienko M., Dojer N., et al. (2013) Nucleotide-resolution DNA double-strand break mapping by next-generation sequencing. Nat Methods 10: 361-365</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27031497">1. Hu J., Meyers R. M., Dong J., Panchakshari R. A., Alt F. W., et al. (2016) Detecting DNA double-stranded breaks in mammalian genomes by linear amplification-mediated high-throughput genome-wide translocation sequencing. Nat Protoc 11: 853-871</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25513782">2. Tsai S. Q., Zheng Z., Nguyen N. T., Liebers M., Topkar V. V., et al. (2015) GUIDE-seq enables genome-wide profiling of off-target cleavage by CRISPR-Cas nucleases. Nat Biotechnol 33: 187-197</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25830891">Ran F. A., Cong L., Yan W. X., Scott D. A., Gootenberg J. S., et al. (2015) In vivo genome editing using Staphylococcus aureus Cas9. Nature 520: 186-191</a></li>
</ol>

<h5>Break-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/break-seq.png"></p>

<p>Break-seq combines DSB labeling with NGS to map chromosome breaks with improved sensitivity and resolution.
DNA trapped in agarose plugs is end-repaired and labeled with biotin. The agarose is then digested by beta-agarase, followed by dilution and fragmentation. The fragmented DNA is purified and end-repaired with unmodified dNTPs, followed by A-tailing. The fragments are purified on magnetic beads, PCR-amplified, purified, and used to prepare a sequencing library.</p>
<h6>Pros:</h6>
<ul>
<li>Simple protocol</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not replicated in other laboratories</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25609572" target="_blank">Break-Seq: Hoffman E. A., McCulley A., Haarer B., Arnak R. and Feng W. Break-seq reveals hydroxyurea-induced chromosome fragility as a result of unscheduled conflict between DNA replication and transcription. Genome Res. 2015;25:402-412</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25609572" target="_blank">Hoffman E. A., McCulley A., Haarer B., Arnak R. and Feng W. Break-seq reveals hydroxyurea-induced chromosome fragility as a result of unscheduled conflict between DNA replication and transcription. Genome Res. 2015;25:402-412</a></li>
</ol>

<h5>DSB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/dsb-seq.png"></p>

<p>DSB-Seq maps in vivo DNA DSBs on a genome-wide scale. 
In this method, DNA is biotinylated by a 3’-end tailing reaction with biotin-16-dUTP. The biotinylated DNA is sonicated and captured with streptavidin-coated beads. The free DNA fragments are purified and used to prepare a sequencing library.</p>
<h6>Pros:</h6>
<ul>
<li>Simple protocol</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not yet adopted widely by the scientific community</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25056547" target="_blank">DSB-Seq: Baranello L., Kouzine F., Wojtowicz D., et al. DNA break mapping reveals topoisomerase II activity genome-wide. Int J Mol Sci. 2014;15:13111-13122</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25056547" target="_blank">Baranello L., Kouzine F., Wojtowicz D., Cui K., Przytycka T. M., et al. DNA break mapping reveals topoisomerase II activity genome-wide. Int J Mol Sci. 2014;15:13111-13122</a></li>
</ol>

<h5>GUIDE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/guide-seq.png"></p>

<p>GUIDE-seq relies on the integration of double-stranded oligodeoxynucleotides (DSOs) into DSBs. It belongs to a family of methods—such as HTGTS, LAM-HTGTS, and Digenome-seq —that are aimed at detecting off-target effects of CRISPR/Cas9 and other RNA-guided nucleases (RGNs).
RGN-induced DSBs are tagged by integration of blunt-ended DSOs in the genomes of living human cells. The DSO integration sites are mapped precisely in the genome at the nucleotide level with unbiased amplification and NGS.</p>
<h6>Pros:</h6>
<ul>
<li>Can generate global specificity landscapes for RGNs in living human cells</li>
<li>Targeted sequencing reduces cost</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Can miss some targets<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25513782">GUIDE-Seq: Tsai S. Q., Zheng Z., Nguyen N. T., Liebers M., Topkar V. V., et al. (2015) GUIDE-seq enables genome-wide profiling of off-target cleavage by CRISPR-Cas nucleases. Nat Biotechnol 33: 187-197</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26786045">1. Kim D., Kim S., Kim S., Park J. and Kim J. S. (2016) Genome-wide target specificities of CRISPR-Cas9 nucleases revealed by multiplex Digenome-seq. Genome Res 26: 406-415</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27031497" target="_blank">Hu J., Meyers R. M., Dong J., Panchakshari R. A., Alt F. W., et al. Detecting DNA double-stranded breaks in mammalian genomes by linear amplification-mediated high-throughput genome-wide translocation sequencing. Nat Protoc. 2016;11:853-871</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26750397" target="_blank">Lee C. M., Cradick T. J., Fine E. J. and Bao G. Nuclease Target Site Selection for Maximizing On-target Activity and Minimizing Off-target Effects in Genome Editing. Mol Ther. 2016;24:475-487</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27347757" target="_blank">Kleinstiver B. P., Tsai S. Q., Prew M. S., et al. Genome-wide specificities of CRISPR-Cas Cpf1 nucleases in human cells. Nat Biotechnol. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26735016" target="_blank">Kleinstiver B. P., Pattanayak V., Prew M. S., et al. High-fidelity CRISPR-Cas9 nucleases with no detectable genome-wide off-target effects. Nature. 2016;529:490-495</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26829318" target="_blank">Yin H., Song C. Q., Dorkin J. R., et al. Therapeutic genome editing by combined viral and non-viral delivery of CRISPR system components <i>in vivo</i>. Nat Biotechnol. 2016;34:328-333</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26480473" target="_blank">Bolukbasi M. F., Gupta A., Oikemus S., et al. DNA-binding-domain fusions enhance the targeting range and precision of Cas9. Nat Methods. 2015;12:1150-1156</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26596280" target="_blank">Friedland A. E., Baral R., Singhal P., et al. Characterization of Staphylococcus aureus Cas9: a smaller Cas9 for all-in-one adeno-associated virus delivery and paired nickase applications. Genome Biol. 2015;16:257</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26524662" target="_blank">Kleinstiver B. P., Prew M. S., Tsai S. Q., et al. Broadening the targeting range of Staphylococcus aureus CRISPR-Cas9 by modifying PAM recognition. Nat Biotechnol. 2015;33:1293-1298</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26780180" target="_blank">Doench J. G., Fusi N., Sullender M., et al. Optimized sgRNA design to maximize activity and minimize off-target effects of CRISPR-Cas9. Nat Biotechnol. 2016;34:184-191</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26829318" target="_blank">Yin H., Song C. Q., Dorkin J. R., Zhu L. J., Li Y., et al. Therapeutic genome editing by combined viral and non-viral delivery of CRISPR system components <i>in vivo</i>. Nat Biotechnol. 2016;34:328-333</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26167643" target="_blank">Chari R., Mali P., Moosburner M. and Church G. M. Unraveling CRISPR-Cas9 genome engineering parameters via a library-on-library approach. Nat Methods. 2015;12:823-826</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26098369" target="_blank">Kleinstiver B. P., Prew M. S., Tsai S. Q., et al. Engineered CRISPR-Cas9 nucleases with altered PAM specificities. Nature. 2015;523:481-485</a></li>
</ol>

<h5>HTGTS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/htgts.png"></p>

<p>HTGTS was developed to study translocation mechanisms in mammalian cells.  This approach is particularly suitable for studying for AID-dependent IgH class-switching (HTGTS-Rep-seq)  and CRISPR/Cas9 genome modifications. 
In HTGTS-Rep-seq, genomic DNA from B-cell populations is sonicated and linearly amplified with a biotinylated primer that anneals downstream of a J segment. The biotin-labeled single-stranded DNA products are enriched with streptavidin beads, and the 3’ ends are ligated to a bridge adaptor containing a 6-nucleotide UMI.</p>
<h6>Pros:</h6>
<ul>
<li>Higher efficiency compared to whole-genome sequencing</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Underestimates the frequency of DSBs <sup>1</sup> </li>
<li>Limited by chromatin accessibility <sup>2</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21962511" target="_blank">HTGTS: Chiarle R., Zhang Y., Frock R. L., et al. Genome-wide translocation sequencing reveals mechanisms of chromosome breaks and rearrangements in B cells. Cell. 2011;147:107-119</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27354528" target="_blank">HTGTS-Rep-Seq: Lin S. G., Ba Z., Du Z., Zhang Y., Hu J. and Alt F. W. Highly sensitive and unbiased approach for elucidating antibody repertoires. Proc Natl Acad Sci U S A. 2016;113:7846-7851</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26924689" target="_blank">HTGTS CRISPR/Cas9: Mei Y., Wang Y., Chen H., Sun Z. S. and Ju X. D. Recent Progress in CRISPR/Cas9 Technology. J Genet Genomics. 2016;43:63-75</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27031497" target="_blank">1. Hu J., Meyers R. M., Dong J., Panchakshari R. A., Alt F. W. and Frock R. L. Detecting DNA double-stranded breaks in mammalian genomes by linear amplification-mediated high-throughput genome-wide translocation sequencing. Nat Protoc. 2016;11:853-871</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25664545" target="_blank">2. Kim D., Bae S., Park J., et al. Digenome-seq: genome-wide profiling of CRISPR-Cas9 off-target effects in human cells. Nat Methods. 2015;12:237-243, 231 p following 243</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26873106" target="_blank">Schwer B., Wei P. C., Chang A. N., et al. Transcription-associated processes cause DNA double-strand breaks and translocations in neural stem/progenitor cells. Proc Natl Acad Sci U S A. 2016;113:2258-2263</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25503383" target="_blank">Frock R. L., Hu J., Meyers R. M., Ho Y. J., Kii E. and Alt F. W. Genome-wide detection of DNA double-stranded breaks induced by engineered nucleases. Nat Biotechnol. 2015;33:179-186</a></li>
</ol>

<h5>LAM-HTGTS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/lam-htgts.png"></p>

<p>LAM-HTGTS is a method for the genome-wide detection of “prey” DSBs via their translocation to a fixed “bait” DSB in cultured mammalian cells.  Bait-prey junctions are cloned directly from isolated gDNA using LAM-PCR and ligated unidirectionally to bridge adapters. Subsequent PCR steps amplify the single-stranded DNA junction library in preparation for sequencing..</p>
<h6>Pros:</h6>
<ul>
<li>Sensitive detection of DSBs within chromosomes</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not applicable to limited amounts of material</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27031497" target="_blank">LAM-HTGTS: Hu J., Meyers R. M., Dong J., Panchakshari R. A., Alt F. W. and Frock R. L. Detecting DNA double-stranded breaks in mammalian genomes by linear amplification-mediated high-throughput genome-wide translocation sequencing. Nat Protoc. 2016;11:853-871</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/nextera-mate-pair.html">Nextera Mate Pair Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27031497" target="_blank">Hu J., Meyers R. M., Dong J., Panchakshari R. A., Alt F. W., et al. Detecting DNA double-stranded breaks in mammalian genomes by linear amplification-mediated high-throughput genome-wide translocation sequencing. Nat Protoc. 2016;11:853-871</a></li>
</ol>

#### DNA low level detection

<h5>DR-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/dr-seq.png"></p>

<p>gDNA-mRNA sequencing (DR-Seq) studies the genomic and transcriptomic relationship of single-cells via sequencing. Nucleic acid amplification prior to physical separation reduces sample loss and risk of contamination. DR-Seq involves multiple amplification steps, including a quasilinear amplification technique similar to MALBAC.</p>
<p>First, mRNA are reverse-transcribed from lysed single-cells using poly-dT primers with Ad-1x adaptors, producing single-stranded cDNA (sscDNA). Ad-1x adaptor sequence contain cell-identifying barcodes, 5' Illumina adaptors, and a T7 promoter. Then, both gDNA and sscDNA are simultaneously amplified via quasilinear whole-genome amplification with Ad-2 primers. These primers are similar to MALBAC adaptors, containing 8 random nucleotide sequence for random priming followed by a constant 27 nucleotide tag at the 5' end. Products of this amplification step are split in 2. One half is prepared for genome sequencing, in which gDNA are PCR amplified and liberated of their Ad-2 adaptors before DNA library prep and sequencing. The other half is used for transcriptome sequencing, where cDNAs are synthesized and amplified by in-vitro transcription. Resulting RNA products are produced only from cDNA fragments flanked with Ad-1x and Ad-2, suppressing amplification of the gDNA fragments. RNA library is prepared for sequencing following the Illumina small RNA protocol. Sequencing gDNA and mRNA from the same cell preserves information between the genome and its expression levels.</p>
<h6>Pros:</h6>
<ul>
<li>Interrogates genomic and transcriptomic behavior from a single-cell</li>
<li>Amplification prior to separation reduces sample loss and contamination</li>
<li>Length-based identifier used to remove duplicate reads</li>
<li>Quasilinear amplification reduces PCR bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Manual single-cell isolation prevents high-throughput adaptation</li>
<li>Quasilinear amplification is temperature-sensitive</li>
<li>RNA reads are 3' end biased<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25599178" target="_blank">DR-Seq: Dey S. S., Kester L., Spanjaard B., Bienko M. and van Oudenaarden A. (2015) Integrated genome and transcriptome sequencing of the same cell. Nat Biotechnol </a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25915121" target="_blank">1. Macaulay I. C., Haerty W., Kumar P., Li Y. I., Hu T. X., et al. (2015) G&amp;T-seq: parallel sequencing of single-cell genomes and transcriptomes. Nat Methods</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25599178">Dey S. S., Kester L., Spanjaard B., Bienko M. and van Oudenaarden A. (2015) Integrated genome and transcriptome sequencing of the same cell. Nat Biotechnol </a></li>
</ol>

<h5>Drop-ChIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/drop-chip.png"></p>

<p>Droplet-based single-cell chromatin immune-precipitation sequencing (Drop-ChIP) analyzes the chromatin states of single-cells by utilizing microfluidics, unique molecular barcodes, and next-generation sequencing.</p>
<p>Single-cells are first isolated into droplets containing lysis buffer and MNase and then fused to a droplet carrying distinct oligonucleotides. These oligonucleotides contain the sequences for cell-specific barcodes, sequencing adaptors, and restriction sites. DNA ligase is also fused with the droplet to complete the tagging process. Then, carrier chromatins are introduced into the pooled droplets before chromatin immune-precipitation. Library preparation is carried out according to ChIP-Seq procedures before sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Analyzes chromatin states from single-cells in a highly parallel manner</li>
<li>Unique molecular barcoding reduces the risk posed by unspecific antibodies</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires a large number of sample cells</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26458175">Drop-ChIP: Rotem A., Ram O., Shoresh N., Sperling R. A., Goren A., et al. (2015) Single-cell ChIP-seq reveals cell subpopulations defined by chromatin state. Nat Biotechnol </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26458175">Rotem A., Ram O., Shoresh N., Sperling R. A., Goren A., et al. (2015) Single-cell ChIP-seq reveals cell subpopulations defined by chromatin state. Nat Biotechnol </a></li>
</ol>

<h5>Drop-ChIP/scChIP-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/drop-chip-scchip-seq.png"></p>

<p>Droplet-based single-cell chromatin immune-precipitation sequencing (Drop-ChIP or scChIP-seq) analyzes the chromatin states of single-cells by utilizing microfluidics, unique molecular barcodes, and next-generation sequencing.</p>
<p>Single-cells are first isolated into droplets containing lysis buffer and MNase and then fused to a droplet carrying distinct oligonucleotides. These oligonucleotides contain the sequences for cell-specific barcodes, sequencing adaptors, and restriction sites. DNA ligase is also fused with the droplet to complete the tagging process. Then, carrier chromatins are introduced into the pooled droplets before chromatin immune-precipitation. Library preparation is carried out according to ChIP-Seq procedures before sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Analyzes chromatin states from single-cells in a highly parallel manner</li>
<li>Unique molecular barcoding reduces the risk posed by unspecific antibodies</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>The data from each cell is sparse</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26458175">Drop-ChIP/scChIP-Seq: Rotem A., Ram O., Shoresh N., Sperling R. A., Goren A., et al. (2015) Single-cell ChIP-seq reveals cell subpopulations defined by chromatin state. Nat Biotechnol </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26458175">Rotem A., Ram O., Shoresh N., Sperling R. A., Goren A., et al. (2015) Single-cell ChIP-seq reveals cell subpopulations defined by chromatin state. Nat Biotechnol </a></li>
</ol>

<h5>Duplex Sequencing</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/duplex-sequencing.png"></p>

<p>Duplex sequencing is a tag-based error correction method to improve sequencing accuracy . In this method, adapters (with primer sequences and random 12 bp indices) are ligated onto the template and amplified using PCR. Deep sequencing provides consensus sequence information from every unique molecular tag. Based on molecular tags and sequencing primers, duplex sequences are aligned, determining the true sequence on each DNA strand.</p>
<h6>Pros:</h6>
<ul>
<li>Very low error rate due to duplex tagging system</li>
<li>PCR amplification errors can be detected and removed from analysis</li>
<li>No additional library preparation steps after addition of adapters</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>PCR amplification errors</li>
<li>Non-linear PCR amplification can lead to biases affecting reproducibility</li>
<li>PCR biases can underrepresent GC-rich templates</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22853953" target="_blank">Duplex Sequencing: Schmitt M. W., Kennedy S. R., Salk J. J., Fox E. J., Hiatt J. B., et al. (2012) Detection of ultra-rare mutations by next-generation sequencing. Proc Natl Acad Sci U S A 109: 14508-14513</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25849638" target="_blank">Schmitt M. W., Fox E. J., Prindle M. J., Reid-Bayliss K. S., True L. D., et al. (2015) Sequencing small genomic targets with high efficiency and extreme accuracy. Nat Methods 12: 423-425</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25237203" target="_blank">Rashid N. U., Sperling A. S., Bolli N., Wedge D. C., Van Loo P., et al. (2014) Differential and limited expression of mutant alleles in multiple myeloma. Blood 124: 3110-3117</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25079324" target="_blank">Wang Y., Waters J., Leung M. L., Unruh A., Roh W., et al. (2014) Clonal evolution in breast cancer revealed by single nucleus genome sequencing. Nature 512: 155-160</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24086148" target="_blank">Kennedy S. R., Salk J. J., Schmitt M. W. and Loeb L. A. (2013) Ultra-sensitive sequencing reveals an age-related increase in somatic mitochondrial mutations that are inconsistent with oxidative damage. PLoS Genet 9: e1003794</a></li>
</ol>

<h5>G&amp;T-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/g-t-seq.png"></p>

<p>G&T-Seq can separate and sequence genomic DNA and full-length mRNA from single cells.  In this method, single cells are isolated and lysed. RNA is captured using biotinylated oligo(dT) capture primers and separated from DNA using streptavidin-coated magnetic beads. Smart-seq2 is used to amplify captured RNA on the bead, while multiple displacement amplification (MDA) is used to amplify DNA. After sequencing, integrating the DNA and RNA sequences provides insights into the gene expression profiles of single cells.</p>
<h6>Pros:</h6>
<ul>
<li>Compatible with any whole-genome amplification method</li>
<li>No 3'-end bias in sequence reads because full-length transcripts are captured</li>
<li>Because DNA and RNA are physically separated and amplified independently, there is no need to mask coding sequences during analysis</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Physical separation of DNA and RNA can increase the risk of sample loss or contamination</li>
<li>Physical separation of DNA and RNA increases handling time</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25915121">G&amp;T-Seq: Macaulay I. C., Haerty W., Kumar P., Li Y. I., Hu T. X., et al. (2015) G&amp;T-seq: parallel sequencing of single-cell genomes and transcriptomes. Nat Methods 12: 519-522</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27212022" target="_blank">Bock C., Farlik M. and Sheffield N. C. Multi-Omics of Single Cells: Strategies and Applications. Trends Biotechnol. 2016;34:605-608</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27091476" target="_blank">Clark S. J., Lee H. J., Smallwood S. A., Kelsey G. and Reik W. Single-cell epigenomics: powerful new methods for understanding gene regulation and cell identity. Genome Biol. 2016;17:72</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26941284" target="_blank">Zhang X., Marjani S. L., Hu Z., Weissman S. M., Pan X., et al. Single-Cell Sequencing for Precise Cancer Research: Progress and Prospects. Cancer Res. 2016;76:1305-1312</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27412011" target="_blank">Vieira Braga F. A., Teichmann S. A. and Chen X. Genetics and immunity in the era of single-cell genomics. Hum Mol Genet. 2016;25:R141-R148</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27272212" target="_blank">Lu L., Lv B., Huang K., Xue Z., Zhu X. and Fan G. Recent advances in preimplantation genetic diagnosis and screening. J Assist Reprod Genet. 2016;33:1129-1134</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26752769" target="_blank">Angermueller C., Clark S. J., Lee H. J., et al. Parallel single-cell sequencing links transcriptional and epigenetic heterogeneity. Nat Methods. 2016;13:229-232</a></li>
</ol>

<h5>MALBAC</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/malbac.png"></p>

<p>Multiple annealing and looping–based amplification cycles (MALBAC) is intended to address some of the shortcomings of MDA . In this method, MALBAC primers randomly anneal to a DNA template. A polymerase with displacement activity at elevated temperatures amplifies the template, generating “semi-amplicons.” As the amplification and annealing process is repeated, the semi-amplicons are amplified into full amplicons that have a 3’ end complimentary to the 5’ end. As a result, full-amplicon ends hybridize to form a looped structure, inhibiting further amplification of the looped amplicon, while only the semi-amplicons and genomic DNA undergo amplification. Deep sequencing of the full-amplicon sequences allows for accurate representation of reads, while sequencing depth provides improved alignment for consensus sequences.</p>
<h6>Pros:</h6>
<ul>
<li>Can sequence large templates</li>
<li>Can perform single-cell sequencing or sequencing for samples with very limited starting material</li>
<li>Full-amplicon looping inhibits over-representation of templates, reducing PCR bias</li>
<li>Can amplify GC-rich regions</li>
<li>Uniform genome coverage</li>
<li>Lower allele drop-out rate compared to MDA</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Polymerase is relatively error prone compared to Phi 29</li>
<li>Temperature-sensitive protocol</li>
<li>Genome coverage up to ~90%, but some regions of the genome are consistently underrepresented</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23258894" target="_blank">MALBAC: Zong C., Lu S., Chapman A. R. and Xie X. S. (2012) Genome-wide detection of single-nucleotide and copy-number variations of a single human cell. Science 338: 1622-1626</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25599178" target="_blank">Dey S. S., Kester L., Spanjaard B., Bienko M. and van Oudenaarden A. (2015) Integrated genome and transcriptome sequencing of the same cell. Nat Biotechnol 33: 285-289</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25953353" target="_blank">Li N., Wang L., Wang H., Ma M., Wang X., et al. (2015) The Performance of Whole Genome Amplification Methods and Next-Generation Sequencing for Pre-Implantation Genetic Diagnosis of Chromosomal Abnormalities. J Genet Genomics 42: 151-159</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26091148" target="_blank">Ning L., Li Z., Wang G., Hu W., Hou Q., et al. (2015) Quantitative assessment of single-cell whole genome amplification methods for detecting copy number variation using hippocampal neurons. Sci Rep 5: 11415</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25860606" target="_blank">Upton K. R., Gerhardt D. J., Jesuadian J. S., Richardson S. R., Sanchez-Luque F. J., et al. (2015) Ubiquitous L1 mosaicism in hippocampal neurons. Cell 161: 228-239</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25879913" target="_blank">Zhang C. Z., Adalsteinsson V. A., Francis J., Cornils H., Jung J., et al. (2015) Calibrating genomic and allelic coverage bias in single-cell sequencing. Nat Commun 6: 6822</a></li>
</ol>

<h5>MDA/IMS-MDA</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mda-ims-mda.png"></p>

<p>Multiple displacement amplification (MDA) is a method commonly used for sequencing microbial genomes due to its ability to amplify templates larger than 0.5 Mbp, but it can also be used to study genomes of other sizes . In this method, 3’-blocked random hexamer primers are hybridized to the template, followed by synthesis with Phi 29 polymerase. Phi 29 performs strand-displacement DNA synthesis, allowing for efficient and rapid DNA amplification. Deep sequencing of the amplified DNA allows for accurate representation of reads, while sequencing depth provides better alignment and consensus for sequences.</p>
<h6>Pros:</h6>
<ul>
<li>Templates used for this method can be circular DNA (plasmids, bacterial DNA)</li>
<li>Can sequence large templates</li>
<li>Can perform single-cell sequencing or sequencing for samples with very limited starting material</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Strong amplification bias. Genome coverage as low as ~6%</li>
<li>PCR biases can underrepresent GC-rich templates</li>
<li>Contaminated reagents can impact results</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/11381035">MDA: Dean F. B., Nelson J. R., Giesler T. L. and Lasken R. S. (2001) Rapid amplification of plasmid and phage DNA using Phi 29 DNA polymerase and multiply-primed rolling circle amplification. Genome Res 11: 1095-1099</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24202554">IMS-MDA:Seth-Smith H. M. et al. (2013) Generating whole bacterial genome sequences of low-abundance species from complex samples with IMS-MDA. Nat Protoc 8: 2404-2412</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25689864" target="_blank">Bigdeli S., Dettloff R. O., Frank C. W., Davis R. W. and Crosby L. D. (2015) A simple method for encapsulating single cells in alginate microspheres allows for direct PCR and whole genome amplification. PLoS One 10: e0117738</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25985139" target="_blank">Ottolini C. S., Newnham L. J., Capalbo A., Natesan S. A., Joshi H. A., et al. (2015) Genome-wide maps of recombination and chromosome segregation in human oocytes and embryos show selection for maternal recombination rates. Nat Genet 47: 727-735</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25915121" target="_blank">Macaulay I. C., Haerty W., Kumar P., Li Y. I., Hu T. X., et al. (2015) G&amp;T-seq: parallel sequencing of single-cell genomes and transcriptomes. Nat Methods 12: 519-522</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25853327" target="_blank">Leung M. L., Wang Y., Waters J. and Navin N. E. (2015) SNES: single nucleus exome sequencing. Genome Biol 16: 55</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26017310" target="_blank">Zhang C. Z., Spektor A., Cornils H., Francis J. M., Jackson E. K., et al. (2015) Chromothripsis from DNA damage in micronuclei. Nature 522: 179-184</a></li>
</ol>

<h5>MIPSTR</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mipstr.png"></p>

<p>MIPSTR: a method for multiplex genotyping of germline and somatic STR variation across many individuals. This method is a variation of the single-molecule molecular inversion probes (smMIP) approach and a novel mapping strategy.</p>
<p>A single molecular inversion probe (smMIP) with common backbone for PCR primer, sequencing adapters, 12 base pair degenerate tag, and targeting arms with locus-specific and STR-flanking sequences is used. Capture across genetically diverse individuals identifies germline STR variation. The use of degenerate tags identifies technical variation. STR variation across tag-defined read groups is considered somatic variation.</p>
<h6>Pros:</h6>
<ul>
<li>Capable of distinguishing technical error from somatic STR mutations</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires high-quality reference genome</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25659649">MIPSTR: Carlson K. D., Sudmant P. H., Press M. O., Eichler E. E., Shendure J., et al. (2015) MIPSTR: a method for multiplex genotyping of germline and somatic STR variation across many individuals. Genome Res 25: 750-761</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25659649">Carlson K. D., Sudmant P. H., Press M. O., Eichler E. E., Shendure J., et al. (2015) MIPSTR: a method for multiplex genotyping of germline and somatic STR variation across many individuals. Genome Res 25: 750-761</a></li>
</ol>

<h5>nuc-seq/SNES</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/nuc-seq-snes.png"></p>

<p>Nuc-seq is a modified MDA protocol that takes advantage of the fact that a single cell in the G2–M stage of the cell cycle has four copies of the genome, which allows the cells to be isolated with a cell sorter and it also significantly increases the genome coverage of single cells. SNES, single nucleotide exome sequencing, is an additional variation that includes targeted selection and sequencing of the exomes.</p>
<p>Div-Seq is a variation, which combines nuc-seq with EdU-mediated labeling of proliferating cells.</p>
<h6>Pros:</h6>
<ul>
<li>nuc-seq: Improves physical coverage performance to more than 90% for single cell sequencing</li>
<li>SNES: 95.94% exome coverage in single cells</li>
<li>SNES: Detection efficiencies of 92.37% for SNVs in an isogenic population</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>nuc-seq: Cannot be applied to cells with low proliferation rates</li>
<li>SNES: Limited to exomes</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25079324">nuc-seq: Wang Y., Waters J., Leung M. L., Unruh A., Roh W., et al. (2014) Clonal evolution in breast cancer revealed by single nucleus genome sequencing. Nature 512: 155-160</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25853327">SNES: Leung M. L., Wang Y., Waters J. and Navin N. E. (2015) SNES: single nucleus exome sequencing. Genome Biol 16: 55</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26741407">Leung M. L., Wang Y., Kim C., Gao R., Jiang J., et al. (2016) Highly multiplexed targeted DNA sequencing from single nuclei. Nat Protoc 11: 214-235</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25853327">Leung M. L., Wang Y., Waters J. and Navin N. E. (2015) SNES: single nucleus exome sequencing. Genome Biol 16: 55</a></li>
</ol>

<h5>OS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/os-seq.png"></p>

<p>Oligonucleotide-selective sequencing (OS-Seq)&nbsp; was developed to improve targeted resequencing, by capturing and sequencing gene targets directly on the flow cell. In this method, target sequences with adapters are used to modify the flow cell primers. Targets in the template are captured onto the flow cell with the modified primers. Further extension, denaturation, and hybridization provide sequence reads for target genes. Deep sequencing provides accurate representation of reads.</p>
<h6>Pros:</h6>
<ul>
<li>Can resequence multiple targets at a time</li>
<li>No gel excision or narrow size purification required</li>
<li>Very fast (single-day) protocol</li>
<li>Samples can be multiplexed</li>
<li>Reduced PCR bias due to removal of amplification steps</li>
<li>Avoids loss of material</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Primers may interact with similar target sequences, leading to sequence ambiguity</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22853953" target="_blank">OS-Seq: Schmitt M. W., Kennedy S. R., Salk J. J., Fox E. J., Hiatt J. B., et al. (2012) Detection of ultra-rare mutations by next-generation sequencing. Proc Natl Acad Sci U S A 109: 14508-14513</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25462399" target="_blank">Markkula N., Suvisaari J., Saarni S. I., Pirkola S., Pena S., et al. (2015) Prevalence and correlates of major depressive disorder and dysthymia in an eleven-year follow-up--results from the Finnish Health 2011 Survey. J Affect Disord 173: 73-80</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26247051" target="_blank">Vattulainen S., Aho J., Salmenperä P., Bruce S., Tallila J., et al. (2015) Accurate genetic diagnosis of Finnish pulmonary arterial hypertension patients using oligonucleotide-selective sequencing. Molecular Genetics &amp; Genomic Medicine 3: 354-362</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24782526" target="_blank">Hopmans E. S., Natsoulis G., Bell J. M., Grimes S. M., Sieh W., et al. (2014) A programmable method for massively parallel targeted sequencing. Nucleic Acids Res 42: e88</a></li>
</ol>

<h5>Safe-SeqS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/safe-seqs.png"></p>

<p>Safe-sequencing system (Safe-SeqS), or more commonly Safe-Seq, is the name given to a unique molecular identifier (UMI) approach to detect rare variants. Since the publication of the method in 2011 the use UMIs have become ubiquitous, particularly in single cell sequencing approaches, but the name of the method fell into disuse.</p>
<p>Safe-Seq assigns a unique identifier (UMI) to each template molecule and amplifies each uniquely tagged template molecule to create UMI families. The abundance of each UMI can be used to distinguish between rare mutations and technical errors and it can also be used to correct for PCR amplification bias.</p>
<h6>Pros:</h6>
<ul>
<li>Distinguish between rare mutations and technical errors</li>
<li>Detect 1 mutant template among 5000 to 1,000,000 wild-type templates<sup>1</sup></li>
<li>Correct for PCR amplification bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Can introduce spurious cross-hybridization</li>
<li>Complex protocol that requires a gel-purification step<sup>2</sup></li>
<li>Uses two or four PCR cycles for barcode addition and does not satisfy the basic principle of labelling each molecule with a single unique barcode<sup>3</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21586637">Safe-SeqS: Kinde I., Wu J., Papadopoulos N., Kinzler K. W. and Vogelstein B. (2011) Detection and quantification of rare mutations with massively parallel sequencing. Proc Natl Acad Sci U S A 108: 9530-9535</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23303603">1. Kinde I., Bettegowda C., Wang Y., Wu J., Agrawal N., et al. (2013) Evaluation of DNA from the Papanicolaou test to detect ovarian and endometrial cancers. Sci Transl Med 5: 167ra164</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27060140">2. Stahlberg A., Krzyzanowski P. M., Jackson J. B., Egyud M., Stein L., et al. (2016) Simple, multiplexed, PCR-based barcoding of DNA enables sensitive mutation detection in liquid biopsies using sequencing. Nucleic Acids Res 44: e105</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26126624">3. Kukita Y., Matoba R., Uchida J., Hamakawa T., Doki Y., et al. (2015) High-fidelity target sequencing of individual molecules identified using barcode sequences: de novo detection and absolute quantitation of mutations in plasma cell-free DNA from cancer patients. DNA Res 22: 269-277</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome </a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25623214">Dal Molin M., Zhang M., de Wilde R. F., Ottenhof N. A., Rezaee N., et al. (2015) Very Long-term Survival Following Resection for Pancreatic Cancer Is Not Explained by Commonly Mutated Genes: Results of Whole-Exome Sequencing Analysis. Clin Cancer Res 21: 1944-1950</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27341568">Eboreime J., Choi S. K., Yoon S. R., Arnheim N. and Calabrese P. (2016) Estimating Exceptionally Rare Germline and Somatic Mutation Frequencies via Next Generation Sequencing. PLoS One 11: e0158340</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26109104">Wang Y., Springer S., Mulvey C. L., Silliman N., Schaefer J., et al. (2015) Detection of somatic mutations and HPV in the saliva and plasma of patients with head and neck squamous cell carcinomas. Sci Transl Med 7: 293ra104</a></li>
</ol>

<h5>scAba-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scaba-seq.png"></p>

<p>scABA-seq is a single-cell, genome-wide and strand-specific 5hmC sequencing technology, based on 5hmC glucosylation and glucosylation-dependent digestion of DNA.</p>
<p>Glucosylated DNA of individual cells is digested with AbaSI. Digested DNA is ligated to an adaptor containing a cell-specific barcode, Illumina 5′adaptor and a T7 promoter. Ligated DNA from different cells is pooled and amplified using in vitro transcription (IVT) mediated by T7 polymerase.</p>
<h6>Pros:</h6>
<ul>
<li>Determine strand-specific glucosylation in individual cells</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Ambiguity might exist in 13 % of the cleaved molecules in the Aba-seq assay<sup>1</sup></li>
<li>Sequence bias in AbaSI activity<sup>2</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27347753">scAba-Seq: Mooijman D., Dey S. S., Boisset J. C., Crosetto N. and van Oudenaarden A. (2016) Single-cell 5hmC sequencing reveals chromosome-wide cell-to-cell variability and enables lineage reconstruction. Nat Biotechnol advance online publication: </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27025842">1. Serandour A. A., Avner S., Mahe E. A., Madigou T., Guibert S., et al. (2016) Single-CpG resolution mapping of 5-hydroxymethylcytosine by chemical labeling and exonuclease digestion identifies evolutionarily unconserved CpGs as TET targets. Genome Biol 17: 56 </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25639471">2. Sun Z., Dai N., Borgaro J. G., Quimby A., Sun D., et al. (2015) A sensitive approach to map genome-wide 5-hydroxymethylcytosine and 5-formylcytosine at single-base resolution. Mol Cell 57: 750-761</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27347753">Mooijman D., Dey S. S., Boisset J. C., Crosetto N. and van Oudenaarden A. (2016) Single-cell 5hmC sequencing reveals chromosome-wide cell-to-cell variability and enables lineage reconstruction. Nat Biotechnol advance online publication: </a></li>
</ol>

<h5>scATAC-Seq (Cell Index)<br>
</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scatac-seq-cell-index.png"></p>

<p>Single-cell ATAC-Seq uses combinatorial cellular indexing to measure chromatin accessibility in thousands of single cells per assay. This avoids the need for compartmentalization of individual cells, which makes the system scalable to analyze thousands of cells at a time.</p>
<p>In this method nuclei are isolated and molecularly tagged in bulk with barcoded Tn5 transposases in wells. Nuclei are then pooled and a limited number redistributed into a second set of wells. A second barcode is then introduced during the PCR amplification step. The fragments are then pooled for library prep and sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>High throughput and scalable</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25953818">scATAC-Seq (Cell Index): Cusanovich D. A., Daza R., Adey A., Pliner H. A., Christiansen L., et al. (2015) Epigenetics. Multiplex single-cell profiling of chromatin accessibility by combinatorial cellular indexing. Science 348: 910-914</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27526324">Corces M. R., Buenrostro J. D., Wu B., Greenside P. G., Chan S. M., et al. (2016) Lineage-specific and single-cell chromatin accessibility charts human hematopoiesis and leukemia evolution. Nat Genet</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26949524">Liu S. and Trapnell C. (2016) Single-cell transcriptome sequencing: recent advances and remaining challenges. F1000Res 5: </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27259149">Lu F., Liu Y., Inoue A., Suzuki T., Zhao K., et al. (2016) Establishing Chromatin Regulatory Landscape during Mouse Preimplantation Development. Cell 165: 1375-1388</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25953818">Cusanovich D. A., Daza R., Adey A., Pliner H. A., Christiansen L., et al. (2015) Epigenetics. Multiplex single-cell profiling of chromatin accessibility by combinatorial cellular indexing. Science 348: 910-914</a></li>
</ol>

<h5>scBS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scbs-seq.png"></p>

<p>Single-cell bisulfite sequencing (scBS-seq) is a version of the well established bisulfite sequencing (BS-seq) and post-bisulfite adaptor tagging (PBAT) protocols, modified to detect methylated cytosines in genomic DNA from single cells. In this method, after single cells are isolated, genomic DNA is treated with sodium bisulfite, which fragments the DNA. The converted DNA, then undergoes random priming several times and is PCR amplified for sequencing. Deep sequencing provides high resolution single nucleotide resolution of methylated cytosines from single cells.</p>

<h6>References:</h6>
<div>Methods Link:</div>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25042786">scBS-seq: Smallwood S. A., Lee H. J., Angermueller C., Krueger F., Saadeh H., et al. (2014) Single-cell genome-wide bisulfite sequencing for assessing epigenetic heterogeneity. Nat Methods 11: 817-820</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><div>Product Links:</div>
<ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<div>Citations:</div>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25042786" target="_blank">Smallwood S. A., Lee H. J., Angermueller C., Krueger F., Saadeh H., et al. (2014) Single-cell genome-wide bisulfite sequencing for assessing epigenetic heterogeneity. Nat Methods 11: 817-820</a></li>
</ol>

<h5>scM&amp;T-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scm-t-seq.png"></p>

<p>scM&amp;T-Seq allows parallel analysis of both epigenetic and gene expression patterns from single cells using Smart-seq2 and scBS-seq. scM&amp;T-Seq is built upon G&amp;T-seq, but instead of using MDA for DNA sequencing, it uses scBS-Seq to determine DNA methylation patterns.</p>
<p>Single cells are isolated and individually lysed. The mRNAs are captured with streptavidin-coupled mRNA capture primers to separate them physically from the DNA strands. Smart-seq2 uses RT with template switching and tagmentation to generate cDNA libraries from the mRNA. DNA libraries are prepared via scBS-seq, which involves bisulfite conversion of DNA strands to identify methylated cytosines. Both libraries are ready for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Investigates links between epigenetic and transcriptional heterogeneity in single cells</li>
<li>Because DNA and RNA are physically separated and amplified independently, there is no need to mask coding sequences during analysis</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Smart-seq2 is not strand-specific and applicable to only poly(A)+ RNA</li>
<li>Does not distinguish between 5mC and 5hmC</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26752769">scM&amp;T-Seq: Angermueller C., Clark S. J., Lee H. J., Macaulay I. C., Teng M. J., et al. (2016) Parallel single-cell sequencing links transcriptional and epigenetic heterogeneity. Nat Methods 13: 229-232</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27091476" target="_blank">Clark S. J., Lee H. J., Smallwood S. A., Kelsey G. and Reik W. Single-cell epigenomics: powerful new methods for understanding gene regulation and cell identity. Genome Biol. 2016;17:72</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27083874" target="_blank">Wen L. and Tang F. Single-cell sequencing in stem cell biology. Genome Biol. 2016;17:71</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27150361" target="_blank">Hu Y., Huang K., An Q., et al. Simultaneous profiling of transcriptome and DNA methylome from a single cell. Genome Biol. 2016;17:88</a></li>
</ol>

<h5>scRC-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scrc-seq.png"></p>

<p>Single-cell RC-seq uses sequence capture to enrich DNA for the junctions between retrotransposon termini and adjacent genomic regions, followed by paired-end sequencing. 
In this method, nuclei are purified first by fluorescence-activated cell sorting (FACS) and then picked with a micromanipulator. The DNA is extracted from nuclei and subjected to linear WGA, followed by exponential PCR in 2 separate reactions for each nucleus, using different enzymes. The products are combined and analyzed via WGS to assess genome coverage. The libraries prepared are enriched by hybridization to locked nucleic acid (LNA) probes and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Detects somatic mutations in single cells</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Low throughput due to manual single-nucleus isolation</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25860606" target="_blank">scRC-Seq: "Upton K. R., Gerhardt D. J., Jesuadian J. S., et al. Ubiquitous L1 mosaicism in hippocampal neurons. Cell. 2015;161:228-239</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25860606" target="_blank">Upton K. R., Gerhardt D. J., Jesuadian J. S., Richardson S. R., Sanchez-Luque F. J., et al. Ubiquitous L1 mosaicism in hippocampal neurons. Cell. 2015;161:228-239</a></li>
</ol>

<h5>scTrio-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/sctrio-seq.png"></p>

<p>scTrio-Seq can analyze genomic CNVs, the DNA methylome, and the transcriptome of an individual mammalian cell simultaneousl.  This approach is an extension of previous methods, such as scMT-seq. </p>
<h6>Pros:</h6>
<ul>
<li>Accurately analyzes the mechanism by which the transcriptome, genome, and DNA methylome regulate each other</li>
<li>CNVs can be identified reliably using scRRBS data</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Lower transcriptome coverage than scMT-seq<sup>1</sup></li>
<li>Results in 3'-biased transcriptome</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26902283">scTrio-Seq: Hou Y., Guo H., Cao C., Li X., Hu B., et al. (2016) Single-cell triple omics sequencing reveals genetic, epigenetic, and transcriptomic heterogeneity in hepatocellular carcinomas. Cell Res </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27150361">1. Hu Y., Huang K., An Q., Du G., Hu G., et al. (2016) Simultaneous profiling of transcriptome and DNA methylome from a single cell. Genome Biol 17: 88</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27212022" target="_blank">Bock C., Farlik M. and Sheffield N. C. Multi-Omics of Single Cells: Strategies and Applications. Trends Biotechnol. 2016;34:605-608</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27708664" target="_blank">Poirion O. B., Zhu X., Ching T. and Garmire L. Single-Cell Transcriptomics Bioinformatics and Computational Challenges. Frontiers in Genetics. 2016;7:163</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27525975" target="_blank">Cheow L. F., Courtois E. T., Tan Y., et al. Single-cell multimodal profiling reveals cellular epigenetic heterogeneity. Nat Methods. 2016;13:833-836</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27442339" target="_blank">Picelli S. Single-cell RNA-sequencing: The future of genome biology is now. RNA Biol. 2016;1-14</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27619166" target="_blank">Qian M., Wang D. C., Chen H. and Cheng Y. Detection of single cell heterogeneity in cancer. Semin Cell Dev Biol. </a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26902283">Hou Y., Guo H., Cao C., Li X., Hu B., et al. (2016) Single-cell triple omics sequencing reveals genetic, epigenetic, and transcriptomic heterogeneity in hepatocellular carcinomas. Cell Res </a></li>
</ol>

<h5>SMDB</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/smdb.png"></p>

<p>SMDB is a method to leverage short-read sequencing to obtain long and accurate reads. 
Using a microfluidics system, the method isolates, amplifies, fragments, and barcodes single DNA molecules in aqueous picoliter droplets. This approach allows the full-length molecules to be sequenced with multi-fold coverage, using short-read sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Limit of detection scales with the number of molecules sequenced and can be orders of magnitude more sensitive than conventional NGS</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires specialized hardware</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27353563" target="_blank">SMDB: Lan F., Haliburton J. R., Yuan A. and Abate A. R. Droplet barcoding for massively parallel single-molecule deep sequencing. Nat Commun. 2016;7:11784</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27353563" target="_blank">Lan F., Haliburton J. R., Yuan A. and Abate A. R. Droplet barcoding for massively parallel single-molecule deep sequencing. Nat Commun. 2016;7:11784</a></li>
</ol>

<h5>smMIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/smmip.png"></p>

<p>The single-molecule molecular inversion probes (smMIP) method uses single-molecule tagging and molecular inversion probes to detect and quantify genetic variations occurring at very low frequencies. In this method, probes are used to detect targets in genomic DNA. After the probed targets are copied, exonuclease digestion leaves the target with a tag, which undergoes PCR amplification and sequencing. Sequencing allows for high-resolution sequence reads of targets, while greater depth allows for better alignment for every unique molecular tag.</p>
<h6>Pros:</h6>
<ul>
<li>Detection of low-frequency targets</li>
<li>Can perform single-cell sequencing or sequencing for samples with very limited starting material</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>PCR amplification errors</li>
<li>PCR biases can underrepresent GC-rich templates</li>
<li>Targets smaller than 500 bp are preferentially amplified by polymerases during PCR</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23382536">smMIP: Hiatt J. B., Pritchard C. C., Salipante S. J., O'Roak B. J. and Shendure J. (2013) Single molecule molecular inversion probes for targeted, high-accuracy detection of low-frequency variation. Genome Res 23: 843-854 </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23382536">Hiatt J. B., Pritchard C. C., Salipante S. J., O'Roak B. J. and Shendure J. (2013) Single molecule molecular inversion probes for targeted, high-accuracy detection of low-frequency variation. Genome Res 23: 843-854 </a></li>
</ol>

#### Rearrangements and markers
<h5>2b-RAD</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/2b-rad.png"></p>

<p>2b-RAD is similar to ddRadseq, but uses type IIB restriction enzymes (BsaXI or AlfI) that will cleave upstream and downstream of a recognition site. This shears the target genome into a large number of DNA fragments with a constant length of 33 bp (BsaXI) or 36 bp (Alfl). These short DNA fragments can be sequenced to determine the genetic variants.</p>
<p>In this method, genomic DNA is first digested with a restriction enzyme (BsaXI) and adaptors with partial (NNN) overhangs are ligated to the fragments. The adaptor-ligated fragments from different samples are combined and the fragments amplified.</p>
<h6>Pros:</h6>
<ul>
<li>The highly reduced 2b-RAD libraries require much less sequencing for accurate genotyping</li>
<li>High density of markers</li>
<li>No interim purification steps reduce losses and processing time</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires a reference genome</li>
<li>The short tags may not be long enough for efficient locus discrimination in complex genomes</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22609625">2b-RAD: Wang S., Meyer E., McKay JK., Matz MV. (2012) 2b-RAD: a simple and flexible method for genome-wide genotyping. Nat Methods 9:808-10</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26711352">Pecoraro C., Babbucci M., Villamor A., Franch R., Papetti C., et al. (2016) Methodological assessment of 2b-RAD genotyping technique for population structure inferences in yellowfin tuna (Thunnus albacares). Mar Genomics 25: 43-48</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27345016">Fu B., Liu H., Yu X. and Tong J. (2016) A high-density genetic map and growth related QTL mapping in bighead carp (Hypophthalmichthys nobilis). Sci Rep 6: 28679</a></li>
</ol>

<h5>Bubble-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bubble-seq.png"></p>

<p>Bubble-Seq: Libraries of restriction fragments that contain replication initiation sites (bubbles) in vivo.</p>
<p>DNA was biotinylated by 3'-end tailing reaction and Biotin-16-dUTP. Biotinylated DNA was sonicated and captured with streptavidin-coated beads. The free DNA fragments were then purified..</p>
<h6>Pros:</h6>
<ul>
<li>Simple protocol</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not widely adopted by the scientific community yet</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23861383">Bubble-Seq: Mesner L. D., Valsakumar V., Cieslik M., Pickin R., Hamlin J. L., et al. (2013) Bubble-seq analysis of the human genome reveals distinct chromatin-mediated mechanisms for regulating early- and late-firing origins. Genome Res 23: 1774-1788</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25695952">Foulk M. S., Urban J. M., Casella C. and Gerbi S. A. (2015) Characterizing and controlling intrinsic biases of lambda exonuclease in nascent strand sequencing reveals phasing between nucleosomes and G-quadruplex motifs around a subset of human replication origins. Genome Res 25: 725-735</a></li>
</ol>

<h5>CAP-seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cap-seq.png"></p>

<p>CAP-seq  maps the 5' end of RNAs anchored to RNAPII. 
In this method, RNA transcripts are treated sequentially with Terminator exonuclease, CIP, and TAP, followed by linker ligation and RT to cDNA. Deep sequencing of the cDNA provides high-resolution sequences of RNAPII transcripts.</p>
<h6>Pros:</h6>
<ul>
<li>Maps RNAs anchored to RNAPII</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Multiple steps and treatments can lead to loss of material</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20885785">CAP-Seq: Illingworth R. S., Gruenewald-Schneider U., Webb S., Kerr A. R., James K. D., et al. (2010) Orphan CpG islands identify numerous conserved promoters in the mammalian genome. PLoS Genet 6: e1001134</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24279449">Suzuki M. M., Yoshinari A., Obara M., Takuno S., Shigenobu S., et al. (2013) Identical sets of methylated and nonmethylated genes in Ciona intestinalis sperm and muscle cells. Epigenetics Chromatin 6: 38</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22855832">Clouaire T., Webb S., Skene P., Illingworth R., Kerr A., et al. (2012) Cfp1 integrates both CpG content and gene activity for accurate H3K4me3 deposition in embryonic stem cells. Genes Dev 26: 1714-1728</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22841499">Gendrel A. V., Apedaile A., Coker H., Termanis A., Zvetkova I., et al. (2012) Smchd1-dependent and -independent pathways determine developmental dynamics of CpG island methylation on the inactive X chromosome. Dev Cell 23: 265-279</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23256043">Farcas A. M., Blackledge N. P., Sudbery I., Long H. K., McGouran J. F., et al. (2012) KDM2B links the Polycomb Repressive Complex 1 (PRC1) to recognition of CpG islands. Elife 1: e00205</a></li>
</ol>

<h5>CPT-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cpt-seq.png"></p>

<p>Genome-wide haplotyping based on contiguity-preserving transposition (CPT-seq) and combinatorial indexing. Tn5 transposition is used to modify DNA with adaptor and index sequences while preserving contiguity. After DNA dilution and compartmentalization, the transposase is removed and the DNA separated into individually indexed libraries. The libraries in each compartment are enriched for neighboring genomic elements and are further indexed via PCR. Combinatorial 96-plex indexing at both the transposition and PCR stage enables the construction of phased synthetic reads from each of the nearly 10,000 virtual compartments.</p>
<h6>Pros:</h6>
<ul>
<li>Highly indexed and efficient</li>
<li>FragScaff to be highly effective at scaffolding large genomes from CPT-seq data<sup>1</sup></li>
<li>The large effective number of virtual compartments per physical compartment could avoid the amplification biases associated with MDA<sup>2</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>The method has not been adopted widely</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25326703">CPT-Seq: Amini S., Pushkarev D., Christiansen L., Kostem E., Royce T., et al. (2014) Haplotype-resolved whole-genome sequencing by contiguity-preserving transposition and combinatorial indexing. Nat Genet 46: 1343-1349</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27307620">1. Kuleshov V., Snyder M. P. and Batzoglou S. (2016) Genome assembly from synthetic long read clouds. Bioinformatics 32: i216-i224</a></li>
<li><a target="_blank" href="http://link.springer.com/article/10.1007/s40484-016-0064-3">2. Cao C.-c. and Sun X. (2016) Combinatorial pooled sequencing: experiment design and decoding. Quantitative Biology 4: 36-46</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25326703">Amini S., Pushkarev D., Christiansen L., Kostem E., Royce T., et al. (2014) Haplotype-resolved whole-genome sequencing by contiguity-preserving transposition and combinatorial indexing. Nat Genet 46: 1343-1349</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27159086">Mostovoy Y., Levy-Sakin M., Lam J., Lam E. T., Hastie A. R., et al. (2016) A hybrid approach for de novo human genome sequence assembly and phasing. Nat Methods 13: 587-590</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25948246">Snyder M. W., Adey A., Kitzman J. O. and Shendure J. (2015) Haplotype-resolved genome sequencing: experimental methods and applications. Nat Rev Genet 16: 344-358</a></li>
</ol>

<h5>ddRADSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ddradseq.png"></p>

<p>Double digest restriction-site associated DNA (ddRADseq), also called ddRAD, is a variation on the RAD sequencing protocol, which is used for SNP discovery and genotyping. , In this variation, the fragment shearing is replaced with a second restriction digestion to improve the tunability and accuracy of the size-selection step. The protocol also includes a second index to allow combinatorial indexing. Several RAD variations 2b-RAD, SLAF-seq, and hyRAD have been developed to address specific applications and there are multiple software packages available to analyze RAD data.</p>
<p>In this method, genomic DNA is first digested with a restriction enzyme and a barcoded P1 adaptor ligated to the fragments. The adaptor-ligated fragments from different samples are combined, if samples are multiplexed, and the DNA digested by a second restriction enzyme. The fragments are size-selected and purified. The P2 primers are then ligated and the fragments amplified.</p>
<h6>Pros:</h6>
<ul>
<li>No reference genome is required<sup>1</sup></li>
<li>Relatively inexpensive, compared to whole-genome sequencing</li>
<li>The degree of genome coverage can be adjusted by selecting various restriction enzymes</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>There can be gaps in the genome coverage</li>
<li>Requires high-quality DNA (See hyRAD for low quality DNA)</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22675423">ddRADSeq: Peterson B. K., Weber J. N., Kay E. H., Fisher H. S. and Hoekstra H. E. (2012) Double digest RADseq: an inexpensive method for de novo SNP discovery and genotyping in model and non-model species. PLoS One 7: e37135</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23473066">1. Reitzel A. M., Herrera S., Layden M. J., Martindale M. Q. and Shank T. M. (2013) Going where traditional markers have not gone before: utility of and promise for RAD sequencing in marine invertebrate phylogeography and population genomics. Mol Ecol 22: 2953-2970</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.sciencedirect.com/science/article/pii/S1055790315002304">DaCosta J. M. and Sorenson M. D. (2016) ddRAD-seq phylogenetics based on nucleotide, indel, and presence-absence polymorphisms: Analyses of two avian genera with contrasting histories. Mol Phylogenet Evol 94: 122-135</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26545807">Lal M. M., Southgate P. C., Jerry D. R. and Zenger K. R. (2015) Fishing for divergence in a sea of connectivity: The utility of ddRADseq genotyping in a marine invertebrate, the black-lip pearl oyster Pinctada margaritifera. Marine Genomics </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27286864">Brown J. K., Taggart J. B., Bekaert M., Wehner S., Palaiokostas C., et al. (2016) Mapping the sex determination locus in the hapuku (Polyprion oxygeneios) using ddRAD sequencing. BMC Genomics 17: 448</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27408618">Clark L. V. and Sacks E. J. (2016) TagDigger: user-friendly extraction of read counts from GBS and RAD-seq data. Source Code Biol Med 11: 11, Hou Y., Nowak M. D., Mirre V., Bjora C. S., Brochmann C., et al. (2015) RAD-seq data point to a northern origin of the arctic-alpine genus Cassiope (Ericaceae). Mol Phylogenet Evol 95: 152-160</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26932983">Shirasawa K., Hirakawa H. and Isobe S. (2016) Analytical workflow of double-digest restriction site-associated DNA sequencing based on empirical and in silico optimization in tomato. DNA Res 23: 145-153</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26730738">Wu Z., Wang B., Chen X., Wu J., King G. J., et al. (2016) Evaluation of Linkage Disequilibrium Pattern and Association Study on Seed Oil Content in Brassica napus Using ddRAD Sequencing. PLoS One 11: e0146383</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27493679">Yang G. Q., Chen Y. M., Wang J. P., Guo C., Zhao L., et al. (2016) Development of a universal and simplified ddRAD library preparation approach for SNP discovery and genotyping in angiosperm plants. Plant Methods 12: 39</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26018616">Cai G., Yang Q., Yi B., Fan C., Zhang C., et al. (2015) A bi-filtering method for processing single nucleotide polymorphism array data improves the quality of genetic map and accuracy of quantitative trait locus mapping in doubled haploid populations of polyploid Brassica napus. BMC Genomics 16: 409</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26398886">Davik J., Sargent D. J., Brurberg M. B., Lien S., Kent M., et al. (2015) A ddRAD Based Linkage Map of the Cultivated Strawberry, Fragaria xananassa. PLoS One 10: e0137746</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26227865">Leache A. D., Banbury B. L., Felsenstein J., de Oca A. N. and Stamatakis A. (2015) Short Tree, Long Tree, Right Tree, Wrong Tree: New Acquisition Bias Corrections for Inferring SNP Phylogenies. Syst Biol 64: 1032-1047</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25663487">Leache A. D., Chavez A. S., Jones L. N., Grummer J. A., Gottscho A. D., et al. (2015) Phylogenomics of phrynosomatid lizards: conflicting signals from sequence capture versus restriction site associated DNA sequencing. Genome Biol Evol 7: 706-719</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26107178">Meik J. M., Streicher J. W., Lawing A. M., Flores-Villela O. and Fujita M. K. (2015) Limitations of Climatic Data for Inferring Species Boundaries: Insights from Speckled Rattlesnakes. PLoS One 10: e0131435</a></li>
</ol>

<h5>Digenome-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/digenome-seq.png"></p>

<p>In vitro Cas9-digested whole-genome sequencing to profile genome-wide Cas9 off-target effects (Digenome-seq). A multiplexed version has also been published. It belongs to a family of methods such as HTGTS, LAM-HTGTS, and Guide-seq that are aimed at detecting off-target effects of CRISPR/Cas9 and other RNA-guided engineered nucleases (RGENs).</p>
<p>This method detects off-target mutations induced by RGENs in a bulk population of cells by sequencing in vitro nuclease-digested genomes (digenomes). These digests should produce many DNA fragments with identical 5′ ends, which give rise to sequence reads that are vertically aligned at cleavage sites.</p>
<h6>Pros:</h6>
<ul>
<li>Relies on DNA cleavage rather than binding</li>
<li>Performed in a genomic context and sites with a DNA/RNA bulge are captured</li>
<li>Off-targets can be detected with a frequency of 0.1% or lower<sup>1</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires in vivo cleavage confirmation</li>
<li>High skill requirement for bioinformatic analysis<sup>2</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25664545">Digenome-Seq: Kim D., Bae S., Park J., Kim E., Kim S., et al. (2015) Digenome-seq: genome-wide profiling of CRISPR-Cas9 off-target effects in human cells. Nat Methods 12: 237-243, 231 p following 243</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26924689">1. Mei Y., Wang Y., Chen H., Sun Z. S. and Ju X. D. (2016) Recent Progress in CRISPR/Cas9 Technology. J Genet Genomics 43: 63-75</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27031497">2. Hu J., Meyers R. M., Dong J., Panchakshari R. A., Alt F. W., et al. (2016) Detecting DNA double-stranded breaks in mammalian genomes by linear amplification-mediated high-throughput genome-wide translocation sequencing. Nat Protoc 11: 853-871</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27272384">Kim D., Kim J., Hur J. K., Been K. W., Yoon S. H., et al. (2016) Genome-wide analysis reveals specificities of Cpf1 endonucleases in human cells. Nat Biotechnol </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26750397">Lee C. M., Cradick T. J., Fine E. J. and Bao G. (2016) Nuclease Target Site Selection for Maximizing On-target Activity and Minimizing Off-target Effects in Genome Editing. Mol Ther 24: 475-487</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26924689">Mei Y., Wang Y., Chen H., Sun Z. S. and Ju X. D. (2016) Recent Progress in CRISPR/Cas9 Technology. J Genet Genomics 43: 63-75</a></li>
</ol>

<h5>EC-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ec-seq.png"></p>

<p>Excision circle sequencing (EC-seq) allows the capture and analysis of immune locus rearrangements from whole thymic and splenic tissues.</p>
<p>RAG-mediated double-stranded cleavage at RSS sites precedes genomic deletion end processing by the nonhomologous end joining (NHEJ) complex. Coding ends are covalently hair-pinned and reopened prior to ligation. The excision circle junction is then ligated from unprocessed DNA ends with little modification.</p>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25367293">EC-Seq: Parkinson N. J., Roddis M., Ferneyhough B., Zhang G., Marsden A. J., et al. (2015) Violation of the 12/23 rule of genomic V(D)J recombination is common in lymphocytes. Genome Res 25: 226-234</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25367293">Parkinson N. J., Roddis M., Ferneyhough B., Zhang G., Marsden A. J., et al. (2015) Violation of the 12/23 rule of genomic V(D)J recombination is common in lymphocytes. Genome Res 25: 226-234</a></li>
</ol>

<h5>Ig-Seq/Rep-Seq/MAF</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ig-seq-rep-seq-maf.png"></p>

<p>Rep-Seq is a collective term for repertoire sequencing technologies. DNA sequencing of immunoglobulin genes (Ig-seq) and molecular amplification fingerprinting (MAF)</p>
<p>In Ig-seq, is a targeted gDNA amplification method performed with primers complementary to the rearranged V-region gene (VDJ recombinant). Amplification of cDNA is then performed with the appropriate 5’ primers. Although throughput is high, in bulk analysis information regarding which VH and VL chains were paired in the same cell is lost, as cells are lysed in bulk and VH and VL genes are amplified in separate reactions. MAF (illustrated below) was developed to correct the amplification biases in Ig-seq, by using UIG tagging before and during the multiplex PCR amplification as well as a bioinformatics pipeline.</p>
<h6>Pros:</h6>
<ul>
<li>Measure antibody frequencies with up to 99% accuracy</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>The data analysis is challenging<sup>1</sup></li>
<li>In bulk analysis the information regarding which VH and VL chains were paired in the same cell is lost</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23898164">Ig-Seq: Vollmers C., Sit R. V., Weinstein J. A., Dekker C. L. and Quake S. R. (2013) Genetic measurement of memory B-cell recall using antibody repertoire sequencing. Proc Natl Acad Sci U S A 110: 13463-13468</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22043864">Rep-Seq: Benichou J., Ben-Hamo R., Louzoun Y. and Efroni S. (2012) Rep-Seq: uncovering the immunological repertoire through next-generation sequencing. Immunology 135: 183-191</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26998518">MAF: Khan T. A., Friedensohn S., Gorter de Vries A. R., Straszewski J., Ruscheweyh H. J., et al. (2016) Accurate and predictive antibody repertoire profiling by molecular amplification fingerprinting. Sci Adv 2: e1501371</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24441474">1. Georgiou G., Ippolito G. C., Beausang J., Busse C. E., Wardemann H., et al. (2014) The promise and challenge of high-throughput sequencing of the antibody repertoire. Nat Biotechnol 32: 158-168</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/nextera-mate-pair.html">Nextera Mate Pair Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26998518">Khan T. A., Friedensohn S., Gorter de Vries A. R., Straszewski J., Ruscheweyh H. J., et al. (2016) Accurate and predictive antibody repertoire profiling by molecular amplification fingerprinting. Sci Adv 2: e1501371</a></li>
</ol>

<h5>IN-Seq/Tn-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/in-seq-tn-seq.png"></p>

<p>Transposon sequencing (Tn-Seq) or insertion sequencing (INSeq) accurately determines quantitative genetic interactions . In this method, a transposon with flanking Mmel digestion sites is transposed into bacteria which, after culturing, can help detect the frequency of mutations within the transposon. After MmeI digestion and subsequent adapter ligation, PCR amplification and sequencing can provide information about the transposon insertion sites.</p>
<h6>Pros:</h6>
<ul>
<li>Can study mutational frequency of transposons</li>
<li>Method can be used to deduce fitness of genes within microorganisms</li>
<li>Protocol is robust, reproducible, and sensitive</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to bacterial studies</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19748469">INSeq: Goodman A. L., McNulty N. P., Zhao Y., et al. Identifying genetic determinants needed to establish a human gut symbiont in its habitat. Cell Host Microbe. 2009;6:279-289</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19767758">Tn-Seq: van Opijnen T., Bodi K. L. and Camilli A. (2009) Tn-seq: high-throughput parallel sequencing for fitness and genetic interaction studies in microorganisms. Nat Methods 6: 767-772</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25996237" target="_blank">Le Breton Y., Belew A. T., Valdes K. M., Islam E., Curry P., et al. (2015) Essential Genes in the Core Genome of the Human Pathogen Streptococcus pyogenes. Sci Rep 5: 9838</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25848053" target="_blank">Lee S. A., Gallagher L. A., Thongdee M., Staudinger B. J., Lippman S., et al. (2015) General and condition-specific essential functions of Pseudomonas aeruginosa. Proc Natl Acad Sci U S A 112: 5189-5194</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25918422" target="_blank">Meeske A. J., Sham L. T., Kimsey H., Koo B. M., Gross C. A., et al. (2015) MurJ and a novel lipid II flippase are required for cell wall biogenesis in Bacillus subtilis. Proc Natl Acad Sci U S A 112: 6437-6442</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25775563" target="_blank">Turner K. H., Wessel A. K., Palmer G. C., Murray J. L. and Whiteley M. (2015) Essential genome of Pseudomonas aeruginosa in cystic fibrosis sputum. Proc Natl Acad Sci U S A 112: 4110-4115</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24832453" target="_blank">Carter R., Wolf J., van Opijnen T., Muller M., Obert C., et al. (2014) Genomic analyses of pneumococci from children with sickle cell disease expose host-specific bacterial adaptations and deficits in current interventions. Cell Host Microbe 15: 587-599</a></li>
</ol>

<h5>RAD/Paired-end RAD-Seq/ddRAD-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rad-paired-end-rad-seq-ddrad-seq.png"></p>

<p>Restriction-site associated DNA (RAD/Paired-end RAD-Seq or ddRADseq) sequencing is a protocol used for SNP discovery and genotyping. In this method, genomic DNA is first digested with restriction enzymes, next barcoded adapters are added, DNA sheared, amplified and sequenced. Deep sequencing allows accurate SNP discovery and genotyping.</p>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/18852878">RAD-Seq:Baird N. A., Etter P. D., Atwood T. S., Currey M. C., Shiver A. L., et al. (2008) Rapid SNP discovery and genetic mapping using sequenced RAD markers. PLoS One 3: e3376</a></li>
<a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/18852878"> </a><li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/18852878"></a><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21712251">Paired end RAD-Seq: Willing E. M., Hoffmann M., Klein J. D., Weigel D. and Dreyer C. (2011) Paired-end RAD-seq for de novo assembly and marker design without available reference. Bioinformatics 27: 2187-2193</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25848968" target="_blank">Combosch D. J. and Vollmer S. V. (2015) Trans-Pacific RAD-Seq population genomics confirms introgressive hybridization in Eastern Pacific Pocillopora corals. Mol Phylogenet Evol 88: 154-162</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26279345" target="_blank">DaCosta J. M. and Sorenson M. D. (2015) ddRAD-seq phylogenetics based on nucleotide, indel, and presence-absence polymorphisms: Analyses of two avian genera with contrasting histories. Mol Phylogenet Evol 94: 122-135</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26394036" target="_blank">Demos T. C., Kerbis Peterhans J. C., Joseph T. A., Robinson J. D., Agwanda B., et al. (2015) Comparative Population Genomics of African Montane Forest Mammals Support Population Persistence across a Climatic Gradient and Quaternary Climatic Cycles. PLoS One 10: e0131800</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25857931" target="_blank">Guo B., DeFaveri J., Sotelo G., Nair A. and Merila J. (2015) Population genomic evidence for adaptive differentiation in Baltic Sea three-spined sticklebacks. BMC Biol 13: 19</a></li>
<li><a href="http://onlinelibrary.wiley.com/doi/10.1111/gcbb.12275/abstract" target="_blank">Liu S., Clark L. V., Swaminathan K., Gifford J. M., Juvik J. A., et al. (2015) High-density genetic map of Miscanthus sinensis reveals inheritance of zebra stripe. GCB Bioenergy n/a-n/a</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25858559" target="_blank">Longo G. and Bernardi G. (2015) The evolutionary history of the embiotocid surfperch radiation based on genome-wide RAD sequence data. Mol Phylogenet Evol 88: 55-63</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25757406" target="_blank">Mathers T. C., Hammond R. L., Jenner R. A., Hanfling B., Atkins J., et al. (2015) Transition in sexual system and sex chromosome evolution in the tadpole shrimp Triops cancriformis. Heredity (Edinb) 115: 37-46</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26398819" target="_blank">Marubodee R., Ogiso-Tanaka E., Isemura T., Chankaew S., Kaga A., et al. (2015) Construction of an SSR and RAD-Marker Based Molecular Linkage Map of Vigna vexillata (L.) A. Rich. PLoS One 10: e0138942</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25762582" target="_blank">Shao C., Niu Y., Rastas P., Liu Y., Xie Z., et al. (2015) Genome-wide SNP identification for the construction of a high-resolution genetic map of Japanese flounder (Paralichthys olivaceus): applications to QTL mapping of Vibrio anguillarum disease resistance and comparative genomic analysis. DNA Res 22: 161-170</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26291568" target="_blank">Takahashi T. and Moreno E. (2015) A RAD-based phylogenetics for Orestias fishes from Lake Titicaca. Mol Phylogenet Evol 93: 307-317</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26372103" target="_blank">Tennessen J. A., Bonner K. M., Bollmann S. R., Johnstun J. A., Yeh J. Y., et al. (2015) Genome-Wide Scan and Test of Candidate Genes in the Snail Biomphalaria glabrata Reveal New Locus Influencing Resistance to Schistosoma mansoni. PLoS Negl Trop Dis 9: e0004077</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26181055" target="_blank">Yu S., Chu W., Zhang L., Han H., Zhao R., et al. (2015) Identification of Laying-Related SNP Markers in Geese Using RAD Sequencing. PLoS One 10: e0131572</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26398139" target="_blank">Zhou Z., Liu S., Dong Y., Gao S., Chen Z., et al. (2015) High-Density Genetic Mapping with Interspecific Hybrids of Two Sea Urchins, Strongylocentrotus nudus and S. intermedius, by RAD Sequencing. PLoS One 10: e0138585</a></li>
</ol>

<h5>RC-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rc-seq.png"></p>

<p>Retrotransposon capture sequencing (RC-Seq) is a high-throughput protocol to map and study retrotransposon insertions . In this method, after genomic DNA is fractionated, retrotransposon binding sites on DNA hybridize to transposon binding sites on a microarray. Deep sequencing provides accurate information that can be aligned to a reference sequence to discover novel retrotransposition events.</p>
<h6>Pros:</h6>
<ul>
<li>Ability to clearly identify and detect novel retrotransposition events</li>
<li>Can specifically study transposon binding sites of interest</li>
<li>High-throughput protocol</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Different types of MEI require separate PCR experiments with different primers</li>
<li>Hybridization errors can lead to sequencing unwanted DNA fragments</li>
<li>PCR biases can underrepresent GC-rich templates</li>
<li>Similar transposition binding sites can lead</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22037309" target="_blank">RC-Seq: Baillie J. K., Barnett M. W., Upton K. R., Gerhardt D. J., Richmond T. A., et al. (2011) Somatic retrotransposition alters the genetic landscape of the human brain. Nature 479: 534-537</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25860606" target="_blank">Upton K. R., Gerhardt D. J., Jesuadian J. S., Richardson S. R., Sanchez-Luque F. J., et al. (2015) Ubiquitous L1 mosaicism in hippocampal neurons. Cell 161: 228-239</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/23540693" target="_blank">Shukla R., Upton K. R., Munoz-Lopez M., Gerhardt D. J., Fisher M. E., et al. (2013) Endogenous retrotransposition activates oncogenic pathways in hepatocellular carcinoma. Cell 153: 101-111</a></li>
</ol>

<h5>Repli-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/repli-seq.png"></p>

<p>Repli-Seq maps the sequences of nascent DNA replication strands throughout the whole genome during each of the six cell cycle phases. This is achieved by growing cells in bromouridine triphosphate (BrdU) media to replace thymidine. The cells are then sorted to their current state in cell division using Fluorescent-activated cell sorting (FACS). BrdU-labelled DNA strands are immunoprecipitated by anti-BrdU antibodies on magnetic beads. These immunoprecipitated strands can be prepared for sequencing following TruSeq DNA library preparation protocol.</p>
<h6>Pros:</h6>
<ul>
<li>Maps sequences of newly replicated DNA to the phases of cell division</li>
<li>Low sample input required (5000 cells) makes it suitable for studying rare cell populations</li>
<li>Streamlined DNA library prep step</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>The BrdU labeling requirement limits this approach to cultured cells</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/19966280" target="_blank">Repli-Seq: Hansen R. S., Thomas S., Sandstrom R., Canfield T. K., Thurman R. E., et al. (2010) Sequencing newly replicated DNA reveals widespread plasticity in human replication timing. Proc Natl Acad Sci U S A 107: 139-144</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25282150" target="_blank">Deyle D. R., Hansen R. S., Cornea A. M., Li L. B., Burt A. A., et al. (2014) A genome-wide map of adeno-associated virus-mediated human gene targeting. Nat Struct Mol Biol 21: 969-975</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23352430" target="_blank">Barlow J. H., Faryabi R. B., Callen E., Wong N., Malhowski A., et al. (2013) Identification of early replicating fragile sites that contribute to genome instability. Cell 152: 620-632</a></li>
</ol>

<h5>TC-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tc-seq.png"></p>

<p>Translocation-capture sequencing (TC-Seq) is a method developed to study chromosomal rearrangements and translocations . In this method, cells are infected with retrovirus expressing l-Scel sites in cells with and without activation-induced cytidine deaminase (AICDA or AID) protein. Genomic DNA from cells is sonicated, linker-ligated, purified, and amplified via semi-nested LM-PCR. The linker is then cleaved and the DNA is sequenced. Any AID-dependent chromosomal rearrangement will be amplified by LM-PCR, while AID-independent translocations will be discarded.</p>
<h6>Pros:</h6>
<ul>
<li>Can study chromosomal translocations within a given model or environment</li>
<li>Random sonication generates unique linker ligation points, and deep sequencing allows reading through rearrangement breakpoints</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>PCR amplification errors</li>
<li>Non-linear PCR amplification can lead to biases affecting reproducibility</li>
<li>PCR biases can underrepresent GC-rich templates</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21962510" target="_blank">TC-Seq: Klein I. A., Resch W., Jankovic M., Oliveira T., Yamane A., et al. (2011) Translocation-capture sequencing reveals the extent and nature of chromosomal rearrangements in B lymphocytes. Cell 147: 95-106</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html" target="_blank">TruSeq Stranded RNA Prep kit</a></li>
<li><a adhocenable="false" href="https://support.illumina.com/sequencing/sequencing_kits/pe_dna_sample_prep_kit.html" target="_blank">Paired-End Sample Preparation kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25119026" target="_blank">Pefanis E., Wang J., Rothschild G., Lim J., Chao J., et al. (2014) Noncoding RNA transcription targets AID to divergently transcribed loci in B cells. Nature 514: 389-393</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/23290917" target="_blank">Jankovic M., Feldhahn N., Oliveira T. Y., Silva I. T., Kieffer-Kwon K. R., et al. (2013) 53BP1 alters the landscape of DNA rearrangements and suppresses AID-induced B cell lymphoma. Mol Cell 49: 623-631</a></li>
</ol>

### Epigenetics

#### DNA-protein interaction

<h5>4-C/4C-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/4-c-4c-seq.png"></p>

<p>4C, also called 4C-seq, is a method similar to 3C and is sometimes called circular 3C. It allows the unbiased detection of all genomic regions that interact with a particular region of interest.  
In this method, DNA-protein complexes are crosslinked using formaldehyde. The sample is fragmented, and the DNA is ligated and digested. The resulting DNA fragments self-circularize, followed by reverse PCR and sequencing. Deep sequencing provides base-pair resolution of the ligated fragments.
</p>
<h6>Pros:</h6>
<ul>
<li>Preferred strategy to assess the DNA contact profile of individual genomic sites</li>
<li>Highly reproducible data</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Will miss local interactions (&lt; 50 kb) from the region of interest</li>
<li>The large circles do not amplify efficiently</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/17033624">4C-Seq: Zhao Z., Tavoosidana G., Sjolinder M., Gondor A., Mariano P., et al. (2006) Circular chromosome conformation capture (4C) uncovers extensive networks of epigenetically regulated intra- and interchromosomal interactions. Nat Genet 38: 1341-1347</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22703176" target="_blank">4C-Seq: Sajan S. A. and Hawkins R. D. Methods for identifying higher-order chromatin structure. Annu Rev Genomics Hum Genet. 2012;13:59-82</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26934861" target="_blank">Cai M., Kim S., Wang K., Farnham P. J., Coetzee G. A. and Lu W. 4C-seq revealed long-range interactions of a functional enhancer at the 8q24 prostate cancer risk locus. Sci Rep. 2016;6:22462</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27240531" target="_blank">Loviglio M. N., Leleu M., Mannik K., et al. Chromosomal contacts connect loci associated with autism, BMI and head circumference phenotypes. Mol Psychiatry. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26673704" target="_blank">Yang R., Kerschner J. L., Gosalia N., Neems D., Gorsic L. K., et al. Differential contribution of cis-regulatory elements to higher order chromatin structure and expression of the CFTR locus. Nucleic Acids Res. 2016;44:3082-3094</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26829752" target="_blank">Acemel R. D., Tena J. J., Irastorza-Azcarate I., Marletaz F., Gomez-Marin C., et al. A single three-dimensional chromatin compartment in amphioxus indicates a stepwise evolution of vertebrate Hox bimodal regulation. Nat Genet. 2016;48:336-341</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27466807" target="_blank">De S., Mitra A., Cheng Y., Pfeifer K. and Kassis J. A. Formation of a Polycomb-Domain in the Absence of Strong Polycomb Response Elements. PLoS Genet. 2016;12:e1006200</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27276213" target="_blank">Eckart N., Song Q., Yang R., et al. Functional Characterization of Schizophrenia-Associated Variation in CACNA1C. PLoS One. 2016;11:e0157086</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27381023" target="_blank">Kaaij L. J., Mokry M., Zhou M., Musheev M., Geeven G., et al. Enhancers reside in a unique epigenetic environment during early zebrafish development. Genome Biol. 2016;17:146</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27524613" target="_blank">Kandaswamy R., Sava G. P., Speedy H. E., et al. Genetic Predisposition to Chronic Lymphocytic Leukemia Is Mediated by a BMF Super-Enhancer Polymorphism. Cell Rep. 2016;16:2061-2067</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26814967" target="_blank">Lin C. Y., Erkek S., Tong Y., et al. Active medulloblastoma enhancers reveal subgroup-specific cellular origins. Nature. 2016;530:57-62</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27239026" target="_blank">Proudhon C., Snetkova V., Raviram R., Lobry C., Badri S., et al. Active and Inactive Enhancers Cooperate to Exert Localized and Long-Range Control of Gene Regulation. Cell Rep. 2016;15:2159-2169</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27320916" target="_blank">Rocha P. P., Raviram R., Fu Y., Kim J., Luo V. M., et al. A Damage-Independent Role for 53BP1 that Impacts Break Order and Igh Architecture during Class Switch Recombination. Cell Rep. 2016;16:48-55</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26807951" target="_blank">Vermunt M. W., Tan S. C., Castelijns B., et al. Epigenomic annotation of gene regulatory alterations during evolution of the primate brain. Nat Neurosci. 2016;19:494-503</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26997247" target="_blank">Wang Q., Sawyer I. A., Sung M. H., et al. Cajal bodies are linked to genome conformation. Nat Commun. 2016;7:10966</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26759081" target="_blank">Wani A. H., Boettiger A. N., Schorderet P., et al. Chromatin topology is coupled to Polycomb group protein subnuclear organization. Nat Commun. 2016;7:10291</a></li>
</ol>

<h5>5-C</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/5-c.png"></p>

<p>5C allows concurrent determination of interactions among multiple sequences and is a high-throughput version of 3C. 
In this method, DNA-protein complexes are crosslinked using formaldehyde. The sample is fragmented and the DNA ligated and digested with restriction enzymes. The resulting DNA fragments are amplified using ligation-mediated PCR and sequenced. Deep sequencing provides base-pair resolution of the ligated fragments.</p>
<h6>Pros:</h6>
<ul>
<li>Different from 4C, 5C provides a matrix of interaction frequencies for many pairs of sites<sup>1</sup> </li>
<li>Can be used to reconstruct the (average) 3D conformation of larger genomic regions</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Requires a priori information of the regulatory sites<sup>2</sup></li>
<li>	Detection may not necessarily mean an interaction, resulting from random chromosomal collisions</li>
<li>	Cannot scale to genome-wide studies that would require a large amount of primers</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/17446898">5C-Seq: Dostie J. and Dekker J. (2007) Mapping networks of physical interactions between genomic elements using 5C technology. Nat Protoc 2: 988-1002</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22215806" target="_blank">1. de Wit E. and de Laat W. A decade of 3C technologies: insights into nuclear organization. Genes Dev. 2012;26:11-24</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27130552" target="_blank">2. Sati S. and Cavalli G. Chromosome conformation capture technologies and their impact in understanding genome function. Chromosoma. 2016;
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27130552" target="_blank">Sati S. and Cavalli G. Chromosome conformation capture technologies and their impact in understanding genome function. Chromosoma. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000844" target="_blank">Reuter J. A., Spacek D. V. and Snyder M. P. High-throughput sequencing technologies. Mol Cell. 2015;58:586-597</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26748519" target="_blank">Smith E. M., Lajoie B. R., Jain G. and Dekker J. Invariant TAD Boundaries Constrain Cell-Type-Specific Looping Interactions between Promoters and Distal Elements around the CFTR Locus. Am J Hum Genet. 2016;98:185-201</a></li>
</ol>

<h5>ATAC-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/atac-seq.png"></p>

<p>ATAC-Seq uses the Tn5 transposome to detect nucleosome-free regions of the genome. The method is commonly used, and optimized protocols are available for tissues, such as blood (Fast-ATAC)<sup>1</sup>, neurons<sup>2</sup>, biobank specimens<sup>3</sup>, and single cells (scATAC-seq<sup>4</sup>  and single-cell ATAC-seq<sup>5</sup>). </p><p>In this method, gDNA is incubated with Tn5 transposomes, which fragments it and adds adapters simultaneously, in open chromatin regions. Deep sequencing of the purified regions provides base-pair resolution of nucleosome-free regions in the genome.</p>
<h6>Pros:</h6>
<ul>
<li>	Two-step protocol with no adapter ligation steps, gel purification, or crosslink reversal</li>
<li>	High signal-to-noise ratio compared to FAIRE-Seq</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	During mechanical sample processing, bound chromatin regions might open and be tagged by the transposome</li>
<li>	Only half of the molecules contain the adapters in the orientation required for PCR amplification</li>
<li>	Distance between adapter sites may not be optimal for PCR amplification<sup>6</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24097267">ATAC-Seq: Buenrostro J. D., Giresi P. G., Zaba L. C., Chang H. Y. and Greenleaf W. J. (2013) Transposition of native chromatin for fast and sensitive epigenomic profiling of open chromatin, DNA-binding proteins and nucleosome position. Nat Methods 10: 1213-1218</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27526324" target="_blank">1. Corces M. R., Buenrostro J. D., Wu B., et al. Lineage-specific and single-cell chromatin accessibility charts human hematopoiesis and leukemia evolution. Nat Genet. 2016;48:1193-1203</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27146274" target="_blank">2. Milani P., Escalante-Chong R., Shelley B. C., et al. Cell freezing protocol suitable for ATAC-Seq on motor neurons derived from human induced pluripotent stem cells. Sci Rep. 2016;6:25474</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27249108" target="_blank">3. Scharer C. D., Blalock E. L., Barwick B. G., et al. ATAC-seq on biobanked specimens defines a unique chromatin accessibility structure in naive SLE B cells. Sci Rep. 2016;6:27030</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26083756" target="_blank">4. Buenrostro J. D., Wu B., Litzenburger U. M., et al. Single-cell chromatin accessibility reveals principles of regulatory variation. Nature. 2015;523:486-490</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25953818" target="_blank">5. Cusanovich D. A., Daza R., Adey A., et al. Multiplex single cell profiling of chromatin accessibility by combinatorial cellular indexing. Science. 2015;348:910-914</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26846207" target="_blank">6. Sos B. C., Fung H. L., Gao D. R., et al. Characterization of chromatin accessibility with a transposome hypersensitive sites sequencing (THS-seq) assay. Genome Biol. 2016;17:20</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27297499" target="_blank">Chaitankar V., Karakulah G., Ratnapriya R., Giuste F. O., Brooks M. J., et al. Next generation sequencing technology and genomewide data analysis: Perspectives for retinal research. Prog Retin Eye Res. 2016;55:1-31</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26721890" target="_blank">Yan H., Tian S., Slager S. L., Sun Z. and Ordog T. Genome-Wide Epigenetic Studies in Human Disease: A Primer on -Omic Technologies. Am J Epidemiol. 2016;183:96-109</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26928226" target="_blank">Bogdanovic O., Smits A. H., de la Calle Mustienes E., Tena J. J., Ford E., et al. Active DNA demethylation at enhancers during the vertebrate phylotypic period. Nat Genet. 2016;48:417-426</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27526324" target="_blank">Corces M. R., Buenrostro J. D., Wu B., Greenside P. G., Chan S. M., et al. Lineage-specific and single-cell chromatin accessibility charts human hematopoiesis and leukemia evolution. Nat Genet. 2016;48:1193-1203</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27386823" target="_blank">Miller C. L., Pjanic M., Wang T., et al. Integrative functional genomics identifies regulatory mechanisms at coronary artery disease loci. Nat Commun. 2016;7:12092</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27309802" target="_blank">Wu J., Huang B., Chen H., et al. The landscape of accessible chromatin in mammalian preimplantation embryos. Nature. 2016;534:652-657</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26977395" target="_blank">Ackermann A. M., Wang Z., Schug J., Naji A. and Kaestner K. H. Integration of ATAC-seq and RNA-seq identifies human alpha cell and beta cell signature genes. Mol Metab. 2016;5:233-244</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27315481" target="_blank">Atianand M. K., Hu W., Satpathy A. T., et al. A Long Noncoding RNA lincRNA-EPS Acts as a Transcriptional Brake to Restrain Inflammation. Cell. 2016;165:1672-1685</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27498878" target="_blank">Boukhaled G. M., Cordeiro B., Deblois G., et al. The Transcriptional Repressor Polycomb Group Factor 6, PCGF6, Negatively Regulates Dendritic Cell Activation and Promotes Quiescence. Cell Rep. 2016;16:1829-1837</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26814966" target="_blank">de Dieuleveult M., Yen K., Hmitou I., Depaux A., Boussouar F., et al. Genome-wide nucleosome specificity and function of chromatin remodellers in ES cells. Nature. 2016;530:113-116</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26878240" target="_blank">Flynn R. A., Do B. T., Rubin A. J., et al. 7SK-BAF axis controls pervasive transcription at enhancers. Nat Struct Mol Biol. 2016;23:231-238</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27397025" target="_blank">George J., Uyar A., Young K., et al. Leukaemia cell of origin identified by chromatin landscape of bulk tumour cells. Nat Commun. 2016;7:12166</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27477909" target="_blank">Han D., Lu X., Shih A. H., et al. A Highly Sensitive and Robust Method for Genome-wide 5hmC Profiling of Rare Cell Populations. Mol Cell. 2016;63:711-719</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27376235" target="_blank">Hay D., Hughes J. R., Babbs C., Davies J. O., Graham B. J., et al. Genetic dissection of the alpha-globin super-enhancer <i>in vivo</i>. Nat Genet. 2016;48:895-903</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27381023" target="_blank">Kaaij L. J., Mokry M., Zhou M., Musheev M., Geeven G., et al. Enhancers reside in a unique epigenetic environment during early zebrafish development. Genome Biol. 2016;17:146</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26823433" target="_blank">Kaufman C. K., Mosimann C., Fan Z. P., et al. A zebrafish melanoma model reveals emergence of neural crest identity during melanoma initiation. Science. 2016;351:aad2197</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27156452" target="_blank">Koues O. I., Collins P. L., Cella M., et al. Distinct Gene Regulatory Pathways for Human Innate versus Adaptive Lymphoid Cells. Cell. 2016;165:1134-1146</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27259149" target="_blank">Lu F., Liu Y., Inoue A., Suzuki T., Zhao K., et al. Establishing Chromatin Regulatory Landscape during Mouse Preimplantation Development. Cell. 2016;165:1375-1388</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27239026" target="_blank">Proudhon C., Snetkova V., Raviram R., et al. Active and Inactive Enhancers Cooperate to Exert Localized and Long-Range Control of Gene Regulation. Cell Rep. 2016;15:2159-2169</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27346425" target="_blank">Rendeiro A. F., Schmidl C., Strefford J. C., et al. Chromatin accessibility maps of chronic lymphocytic leukaemia identify subtype-specific epigenome signatures and transcription regulatory networks. Nat Commun. 2016;7:11938</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27114036" target="_blank">Sebe-Pedros A., Ballare C., Parra-Acero H., et al. The Dynamic Regulatory Genome of Capsaspora and the Origin of Animal Multicellularity. Cell. 2016;165:1224-1237</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27156451" target="_blank">Shih H. Y., Sciume G., Mikami Y., et al. Developmental Acquisition of Regulomes Underlies Innate Lymphoid Cell Functionality. Cell. 2016;165:1120-1133</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26956608" target="_blank">Smith J. D., Suresh S., Schlecht U., et al. Quantitative CRISPR interference screens in yeast identify chemical-genetic interactions and new rules for guide RNA design. Genome Biol. 2016;17:45</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26912704" target="_blank">Wang L., Siegenthaler J. A., Dowell R. D. and Yi R. Foxc1 reinforces quiescence in self-renewing hair follicle stem cells. Science. 2016;351:613-617</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27507714" target="_blank">Wang W., Org T., Montel-Hagen A., et al. MEF2C protects bone marrow B-lymphoid progenitors during stress haematopoiesis. Nat Commun. 2016;7:12376</a></li>
</ol>

<h5>CATCH-IT</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/catch-it.png"></p>

<p>CATCH-IT is a direct method for measuring nucleosome turnover dynamics genome-wide. 
In this method, cells are treated briefly with the methionine surrogate azidohomoalanine (Aha), which couples biotin to nucleosomes containing newly incorporated histones. The labeled chromatin is affinity-purified with streptavidin, washed stringently to remove nonhistone proteins, and analyzed using tiling microarrays.</p>
<h6>Pros:</h6>
<ul>
<li>Can determine differences in nucleosome turnover across the genome</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Potential artifacts</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/20508129" target="_blank">CATCH-IT: Deal R. B., Henikoff J. G. and Henikoff S. Genome-wide kinetics of nucleosome turnover determined by metabolic labeling of histones. Science. 2010;328:1161-1164</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25297728" target="_blank">Zentner G. E. and Henikoff S. High-resolution digital profiling of the epigenome. Nat Rev Genet. 2014;15:814-827</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26280901" target="_blank">Perez-Lluch S., Blanco E., Tilgner H., et al. Absence of canonical marks of active chromatin in developmentally regulated genes. Nat Genet. 2015;47:1158-1167</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24737864" target="_blank">Skene P. J., Hernandez A. E., Groudine M. and Henikoff S. The nucleosomal barrier to promoter escape by RNA polymerase II is overcome by the chromatin remodeler Chd1. Elife. 2014;3:e02042</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24606920" target="_blank">Weber C. M., Ramachandran S. and Henikoff S. Nucleosomes are context-specific, H2A.Z-modulated barriers to RNA polymerase. Mol Cell. 2014;53:819-830</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24317489" target="_blank">Teves S. S. and Henikoff S. Transcription-generated torsional stress destabilizes nucleosomes. Nat Struct Mol Biol. 2014;21:88-94</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25102063" target="_blank">Yildirim O., Hung J. H., Cedeno R. J., Weng Z., Lengner C. J. and Rando O. J. A system for genome-wide histone variant dynamics in ES cells reveals dynamic MacroH2A2 replacement at promoters. PLoS Genet. 2014;10:e1004515</a></li>
</ol>

<h5>Chem-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/chem-seq.png"></p>

<p>Chem-seq can be used to detect the binding of small-molecule ligands, such as therapeutic drugs, to proteins associated with the genome. This information may provide important insights into the perturbation of cellular function by small-molecule drugs.  
The Chem-seq method uses 2 approaches. In living cells, the biotinylated drug is added to allow drug-target binding. The complex is crosslinked with formaldehyde, the cells are lysed and sonicated, and the complex is captured on streptavidin beads. The enriched DNA fragments are purified and sequenced. For in vitro analysis, the biotinylated drug is added to a cell extract, and the remaining steps are performed as for the in vivo procedure.</p>
<h6>Pros:</h6>
<ul>
<li>Can be applied to living, human cells</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Creating biotin derivative may alter drug activity</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24336317" target="_blank">Anders L., Guenther M. G., Qi J., et al. Genome-wide localization of small molecules. Nat Biotechnol. 2014;32:92-96</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24336317" target="_blank">Anders L., Guenther M. G., Qi J., et al. Genome-wide localization of small molecules. Nat Biotechnol. 2014;32:92-96</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24928520" target="_blank">Jin C., Yang L., Xie M., et al. Chem-seq permits identification of genomic targets of drugs against androgen receptor regulation selected by functional phenotypic screens. Proc Natl Acad Sci U S A. 2014;111:9235-9240</a></li>
</ol>

<h5>ChIA-PET</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/chia-pet.png"></p>

<p>ChIA-PET features an immunoprecipitation step to map long-range DNA interactions, similar to Hi-C<sup>1</sup>. In this method, DNA-protein complexes are crosslinked and fragmented. Specific antibodies are used to immunoprecipitate proteins of interest. Two sets of linkers, with unique barcodes, are ligated to the ends of the DNA fragments in separate aliquots, which then self-ligate based on proximity. The DNA aliquots are precipitated, digested with restriction enzymes, and sequenced. Deep sequencing provides base-pair resolution of the ligated fragments. Hi-C and ChIA-PET currently provide the best balance of resolution and reasonable coverage in the human genome to map long-range interactions<sup>2</sup>. 
</p><p>
A modified protocol, called advanced or long-read ChIA-PET, has been published by Tang et al<sup>3</sup>.  This method replaces the 2 separate ligation reactions with 2 half linkers and a single biotinylated linker ligation. Next, the de-crosslinked, purified DNA is fragmented and adapters are ligated using Tn5 transposase in a single step. Finally, the DNA is PCR-amplified and sequenced<sup>4</sup>.</p>
<h6>Pros:</h6>
<ul>
<li>	Suitable for detecting a large number of both long-range and short-range chromatin interactions globally<sup>5</sup> </li>
<li>	Studies the interactions made by specific proteins or protein complexes</li>
<li>	Public ChIA-PET datasets are available through the ENCODE Project<sup>6</sup> </li>
<li>	Removes background generated during traditional ChIP assays</li>
<li>	Immunoprecipitation step reduces data complexity</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Requires a large amount of starting material required, generally at least 100 million cells <sup>7</sup></li>
<li>	Nonspecific antibodies can pull down unwanted protein complexes and contaminate the pool</li>
<li>	Linkers can self-ligate, generating ambiguity about true DNA interactions</li>
<li>	Limited sensitivity; may detect as little as 10% of interactions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20181287">ChIA-PET: Li G., Fullwood M. J., Xu H., Mulawadi F. H., Velkov S., et al. (2010) ChIA-PET tool for comprehensive chromatin interaction analysis with paired-end tag sequencing. Genome Biol 11: R22</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/19890323" target="_blank">1. Fullwood M. J., Liu M. H., Pan Y. F., et al. An oestrogen-receptor-alpha-bound human chromatin interactome. Nature. 2009;462:58-64</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23657480" target="_blank">2. Dekker J., Marti-Renom M. A. and Mirny L. A. Exploring the three-dimensional organization of genomes: interpreting chromatin interaction data. Nat Rev Genet. 2013;14:390-403</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26686651" target="_blank">3. Tang Z., Luo O. J., Li X., et al. CTCF-Mediated Human 3D Genome Architecture Reveals Chromatin Topology for Transcription. Cell. 2015;163:1611-1627</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27130552" target="_blank">4. Sati S. and Cavalli G. Chromosome conformation capture technologies and their impact in understanding genome function. Chromosoma. 2016;
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22703176" target="_blank">5. Sajan S. A. and Hawkins R. D. Methods for identifying higher-order chromatin structure. Annu Rev Genomics Hum Genet. 2012;13:59-82</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21526222" target="_blank">6. Consortium E. P. A user's guide to the encyclopedia of DNA elements (ENCODE). PLoS Biol. 2011;9:e1001046</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27643841" target="_blank">7. Mumbach M. R., Rubin A. J., Flynn R. A., et al. HiChIP: efficient and sensitive analysis of protein-directed genome architecture. Nat Methods. 2016;13:919-922</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_chip_sample_prep_kit.html">TruSeq ChIP-Seq Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27130552" target="_blank">Sati S. and Cavalli G. Chromosome conformation capture technologies and their impact in understanding genome function. Chromosoma. 2016;</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26898941" target="_blank">Ricano-Ponce I., Zhernakova D. V., Deelen P., et al. Refined mapping of autoimmune disease associated genetic variants with gene expression suggests an important role for non-coding RNAs. J Autoimmun. 2016;68:62-74</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26926107" target="_blank">Chang H., Liu Y., Xue M., et al. Synergistic action of master transcription factors controls epithelial-to-mesenchymal transition. Nucleic Acids Res. 2016;44:2514-2527</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27600471" target="_blank">Darabi H., Beesley J., Droit A., et al. Fine scale mapping of the 17q22 breast cancer locus using dense SNPs, genotyped within the Collaborative Oncological Gene-Environment Study (COGs). Sci Rep. 2016;6:32512</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27064257" target="_blank">Fujimoto A., Furuta M., Totoki Y., et al. Whole-genome mutational landscape and characterization of noncoding and structural mutations in liver cancer. Nat Genet. 2016;48:500-509</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27259153" target="_blank">Tewhey R., Kotliar D., Park D. S., et al. Direct Identification of Hundreds of Expression-Modulating Variants using a Multiplexed Reporter Assay. Cell. 2016;165:1519-1529</a></li>
</ol>

<h5>ChIP-Seq/ChIP-exo/HT-ChIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/chip-seq-chip-exo-ht-chip.png"></p>

<p>ChIP-Seq is a well-established method to map specific protein-binding sites.  It has given rise to a vast number of derivatives, such as AHT-ChIP-Seq<sup>1</sup>, BisChIP-Seq<sup>2</sup>, CAST-ChIP<sup>3</sup>, ChIP-BMS<sup>4</sup>, ChIP-BS-seq<sup>5</sup>, ChIPmentation<sup>6</sup>, Drop-ChIP<sup>7</sup>, Mint-ChIP<sup>8</sup>, PAT–ChIP<sup>9</sup>, reChIP-seq<sup>10</sup>, scChIP-seq<sup>11</sup>, and X-ChIP<sup>12</sup>. Sequential ChIP-seq (reChIP) can also show the association of different proteins on the chromatin<sup>13</sup>. </p><p>
In this method, DNA-protein complexes are crosslinked <i>in vivo</i>. Next, samples are fragmented and treated with an exonuclease to trim unbound oligonucleotides. Protein-specific antibodies are used to immunoprecipitate the DNA-protein complex. The DNA is extracted, purified, and sequenced, giving high-resolution sequences of the protein-binding sites.</p>
<h6>Pros:</h6>
<ul>
<li>	Base-pair resolution of protein-binding sites</li>
<li>	Can map specific regulatory factors or proteins </li>
<li>	Exonuclease use eliminates contamination by unbound DNA<sup>14</sup> </li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Nonspecific antibodies can dilute the pool of DNA-protein complexes of interest</li>
<li>	Target protein must be known and be able to raise an antibody</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/2454748">ChIP-Seq: Solomon M. J., Larsen P. L. and Varshavsky A. (1988) Mapping protein-DNA interactions in vivo with formaldehyde: evidence that histone H4 is retained on a highly transcribed gene. Cell 53: 937-947</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24034248">ChIP-exo: Yen K., Vinayachandran V. and Pugh B. F. (2013) SWR-C and INO80 chromatin remodelers recognize nucleosome-free regions near +1 nucleosomes. Cell 154: 1246-1256</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23429716">HT-ChIP: Blecher-Gonen R., Barnett-Itzhaki Z., Jaitin D., Amann-Zalcenstein D., Lara-Astiaso D., et al. (2013) High-throughput chromatin immunoprecipitation for genome-wide mapping of in vivo protein-DNA interactions and epigenomic states. Nat Protoc 8: 539-554</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24200198" target="_blank">1. Aldridge S., Watt S., Quail M. A., et al. AHT-ChIP-seq: a completely automated robotic protocol for high-throughput chromatin immunoprecipitation. Genome Biol. 2013;14:R124</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22466171" target="_blank">2. Statham A. L., Robinson M. D., Song J. Z., Coolen M. W., Stirzaker C. and Clark S. J. Bisulfite sequencing of chromatin immunoprecipitated DNA (BisChIP-seq) directly informs methylation status of histone-modified DNA. Genome Res. 2012;22:1120-1127</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24095734" target="_blank">3. Schauer T., Schwalie P. C., Handley A., Margulies C. E., Flicek P. and Ladurner A. G. CAST-ChIP maps cell-type-specific chromatin states in the Drosophila central nervous system. Cell Rep. 2013;5:271-282</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21913084" target="_blank">4. Li Y. and Tollefsbol T. O. Combined chromatin immunoprecipitation and bisulfite methylation sequencing analysis. Methods Mol Biol. 2011;791:239-251</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22466170" target="_blank">5. Brinkman A. B., Gu H., Bartels S. J., et al. Sequential ChIP-bisulfite sequencing enables direct genome-scale investigation of chromatin and DNA methylation cross-talk. Genome Res. 2012;22:1128-1138</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26280331" target="_blank">6. Schmidl C., Rendeiro A. F., Sheffield N. C. and Bock C. ChIPmentation: fast, robust, low-input ChIP-seq for histones and transcription factors. Nat Methods. 2015;12:963-965</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26458175" target="_blank">7. Rotem A., Ram O., Shoresh N., et al. Single-cell ChIP-seq reveals cell subpopulations defined by chromatin state. Nat Biotechnol. 2015;33:1165-1172</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26687680" target="_blank">8. van Galen P., Viny A. D., Ram O., et al. A Multiplexed System for Quantitative Comparisons of Chromatin Landscapes. Mol Cell. 2016;61:170-180</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22082985" target="_blank">9. Fanelli M., Amatori S., Barozzi I. and Minucci S. Chromatin immunoprecipitation and high-throughput sequencing from paraffin-embedded pathology tissue. Nat Protoc. 2011;6:1905-1919</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22113276" target="_blank">10. Truax A. D. and Greer S. F. ChIP and Re-ChIP assays: investigating interactions between regulatory proteins, histone modifications, and the DNA sequences to which they bind. Methods Mol Biol. 2012;809:175-188</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26458175" target="_blank">11. Rotem A., Ram O., Shoresh N., et al. Single-cell ChIP-seq reveals cell subpopulations defined by chromatin state. Nat Biotechnol. 2015;33:1165-1172</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24737864" target="_blank">12. Skene P. J., Hernandez A. E., Groudine M. and Henikoff S. The nucleosomal barrier to promoter escape by RNA polymerase II is overcome by the chromatin remodeler Chd1. Elife. 2014;3:e02042</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25938714" target="_blank">13. Elsasser S. J., Noh K. M., Diaz N., Allis C. D. and Banaszynski L. A. Histone H3.3 is required for endogenous retroviral element silencing in embryonic stem cells. Nature. 2015;522:240-244</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23088423" target="_blank">14. Zentner G. E. and Henikoff S. Surveying the epigenomic landscape, one base at a time. Genome Biol. 2012;13:250</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_chip_sample_prep_kit.html">TruSeq ChIP-Seq kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26721890" target="_blank">Yan H., Tian S., Slager S. L., Sun Z. and Ordog T. Genome-Wide Epigenetic Studies in Human Disease: A Primer on -Omic Technologies. Am J Epidemiol. 2016;183:96-109</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27476967" target="_blank">Rinaldi L., Datta D., Serrat J., et al. Dnmt3a and Dnmt3b Associate with Enhancers to Regulate Human Epidermal Stem Cell Homeostasis. Cell Stem Cell. 2016;19:491-501</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27299313" target="_blank">Woolnough J. L., Atwood B. L., Liu Z., Zhao R. and Giles K. E. The Regulation of rRNA Gene Transcription during Directed Differentiation of Human Embryonic Stem Cells. PLoS One. 2016;11:e0157276</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27545881" target="_blank">Schmidt S. F., Madsen J. G., Frafjord K. O., et al. Integrative Genomics Outlines a Biphasic Glucose Response and a ChREBP-RORgamma Axis Regulating Proliferation in beta Cells. Cell Rep. 2016;16:2359-2372</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27457071" target="_blank">Nelson D. M., Jaber-Hijazi F., Cole J. J., et al. Mapping H4K20me3 onto the chromatin landscape of senescent cells indicates a function in control of cell senescence and tumor suppression through preservation of genetic and epigenetic stability. Genome Biol. 2016;17:158</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27027282" target="_blank">Wu T. P., Wang T., Seetin M. G., et al. DNA methylation on N(6)-adenine in mammalian embryonic stem cells. Nature. 2016;532:329-333</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26369632" target="_blank">Zwart W., Flach K. D., Rudraraju B., et al. SRC3 Phosphorylation at Serine 543 Is a Positive Independent Prognostic Factor in ER-Positive Breast Cancer. Clin Cancer Res. 2016;22:479-491</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26735971" target="_blank">Yasuma K., Yasunaga J., Takemoto K., et al. HTLV-1 bZIP Factor Impairs Anti-viral Immunity by Inducing Co-inhibitory Molecule, T Cell Immunoglobulin and ITIM Domain (TIGIT). PLoS Pathog. 2016;12:e1005372</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27466807" target="_blank">De S., Mitra A., Cheng Y., Pfeifer K. and Kassis J. A. Formation of a Polycomb-Domain in the Absence of Strong Polycomb Response Elements. PLoS Genet. 2016;12:e1006200</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26796577" target="_blank">Bevington S. L., Cauchy P., Piper J., et al. Inducible chromatin priming is associated with the establishment of immunological memory in T cells. EMBO J. 2016;35:515-535</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27376235" target="_blank">Hay D., Hughes J. R., Babbs C., et al. Genetic dissection of the alpha-globin super-enhancer <i>in vivo</i>. Nat Genet. 2016;48:895-903</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25801168" target="_blank">Weiner A., Hsieh T. H., Appleboim A., et al. High-resolution chromatin dynamics during a yeast stress response. Mol Cell. 2015;58:371-386</a></li>
</ol>

<h5>ChIPmentation</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/chipmentation.png"></p>

<p>ChIPmentation combines ChIP with sequencing library preparation by Tn5 transposase (tagmentation). Both ATAC-seq and ChIPmentation can be combined usefully in the same experiment to assay open chromatin and protein binding, respectively.<sup>1</sup> This combination of methods takes advantage of the flexibility and efficiency provided by using Tn5 transposase in library preparation. Tagmentation is performed directly on bead-bound, immunoprecipitated chromatin, followed by standard library preparation methods.</p>
<h6>Pros:</h6>
<ul>
<li>Can generated accurate profiles from as little as 10,000 cells</li>
<li>Simple, one-step reaction</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported	</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26280331" target="_blank">ChIPmentation: Schmidl C., Rendeiro A. F., Sheffield N. C. and Bock C. ChIPmentation: fast, robust, low-input ChIP-seq for histones and transcription factors. Nat Methods. 2015;12:963-965</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27297499" target="_blank">1. Chaitankar V., Karakulah G., Ratnapriya R., Giuste F. O., Brooks M. J. and Swaroop A. Next generation sequencing technology and genomewide data analysis: Perspectives for retinal research. Prog Retin Eye Res. 2016;55:1-31</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27346425" target="_blank">Rendeiro A. F., Schmidl C., Strefford J. C., Walewska R., Davis Z., et al. Chromatin accessibility maps of chronic lymphocytic leukaemia identify subtype-specific epigenome signatures and transcription regulatory networks. Nat Commun. 2016;7:11938</a></li>
</ol>

<h5>DamID</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/damid.png"></p>

<p>DamID allows the identification of protein-binding sites in living cells without the need for crosslinking or immunoprecipitation. It was developed in 2006 as a microarray method before it was adapted to NGS. DamID involves the low-level expression of a fusion protein consisting of DNA adenine methyltransferase (Dam) and a chromatin protein of interest. This fusion protein is targeted to the native binding sites of the chromatin protein, where Dam methylates adenines in the surrounding DNA. Subsequently, the methylated DNA fragments are isolated, amplified by selective PCR, and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Allows the identification of protein-binding sites in living cells without the need for crosslinking or immunoprecipitation</li>
<li>Dedicated algorithms are available<sup>1</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Dam can be toxic</li>
<li>Limited to kilobase-sized regions</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/17038565" target="_blank">DamID: Vogel M. J., Guelen L., de Wit E., et al. Human heterochromatin proteins form large domains containing KRAB-ZNF genes. Genome Res. 2006;16:1493-1504</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25785608" target="_blank">1. Li R., Hempel L. U. and Jiang T. A non-parametric peak calling algorithm for DamID-Seq. PLoS One. 2015;10:e0117415</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27001518" target="_blank">Pindyurin A. V., Pagie L., Kozhevnikova E. N., van Arensbergen J. and van Steensel B. Inducible DamID systems for genomic mapping of chromatin proteins in Drosophila. Nucleic Acids Res. 2016;44:5646-5657</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27597321" target="_blank">Mitchell A. C., Javidfar B., Bicks L. K., et al. Longitudinal assessment of neuronal 3D genomes in mouse prefrontal cortex. Nat Commun. 2016;7:12743</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27099177" target="_blank">Perovanovic J., Dell'Orso S., Gnochi V. F., et al. Laminopathies disrupt epigenomic developmental programs and cell fate. Sci Transl Med. 2016;8:335ra358</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26787877" target="_blank">McCann T. S., Guo Y., McDonald W. H. and Tansey W. P. Antagonistic roles for the ubiquitin ligase Asr1 and the ubiquitin-specific protease Ubp3 in subtelomeric gene silencing. Proc Natl Acad Sci U S A. 2016;113:1309-1314</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25887553" target="_blank">Carl S. H. and Russell S. Common binding by redundant group B Sox proteins is evolutionarily conserved in Drosophila. BMC Genomics. 2015;16:292</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26365489" target="_blank">Kind J., Pagie L., de Vries S. S., et al. Genome-wide maps of nuclear lamina interactions in single human cells. Cell. 2015;163:134-147</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25793375" target="_blank">Klocko A. D., Rountree M. R., Grisafi P. L., Hays S. M., Adhvaryu K. K. and Selker E. U. Neurospora importin alpha is required for normal heterochromatic formation and DNA methylation. PLoS Genet. 2015;11:e1005083</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25798942" target="_blank">Steglich B., Stralfors A., Khorosjutina O., et al. The Fun30 chromatin remodeler Fft3 controls nuclear organization and chromatin structure of insulators and subtelomeres in fission yeast. PLoS Genet. 2015;11:e1005101</a></li>
</ol>

<h5>DNase-Seq/DNasel-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/dnase-seq-dnasel-seq.png"></p>

<p>DNase I footprinting was first published in 1978 and predates both Sanger sequencing and NGS. The first published use with NGS was published by Boyle et al. and later optimized for sequencing<sup>1</sup>. A high-sensitivity protocol is also available (scDNase-seq)<sup>2</sup>.</p>
<p>In this method, DNA-protein complexes are treated with DNase l, followed by DNA extraction and sequencing. Sequences bound by regulatory proteins are protected from DNase l digestion. Deep sequencing provides accurate representation of the location of regulatory proteins in the genome. In a variation on this approach, the DNA-protein complexes are stabilized by formaldehyde crosslinking before DNase I digestion. The crosslinking is reversed before DNA purification. In an alternative modification, called GeF-seq, both the crosslinking and the DNase I digestion are carried out <i>in vivo</i>, within permeabilized cells<sup>3</sup>.</p>
<h6>Pros:</h6>
<ul>
<li>Can detect “open” chromatin<sup>4</sup></li>
<li>No prior knowledge of the sequence or binding protein is required</li>
<li>Compared to formaldehyde-assisted isolation of regulatory elements and sequencing (FAIRE-seq), has greater sensitivity at promoters<sup>5</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>DNase l is sequence-specific and hypersensitive sites might not account for the entire genome<sup>6</sup></li>
<li>DNA loss through the multiple purification steps limits sensitivity<sup>7</sup></li>
<li>Integration of DNase I with ChIP data is necessary to identify and differentiate similar protein-binding sites</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/18243105">DNase-Seq: Boyle A. P. et al. (2008) High-resolution mapping and characterization of open chromatin across the genome. Cell 132: 311-322</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/6269069" target="_blank">1. Anderson S. Shotgun DNA sequencing using cloned DNase I-generated fragments. Nucleic Acids Res. 1981;9:3015-3027</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26605532" target="_blank">2. Jin W., Tang Q., Wan M., et al. Genome-wide detection of DNase I hypersensitive sites in single cells and FFPE tissue samples. Nature. 2015;528:142-146</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23580539" target="_blank">3. Chumsakul O., Nakamura K., Kurata T., et al. High-resolution mapping of <i>in vivo</i> genomic transcription factor binding sites using <i>in situ</i> DNase I footprinting and ChIP-seq. DNA Res. 2013;20:325-338</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23088423" target="_blank">4. Zentner G. E. and Henikoff S. Surveying the epigenomic landscape, one base at a time. Genome Biol. 2012;13:250</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23770639" target="_blank">5. Kumar V., Muratani M., Rayan N. A., et al. Uniform, optimal signal processing of mapped deep-sequencing data. Nat Biotechnol. 2013;31:615-622</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26721890" target="_blank">6. Yan H., Tian S., Slager S. L., Sun Z. and Ordog T. Genome-Wide Epigenetic Studies in Human Disease: A Primer on -Omic Technologies. Am J Epidemiol. 2016;183:96-109</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27259149" target="_blank">7. Lu F., Liu Y., Inoue A., Suzuki T., Zhao K. and Zhang Y. Establishing Chromatin Regulatory Landscape during Mouse Preimplantation Development. Cell. 2016;165:1375-1388</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_chip_sample_prep_kit.html">TruSeq ChIP-Seq kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27297499" target="_blank">Chaitankar V., Karakulah G., Ratnapriya R., Giuste F. O., Brooks M. J., et al. Next generation sequencing technology and genomewide data analysis: Perspectives for retinal research. Prog Retin Eye Res. 2016;55:1-31</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26721890" target="_blank">Yan H., Tian S., Slager S. L., Sun Z. and Ordog T. Genome-Wide Epigenetic Studies in Human Disease: A Primer on -Omic Technologies. Am J Epidemiol. 2016;183:96-109</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27250572" target="_blank">Qiu Z., Li R., Zhang S., et al. Identification of Regulatory DNA Elements Using Genome-wide Mapping of DNase I Hypersensitive Sites during Tomato Fruit Development. Mol Plant. 2016;9:1168-1182</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27087856" target="_blank">Frank C. L., Manandhar D., Gordan R. and Crawford G. E. HDAC inhibitors cause site-specific chromatin remodeling at PU.1-bound enhancers in K562 cells. Epigenetics Chromatin. 2016;9:15</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27259149" target="_blank">Lu F., Liu Y., Inoue A., Suzuki T., Zhao K., et al. Establishing Chromatin Regulatory Landscape during Mouse Preimplantation Development. Cell. 2016;165:1375-1388</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27350436" target="_blank">Badal S. S., Wang Y., Long J., et al. miR-93 regulates Msk2-mediated chromatin remodelling in diabetic nephropathy. Nat Commun. 2016;7:12076</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27036006" target="_blank">Adar S., Hu J., Lieb J. D. and Sancar A. Genome-wide kinetics of DNA excision repair in relation to chromatin state and mutagenesis. Proc Natl Acad Sci U S A. 2016;113:E2124-2133</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26796577" target="_blank">Bevington S. L., Cauchy P., Piper J., Bertrand E., Lalli N., et al. Inducible chromatin priming is associated with the establishment of immunological memory in T cells. EMBO J. 2016;35:515-535</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26808453" target="_blank">Browne J. A., Yang R., Eggener S. E., Leir S. H. and Harris A. HNF1 regulates critical processes in the human epididymis epithelium. Mol Cell Endocrinol. 2016;425:94-102</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27297499" target="_blank">Chaitankar V., Karakulah G., Ratnapriya R., Giuste F. O., Brooks M. J., et al. Next generation sequencing technology and genomewide data analysis: Perspectives for retinal research. Prog Retin Eye Res. 2016;55:1-31</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27526324" target="_blank">Corces M. R., Buenrostro J. D., Wu B., Greenside P. G., Chan S. M., et al. Lineage-specific and single-cell chromatin accessibility charts human hematopoiesis and leukemia evolution. Nat Genet. 2016;48:1193-1203</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26586797" target="_blank">Georgakilas G., Vlachos I. S., Zagganas K., et al. DIANA-miRGen v3.0: accurate characterization of microRNA promoters and their regulators. Nucleic Acids Res. 2016;44:D190-195</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27525976" target="_blank">Lensing S. V., Marsico G., Hansel-Hertsch R., Lam E. Y., Tannahill D. and Balasubramanian S. DSBCapture: <i>in situ</i> capture and sequencing of DNA breaks. Nat Methods. 2016;13:855-857</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26446995" target="_blank">Metser G., Shin H. Y., Wang C., et al. An autoregulatory enhancer controls mammary-specific STAT5 functions. Nucleic Acids Res. 2016;44:1052-1063</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27545881" target="_blank">Schmidt S. F., Madsen J. G., Frafjord K. O., Poulsen L., Salo S., et al. Integrative Genomics Outlines a Biphasic Glucose Response and a ChREBP-RORgamma Axis Regulating Proliferation in beta Cells. Cell Rep. 2016;16:2359-2372</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27376239" target="_blank">Shin H. Y., Willi M., Yoo K. H., et al. Hierarchy within the mammary STAT5-driven Wap super-enhancer. Nat Genet. 2016;48:904-911</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26890492" target="_blank">Thompson B., Varticovski L., Baek S. and Hager G. L. Genome-Wide Chromatin Landscape Transitions Identify Novel Pathways in Early Commitment to Osteoblast Differentiation. PLoS One. 2016;11:e0148619</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26673704" target="_blank">Yang R., Kerschner J. L., Gosalia N., et al. Differential contribution of cis-regulatory elements to higher order chromatin structure and expression of the CFTR locus. Nucleic Acids Res. 2016;44:3082-3094</a></li>
</ol>

<h5>DNaseI-SIM</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/dnasei-sim.png"></p>

<p>This method is a simplified DNase I protocol specifically intended for plants. It contains an additional step of nuclei purification in Percoll gradients prior to DNase I digestion, in order to remove cellular debris and starch granules more efficiently. A DNA end-polishing step, using T4 DNA polymerase, is performed directly in the nuclei following DNase I digestion. These additional steps obviate the need for gel purification and its attendant loss of material.</p>
<h6>Pros:</h6>
<ul>
<li>Does not require gel purification</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Optimized for plants only</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26339280">DNaseI-SIM: Cumbie J. S., Filichkin S. A. and Megraw M. (2015) Improved DNase-seq protocol facilitates high resolution mapping of DNase I hypersensitive sites in roots in Arabidopsis thaliana. Plant Methods 11: 42</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26339280">Cumbie J. S., Filichkin S. A. and Megraw M. (2015) Improved DNase-seq protocol facilitates high resolution mapping of DNase I hypersensitive sites in roots in Arabidopsis thaliana. Plant Methods 11: 42</a></li>
</ol>

<h5>FAIRE-Seq/Sono-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/faire-seq-sono-seq.png"></p>

<p>FAIRE-seq and Sono-Seq  are based on differences in crosslinking efficiencies between DNA and nucleosomes or sequence-specific DNA-binding proteins. 
In this method, DNA-protein complexes are crosslinked briefly <i>in vivo</i> using formaldehyde. The sample is then lysed and sonicated. After phenol/chloroform extraction, the DNA in the aqueous phase is purified and sequenced. Sequencing provides information for regions of DNA that are not occupied by histones.</p>
<p>Pros:</p>
<ul>
<li>	Simple and highly reproducible protocol</li>
<li>	Does not require antibodies</li>
<li>	Does not require enzymes, such as DNase or MNase, avoiding the optimization and extra steps necessary for enzymatic processing</li>
<li>	Does not require a single-cell suspension or nuclear isolation, so it is easily adapted for use on tissue samples<sup>1</sup> </li>
</ul>
<p>Cons:</p>
<ul>
<li>	Cannot identify regulatory proteins bound to DNA</li>
<li>	DNase-Seq may be better at identifying nucleosome-depleted promoters of highly expressed genes<sup>2</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/19303047" target="_blank">FAIRE-Seq: Giresi P. G. and Lieb J. D. (2009) Isolation of active regulatory elements from eukaryotic chromatin using FAIRE (Formaldehyde Assisted Isolation of Regulatory Elements). Methods 48: 233-239</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/17002501" target="_blank">FAIRE-Seq: Hogan G. J., Lee C. K. and Lieb J. D. (2006) Cell cycle-specified fluctuation of nucleosome occupancy at gene promoters. PLoS Genet 2: e158</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19706456">Sono-Seq: Auerbach R. K., Euskirchen G., Rozowsky J., Lamarre-Vincent N., Moqtaderi Z., et al. (2009) Mapping accessible chromatin regions using Sono-Seq. Proc Natl Acad Sci U S A 106: 14926-14931</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22262007" target="_blank">1. Simon J. M., Giresi P. G., Davis I. J. and Lieb J. D. Using formaldehyde-assisted isolation of regulatory elements (FAIRE) to isolate active regulatory DNA. Nat Protoc. 2012;7:256-267</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21750106" target="_blank">2. Song L., Zhang Z., Grasfeder L. L., et al. Open chromatin defined by DNaseI and FAIRE identifies regulatory elements that shape cell-type identity. Genome Res. 2011;21:1757-1767</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_chip_sample_prep_kit.html">TruSeq ChIP-seq Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26721890" target="_blank">Yan H., Tian S., Slager S. L., Sun Z. and Ordog T. Genome-Wide Epigenetic Studies in Human Disease: A Primer on -Omic Technologies. Am J Epidemiol. 2016;183:96-109</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27487356" target="_blank">Lavender C. A., Cannady K. R., Hoffman J. A., Trotter K. W., Gilchrist D. A., et al. Downstream Antisense Transcription Predicts Genomic Features That Define the Specific Chromatin Environment at Mammalian Promoters. PLoS Genet. 2016;12:e1006224</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27161480" target="_blank">Behura S. K., Sarro J., Li P., et al. High-throughput cis-regulatory element discovery in the vector mosquito Aedes aegypti. BMC Genomics. 2016;17:341</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25865119" target="_blank">Verfaillie A., Imrichova H., Atak Z. K., et al. Decoding the regulatory landscape of melanoma reveals TEADS as regulators of the invasive cell state. Nat Commun. 2015;6:6683</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26977395" target="_blank">Ackermann A. M., Wang Z., Schug J., Naji A. and Kaestner K. H. Integration of ATAC-seq and RNA-seq identifies human alpha cell and beta cell signature genes. Mol Metab. 2016;5:233-244</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26814966" target="_blank">de Dieuleveult M., Yen K., Hmitou I., Depaux A., Boussouar F., et al. Genome-wide nucleosome specificity and function of chromatin remodellers in ES cells. Nature. 2016;530:113-116</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27398095" target="_blank">Du J., Leung A., Trac C., et al. Chromatin variation associated with liver metabolism is mediated by transposable elements. Epigenetics Chromatin. 2016;9:28</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27542528" target="_blank">Fabrizius A., Andre D., Laufs T., et al. Critical re-evaluation of neuroglobin expression reveals conserved patterns among mammals. Neuroscience. 2016;337:339-354</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26981385" target="_blank">Nevedomskaya E., Stelloo S., van der Poel H. G., et al. Androgen receptor DNA binding and chromatin accessibility profiling in prostate cancer. Genom Data. 2016;7:124-126</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26559958" target="_blank">Bicker A., Brahmer A. M., Meller S., Kristiansen G., Gorr T. A. and Hankeln T. The Distinct Gene Regulatory Network of Myoglobin in Prostate and Breast Cancer. PLoS One. 2015;10:e0142662</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25679813" target="_blank">Davie K., Jacobs J., Atkins M., et al. Discovery of transcription factors and regulatory regions driving <i>in vivo</i> tumor development by ATAC-seq and FAIRE-seq open chromatin profiling. PLoS Genet. 2015;11:e1004994</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25944915" target="_blank">Naval-Sanchez M., Potier D., Hulselmans G., Christiaens V. and Aerts S. Identification of Lineage-Specific Cis-Regulatory Modules Associated with Variation in Transcription Factor Binding and Chromatin Activity Using Ornstein-Uhlenbeck Models. Mol Biol Evol. 2015;32:2441-2455</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25835000" target="_blank">Reschen M. E., Gaulton K. J., Lin D., et al. Lipid-induced epigenomic changes in human macrophages identify a coronary artery disease-associated variant that regulates PPAP2B Expression through Altered C/EBP-beta binding. PLoS Genet. 2015;11:e1005061</a></li>
</ol>

<h5>FiT-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/fit-seq.png"></p>

<p>FiT-seq is a method to extract soluble chromatin from FFPE tissue samples for the detection of histone-binding sites.  The distinguishing feature of this method is a proteinase K digestion step to reverse the effects of heavily crosslinked fixed chromatin in FFPE tissues, before the sonication step.</p>
<h6>Pros:</h6>
<ul>
<li>	Works on FFPE samples</li>
<li>	Higher resolution and sensitivity than pathology tissue chromatin immunoprecipitation (PAT-ChIP)</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not tested in other laboratories</li>
<li>Sonication may introduce sequence bias<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27111282">FiT-Seq: Cejas P., Li L., O'Neill N. K., Duarte M., Rao P., et al. (2016) Chromatin immunoprecipitation from fixed clinical tissues reveals tumor-specific enhancer profiles. Nat Med 22: 685-691</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19693276">Teytelman L., Ozaydin B., Zill O., Lefrancois P., Snyder M., et al. (2009) Impact of chromatin structures on DNA processing for genomic analyses. PLoS One 4: e6700</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27111282">Cejas P., Li L., O'Neill N. K., Duarte M., Rao P., et al. (2016) Chromatin immunoprecipitation from fixed clinical tissues reveals tumor-specific enhancer profiles. Nat Med 22: 685-691</a></li>
</ol>

<h5>Hi-C/3C-Seq/Capture-C</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/hi-c-3c-seq-capture-c.png"></p>

<p>Hi-C, 3C-Seq, and Capture-C comprise a family of methods for analyzing chromatin interactions. Capture-C adds an additional pull-down of the biotinylated fragments with magnetic beads to the 3C method. A new refinement of the Capture-C method (NG Capture-C) is available. The Hi-C approach extends 3C-Seq to map chromatin contacts genome-wide, and it has also been applied to studying <i>in situ</i> chromatin interactions. </p>
<p>In this method, DNA-protein complexes are crosslinked with formaldehyde. The sample is fragmented, and the DNA is extracted, ligated, and digested with restriction enzymes. The resulting DNA fragments are PCR-amplified and sequenced. Deep sequencing provides base-pair resolution of the ligated fragments.</p>
<h6>Pros:</h6>
<ul>
<li>Allows detection of long-range DNA interactions</li>
<li>High-throughput method</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Detection may result from random chromosomal collisions</li>
<li>Less than 1% of DNA fragments actually yield ligation products<sup>1</sup></li>
<li>Due to multiple steps, the method requires large amounts of starting material</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19815776">Hi-C: Lieberman-Aiden E., van Berkum N. L., Williams L., Imakaev M., Ragoczy T., et al. (2009) Comprehensive mapping of long-range interactions reveals folding principles of the human genome. Science 326: 289-293</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22776363">3-C: Duan Z., Andronescu M., Schutz K., Lee C., Shendure J., et al. (2012) A genome-wide 3C-method for characterizing the three-dimensional architectures of genomes. Methods 58: 277-288</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24413732">Capture-C:Hughes J. R., Roberts N., McGowan S., Hay D., Giannoulatou E., et al. (2014) Analysis of hundreds of cis-regulatory landscapes at high resolution in a single, high-throughput experiment. Nat Genet 46: 205-212</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27634217" target="_blank">1. Bourgo R. J., Singhal H. and Greene G. L. Capture of associated targets on chromatin links long-distance chromatin looping to transcriptional coordination. Nat Commun. 2016;7:12893</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27130552" target="_blank">Sati S. and Cavalli G. Chromosome conformation capture technologies and their impact in understanding genome function. Chromosoma. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27115497" target="_blank">Turaev D. and Rattei T. High definition for systems biology of microbial communities: metagenomics gets genome-centric and strain-resolved. Curr Opin Biotechnol. 2016;39:174-181</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26989773" target="_blank">Criscione S. W., De Cecco M., Siranosian B., et al. Reorganization of chromosome architecture in replicative cellular senescence. Sci Adv. 2016;2:e1500882</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27432957" target="_blank">Darrow E. M., Huntley M. H., Dudchenko O., et al. Deletion of DXZ4 on the human inactive X chromosome alters higher-order genome architecture. Proc Natl Acad Sci U S A. 2016;113:E4504-4512</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26971819" target="_blank">Krijger P. H., Di Stefano B., de Wit E., et al. Cell-of-Origin-Specific 3D Genome Structure Acquired during Somatic Cell Reprogramming. Cell Stem Cell. 2016;18:597-610</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27410265" target="_blank">Veluchamy A., Jegu T., Ariel F., et al. LHP1 Regulates H3K27me3 Spreading and Shapes the Three-Dimensional Conformation of the Arabidopsis Genome. PLoS One. 2016;11:e0158936</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26829752" target="_blank">Acemel R. D., Tena J. J., Irastorza-Azcarate I., et al. A single three-dimensional chromatin compartment in amphioxus indicates a stepwise evolution of vertebrate Hox bimodal regulation. Nat Genet. 2016;48:336-341</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27384883" target="_blank">Bigot P., Colli L. M., Machiela M. J., et al. Functional characterization of the 12p12.1 renal cancer-susceptibility locus implicates BHLHE41. Nat Commun. 2016;7:12098</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26869583" target="_blank">Capurso D., Bengtsson H. and Segal M. R. Discovering hotspots in functional genomic data superposed on 3D chromatin configuration reconstructions. Nucleic Acids Res. 2016;44:2028-2035</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26883634" target="_blank">Gunnell A., Webb H. M., Wood C. D., et al. RUNX super-enhancer control through the Notch pathway by Epstein-Barr virus transcription factors regulates B cell growth. Nucleic Acids Res. 2016;44:4636-4650</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27548313" target="_blank">Kim K. D., Tanizawa H., Iwasaki O. and Noma K. Transcription factors mediate condensin recruitment and global chromosomal organization in fission yeast. Nat Genet. 2016;48:1242-1252</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26751768" target="_blank">Petryk N., Kahli M., d'Aubenton-Carafa Y., et al. Replication landscape of the human genome. Nat Commun. 2016;7:10208</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26729303" target="_blank">Pichugina T., Sugawara T., Kaykov A., et al. A diffusion model for the coordination of DNA replication in Schizosaccharomyces pombe. Sci Rep. 2016;6:18757</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26848124" target="_blank">Putnam N. H., O'Connell B. L., Stites J. C., et al. Chromosome-scale shotgun assembly using an <i>in vitro</i> method for long-range linkage. Genome Res. 2016;26:342-350</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27320916" target="_blank">Rocha P. P., Raviram R., Fu Y., et al. A Damage-Independent Role for 53BP1 that Impacts Break Order and Igh Architecture during Class Switch Recombination. Cell Rep. 2016;16:48-55</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26951677" target="_blank">Tjong H., Li W., Kalhor R., et al. Population-based 3D genome structure analysis reveals driving forces in spatial genome organization. Proc Natl Acad Sci U S A. 2016;113:E1663-1672</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26518482" target="_blank">Ulianov S. V., Khrameeva E. E., Gavrilov A. A., et al. Active chromatin and transcription play a key role in chromosome partitioning into topologically associating domains. Genome Res. 2016;26:70-84</a></li>
</ol>

<h5>HiTS-FLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/hits-flip.png"></p>

<p>HiTS-FLIP is a technique for measuring quantitative protein-DNA binding affinity at unprecedented depth. In this approach, the optics built into a high-throughput sequencer are used to visualize in vitro binding of a protein to sequenced DNA in a flow cell. 
A microfluidic flow cell with anchored single-stranded DNA is sequenced by synthesis. Second-strand DNA is stripped and rebuilt using Klenow polymerase and unmodified dNTPs to form double-stranded DNA clusters. Fluorescently labeled binding protein is introduced at different concentrations, and binding is imaged.</p>
<h6>Pros:</h6>
<ul>
<li>Quantitative and comprehensive</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires specialized hardware</li>
<li>Not yet adopted widely by the scientific community</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21706015" target="_blank">HiTS-FLIP: Nutiu R., Friedman R. C., Luo S., et al. Direct measurement of DNA affinity landscapes on a high-throughput sequencing instrument. Nat Biotechnol. 2011;29:659-664</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row">
<div class="col-sm-6">
<ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21706015" target="_blank">Nutiu R., Friedman R. C., Luo S., et al. Direct measurement of DNA affinity landscapes on a high-throughput sequencing instrument. Nat Biotechnol. 2011;29:659-664</a></li>
</ol>

<h5>MAINE-Seq/Mnase-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/maine-seq-mnase-seq-nucleo-seq.png"></p>

<p>Micrococcal nuclease (MNase)-assisted isolation of nucleosomes sequencing (MAINE-Seq), is a variation on the well-established use of MNase digestion to map nucleosome positions (MNase-Seq). It is estimated that almost half the genome contains regularly spaced arrays of nucleosomes, which are enriched in active chromatin domains . In MAINE-Seq, genomic DNA is treated with MNase. The DNA from the DNA-protein complexes is then extracted and sequenced. Sequences bound by regulatory proteins are protected from MNase digestion. Deep sequencing provides accurate representation of the location of regulatory proteins in the genome.</p>
<h6>Pros:</h6>
<ul>
<li>Can map nucleosomes and other DNA-binding proteins</li>
<li>Identifies location of various regulatory proteins in the genome</li>
<li>Covers broad range of regulatory sites</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>MNase sites might not account for the entire genome</li>
<li>Does not provide much information about the kind of regulatory elements</li>
<li>Integration of MNase with ChIP data is necessary to identify and differentiate similar protein-binding sites</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/6272844" target="_blank">MAINE-Seq: Cusick M. E., Herman T. M., DePamphilis M. L. and Wassarman P. M. (1981) Structure of chromatin at deoxyribonucleic acid replication forks: prenucleosomal deoxyribonucleic acid is rapidly excised from replicating simian virus 40 chromosomes by micrococcal nuclease. Biochemistry 20: 6648-6658</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/20054063" target="_blank">MAINE-Seq: Ponts N., Harris E. Y., Prudhomme J., Wick I., Eckhardt-Ludka C., et al. (2010) Nucleosome landscape and control of transcription in the human malaria parasite. Genome Res 20: 228-238</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23811145" target="_blank">MNase-Seq: Schlesinger F., Smith A. D., Gingeras T. R., Hannon G. J. and Hodges E. (2013) De novo DNA demethylation and noncoding transcription define active intergenic regulatory elements. Genome Res 23: 1601-1614</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_chip_sample_prep_kit.html">TruSeq ChIP-seq Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25605800" target="_blank">Carissimi C., Laudadio I., Cipolletta E., Gioiosa S., Mihailovich M., et al. (2015) ARGONAUTE2 cooperates with SWI/SNF complex to determine nucleosome occupancy at human Transcription Start Sites. Nucleic Acids Res 43: 1498-1512</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25921534" target="_blank">Comoglio F., Schlumpf T., Schmid V., Rohs R., Beisel C., et al. (2015) High-resolution profiling of Drosophila replication start sites reveals a DNA shape and chromatin signature of metazoan origins. Cell Rep 11: 821-834</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25815464" target="_blank">Fuda N. J., Guertin M. J., Sharma S., Danko C. G., Martins A. L., et al. (2015) GAGA factor maintains nucleosome-free regions and has a role in RNA polymerase II recruitment to promoters. PLoS Genet 11: e1005108</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25801031" target="_blank">Merkin J. J., Chen P., Alexis M. S., Hautaniemi S. K. and Burge C. B. (2015) Origins and impacts of new Mammalian exons. Cell Rep 10: 1992-2005</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26305327" target="_blank">Nalabothula N., Al-Jumaily T., Eteleeb A. M., Flight R. M., Xiaorong S., et al. (2015) Genome-Wide Profiling of PARP1 Reveals an Interplay with Gene Regulatory Regions and DNA Methylation. PLoS One 10: e0135410</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25798942" target="_blank">Steglich B., Stralfors A., Khorosjutina O., Persson J., Smialowska A., et al. (2015) The Fun30 chromatin remodeler Fft3 controls nuclear organization and chromatin structure of insulators and subtelomeres in fission yeast. PLoS Genet 11: e1005101</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26235892" target="_blank">van Oevelen C., Collombet S., Vicent G., Hoogenkamp M., Lepoivre C., et al. (2015) C/EBPalpha Activates Pre-existing and De Novo Macrophage Enhancers during Induced Pre-B Cell Transdifferentiation and Myelopoiesis. Stem Cell Reports 5: 232-247</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25378314" target="_blank">Wang L., Huang H., Dougherty G., Zhao Y., Hossain A., et al. (2015) Epidaurus: aggregation and integration analysis of prostate cancer epigenome. Nucleic Acids Res 43: e7</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26305225" target="_blank">Yazdi P. G., Pedersen B. A., Taylor J. F., Khattab O. S., Chen Y. H., et al. (2015) Nucleosome Organization in Human Embryonic Stem Cells. PLoS One 10: e0136314</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24606920" target="_blank">Weber C. M., Ramachandran S. and Henikoff S. (2014) Nucleosomes are context-specific, H2A.Z-modulated barriers to RNA polymerase. Mol Cell 53: 819-830</a></li>
</ol>

<h5>MINCE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mince-seq.png"></p>

<p>MINCE-seq was developed to characterize the genome-wide location of nucleosomes and other chromatin proteins behind replication forks at high temporal and spatial resolution. 
In this method, newly replicated DNA is labeled with the nucleotide analog EdU, which is coupled with biotin using click chemistry. Coupling with biotin ensures highly specific purification of newly replicated DNA from asynchronous cells, even if it is only a fraction of a percentage of total DNA. Subsequent MNase treatment recovers DNA fragments bound both by nucleosomes and by nonhistone DNA-binding proteins, which enables the mapping of newly replicated chromatin at near base-pair resolution.</p>
<h6>Pros:</h6>
<ul>
<li>	Maps newly replicated chromatin at near base-pair resolution</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Robustness unknown</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27062929">MINCE-Seq: Ramachandran S. and Henikoff S. (2016) Transcriptional Regulators Compete with Nucleosomes Post-replication. Cell 165: 580-592</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27062929">Ramachandran S. and Henikoff S. (2016) Transcriptional Regulators Compete with Nucleosomes Post-replication. Cell 165: 580-592</a></li>
</ol>

<h5>MPE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mpe-seq.png"></p>

<p>MPE-seq is a method for the genome-wide characterization of chromatin that involves the treatment of nuclei with a complex of methidiumpropyl-EDTA (MPE) and ferrous iron. The MPE-Fe(II) complex binds to DNA via intercalation of the methidium moiety and then generates single- and double-stranded DNA breaks in the presence of oxygen.<sup>1</sup>
MPE-Fe(II) preferentially cleaves the linker DNA between nucleosomes with little sequence bias, unlike MNase. For example, DNA sequences at RNA splice sites are hypersensitive to digestion by MNase but not by MPE-Fe(II). The combined use of MPE-seq and MNase-Seq should allow the identification of noncanonical chromatin structures.</p>
<h6>Pros:</h6>
<ul>
<li>Very little sequence bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not replicated in other laboratories</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26080409" target="_blank">MPE-Seq: Ishii H., Kadonaga J. T. and Ren B. MPE-seq, a new method for the genome-wide analysis of chromatin structure. Proc Natl Acad Sci U S A. 2015;112:E3457-3465</a></li>
  <li><a href=" http://pubs.acs.org/doi/abs/10.1021/ja00365a069" target="_blank">1. Hertzberg R. P. and Dervan P. B. Cleavage of double helical DNA by methidium-propyl-EDTA-iron(II). Journal of the American Chemical Society. 1982;104:313-315</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26080409" target="_blank">Ishii H., Kadonaga J. T. and Ren B. MPE-seq, a new method for the genome-wide analysis of chromatin structure. Proc Natl Acad Sci U S A. 2015;112:E3457-3465</a></li>
</ol>

<h5>NG Capture-C</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ng-capture-c.png"></p>

<p>NG Capture-C is a refinement of 3C-Seq  and Hi-C.  It represents a family of methods used to analyze chromatin interactions. NG Capture-C adds multiple pull-down steps of the biotinylated fragments with magnetic beads to the 3C method.
The protocol uses formaldehyde fixation followed by restriction enzyme digestion and ligation to form ~10 kb concatamers. The DNA is extracted and sonicated. Indexing adapters are added, and the samples are pooled, purified by pull-down, and PCR-amplified. The pull-down and PCR steps can be repeated to yield up to a million-fold enrichment.</p>
<h6>Pros:</h6>
<ul>
<li>High sensitivity to detect cis and trans interactions</li>
<li>Low sample input requirements</li>
<li>Sonicated capture fragments reduces cost compared to capture-C</li>
<li>	Sonicated capture fragments act as UMIs to reduce PCR bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26595209" target="_blank">NG Capture-C: Davies J. O., Telenius J. M., McGowan S. J., et al. Multiplexed analysis of chromosome conformation at vastly improved sensitivity. Nat Methods. 2016;13:74-80</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27130552" target="_blank">Sati S. and Cavalli G. Chromosome conformation capture technologies and their impact in understanding genome function. Chromosoma. 2016;</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26595209" target="_blank">Davies J. O., Telenius J. M., McGowan S. J., et al. Multiplexed analysis of chromosome conformation at vastly improved sensitivity. Nat Methods. 2016;13:74-80</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27376235" target="_blank">Hay D., Hughes J. R., Babbs C., Davies J. O., Graham B. J., et al. Genetic dissection of the alpha-globin super-enhancer in vivo. Nat Genet. 2016;48:895-903</a></li>
</ol>

<h5>NOMe-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/nome-seq.png"></p>

<p>NOMe-Seq is a single-molecule, high-resolution nucleosome positioning assay.  This method is based on the ability of the GpC methyltransferase M.CviPI to methylate GpC sites that are not bound by nucleosomes, to create a digital footprint of nucleosome positioning. M.CviPI can map nucleosome positions at CpG-poor promoters, irrespective of their endogenous methylation status.
In this method, native chromatin is treated with M.CviPI, following which the DNA is treated with sodium bisulfite and subjected to WGBS. From these data, CpG methylation patterns as well as nucleosome-free regions (GpC methylation) can be identified.<sup>1</sup></p>
<h6>Pros:</h6>
<ul>
<li>	High resolution</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Relies on the presence of GpC residues<sup>2</sup> </li>
</ul>
<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22960375">NOMe-Seq: Kelly T. K., Liu Y., Lay F. D., Liang G., Berman B. P. and Jones P. A. Genome-wide mapping of nucleosome positioning and DNA methylation within individual DNA molecules. Genome Res. 2012;22:2497-2506</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27478504" target="_blank">1. Wallner S., Schroder C., Leitao E., et al. Epigenetic dynamics of monocyte-to-macrophage differentiation. Epigenetics Chromatin. 2016;9:33</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26080409" target="_blank">2. Ishii H., Kadonaga J. T. and Ren B. MPE-seq, a new method for the genome-wide analysis of chromatin structure. Proc Natl Acad Sci U S A. 2015;112:E3457-3465</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25421684" target="_blank">Shull A. Y., Noonepalle S. K., Lee E. J., Choi J. H. and Shi H. Sequencing the cancer methylome. Methods Mol Biol. 2015;1238:627-651</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/29224149" target="_blank">Lay F. D., Kelly T. K. and Jones P. A. Nucleosome Occupancy and Methylome Sequencing (NOMe-seq). Methods Mol Biol. 2018;1708:267-284</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27478504" target="_blank">Wallner S., Schroder C., Leitao E., Berulava T., Haak C., et al. Epigenetic dynamics of monocyte-to-macrophage differentiation. Epigenetics Chromatin. 2016;9:33</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25747664" target="_blank">Lay F. D., Liu Y., Kelly T. K., et al. The role of DNA methylation in directing the functional organization of the cancer epigenome. Genome Res. 2015;25:467-477</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26484155" target="_blank">Statham A. L., Taberlay P. C., Kelly T. K., Jones P. A. and Clark S. J. Genome-wide nucleosome occupancy and DNA methylation profiling of four human cell lines. Genom Data. 2015;3:94-96</a></li>
</ol>

<h5>ORGANIC</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/organic.png"></p>

<p>ORGANIC is a gentle protocol that avoids crosslinking and sonication.  The method is a combination of MNase-Seq and native ChIP that provides accurate maps of chromatin-occupied regions in complex eukaryotic genomes.</p>
<h6>Pros:</h6>
<ul>
<li>Avoids sonication bias<sup>1</sup></li>
<li>Avoids crosslinking artifacts<sup>2</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Potentially poor solubilization of proteins<sup>2</sup></li>
<li>MNase sequence bias <sup>3</sup></li>
<li>Nuclei isolation may introduce artifacts</li>
<li>Not replicated in other laboratories</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24336359">ORGANIC: Kasinathan S., Orsi G. A., Zentner G. E., Ahmad K. and Henikoff S. (2013) High-resolution mapping of transcription factor binding sites on native chromatin. Nat Methods advance online publication: </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19693276">1. Teytelman L., Ozaydin B., Zill O., Lefrancois P., Snyder M., et al. (2009) Impact of chromatin structures on DNA processing for genomic analyses. PLoS One 4: e6700</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25297728">2. Zentner G. E. and Henikoff S. (2014) High-resolution digital profiling of the epigenome. Nat Rev Genet 15: 814-827</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26578577">3. Kensche P. R., Hoeijmakers W. A., Toenhake C. G., Bras M., Chappell L., et al. (2016) The nucleosome landscape of Plasmodium falciparum reveals chromatin architecture and dynamics of regulatory sequences. Nucleic Acids Res 44: 2110-2124</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25297728" target="_blank">Zentner G. E. and Henikoff S. High-resolution digital profiling of the epigenome. Nat Rev Genet. 2014;15:814-827</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24336359">Kasinathan S., Orsi G. A., Zentner G. E., Ahmad K. and Henikoff S. (2013) High-resolution mapping of transcription factor binding sites on native chromatin. Nat Methods advance online publication: </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25297728">Zentner G. E. and Henikoff S. (2014) High-resolution digital profiling of the epigenome. Nat Rev Genet 15: 814-827</a></li>
</ol>

<h5>PAT-ChIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pat-chip.png"></p>

<p>PAT-ChIP is a variation of ChIP-Seq, optimized for the analysis of chromatin derived from FFPE samples. The distinguishing features of this method are dewaxing with a xylene substitute (Histolemon, Carlo Erba) followed by both MNase digestion and sonication.  FiT-seq introduces further refinements to this method.</p>
<h6>Pros:</h6>
<ul>
<li>Works on FFPE samples</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Long protocol takes 4 days</li>
<li>Low yield</li>
<li>Sonication may introduce sequence bias <sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22082985" target="_blank">PAT-ChIP: Fanelli M., Amatori S., Barozzi I. and Minucci S. Chromatin immunoprecipitation and high-throughput sequencing from paraffin-embedded pathology tissue. Nat Protoc. 2011;6:1905-1919</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27111282" target="_blank">FiT-Seq: Cejas P., Li L., O'Neill N. K., et al. Chromatin immunoprecipitation from fixed clinical tissues reveals tumor-specific enhancer profiles. Nat Med. 2016;22:685-691</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/19693276" target="_blank">1. Teytelman L., Ozaydin B., Zill O., et al. Impact of chromatin structures on DNA processing for genomic analyses. PLoS One. 2009;4:e6700</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23986147" target="_blank">Mimura I., Kanki Y., Kodama T. and Nangaku M. Revolution of nephrology research by deep sequencing: ChIP-seq and RNA-seq. Kidney Int. 2014;85:31-38</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27111282" target="_blank">Cejas P., Li L., O'Neill N. K., Duarte M., Rao P., et al. Chromatin immunoprecipitation from fixed clinical tissues reveals tumor-specific enhancer profiles. Nat Med. 2016;22:685-691</a></li>
</ol>

<h5>PB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pb-seq.png"></p>

<p>PB–seq is a DNA-binding assay that allows the DNA-protein binding energy landscape to be characterized genome-wide, in the absence of chromatin.  It belongs to the family of methods more commonly known as systematic evolution of ligands by exponential enrichment (SELEX). 
Genomic DNA is sonicated, size-selected, and purified. After hybridization to the DNA-binding protein the protein-bound DNA is isolated, extracted, and prepared for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Determines binding efficiencies independent of chromatin structure</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not yet adopted widely by the scientific community</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22479205" target="_blank">PB-Seq: "Guertin M. J., Martins A. L., Siepel A. and Lis J. T. Accurate prediction of inducible transcription factor binding intensities in vivo. PLoS Genet. 2012;8:e1002610</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22479205" target="_blank">Guertin M. J., Martins A. L., Siepel A. and Lis J. T. Accurate prediction of inducible transcription factor binding intensities in vivo. PLoS Genet. 2012;8:e1002610</a></li>
</ol>

<h5>Pu-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pu-seq.png"></p>

<p>Pu-seq provides direct replication-origin location and efficiency data, as well as indirect estimates of replication timing. 
Alkali treatment of duplex ribonucleotide-containing DNA results in phosphate-backbone cleavage 3’ to the ribose, resulting in a 5’-hydroxyl end. If the denatured DNA is used as a template for random-hexamer primer extension, 5’ to 3’ synthesis results in a flush end adjacent to the initial ribose. By generating a library from single-stranded DNA and placing distinct index primers at each end, sequencing reads can be mapped to individual strands, to determine the original ribonucleotide position with single-base accuracy.</p>
<h6>Pros:</h6>
<ul>
<li>Single-base accuracy</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Only applied to yeast</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25664722" target="_blank">Daigaku Y., Keszthelyi A., Muller C. A., et al. A global profile of replicative polymerase usage. Nat Struct Mol Biol. 2015;22:192-198</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26492137" target="_blank">Keszthelyi A., Daigaku Y., Ptasinska K., Miyabe I. and Carr A. M. Mapping ribonucleotides in genomic DNA and exploring replication dynamics by polymerase usage sequencing (Pu-seq). Nat Protoc. 2015;10:1786-1801</a></li>
</ol>

<h5>SELEX</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/selex.png"></p>

<p>From the time that the first SELEX experiments were described by 3 independent groups in 1990 the method has been adapted to a wide range of technologies<sup>1-5</sup>. A highly multiplexed, parallel HT-SELEX method was developed for NGS.<sup>6</sup> A variation of SELEX-seq <sup>7</sup> uses Nextera adapter sequences for efficient library preparation.<sup>8</sup></p>
<p>In this method, proteins are expressed as fusions with streptavidin-binding peptide (SBP), conjugated to Gaussia luciferase, in the pD40htSELEX expression vector. Each DNA ligand contains a 14 bp randomized region (14N), and a 5 bp barcode that uniquely identifies the individual SELEX sample. Partially nested primers are used in successive SELEX rounds. A double-stranded DNA mixture containing all possible 14 bp sequences is incubated with a DNA-binding protein immobilized into a well of a 96-well plate, resulting in binding of DNA to the protein. After washing and elution, the resulting population of more specific sequences is amplified by PCR and sequenced.</p>
<p>&nbsp;</p>
<h6>Pros:</h6>
<ul>
<li>High-throughput and efficient</li>
<li>Software pipelines are available<sup>9,10</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Could contain sequence bias<sup>11</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/1697402" target="_blank">1. Ellington A. D. and Szostak J. W. In vitro selection of RNA molecules that bind specific ligands. Nature. 1990;346:818-822</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/2200121" target="_blank">2. Tuerk C. and Gold L. Systematic evolution of ligands by exponential enrichment: RNA ligands to bacteriophage T4 DNA polymerase. Science. 1990;249:505-510</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/2225067" target="_blank">3. Sullenger B. A., Gallardo H. F., Ungers G. E. and Gilboa E. Overexpression of TAR sequences renders cells resistant to human immunodeficiency virus replication. Cell. 1990;63:601-608</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27628341" target="_blank">4. Chen D., Orenstein Y., Golodnitsky R., et al. SELMAP - SELEX affinity landscape MAPping of transcription factor binding sites using integrated microfluidics. Sci Rep. 2016;6:33351</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27652575" target="_blank">5. Takahashi M., Wu X., Ho M., et al. High throughput sequencing analysis of RNA libraries reveals the influences of initial library and PCR methods on SELEX efficiency. Sci Rep. 2016;6:33697</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/20378718" target="_blank">6. Jolma A., Kivioja T., Toivonen J., et al. Multiplexed massively parallel SELEX for characterization of human transcription factor binding specificities. Genome Res. 2010;20:861-873</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22153072" target="_blank">7.Slattery M., Riley T., Liu P., et al. Cofactor binding evokes latent differences in DNA binding specificity between Hox proteins. Cell. 2011;147:1270-1282</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26823969" target="_blank">8. Zhang Y., Lee J. K., Toso E. A., et al. DNA-binding sequence specificity of DUX4. Skelet Muscle. 2016;6:8</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27080809" target="_blank">9. Hoinka J. and Przytycka T. AptaPLEX - A dedicated, multithreaded demultiplexer for HT-SELEX data. Methods. 2016;106:82-85</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26395772" target="_blank">10. Caroli J., Taccioli C., De La Fuente A., Serafini P. and Bicciato S. APTANI: a computational tool to select aptamers through sequence-structure motif analysis of HT-SELEX data. Bioinformatics. 2016;32:161-164</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27652575" target="_blank">11. Takahashi M., Wu X., Ho M., et al. High throughput sequencing analysis of RNA libraries reveals the influences of initial library and PCR methods on SELEX efficiency. Sci Rep. 2016;6:33697</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26999002" target="_blank">Anzalone A. V., Lin A. J., Zairis S., Rabadan R. and Cornish V. W. Reprogramming eukaryotic translation with ligand-responsive synthetic RNA switches. Nat Methods. 2016;13:453-458</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27312879" target="_blank">Jijakli K., Khraiwesh B., Fu W., et al. The in vitro selection world. Methods. 2016;106:3-13</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26972786" target="_blank">Urak K. T., Shore S., Rockey W. M., Chen S. J., McCaffrey A. P. and Giangrande P. H. In vitro RNA SELEX for the generation of chemically-optimized therapeutic RNA drugs. Methods. 2016;103:167-174</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27043307" target="_blank">Ahirwar R., Vellarikkal S. K., Sett A., et al. Aptamer-Assisted Detection of the Altered Expression of Estrogen Receptor Alpha in Human Breast Cancer. PLoS One. 2016;11:e0153001</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27648925" target="_blank">Iaboni M., Fontanella R., Rienzo A., et al. Targeting Insulin Receptor with a Novel Internalizing Aptamer. Mol Ther Nucleic Acids. 2016;5:e365</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27121794" target="_blank">Long Y., Qin Z., Duan M., et al. Screening and identification of DNA aptamers toward Schistosoma japonicum eggs via SELEX. Sci Rep. 2016;6:24986</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27010430" target="_blank">Janowski R., Heinz G. A., Schlundt A., et al. Roquin recognizes a non-canonical hexaloop structure in the 3'-UTR of Ox40. Nat Commun. 2016;7:11032</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27510448" target="_blank">Schneider T., Hung L. H., Schreiner S., et al. CircRNA-protein complexes: IMP3 protein component defines subfamily of circRNPs. Sci Rep. 2016;6:31313</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26972799" target="_blank">Stewart H., Bingham R. J., White S. J., et al. Identification of novel RNA secondary structures within the hepatitis C virus genome reveals a cooperative involvement in genome packaging. Sci Rep. 2016;6:22952</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26738816" target="_blank">Oakes B. L., Xia D. F., Rowland E. F., et al. Multi-reporter selection for the design of active and more specific zinc-finger nucleases for genome editing. Nat Commun. 2016;7:10194</a></li>
</ol>

<h5>THS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ths-seq.png"></p>

<p>THS-seq is a method for highly sensitive characterization of chromatin accessibility. This variation on ATAC-seq uses linear amplification of accessible DNA ends, <i>in vitro</i> transcription, and an engineered Tn5 super-mutant.</p>
<h6>Pros:</h6>
<ul>
<li>Requires very little input materials</li>
<li>Can detect small regions near distal enhancers</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires an engineered transposase</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26846207">THS-Seq: Sos B. C., Fung H. L., Gao D. R., Osothprarop T. F., Kia A., et al. (2016) Characterization of chromatin accessibility with a transposome hypersensitive sites sequencing (THS-seq) assay. Genome Biol 17: 20</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26846207">Sos B. C., Fung H. L., Gao D. R., Osothprarop T. F., Kia A., et al. (2016) Characterization of chromatin accessibility with a transposome hypersensitive sites sequencing (THS-seq) assay. Genome Biol 17: 20 </a></li>
</ol>

<h5>UMI-4C</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/umi-4c.png"></p>

<p>This variation on the 4C approach uses UMIs to derive high-complexity quantitative chromosome contact profiles with controlled signal-to-noise ratios.  It is an efficient and accurate method for analyzing targeted loci. The method is paired with software to analyze the data <a href="https://bitbucket.org/tanaylab/umi4cpackage" target="_blank">(https://bitbucket.org/tanaylab/umi4cpackage).</a></li></p>
<h6>Pros:</h6>
<ul>
<li>Improved sensitivity and specificity</li>
<li>Multiplexing allows robust comparison of contact distributions between loci and conditions</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27376768" target="_blank">UMI-4C: Schwartzman O., Mukamel Z., Oded-Elkayam N., et al. UMI-4C for quantitative and targeted chromosomal contact profiling. Nat Methods. 2016;13:685-691</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27376768" target="_blank">Schwartzman O., Mukamel Z., Oded-Elkayam N., et al. UMI-4C for quantitative and targeted chromosomal contact profiling. Nat Methods. 2016;13:685-691</a></li>
</ol>

<h5>X-ChIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/x-chip.png"></p>

<p>X-ChIP, crosslinked chromatin followed by immunoprecipitation, is a foundational technique in chromatin research. With the advent of NGS this simple technique, now called X-ChIP-seq, is able produce high-resolution results. The method involves cross-linking with 1% formaldehyde for 10 min at room temperature. The cells are washed and resuspended in Lysis buffer. After MNase digestion the chromatin is solubilized by brief sonication and then subjected to chromatin immunoprecipitation.</p>
<h6>Pros:</h6>
<ul>
<li>Single base resolution</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Sonication may introduce sequence bias <sup>1</sup></li>
<li>Captures protein–DNA interactions regardless of duration <sup>2</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/11493924">X-ChIP: Breiling A., Turner B. M., Bianchi M. E. and Orlando V. (2001) General transcription factors bind promoters repressed by Polycomb group proteins. Nature 412: 651-655</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21413363">X-ChIP: Negre N. and Cavalli G. (2001) Finding Downstream Target DNAs for Chromatin Proteins by X-CHIP in Drosophila. Mapping Protein/DNA Interactions by Cross-Linking </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26079792">X-ChIP-Seq: Skene P. J. and Henikoff S. (2015) A simple method for generating high-resolution maps of genome-wide protein binding. Elife 4: e09225</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19693276">1. Teytelman L., Ozaydin B., Zill O., Lefrancois P., Snyder M., et al. (2009) Impact of chromatin structures on DNA processing for genomic analyses. PLoS One 4: e6700</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26490019">2. Zentner G. E., Kasinathan S., Xin B., Rohs R. and Henikoff S. (2015) ChEC-seq kinetics discriminates transcription factor binding sites by DNA sequence and shape in vivo. Nat Commun 6: 8733</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25297728" target="_blank">Zentner G. E. and Henikoff S. High-resolution digital profiling of the epigenome. Nat Rev Genet. 2014;15:814-827</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26729620">Schmidt S. V., Krebs W., Ulas T., Xue J., Bassler K., et al. (2016) The transcriptional regulator network of human inflammatory macrophages is defined by open chromatin. Cell Res 26: 151-170</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25938714">Elsasser S. J., Noh K. M., Diaz N., Allis C. D. and Banaszynski L. A. (2015) Histone H3.3 is required for endogenous retroviral element silencing in embryonic stem cells. Nature 522: 240-244 </a></li>
</ol>

#### Methylation

<h5>Aba-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/aba-seq.png"></p>

<p>Aba-seq is a method for high-resolution mapping of the 5hmC methylome that provides sensitive detection of 5hmC at low-occupancy regions.  
The method relies on the unique property of the restriction enzyme AbaSI to recognize glucosylated 5hmC with high specificity, compared to 5mC and C. A single-cell variation, scAba-seq, is also available<sup>1</sup>.  A related method uses PvuRts1I to overcome the sequence bias in AbaSI<sup>2</sup>.</p>
<h6>Pros:</h6>
<ul>
<li>	Covers CpG and non-CpG methylation throughout the genome at single-base resolution</li>
<li>	Covers 5mC in dense and less dense repeat regions</li>
<li>	Clearly differentiates between 5mC and 5hmC</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Ambiguity can exist in 13% of the cleaved molecules in the Aba-seq assay<sup>3</sup> </li>
<li>	Sequence bias in AbaSI activity<sup>4</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23352666">Aba-Seq: Sun Z., Terragni J., Borgaro J. G., Liu Y., Yu L., et al. (2013) High-resolution enzymatic mapping of genomic 5-hydroxymethylcytosine in mouse embryonic stem cells. Cell Rep 3: 567-576</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27347753" target="_blank">1. Mooijman D., Dey S. S., Boisset J. C., Crosetto N. and van Oudenaarden A. Single-cell 5hmC sequencing reveals chromosome-wide cell-to-cell variability and enables lineage reconstruction. Nat Biotechnol. 2016;34:852-856</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25639471" target="_blank">2. Sun Z., Dai N., Borgaro J. G., et al. A sensitive approach to map genome-wide 5-hydroxymethylcytosine and 5-formylcytosine at single-base resolution. Mol Cell. 2015;57:750-761</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27025842" target="_blank">3. Serandour A. A., Avner S., Mahe E. A., et al. Single-CpG resolution mapping of 5-hydroxymethylcytosine by chemical labeling and exonuclease digestion identifies evolutionarily unconserved CpGs as TET targets. Genome Biol. 2016;17:56</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25639471" target="_blank">4. Sun Z., Dai N., Borgaro J. G., et al. A sensitive approach to map genome-wide 5-hydroxymethylcytosine and 5-formylcytosine at single-base resolution. Mol Cell. 2015;57:750-761</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25159599" target="_blank">Plongthongkum N., Diep D. H. and Zhang K. Advances in the profiling of DNA modifications: cytosine methylation and beyond. Nat Rev Genet. 2014;15:647-661</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23352666" target="_blank">Sun Z., Terragni J., Borgaro J. G., et al. High-resolution enzymatic mapping of genomic 5-hydroxymethylcytosine in mouse embryonic stem cells. Cell Rep. 2013;3:567-576</a></li>
</ol>

<h5>BisChIP-Seq/ChIP-BS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bischip-seq-chip-bs-seq.png"></p>

<p>BisChIP-seq, ChIP-BS-seq, and ChIP-BMS all refer to essentially the same method.  It is a direct, quantitative approach to assess DNA methylation patterns associated with chromatin modifications or chromatin-associated factors.<sup>1</sup> </p><p>
The ChIP-capturing step is used to obtain a restricted representation of the genome occupied by the epigenetic feature of interest. The captured DNA fragments are subjected to end-repair, adapter ligation using methylated adapters, bisulfite conversion, PCR amplification, and NGS.</p>
<h6>Pros:</h6>
<ul>
<li>	Genome-wide coverage of 5mC in dense CpG areas and repeat regions</li>
<li>	MBD proteins do not interact with 5hmC</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Does not cover genome-wide CpGs and non-CpG methylation; misses areas with less dense 5mC</li>
<li>	Base-pair resolution is lower (~150 bp), as opposed to single-base resolution with other methods</li>
<li>	Protein-based selection is biased toward hypermethylated regions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25159599">BisChIP-Seq/ChIP-BS-Seq: Plongthongkum N., Diep D. H. and Zhang K. (2014) Advances in the profiling of DNA modifications: cytosine methylation and beyond. Nat Rev Genet 15: 647-661</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22466170" target="_blank">1. Brinkman A. B., Gu H., Bartels S. J., et al. Sequential ChIP-bisulfite sequencing enables direct genome-scale investigation of chromatin and DNA methylation cross-talk. Genome Res. 2012;22:1128-1138</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25159599" target="_blank">Plongthongkum N., Diep D. H. and Zhang K. Advances in the profiling of DNA modifications: cytosine methylation and beyond. Nat Rev Genet. 2014;15:647-661</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25421684" target="_blank">Shull A. Y., Noonepalle S. K., Lee E. J., Choi J. H. and Shi H. Sequencing the cancer methylome. Methods Mol Biol. 2015;1238:627-651</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27385050">Jin J., Lian T., Gu C., Yu K., Gao Y. Q., et al. (2016) The effects of cytosine methylation on general transcription factors. Sci Rep 6: 29119</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25798578">Varshney D., Vavrova-Anderson J., Oler A. J., Cowling V. H., Cairns B. R., et al. (2015) SINE transcription by RNA polymerase III is suppressed by histone methylation but not by DNA methylation. Nat Commun 6: 6569</a></li>
</ol>

<h5>BS-Seq/Bisulfite-seq/WGBS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bs-seq-bisulfite-seq-wgbs.png"></p>

<p>Bisulfite sequencing (BS-Seq) or whole-genome bisulfite sequencing (WGBS) is a well-established protocol to detect methylated cytosines in genomic DNA . In this method, genomic DNA is treated with sodium bisulfite and then sequenced, providing single-base resolution of methylated cytosines in the genome. Upon bisulfite treatment, unmethylated cytosines are deaminated to uracils which, upon sequencing, are converted to thymidines. Simultaneously, methylated cytosines resist deamination and are read as cytosines. The location of the methylated cytosines can then be determined by comparing treated and untreated sequences. Bisulfite treatment of DNA converts unmethylated cytosines to thymidines, leading to reduced sequence complexity. Very accurate deep sequencing serves to mitigate this loss of complexity.</p>
<h6>Pros:</h6>
<ul>
<li>CpG and non-CpG methylation throughout the genome is covered at single-base resolution</li>
<li>5mC in dense, less dense, and repeat regions are covered</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Bisulfite converts unmethylated cytosines to thymidines, reducing sequence complexity, which can make it difficult to create alignments</li>
<li>NPs where a cytosine is converted to thymidine will be missed upon bisulfite conversion</li>
<li>Bisulfite conversion does not distinguish between 5mC and 5hmC</li>
</ul>

<h6>References:</h6>
<p>Methods Link:</p>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/8127720">BS-Seq: Feil R., Charlton J., Bird A. P., Walter J. and Reik W. (1994) Methylation analysis on individual chromosomes: improved protocol for bisulphite genomic sequencing. Nucleic Acids Res 22: 695-696</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22120008">Bisulfite-seq: Berman B. P., Weisenberger D. J., Aman J. F., Hinoue T., Ramjan Z., et al. (2012) Regions of focal DNA hypermethylation and long-range hypomethylation in colorectal cancer coincide with nuclear lamina-associated domains. Nat Genet 44: 40-46</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19829295">WGBS: Lister R., Pelizzola M., Dowen R. H., Hawkins R. D., Hon G., et al. (2009) Human DNA methylomes at base resolution show widespread epigenomic differences. Nature 462: 315-322</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><p>Product Link:</p>
<ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
</ul>
</div>
</div>

<p>Citations:</p>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26138366" adhocenable="false">Seki M., Nishimura R., Yoshida K., Shimamura T., Shiraishi Y., et al. (2015) Integrated genetic and epigenetic analysis defines novel molecular subgroups in rhabdomyosarcoma. Nat Commun 6: 7557</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25821913" adhocenable="false">Nugent B. M., Wright C. L., Shetty A. C., Hodes G. E., Lenz K. M., et al. (2015) Brain feminization requires active repression of masculinization via DNA methylation. Nat Neurosci 18: 690-697</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25796047" adhocenable="false">Lee H. Y., An J. H., Jung S. E., Oh Y. N., Lee E. Y., et al. (2015) Genome-wide methylation profiling and a multiplex construction for the identification of body fluids using epigenetic markers. Forensic Sci Int Genet 17: 17-24</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25706888" adhocenable="false">Lin, I. H., Chen D. T., Chang Y. F., Lee Y. L., Su C. H., et al. (2015) Hierarchical clustering of breast cancer methylomes revealed differentially methylated and expressed breast cancer genes. PLoS One 10: e0118453</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25691127" adhocenable="false">Elliott G., Hong C., Xing X., Zhou X., Li D., et al. (2015) Intermediate DNA methylation is a conserved signature of genome regulation. Nat Commun 6: 6363</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25638528" adhocenable="false">Coit P., Yalavarthi S., Ognenovski M., Zhao W., Hasni S., et al. (2015) Epigenome profiling reveals significant DNA demethylation of interferon signature genes in lupus neutrophils. J Autoimmun 58: 59-66</a></li>
</ol>

<h5>BSAS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bsas.png"></p>

<p>BSAS is a targeted BS-Seq method that uses PCR enrichment of targeted regions and transposome-mediated library construction for rapid generation of sequencing libraries, from low (1 ng) sample input.
Genomic DNA is bisulfite-converted and subjected to PCR, using primers specific for bisulfite-converted DNA. The amplicons are subjected to Nextera XT library preparation, including dual indexing. The final libraries consist of a random insert of bisulfite-converted amplified DNA, capture probes, and specific index sequences. These libraries are multiplexed and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Can be applied to any genomic region from any DNA source, including tissue and cell culture.</li>
<li>Rapid and highly quantitative</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Does not cover whole genome.</li>
<li>Genome and target must be known</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24279302">BSAS: Masser D. R., Berg A. S. and Freeman W. M. (2013) Focused, high accuracy 5-methylcytosine quantitation with base resolution by benchtop next-generation sequencing. Epigenetics Chromatin 6: 33</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/nextera-xt-dna.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-nano-dna.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27338589" target="_blank">Sun L., Wang J., Yin X., et al. Identification of a 5-Methylcytosine Site that may Regulate C/EBPbeta Binding and Determine Tissue-Specific Expression of the BPI Gene in Piglets. Sci Rep. 2016;6:28506</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25919924" target="_blank">Ou X., Thakali K. M., Shankar K., Andres A. and Badger T. M. Maternal adiposity negatively influences infant brain white matter development. Obesity (Silver Spring). 2015;23:1047-1054</a></li>
</ol>

<h5>BSPP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bspp.png"></p>

<p>Bisulfite sequencing with padlock probes (BSPPs), is a targeted method that isolates selected locations for methylation profiling.</p>
<p>Padlock probes are ~100-nucleotide DNA fragments designed to hybridize to genomic DNA targets in a horseshoe manner. After the gap between the two hybridized, locus-specific arms of a padlock probe is filled and ligated, the circular strand of DNA can be amplified.</p>
<h6>Pros:</h6>
<ul>
<li>Requires only 100 ng of DNA for amplification-free WGBS of mammalian genomes</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Failure to capture areas with lower CpG densities<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19330000">BSPP: Deng J., Shoemaker R., Xie B., Gore A., LeProust E. M., et al. (2009) Targeted bisulfite sequencing reveals changes in DNA methylation associated with nuclear reprogramming. Nat Biotechnol 27: 353-360</a></li>
<li><a target="_blank" href="http://www.bloodjournal.org/content/126/23/5226?sso-checked=true">1. Tanaka T., Reilly B., Diep D., Zhang K. and Bejar R. (2015) Cytosine Methylation Patterns As Biomarkers in MDS. Blood 126: 5226-5226</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25421684">Shull A. Y., Noonepalle S. K., Lee E. J., Choi J. H. and Shi H. (2015) Sequencing the cancer methylome. Methods Mol Biol 1238: 627-651</a></li>
</ol>

<h5>CAB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cab-seq.png"></p>

<p>CAB-Seq can detect 5caC with single-base resolution in DNA. It is based on the observation that modified 5caC can survive the bisulfite treatment without deamination.</p>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23758547">CAB-Seq: Lu X., Song C. X., Szulwach K., Wang Z., Weidenbacher P., et al. (2013) Chemical modification-assisted bisulfite sequencing (CAB-Seq) for 5-carboxylcytosine detection in DNA. J Am Chem Soc 135: 9315-9317</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25159599">Plongthongkum N., Diep D. H. and Zhang K. (2014) Advances in the profiling of DNA modifications: cytosine methylation and beyond. Nat Rev Genet 15: 647-661</a></li>
</ol>

<h5>EpiRADSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/epiradseq.png"></p>

<p>EpiRADseq is similar to the widely-used double digest restriction-site associated DNA sequencing-based method (ddRADseq), except that it utilizes a methylation-sensitive restriction enzyme.</p>
<h6>Pros:</h6>
<ul>
<li>Does not need a reference genome</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not widely adapted by the scientific community yet</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12435/abstract">EpiRADSeq: Schield D. R., Walsh M. R., Card D. C., Andrew A. L., Adams R. H., et al. (2016) EpiRADseq: scalable analysis of genomewide patterns of methylation using next-generation sequencing. Methods in Ecology and Evolution 7: 60-69</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/nextera-xt-dna.html">Nextera XT DNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-nano-dna.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12435/abstract">Schield D. R., Walsh M. R., Card D. C., Andrew A. L., Adams R. H., et al. (2016) EpiRADseq: scalable analysis of genomewide patterns of methylation using next-generation sequencing. Methods in Ecology and Evolution 7: 60-69</a></li>
</ol>

<h5>fC-CET</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/fc-cet.png"></p>

<p>fC-CET is a bisulfite-free method for whole-genome analysis of 5fC. The method is based on selective chemical labeling of 5fC and subsequent C-to-T transition during PCR.</p>
<p>Genomic DNA is sequentially labeled with an azido derivative of 1,3-indandione (AI), conjugated to biotin for pulldown enrichment and ligated to adaptors for high-throughput sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Results are in agreement with fC-Seal</li>
<li>Sequences with a single 5fC, was enriched ~100-fold</li>
<li>No noticeable DNA degradation, ideal for analyses of precious DNA.</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not widely adapted by the scientific community yet</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26344045">fC-CET: Xia B., Han D., Lu X., Sun Z., Zhou A., et al. (2015) Bisulfite-free, base-resolution analysis of 5-formylcytosine at the genome scale. Nat Methods 12: 1047-1050</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26344045">Xia B., Han D., Lu X., Sun Z., Zhou A., et al. (2015) Bisulfite-free, base-resolution analysis of 5-formylcytosine at the genome scale. Nat Methods 12: 1047-1050</a></li>
</ol>

<h5>fC-Seal</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/fc-seal.png"></p>

<p>In fC-Seal, 5hmC residues in the genome are blocked with regular glucose, and 5fC residues are reduced to 5hmC by NaBH4. The newly generated 5hmC residues are then modified, enriched, and sequenced.</p>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23602153">fC-Seal: Song C. X., Szulwach K. E., Dai Q., Fu Y., Mao S. Q., et al. (2013) Genome-wide profiling of 5-formylcytosine reveals its roles in epigenetic priming. Cell 153: 678-691</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23602153">Song C. X., Szulwach K. E., Dai Q., Fu Y., Mao S. Q., et al. (2013) Genome-wide profiling of 5-formylcytosine reveals its roles in epigenetic priming. Cell 153: 678-691</a></li>
</ol>

<h5>fCAB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/fcab-seq.png"></p>

<p>fCAB-seq is a method for EtONH2-modified bisulfite sequencing for base-resolution detection of 5fC in genomic DNA. This method is complimentary to fC-Seal, which was developed as a highly selective chemical labeling approach for the affinity purification and genome-wide profiling of 5fC.</p>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23602153">fCAB-Seq: Song C. X., Szulwach K. E., Dai Q., Fu Y., Mao S. Q., et al. (2013) Genome-wide profiling of 5-formylcytosine reveals its roles in epigenetic priming. Cell 153: 678-691</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27356879">Van Haute L., Dietmann S., Kremer L., Hussain S., Pearce S. F., et al. (2016) Deficient methylation and formylation of mt-tRNA(Met) wobble cytosine in a patient carrying mutations in NSUN3. Nat Commun 7: 12039</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26344045">Xia B., Han D., Lu X., Sun Z., Zhou A., et al. (2015) Bisulfite-free, base-resolution analysis of 5-formylcytosine at the genome scale. Nat Methods 12: 1047-1050</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24813617">Wang L., Zhang J., Duan J., Gao X., Zhu W., et al. (2014) Programming and Inheritance of Parental DNA Methylomes in Mammals. Cell 157: 979-991</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24875479">Becker D., Lutsik P., Ebert P., Bock C., Lengauer T., et al. (2014) BiQ Analyzer HiMod: an interactive software tool for high-throughput locus-specific analysis of 5-methylcytosine and its oxidized derivatives. Nucleic Acids Res 42: W501-507</a></li>
</ol>

<h5>MBDCap-Seq/MethylCap-Seq/MBD-Seq/MBDCap/MiGS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mbdcap-seq-methylcap-seq-mbd-seq-mbdcap-migs.png"></p>

<p>Methyl-CpG binding domain-based capture and sequencing (MethylCap , MBD-Seq , MBDCap-Seq , MBDCap) or MBD-isolated genome sequencing (MiGS ), uses proteins to capture methylated DNA in the genome. Genomic DNA is first sonicated and incubated with tagged MBD proteins that can bind methylated cytosines. The protein-DNA complex is then precipitated with antibody-conjugated beads that are specific to the protein tag. Deep sequencing provides greater genome coverage, representing the majority of MBD-bound methylated DNA.</p>
<h6>Pros:</h6>
<ul>
<li>Genome-wide coverage of 5mC in dense CpG areas and repeat regions</li>
<li>MBD proteins do not interact with 5hmC</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Genome-wide CpGs and non-CpG methylation is not covered</li>
<li>Areas with less dense 5mC are also missed</li>
<li>Base-pair resolution is lower (~150 bp) as opposed to single base resolution</li>
<li>Protein-based selection is biased towards hypermethylated regions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20852634">Methyl-Cap: Bock C., Tomazou E. M., Brinkman A. B., Muller F., Simmer F., et al. (2010) Quantitative comparison of genome-wide DNA methylation mapping technologies. Nat Biotechnol 28: 1106-1114</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20542119">Methyl-Cap: Brinkman A. B., Simmer F., Ma K., Kaan A., Zhu J., et al. (2010) Whole-genome DNA methylation profiling using MethylCap-seq. Methods 52: 232-236</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20818161">MBD-Seq: Nair S. S., Coolen M. W., Stirzaker C., Song J. Z., Statham A. L., et al. (2011) Comparison of methyl-DNA immunoprecipitation (MeDIP) and methyl-CpG binding domain (MBD) protein capture for genome-wide DNA methylation analysis reveal CpG sequence coverage bias. Epigenetics 6: 34-44</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22968699">MBDCap-Seq: de Assis S., Warri A., Cruz M. I., Laja O., Tian Y., et al. (2012) High-fat or ethinyl-oestradiol intake during pregnancy increases mammary cancer risk in several generations of offspring. Nat Commun 3: 1053</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/18162535">MBDCap: Rauch T. A., Zhong X., Wu X., Wang M., Kernstine K. H., et al. (2008) High-resolution mapping of DNA hypermethylation and hypomethylation in lung cancer. Proc Natl Acad Sci U S A 105: 252-257</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/18987807">MBDCap: Rauch T. A. and Pfeifer G. P. (2009) The MIRA method for DNA methylation analysis. Methods Mol Biol 507: 65-75</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19906696">MiGS: Serre D., Lee B. H. and Ting A. H. (2010) MBD-isolated Genome Sequencing provides a high-throughput and comprehensive survey of DNA methylation in the human genome. Nucleic Acids Res 38: 391-399</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html" target="_blank">TruSeq ChIP-Seq kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html" target="_blank">Truseq DNA PCR-free library prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26086966" target="_blank">Bose R., Spulber S., Kilian P., Heldring N., Lonnerberg P., et al. (2015) Tet3 mediates stable glucocorticoid-induced alterations in DNA methylation and Dnmt3a/Dkk1 expression in neural progenitors. Cell Death Dis 6: e1793</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26107953" target="_blank">Carrillo J. A., He Y., Luo J., Menendez K. R., Tablante N. L., et al. (2015) Methylome Analysis in Chickens Immunized with Infectious Laryngotracheitis Vaccine. PLoS One 10: e0100476</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25706873" target="_blank">Nishikawa K., Iwamoto Y., Kobayashi Y., Katsuoka F., Kawaguchi S., et al. (2015) DNA methyltransferase 3a regulates osteoclast differentiation by coupling to an S-adenosylmethionine-producing metabolic pathway. Nat Med 21: 281-287</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25641231" target="_blank">Stirzaker C., Zotenko E., Song J. Z., Qu W., Nair S. S., et al. (2015) Methylome sequencing in triple-negative breast cancer reveals distinct methylation clusters with prognostic value. Nat Commun 6: 5899</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25593324" target="_blank">Yang B. H., Floess S., Hagemann S., Deyneko I. V., Groebe L., et al. (2015) Development of a unique epigenetic signature during in vivo Th17 differentiation. Nucleic Acids Res 43: 1537-1548</a></li>
</ol>

<h5>MeDIP-Seq/DIP-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/medip-seq-dip-seq.png"></p>

<p>Methylated DNA immunoprecipitation sequencing (MeDIP-Seq) or DNA immunoprecipitation sequencing (DIP-Seq) is commonly used to study 5mC or 5hmC modification. Specific antibodies can be used to study cytosine modifications. If using 5mC-specific antibodies, methylated DNA is isolated from genomic DNA via immunoprecipitation. Anti-5mC antibodies are incubated with fragmented genomic DNA and precipitated, followed by DNA purification and sequencing. Deep sequencing provides greater genome coverage, representing the majority of immunoprecipitated methylated DNA.</p>
<h6>Pros:</h6>
<ul>
<li>Covers CpG and non-CpG 5mC throughout the genome</li>
<li>5mC in dense, less dense, and repeat regions are covered</li>
<li>Antibody-based selection is independent of sequence and does not enrich for 5hmC due to antibody specificity</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Base-pair resolution is lower (~150 bp) as opposed to single base resolution</li>
<li>Antibody specificity and selectivity must be tested to avoid nonspecific interaction</li>
<li>Antibody-based selection is biased towards hypermethylated regions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/16007088">MeDIP-Seq: Weber M., Davies J. J., Wittig D., Oakeley E. J., Haase M., et al. (2005) Chromosome-wide and promoter-specific analyses identify sites of differential DNA methylation in normal and transformed human cells. Nat Genet 37: 853-862</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23602152">DIP-Seq: Shen L., Wu H., Diep D., Yamaguchi S., D'Alessio A. C., et al. (2013) Genome-wide analysis reveals TET- and TDG-dependent 5-methylcytosine oxidation dynamics. Cell 153: 692-706</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/nextera-xt-dna.html">Nextera XT DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-rapid-exome.html">Nextera DNA Exome</a>/<a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/nextera-rapid-capture-custom-enrichment.html">Custom Enrichment Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25697895" target="_blank">Lee H. J., Lowdon R. F., Maricque B., Zhang B., Stevens M., et al. (2015) Developmental enhancers revealed by extensive DNA methylome maps of zebrafish early embryos. Nat Commun 6: 6315</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25928765" target="_blank">Martin T. C., Yet I., Tsai P. C. and Bell J. T. (2015) coMET: visualisation of regional epigenome-wide association scan results and DNA co-methylation patterns. BMC Bioinformatics 16: 131</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25691127" target="_blank">Elliott G., Hong C., Xing X., Zhou X., Li D., et al. (2015) Intermediate DNA methylation is a conserved signature of genome regulation. Nat Commun 6: 6363</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25690954" target="_blank">Gascard P., Bilenky M., Sigaroudinia M., Zhao J., Li L., et al. (2015) Epigenetic and transcriptional determinants of the human breast. Nat Commun 6: 6351</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26086966" target="_blank">Bose R., Spulber S., Kilian P., Heldring N., Lonnerberg P., et al. (2015) Tet3 mediates stable glucocorticoid-induced alterations in DNA methylation and Dnmt3a/Dkk1 expression in neural progenitors. Cell Death Dis 6: e1793</a></li>
</ol>

<h5>MeDIP-Seq/DIP-Seq/hMeDIP-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/medip-seq-dip-seq-hmedip-seq.png"></p>

<p>Methylated DNA immunoprecipitation sequencing (MeDIP-Seq), DNA immunoprecipitation sequencing (DIP-Seq) or Hydroxymethylated DNA immunoprecipitation sequencing (hMeDIP-Seq), is commonly used to study 5mC or 5hmC modification. Specific antibodies can be used to study cytosine modifications. If using 5mC-specific antibodies, methylated DNA is isolated from genomic DNA via immunoprecipitation. Anti-5mC antibodies are incubated with fragmented genomic DNA and precipitated, followed by DNA purification and sequencing. Deep sequencing provides greater genome coverage, representing the majority of immunoprecipitated methylated DNA.</p>
<h6>Pros:</h6>
<ul>
<li>Covers CpG and non-CpG 5mC throughout the genome</li>
<li>5mC in dense, less dense, and repeat regions are covered</li>
<li>Antibody-based selection is independent of sequence and does not enrich for 5hmC due to antibody specificity</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Base-pair resolution is lower (~150 bp) as opposed to single base resolution</li>
<li>Antibody specificity and selectivity must be tested to avoid nonspecific interaction</li>
<li>Antibody-based selection is biased towards hypermethylated regions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/16007088">MeDIP-Seq: Weber M., Davies J. J., Wittig D., Oakeley E. J., Haase M., et al. (2005) Chromosome-wide and promoter-specific analyses identify sites of differential DNA methylation in normal and transformed human cells. Nat Genet 37: 853-862</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23602152">DIP-Seq: Shen L., Wu H., Diep D., Yamaguchi S., D'Alessio A. C., et al. (2013) Genome-wide analysis reveals TET- and TDG-dependent 5-methylcytosine oxidation dynamics. Cell 153: 692-706</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24875481">hMeDIP-Seq: Jin C., Lu Y., Jelinek J., Liang S., Estecio M. R., et al. (2014) TET1 is a maintenance DNA demethylase that prevents methylation spreading in differentiated cells. Nucleic Acids Res 42: 6956-6971</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/methylation_450_beadchip_kits.html">Infinium HumanMethylation450 Arrays</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_dna_library_prep_kit.html">Nextera DNA Library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera-rapid-capture-exome-kits.html">Nextera Rapid Capture Exome</a>/<a href="/content/illumina-marketing/emea/en_GB/products/nextera-rapid-capture-custom-enrichment-kit.html">Custom Enrichment Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25697895" target="_blank">Lee H. J., Lowdon R. F., Maricque B., Zhang B., Stevens M., et al. (2015) Developmental enhancers revealed by extensive DNA methylome maps of zebrafish early embryos. Nat Commun 6: 6315</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25928765" target="_blank">Martin T. C., Yet I., Tsai P. C. and Bell J. T. (2015) coMET: visualisation of regional epigenome-wide association scan results and DNA co-methylation patterns. BMC Bioinformatics 16: 131</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25691127" target="_blank">Elliott G., Hong C., Xing X., Zhou X., Li D., et al. (2015) Intermediate DNA methylation is a conserved signature of genome regulation. Nat Commun 6: 6363</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25690954" target="_blank">Gascard P., Bilenky M., Sigaroudinia M., Zhao J., Li L., et al. (2015) Epigenetic and transcriptional determinants of the human breast. Nat Commun 6: 6351</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26086966" target="_blank">Bose R., Spulber S., Kilian P., Heldring N., Lonnerberg P., et al. (2015) Tet3 mediates stable glucocorticoid-induced alterations in DNA methylation and Dnmt3a/Dkk1 expression in neural progenitors. Cell Death Dis 6: e1793</a></li>
</ol>

<h5>Methyl-Seq/MRE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/methyl-seq-mre-seq.png"></p>

<p>Methylation sensitive restriction enzyme sequencing MSRE/MRE-Seq or Methyl-Seq are protocols that use methylation sensitive restriction enzymes on genomic DNA to study DNA methylation. In this method, genomic DNA is first separately digested with different methylation sensitive restriction enzymes and then library prepped and sequenced. Deep sequencing allows for accurate detection of methylation sites in the genome.</p>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20613842">MRE-Seq: Maunakea A. K., Nagarajan R. P., Bilenky M., Ballinger T. J., D'Souza C., et al. (2010) Conserved role of intragenic DNA methylation in regulating alternative promoters. Nature 466: 253-257</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19273619">Methyl-Seq: Brunner A. L., Johnson D. S., Kim S. W., Valouev A., Reddy T. E., et al. (2009) Distinct DNA methylation patterns characterize differentiated human embryonic stem cells and developing human fetal liver. Genome Res 19: 1044-1056</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-nano-dna.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26301496" target="_blank">Chen K., Chen Z., Wu D., Zhang L., Lin X., et al. (2015) Broad H3K4me3 is associated with increased transcription elongation and enhancer activity at tumor-suppressor genes. Nat Genet</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25691127" target="_blank">Elliott G., Hong C., Xing X., Zhou X., Li D., et al. (2015) Intermediate DNA methylation is a conserved signature of genome regulation. Nat Commun 6: 6363</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25690954" target="_blank">Gascard P., Bilenky M., Sigaroudinia M., Zhao J., Li L., et al. (2015) Epigenetic and transcriptional determinants of the human breast. Nat Commun 6: 6351</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25697895" target="_blank">Lee H. J., Lowdon R. F., Maricque B., Zhang B., Stevens M., et al. (2015) Developmental enhancers revealed by extensive DNA methylome maps of zebrafish early embryos. Nat Commun 6: 6315</a></li>
</ol>

<h5>MIRA</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mira.png"></p>

<p>(MIRA) uses the high affinity of a methylated-CpG-binding protein complex (MBD2B and MBD3L1) to enrich regions with methylated CpG dinucleotides. This approach can be applied to both array-based DNA analysis and NGS sequencing, which are sometimes distinguished as MIRA-chip and MIRA-Seq.</p>
<p>In the MIRA procedure, the fragmented genomic DNA is incubated with purified GST-MBD2B and His-MBD3L1 proteins. The high affinity MBD2B/MBD3L1 complex binds to the methylated genomic DNA templates. The methylated genomic DNA fragments are captured on glutathione-coated magnetic beads. The enriched methylated DNA fraction is amplified, labeled and analyzed by NGS sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>High specificity and sensitivity requiring as little as 1ng input gDNA</li>
<li>Does not require DNA denaturation</li>
<li>Independent of restriction sites</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Resolution limited to 100 bases</li>
<li>It requires a minimum of two methylated CpGs in the captured fragment<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25798578">MIRA: Rauch T. A. and Pfeifer G. P. (2010) DNA methylation profiling using the methylated-CpG island recovery assay (MIRA). Methods 52: 213-217</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25977295">MIRA-ChIP: Jung M., Jin S. G., Zhang X., Xiong W., Gogoshin G., et al. (2015) Longitudinal epigenetic and gene expression profiles analyzed by three-component analysis reveal down-regulation of genes involved in protein translation in human aging. Nucleic Acids Res </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27009155">MIRA-Seq: Benjamin A. L., Green B. B., Crooker B. A., McKay S. D. and Kerr D. E. (2016) Differential responsiveness of Holstein and Angus dermal fibroblasts to LPS challenge occurs without major differences in the methylome. BMC Genomics 17: 258</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27056100">1. Rauch T. A. and Pfeifer G. P. (2011) Methods for Assessing Genome-wide DNA Methylation. 135-147</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27009155">Benjamin A. L., Green B. B., Crooker B. A., McKay S. D. and Kerr D. E. (2016) Differential responsiveness of Holstein and Angus dermal fibroblasts to LPS challenge occurs without major differences in the methylome. BMC Genomics 17: 258</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26384656">Jin S. G., Xiong W., Wu X., Yang L. and Pfeifer G. P. (2015) The DNA methylation landscape of human melanoma. Genomics 106: 322-330</a></li>
</ol>

<h5>oxBS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/oxbs-seq.png"></p>

<p>Oxidative bisulfite sequencing (oxBS-Seq) differentiates between 5mC and 5hmC. With oxBS, 5hmC is oxidized to 5formylcytosine (5fC) with an oxidizing agent, while 5mC remains unchanged. Sodium bisulfite treatment of oxidized 5hmC results in its deamination to uracil which, upon sequencing, is read as a thymidine. Deep sequencing of oxBS-treated DNA and sequence comparison of treated vs. untreated can identify 5mC locations at base resolution.</p>
<h6>Pros:</h6>
<ul>
<li>CpG and non-CpG methylation throughout the genmoe is covered at single-base resolution</li>
<li>5mC dense and less dense in repeat regions are covered</li>
<li>Method clearly differentiates between 5mC and 5hmC, precisely identifying 5mC</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Bisulfite converts unmethylated cytosines to thymidines, reducing sequence complexity, which can make it difficult to create alignments</li>
<li>SNPs where a cytosine is converted to thymidine will be missed upon bisulfite conversion<br>
</li>
</ul>

<h6>References:</h6>
<p>Methods Link:</p>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22539555">oxBS-Seq: Booth M. J., Branco M. R., Ficz G., Oxley D., Krueger F., et al. (2012) Quantitative sequencing of 5-methylcytosine and 5-hydroxymethylcytosine at single-base resolution. Science 336: 934-937</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><p>Product Links:</p>
<ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<div>Citations:</div>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24755596" target="_blank">Booth M. J., Marsico G., Bachman M., Beraldi D. and Balasubramanian S. (2014) Quantitative sequencing of 5-formylcytosine in DNA at single-base resolution. Nat Chem 6: 435-440</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24008380" target="_blank">Booth M. J., Ost T. W., Beraldi D., Bell N. M., Branco M. R., et al. (2013) Oxidative bisulfite sequencing of 5-methylcytosine and 5-hydroxymethylcytosine. Nat Protoc 8: 1841-1851</a></li>
</ol>

<h5>PBAT</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pbat.png"></p>

<p>To avoid the bisulfite-induced loss of intact sequencing templates, in post-bisulfite adapter tagging (PBAT) bisulfite treatment is followed by adapter tagging and two rounds of random primer extension. This procedure generates a substantial number of unamplified reads from as little as subnanogram quantities of DNA</p>
<h6>Pros:</h6>
<ul>
<li>Requires only 100 ng of DNA for amplification-free WGBS of mammalian genomes</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Bisulfite converts unmethylated cytosines to thymidines, reducing sequence complexity, which can make it difficult to create alignments</li>
<li>SNPs where a cytosine is converted to thymidine will be missed upon bisulfite conversion</li>
<li>Bisulfite conversion does not distingush between 5mC and 5hmC</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22649061">PBAT: Miura F., Enomoto Y., Dairiki R. and Ito T. (2012) Amplification-free whole-genome bisulfite sequencing by post-bisulfite adaptor tagging. Nucleic Acids Res 40: e136</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-nano-dna.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25732828" target="_blank">Farlik M., Sheffield N. C., Nuzzo A., Datlinger P., Schonegger A., et al. (2015) Single-cell DNA methylome sequencing and bioinformatic inference of epigenomic cell-state dynamics. Cell Rep 10: 1386-1397</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26046443" target="_blank">Guo F., Yan L., Guo H., Li L., Hu B., et al. (2015) The Transcriptome and DNA Methylome Landscapes of Human Primordial Germ Cells. Cell 161: 1437-1452</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25324297" target="_blank">Miura F. and Ito T. (2015) Highly sensitive targeted methylome sequencing by post-bisulfite adaptor tagging. DNA Res 22: 13-18</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25228647" target="_blank">Liu S., Brind'Amour J., Karimi M. M., Shirane K., Bogutz A., et al. (2014) Setdb1 is required for germline development and silencing of H3K9me3-marked endogenous retroviruses in primordial germ cells. Genes Dev 28: 2041-2055</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25501653" target="_blank">Okae H., Chiba H., Hiura H., Hamada H., Sato A., et al. (2014) Genome-wide analysis of DNA methylation dynamics during early human development. PLoS Genet 10: e1004868</a></li>
</ol>

<h5>RRBS-Seq/scRRBS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rrbs-seq-scrrbs.png"></p>

<p>Reduced-representation bisulfite sequencing (RRBS-Seq ) or single-cell reduced-representation bisulfite sequencing (scRRBS ) is a protocol that uses one or multiple restriction enzymes on the genomic DNA to produce sequence-specific fragmentation. The fragmented genomic DNA is then treated with bisulfite and sequenced. This is the method of choice to study specific regions of interest. It is particularly effective where methylation is high, such as in promoters and repeat regions.&nbsp;</p>
<h6>Pros:</h6>
<ul>
<li>Genome-wide coverage of CpGs in islands at single-base resolution</li>
<li>Areas dense in CpG methylation are covered</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Restriction enzymes cut at specific sites, providing biased sequence selection</li>
<li>Method measures 10-15% of all CpGs in genome</li>
<li>Cannot distinguish between 5mC and 5hmC</li>
<li>Does not cover non-CpG areas, genome-wide CpGs, and CpGs in areas without the enzyme restriction site</li>
</ul>

<h6>References:</h6>
<p>Methods Links:</p>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/16224102">RRBS: Meissner A., Gnirke A., Bell G. W., Ramsahoye B., Lander E. S., et al. (2005) Reduced representation bisulfite sequencing for comparative high-resolution DNA methylation analysis. Nucleic Acids Res 33: 5868-5877</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25837417">scRRBS: Guo H., Zhu P., Guo F., Li X., Wu X., et al. (2015) Profiling DNA methylome landscapes of mammalian cells with single-cell reduced-representation bisulfite sequencing. Nat Protoc 10: 645-659</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><div>Product Links:</div>
<ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<div>Citations:</div>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25837417" target="_blank">Guo H., Zhu P., Guo F., Li X., Wu X., et al. (2015) Profiling DNA methylome landscapes of mammalian cells with single-cell reduced-representation bisulfite sequencing. Nat Protoc 10: 645-659</a></li>
<li><a adhocenable="false" href="http://www.sciencedirect.com/science/article/pii/S2214784515300013" target="_blank">Hannon E., Chand A. N., Evans M. D., Wong C. C. Y., Grubb M. S., et al. A role for CaV1 and calcineurin signalling to depolarization-induced changes in neuronal DNA methylation. Neuroepigenetics &nbsp;</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25997618" target="_blank">Lin X., Stenvang J., Rasmussen M. H., Zhu S., Jensen N. F., et al. (2015) The potential role of Alu Y in the development of resistance to SN38 (Irinotecan) or oxaliplatin in colorectal cancer. BMC Genomics 16: 404</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26233891" target="_blank">Lee E.-J., Rath P., Liu J., Ryu D., Pei L., et al. Identification of Global DNA Methylation Signatures in Glioblastoma-Derived Cancer Stem Cells. Journal of Genetics and Genomics</a> &nbsp;</li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25943404" target="_blank">Yang Y., Sebra R., Pullman B. S., Qiao W., Peter I., et al. (2015) Quantitative and multiplexed DNA methylation analysis using long-read single-molecule real-time bisulfite sequencing (SMRT-BS). BMC Genomics 16: 350</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25990724" target="_blank">Zhang G., Esteve P. O., Chin H. G., Terragni J., Dai N., et al. (2015) Small RNA-mediated DNA (cytosine-5) methyltransferase 1 inhibition leads to aberrant DNA methylation. Nucleic Acids Res 43: 6112-6124</a></li>
</ol>

<h5>T-WGBS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/t-wgbs.png"></p>

<p>Tagmentation-based whole-genome bisulfite sequencing (T-WGBS) is a protocol that utilizes the Epicentre Tn5 transposome and bisulfite conversion to study 5mC . In this method, DNA is incubated with Tn5 transposome containing methylated primers, which fragments the DNA and ligates adapters. Tagged DNA first undergoes oligo displacement, followed by methylated oligo replacement and gap repair, assuring methylated adapter addition to tagmented DNA. DNA is then treated with sodium bisulfite, PCR-amplified, and sequenced. Deep sequencing provides single-base resolution of 5mC in the genome.</p>
<h6>Pros:</h6>
<ul>
<li>Can sequence samples with very limited starting material (~20 ng)</li>
<li>Fast protocol with few steps</li>
<li>Elimination of multiple steps prevents loss of DNA</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Bisulfite converts unmethylated cytosines to thymidines, reducing sequence complexity, which can make it difficult to create alignments</li>
<li>SNPs where a cytosine is converted to thymidine will be missed upon bisulfite conversion</li>
<li>Bisulfite conversion does not distinguish between 5mC and 5hmC</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24071908">T-WGBS: Wang Q., Gu L., Adey A., Radlwimmer B., Wang W., et al. (2013) Tagmentation-based whole-genome bisulfite sequencing. Nat Protoc 8: 2022-2032</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-nano-dna.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25158935" target="_blank">Cabezas-Wallscheid N., Klimmeck D., Hansson J., Lipka D. B., Reyes A., et al. (2014) Identification of regulatory networks in HSCs and their immediate progeny via integrated proteome, transcriptome, and DNA methylome analysis. Cell Stem Cell 15: 507-522</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24071908" target="_blank">Wang Q., Gu L., Adey A., Radlwimmer B., Wang W., et al. (2013) Tagmentation-based whole-genome bisulfite sequencing. Nat Protoc 8: 2022-2032</a></li>
</ol>

<h5>TAB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tab-seq.png"></p>

<p>TAB-Seq is a novel method that uses bisulfite conversion and Tet proteins to study 5hmC . In this protocol, 5hmC is first protected with a glucose moiety that allows selective interaction and subsequent oxidation of 5mC with the Tet proteins. The oxidized genomic DNA is then treated with bisulfite, where 5hmC remains unchanged and is read as a cytosine, while 5mC and unmethylated cytosines are deaminated to uracil and read as thymidines upon sequencing. Deep sequencing of TAB-treated DNA compared with untreated DNA provides accurate representation of 5hmC localization in the genome.&nbsp;</p>
<h6>Pros:</h6>
<ul>
<li>CpG and non-CpG hydroxymethylation throughout the genome is covered at single-base resolution</li>
<li>Dense, less dense, and 5hmC in repeat regions are covered</li>
<li>Method clearly differentiates between 5hmC and 5mC, specifically identifying 5hmC</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Bisulfite converts unmethylated cytosines to thymidines, reducing sequence complexity, which can make it difficult to create alignments</li>
<li>SNPs where a cytosine is converted to thymidine will be missed upon bisulfite conversion</li>
<li>Requires deep sequencing to provide sufficient depth to cover the entire genome and accurately map the low amounts of 5hmC</li>
</ul>

<h6>References:</h6>
<div>Methods Link:</div>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22608086" target="_blank">TAB-Seq: Yu M., Hon G. C., Szulwach K. E., Song C. X., Zhang L., et al. (2012) Base-resolution analysis of 5-hydroxymethylcytosine in the mammalian genome. Cell 149: 1368-1380</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><div>Product Links:</div>
<ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/microarray-kits/infinium-methylation-epic.html">Infinium MethylationEPIC Kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-dna-pcr-free.html" target="_blank">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<div>Citations:</div>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25762136" target="_blank">Gabel H. W., Kinde B., Stroud H., Gilbert C. S., Harmin D. A., et al. (2015) Disruption of DNA-methylation-dependent long gene repression in Rett syndrome. Nature 522: 89-93</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26046443" target="_blank">Guo F., Yan L., Guo H., Li L., Hu B., et al. (2015) The Transcriptome and DNA Methylome Landscapes of Human Primordial Germ Cells. Cell 161: 1437-1452</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25813045" target="_blank">Li Q., Suzuki M., Wendt J., Patterson N., Eichten S. R., et al. (2015) Post-conversion targeted capture of modified cytosines in mammalian and plant genomes. Nucleic Acids Res 43: e81</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25639471" target="_blank">Sun Z., Dai N., Borgaro J. G., Quimby A., Sun D., et al. (2015) A sensitive approach to map genome-wide 5-hydroxymethylcytosine and 5-formylcytosine at single-base resolution. Mol Cell 57: 750-761</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25179373" target="_blank">Nazor K. L., Boland M. J., Bibikova M., Klotzle B., Yu M., et al. (2014) Application of a low cost array-based technique - TAB-Array - for quantifying and mapping both 5mC and 5hmC at single base resolution in human pluripotent stem cells. Genomics 104: 358-367</a></li>
</ol>

### Proteomics

#### Protein-protein interaction
<h5>PD-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pd-seq.png"></p>

<p>Candidate cellular protein target identification (PD-Seq)&nbsp; is a protocol that can detect protein-protein interactions. In this method, apigenin is coupled to amino polyethyleneglycol-polyacrylamide copolymer beads (PEGA beads) after activation with 4-nitro-phenyl bromoacetate. The apigenin-loaded beads are used for screening phage display cDNA library generated from human breast cancer tumor cells mRNA. After three rounds, the fractions are used to make libraries and sequenced on the Illumina platform.</p>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23697369" target="_blank">PD-Seq: Arango D. et al. (2013) Molecular basis for the action of a dietary flavonoid revealed by the comprehensive identification of apigenin human targets. Proc Natl Acad Sci U S A 110: E2153-2162</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/23697369" target="_blank">Arango D., Morohashi K., Yilmaz A., Kuramochi K., Parihar A., et al. (2013) Molecular basis for the action of a dietary flavonoid revealed by the comprehensive identification of apigenin human targets. Proc Natl Acad Sci U S A 110: E2153-2162</a></li>
</ol>

<h5>ProP-PD/PDZ-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/prop-pd-pdz-seq.png"></p>

<p>Proteomic peptide-phage display (ProP-PD) is a protocol that identifies short linear motif (SLiM) interactions or PDZ domains (PDZ-Seq ). In this method, C-terminal sequences are first identified, an oligo library is created, followed by construction of a phage display library, which is hybridized to immobilized bait proteins. Sequences of display phages that interact with the bait protein are isolated, sequenced and counted. Deep sequencing provides detailed information pertaining to the motifs that interact with specific proteins.</p>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24550280">ProP-PD: Ivarsson Y., Arnold R., McLaughlin M., Nim S., Joshi R., et al. (2014) Large-scale interaction profiling of PDZ domains through proteomic peptide-phage display using human and viral phage peptidomes. Proc Natl Acad Sci U S A 111: 2542-2547</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20714644">PDZ-Seq: Ernst A., Gfeller D., Kan Z., Seshagiri S., Kim P. M., et al. (2010) Coevolution of PDZ domain-ligand interactions analyzed by high-throughput phage display and deep sequencing. Mol Biosyst 6: 1782-1790</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24550280" target="_blank">Ivarsson Y., Arnold R., McLaughlin M., Nim S., Joshi R., et al. (2014) Large-scale interaction profiling of PDZ domains through proteomic peptide-phage display using human and viral phage peptidomes. Proc Natl Acad Sci U S A 111: 2542-2547</a></li>
</ol>

### Transcriptome

#### RNA low level detection

<h5>Act-Seq</h5>

<div class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/act-seq.png"></div>

<p>Act-Seq minimizes artificially induced transcriptional perturbations common in scRNA-Seq workflows. This is achieved by immediately treating dissociated cells with actinomycin D (actD), a transcription inhibitor of all three eukaryotic RNA polymerases. Authors showed that actD treatment is especially important in inhibiting dissociation-induced immediate-early genes (IEGs) activation that are often seen in scRNA-Seq experiments using conventional dissociation methods. scRNA-Seq of individual cells are assayed using the Drop-Seq method. This method is ideal for interrogating acute transcriptional changes upon external stimuli.</p>
<p>Published: October 2017</p>
<h6>Pros:</h6>
<ul>
<li>Ideal for cell types with low RNA content or where cytoplasmic RNA capture is crucial</li>
<li>Eliminates activation of gene expression induced by cell dissociation</li>
<li>Not reliant on flow-sorting of nuclei after immunostaining</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires custom microfluidics system (Drop-Seq)</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/29024657" target="_blank">Act-Seq: Wu YE, Pan L, Zuo Y, Li X and Hong W. Detecting Activated Cell Populations Using Single-Cell RNA-Seq. Neuron. 2017;96:313-329.e316</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera-dna.html">Nextera DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h5>CEL-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cel-seq.png"></p>

<p>CEL-Seq uses barcoding and pooling of RNA to overcome challenges from low input.  In this method, each cell undergoes RT with a unique barcoded primer in its individual tube. After second-strand synthesis, cDNAs from all reaction tubes are pooled and PCR-amplified. Paired-end deep sequencing of the PCR products allows for accurate detection of sequence information derived from both strands.
</p><p>Similar methods: CEL-Seq2, Quartz-Seq, Drop-seq, MARS-Seq, CytoSeq, inDrop, Hi-SCL</p>
<h6>Pros:</h6>
<ul>
<li>Barcoding and pooling allow for multiplexing and studying many different single cells at a time</li>
<li>Cross-contamination is greatly reduced due to using 1 tube per cell</li>
<li>Fewer steps than single-cell tagged reverse-transcription sequencing (STRT-Seq)</li>
<li>Very little read-length bias </li>
<li>Strand-specific</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Strongly 3' biased<sup>1</sup> </li>
<li>Abundant transcripts are amplified preferentially</li>
<li>Requires at least 400 pg of total RNA</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22939981">CEL-Seq: Hashimshony T., Wagner F., Sher N. and Yanai I. (2012) CEL-Seq: single-cell RNA-Seq by multiplexed linear amplification. Cell Rep 2: 666-673</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23897237" target="_blank">1. Shapiro E., Biezuner T. and Linnarsson S. Single-cell sequencing-based technologies will revolutionize whole-organism science. Nat Rev Genet. 2013;14:618-630</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26941284" target="_blank">Zhang X., Marjani S. L., Hu Z., Weissman S. M., Pan X., et al. Single-Cell Sequencing for Precise Cancer Research: Progress and Prospects. Cancer Res. 2016;76:1305-1312</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26544934" target="_blank">Grun D. and van Oudenaarden A. Design and Analysis of Single-Cell Sequencing Experiments. Cell. 2015;163:799-810</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000846" target="_blank">Kolodziejczyk A. A., Kim J. K., Svensson V., Marioni J. C. and Teichmann S. A. The Technology and Biology of Single-Cell RNA Sequencing. Mol Cell. 2015;58:610-620</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25438696" target="_blank">Liang J., Cai W. and Sun Z. Single-Cell Sequencing Technologies: Current and Future. J Genet Genomics. 2014;41:513-528</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26886793" target="_blank">Levin M., Anavy L., Cole A. G., et al. The mid-developmental transition and the evolution of animal body plans. Nature. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27705792" target="_blank">Seillet C., Mielke L. A., Amann-Zalcenstein D. B., et al. Deciphering the Innate Lymphoid Cell Transcriptional Program. Cell Rep. 2016;17:436-447</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27347753" target="_blank">Mooijman D., Dey S. S., Boisset J. C., Crosetto N. and van Oudenaarden A. Single-cell 5hmC sequencing reveals chromosome-wide cell-to-cell variability and enables lineage reconstruction. Nat Biotechnol. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26524239" target="_blank">Thomsen E. R., Mich J. K., Yao Z., et al. Fixed single-cell transcriptomic characterization of human radial glial diversity. Nat Methods. 2016;13:87-93</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26287467" target="_blank">Grun D., Lyubimova A., Kester L., et al. Single-cell messenger RNA sequencing reveals rare intestinal cell types. Nature. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000487" target="_blank">Klein A. M., Mazutis L., Akartuna I., et al. Droplet barcoding for single-cell transcriptomics applied to embryonic stem cells. Cell. 2015;161:1187-1201</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24747814" target="_blank">Grun D., Kester L. and van Oudenaarden A. Validation of noise models for single-cell transcriptomics. Nat Methods. 2014;11:637-640</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24419370" target="_blank">Bhargava V., Head S. R., Ordoukhanian P., Mercola M. and Subramaniam S. Technical variations in low-input RNA-seq methodologies. Sci Rep. 2014;4:3678</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25487147" target="_blank">Hashimshony T., Feder M., Levin M., Hall B. K. and Yanai I. Spatiotemporal transcriptomics reveals the evolutionary history of the endoderm germ layer. Nature. 2014;</a></li>
</ol>

<h5>CirSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cirseq.png"></p>

<p>CirSeq accurately identifies ultra-rare and low-frequency genetic variants in RNA viruses. The method uses a unique step for circularization of fragmented viral RNAs, followed by rolling-circle RT. ,   CirSeq corrects for mutations introduced during its amplification steps by aligning the tandem-repeat sequences with each other and excluding those reads using informatics tools.
First, single-stranded RNAs are fragmented using Zn<sup>2+</sup> and size-selected to no more than one-third of the sequencing read length. Next, they are circularized and reverse-transcribed using random primers. Rolling-circle RT is used to generate tandem-repeat cDNA strands. The first-strand cDNAs are amplified, generating double-stranded cDNAs, followed by end repair, poly(A) tailing, and adapter ligation. The cDNA libraries are ready for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Detects ultra-rare and low-frequency genetic variants in RNA viruses</li>
<li>Rolling-circle RT creates tandem-repeat cDNAs that can be used to correct artificial mutations</li>
<li>Error rates reported are far below those observed using standard RNA virus sequencing methods</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Whole process takes ~5 days</li>
<li>Unsuitable for sequencing clinical isolates, because it needs large quantities of purified viral RNAs</li>
<li>Not applicable for de novo sequencing of viral RNAs</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24284629" target="_blank">CirSeq: Acevedo A., Brodsky L. and Andino R. Mutational and fitness landscapes of an RNA virus revealed through population sequencing. Nature. 2014;505:686-690</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24967624" target="_blank">CirSeq Protocol: Acevedo A. and Andino R. Library preparation for highly accurate population sequencing of RNA viruses. Nat Protoc. 2014;9:1760-1769</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27693290" target="_blank">Posada-Cespedes S., Seifert D. and Beerenwinkel N. Recent advances in inferring viral diversity from high-throughput sequencing data. Virus Res. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25824477" target="_blank">Andino R. and Domingo E. Viral quasispecies. Virology. 2015;479-480C:46-51</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25637723" target="_blank">Gordon A. J., Satory D., Halliday J. A. and Herman C. Lost in transcription: transient errors in information transfer. Curr Opin Microbiol. 2015;24C:80-87</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24284629" target="_blank">Acevedo A., Brodsky L. and Andino R. Mutational and fitness landscapes of an RNA virus revealed through population sequencing. Nature. 2014;505:686-690</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26960407" target="_blank">Wang K., Ma Q., Jiang L., et al. Ultra-precise detection of mutations by droplet-based amplification of circularized DNA. BMC Genomics. 2016;17:214</a></li>
</ol>

<h5>CLaP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/clap.png"></p>

<p>CLaP is a noninvasive, laser-based labeling technique for single cells.  The method uses lasers to crosslink specific cells with fluorescent tags before isolating individual cells for sequencing.</p><p>
In CLaP, cells of interest are tagged by crosslinking biotin-4-fluorescein (B4F) to the cell membrane with laser irradiation. Next, streptavidin-conjugated fluorescent labels are bound to biotinylated cells. These steps can be repeated to tag multiple cell types with a variety of fluorescent tags. The tagged cells are subsequently isolated and processed to generate cDNA libraries for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Noninvasive, targeted, laser-based single-cell labeling</li>
<li>Enables automated, image-based cell selection</li>
<li>Fluorescence-based tags can be substituted with other labels, such as electron-dense molecules</li>
<li>Multicolored fluorescent stains can be used</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Diffusion of reagents through the extracellular matrix and continuous laser illumination limit the procedure for 3-dimensional environments/tissues</li>
<li>Cellular specificity may be decreased slightly in primary cell cultures.</li>
<li>Image-based selection limits the potential for high-throughput applications</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27198043">CLaP: Binan L., Mazzaferri J., Choquet K., Lorenzo L. E., Wang Y. C., et al. (2016) Live single-cell laser tag. Nat Commun 7: 11636</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27757061" target="_blank">Gurwitz D. Human iPSC-derived neurons and lymphoblastoid cells for personalized medicine research in neuropsychiatric disorders. Dialogues Clin Neurosci. 2016;18:267-276</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27198043">Binan L., Mazzaferri J., Choquet K., Lorenzo L. E., Wang Y. C., et al. (2016) Live single-cell laser tag. Nat Commun 7: 11636</a></li>
</ol>

<h5>CytoSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cytoseq.png"></p>

<p>CytoSeq enables gene expression profiling of thousands of single cells.  In this method, single cells are randomly deposited into wells. A combinatorial library of beads with specific capture probes is added to each well. After cell lysis, mRNAs hybridize the to beads, which are pooled subsequently for RT, amplification, and sequencing. Deep sequencing provides accurate, high-coverage gene expression profiles of several single cells.
</p><p>Similar methods: CEL-Seq, Quartz-Seq, MARS-Seq, inDrop, Hi-SCL.</p>
<h6>Pros:</h6>
<ul>
<li>Can readily scale to 10,000s or 100,000s of cells</li>
<li>Complements and expands the capabilities of fluorescence or mass spectrometry–based cytometry</li>
<li>Detects any transcribed mRNA without the limitations of antibody availability</li>
<li>Enables rare cell characterization on small samples with insufficient cells for traditional flow cytometry</li>
<li>Allows direct analysis of complex samples of heterogeneous cell size and shape</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Sequencing depth requires large number of reads (eg, 200,000 transcripts per cell requires 2 million reads for 10X coverage: 2 billion reads for 1000 cells)</li>
<li>Single run can be relatively expensive and time-consuming</li>
<li>Trade-off between depth of sequencing and differential gene expression</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25657253" target="_blank">CytoSeq: Fan H. C., Fu G. K. and Fodor S. P. (2015) Expression profiling. Combinatorial labeling of single cells for gene expression cytometry. Science 347: 1258367</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.cell.com/trends/biotechnology/fulltext/S0167-7799(16)30162-7" target="_blank">Friedensohn S., Khan T. A. and Reddy S. T. Advanced Methodologies in High-Throughput Sequencing of Immune Repertoires. Trends in Biotechnology. 2017;35:203-214</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000846" target="_blank">Kolodziejczyk A. A., Kim J. K., Svensson V., Marioni J. C. and Teichmann S. A. The Technology and Biology of Single-Cell RNA Sequencing. Mol Cell. 2015;58:610-620</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26450340" target="_blank">Saadatpour A., Lai S., Guo G. and Yuan G. C. Single-Cell Analysis in Cancer Genomics. Trends Genet. 2015;31:576-586</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25657253" target="_blank">Fan H. C., Fu G. K. and Fodor S. P. (2015) Expression profiling. Combinatorial labeling of single cells for gene expression cytometry. Science 347: 1258367</a></li>
</ol>

<h5>Digital RNA</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/digital-rna.png"></p>

<p>Digital RNA sequencing is an approach to RNA-Seq that removes sequence-dependent PCR amplification biases by barcoding the RNA molecules before amplification.  RNA is reverse-transcribed to cDNA, and an excess of adapters, each with a unique barcode, is added to the preparation. This barcoded cDNA is amplified and sequenced. Deep sequencing reads are compared, and the barcodes are used to determine the actual distribution of RNA abundance.</p>
<h6>Pros:</h6>
<ul>
<li>Low amplification bias during PCR</li>
<li>Provides information about abundance of RNA</li>
<li>Detection of low-copy–number RNA</li>
<li>Single-copy resolution</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Some amplification bias still persists</li>
<li>Barcodes may miss targets during ligation</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22232676" target="_blank">Digital RNA: Shiroguchi K., Jia T. Z., Sims P. A. and Xie X. S. (2012) Digital RNA sequencing minimizes sequence-dependent bias and amplification noise with optimized single-molecule barcodes. Proc Natl Acad Sci U S A 109: 1347-1352</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li>This method has been widely integrated into various sequencing techniques due to its high versatility.</li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22232676" target="_blank">Digital RNA: Shiroguchi K., Jia T. Z., Sims P. A. and Xie X. S. (2012) Digital RNA sequencing minimizes sequence-dependent bias and amplification noise with optimized single-molecule barcodes. Proc Natl Acad Sci U S A 109: 1347-1352</a></li>
</ol>

<h5>Div-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/div-seq.png"></p>

<p>Div-Seq is a single-nucleus RNA sequencing technique that improves upon Nuc-Seq by incorporating 5-ethynyl-2’-deoxyuridine (EdU) labeling to identify dividing cells during their different cell stages. EdU labeling also enables identification of different cell types in complex tissue samples and rare cell populationsduring FACS. Briefly, samples are labeled in vivo with EdU, dissected, and fixed before isolation into single nuclei. Individual nuclei are tagged fluorescently and sorted by FACS. From this step, the procedure follows the Nuc-Seq method: cDNA synthesis is performed using the Smart-seq2 protocol, while the cDNA library is prepared with Tn5 transposase–mediated tagmentation.</p>
<p>Similar methods: Nuc-seq, snRNA-seq</p>
<h6>Pros:</h6>
<ul>
<li>Tracks transcriptome dynamics in single nuclei</li>
<li>Detects rare cell populations </li>
<li>Compatible with fresh, frozen, or fixed sample types</li>
<li>EdU labeling gives unbiased identification of different types of dividing cells and their current stage in the cell cycle</li>
<li>	Mild nuclear dissociation technique minimizes gene expression changes commonly seen in protease-mediated dissociation</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Excludes any information from cytoplasmic RNA</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27471252" target="_blank">Div-Seq: Habib N., Li Y., Heidenreich M., et al. Div-Seq: Single-nucleus RNA-Seq reveals dynamics of rare adult newborn neurons. Science. 2016;353:925-928</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row">
<div class="col-sm-6">
<ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27824854" target="_blank">Wagner A., Regev A. and Yosef N. Revealing the vectors of cellular identity with single-cell genomics. Nat Biotechnol. 2016;34:1145-1160</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27814520" target="_blank">Goncalves J. T., Schafer S. T. and Gage F. H. Adult Neurogenesis in the Hippocampus: From Stem Cells to Behavior. Cell. 2016;167:897-914</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27471252" target="_blank">Habib N., Li Y., Heidenreich M., et al. Div-Seq: Single-nucleus RNA-Seq reveals dynamics of rare adult newborn neurons. Science. 2016;353:925-928</a></li>
</ol>

<h5>DP-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/dp-seq.png"></p>

<p>DP-Seq amplifies mRNA from limited starting material, as low as 50 pg.  In this method, a specific set of heptamer primers is designed. The enriched poly(A)-selected mRNA undergoes first-strand cDNA synthesis. Next, the designed primers are hybridized to the first-strand cDNA, followed by second-strand synthesis and PCR. Deep sequencing of the amplified DNA allows for accurate detection of specific mRNA expression at the single-cell level.</p>
<h6>Pros:</h6>
<ul>
<li>As little as 50 pg of starting material can be used</li>
<li>Little transcript-length bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>The sequences of the target areas must be known to design the heptamers</li>
<li>Exponential amplification during PCR can lead to primer-dimers and spurious PCR products</li>
<li>Some read-length bias</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23624976" target="_blank">DP-Seq: Bhargava V., Ko P., Willems E., Mercola M. and Subramaniam S. (2013) Quantitative transcriptomics using designed primer-based amplification. Sci Rep 3: 1740</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html" target="_blank">Nextera XT DNA Library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25961929" target="_blank">Friedmann-Morvinski D., Bhargava V., Gupta S., Verma I. M. and Subramaniam S. Identification of therapeutic targets for glioblastoma by network analysis. Oncogene. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000846" target="_blank">Kolodziejczyk A. A., Kim J. K., Svensson V., Marioni J. C. and Teichmann S. A. The Technology and Biology of Single-Cell RNA Sequencing. Mol Cell. 2015;58:610-620</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24502796" target="_blank">Head S. R., Komori H. K., LaMere S. A., et al. Library construction for next-generation sequencing: overviews and challenges. Biotechniques. 2014;56:61-64, 66, 68, passim</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24419370" target="_blank">Bhargava V., Head S. R., Ordoukhanian P., Mercola M. and Subramaniam S. (2014) Technical variations in low-input RNA-seq methodologies. Sci Rep 4: 3678</a></li>
</ol>

<h5>Drop-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/drop-seq.png"></p>

<p>Drop-Seq analyzes mRNA transcripts from droplets of individual cells in a highly parallel fashion.  
This single-cell sequencing method uses a microfluidic device to compartmentalize droplets containing a single cell, lysis buffer, and a microbead covered with barcoded primers. Each primer contains: 1) a 30 bp oligo(dT) sequence to bind mRNAs; 2) an 8 bp molecular index to identify each mRNA strand uniquely; 3) a 12 bp barcode unique to each cell and 4) a universal sequence identical across all beads. Following compartmentalization, cells in the droplets are lysed and the released mRNA hybridizes to the oligo(dT) tract of the primer beads. Next, all droplets are pooled and broken to release the beads within. After the beads are isolated, they are reverse-transcribed with template switching. This generates the first cDNA strand with a PCR primer sequence in place of the universal sequence. cDNAs are PCR-amplified, and sequencing adapters are added using the Nextera XT Library Preparation Kit. The barcoded mRNA samples are ready for sequencing.
</p><p>Similar methods: CEL-Seq, Quartz-Seq, MARS-Seq, CytoSeq, inDrop, Hi-SCL.</p>
<h6>Pros:</h6>
<ul>
<li>Analyze sequences of single-cells in a highly parallel manner</li>
<li>Unique molecular and cell barcodes enables cell and gene specific identification of mRNA strands</li>
<li>Reverse transcription with template-switching PCR produce high-yield reads from single cells</li>
<li>Low cost - $0.07 per cell ($653 per 10,000 cells) and fast library prep (10,000 cells per day)</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires custom microfluidics device to perform droplet separation</li>
<li>Low gene-per-cell sensitivity compared to other scRNA-Seq methods<sup>1</sup></li>
<li>Limited to mRNA transcripts</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000488" target="_blank">Drop-Seq: Macosko E. Z., Basu A., Satija R., Nemesh J., Shekhar K., et al. (2015) Highly Parallel Genome-wide Expression Profiling of Individual Cells Using Nanoliter Droplets. Cell 161: 1202-1214</a></li>
<li><a href="http://biorxiv.org/content/early/2016/01/05/035758" target="_blank">1. Ziegenhain C., Parekh S., Vieth B., Smets M., Leonhardt H., et al. (2016) Comparative analysis of single-cell RNA-sequencing methods. bioRxiv</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26795869" target="_blank">Bowen J. R., Ferris M. T. and Suthar M. S. Systems biology: A tool for charting the antiviral landscape. Virus Res. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27297499" target="_blank">Chaitankar V., Karakulah G., Ratnapriya R., Giuste F. O., Brooks M. J. and Swaroop A. Next generation sequencing technology and genomewide data analysis: Perspectives for retinal research. Prog Retin Eye Res. 2016;</a></li>
<li><a href="link.springer.com/article/10.1007/s40484-016-0060-7" target="_blank">Zhao Q.-Y., Gratten J., Restuadi R. and Li X. Mapping and differential expression analysis from short-read RNA-Seq data in model organisms. Quantitative Biology. 2016;4:22-35</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26813401" target="_blank">Conesa A., Madrigal P., Tarazona S., Gomez-Cabrero D., Cervera A., et al. A survey of best practices for RNA-seq data analysis. Genome Biol. 2016;17:13</a></li>
<li><a href="http://www.cell.com/trends/biotechnology/fulltext/S0167-7799(16)30162-7" target="_blank">Friedensohn S., Khan T. A. and Reddy S. T. Advanced Methodologies in High-Throughput Sequencing of Immune Repertoires. Trends in Biotechnology. 2017;35:203-214</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27571192" target="_blank">Poulin J. F., Tasic B., Hjerling-Leffler J., Trimarchi J. M. and Awatramani R. Disentangling neural cell diversity using single-cell transcriptomics. Nat Neurosci. 2016;19:1131-1141</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26544934" target="_blank">Grun D. and van Oudenaarden A. Design and Analysis of Single-Cell Sequencing Experiments. Cell. 2015;163:799-810</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26450340" target="_blank">Saadatpour A., Lai S., Guo G. and Yuan G. C. Single-Cell Analysis in Cancer Genomics. Trends Genet. 2015;31:576-586</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26248267" target="_blank">Alizadeh A. A., Aranda V., Bardelli A., et al. Toward understanding and exploiting tumor heterogeneity. Nat Med. 2015;21:846-853</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://biorxiv.org/content/biorxiv/early/2016/01/05/035758.full.pdf" target="_blank">Ziegenhain C., Parekh S., Vieth B., et al. Comparative analysis of single-cell RNA-sequencing methods. bioRxiv. 2016;</a></li>
</ol>

<h5>FRISCR</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/friscr.png"></p>

<p>FRISCR characterizes transcriptome profiles from fixed and stained single cells.  The method uses a combination of molecular barcodes and Tn5 tagmentation to identify each cDNA fragment uniquely from every cell.
</p><p>The cell suspension is fixed with paraformaldehyde, permeabilized, and immunostained. Individual cells are sorted into tubes by FACS. These cells are lysed and reverse-crosslinked by incubation at 56°C for 1 hour. mRNA from the cells is isolated by dT25 magnetic bead pull-down. The mRNA sequencing library is prepared according to the Smart-seq2 procedure: 1) template-switching RT with Moloney murine leukemia virus reverse transcriptase; 2) the resulting cDNAs are PCR amplified; and 3) the cDNA library is generated using the Nextera XT Library Preparation Kit. The cDNA fragments are flanked with adapters and are ready for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Full-length mRNA transcriptome profiling from fixed and stained single-cells</li>
<li>Immunostaining enables targeting of rare cell populations</li>
<li>Generate full-length mRNA reads</li>
<li>Significantly more mRNA recovered compared to fixed cells from Triton-X100 lysis</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>3' to 5' bias</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26524239" target="_blank">FRISCR: Thomsen E. R., Mich J. K., Yao Z., Hodge R. D., Doyle A. M., et al. (2016) Fixed single-cell transcriptomic characterization of human radial glial diversity. Nat Methods 13: 87-93</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27083874" target="_blank">Wen L. and Tang F. Single-cell sequencing in stem cell biology. Genome Biol. 2016;17:71</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
Thomsen E. R., Mich J. K., Yao Z., Hodge R. D., Doyle A. M., et al. (2016) Fixed single-cell transcriptomic characterization of human radial glial diversity. Nat Methods 13: 87-93</ol>

<h5>G&amp;T-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/g-t-seq.png"></p>

<p>G&T-Seq can separate and sequence genomic DNA and full-length mRNA from single cells.  In this method, single cells are isolated and lysed. RNA is captured using biotinylated oligo(dT) capture primers and separated from DNA using streptavidin-coated magnetic beads. Smart-seq2 is used to amplify captured RNA on the bead, while multiple displacement amplification (MDA) is used to amplify DNA. After sequencing, integrating the DNA and RNA sequences provides insights into the gene expression profiles of single cells.</p>
<h6>Pros:</h6>
<ul>
<li>Compatible with any whole-genome amplification method</li>
<li>No 3'-end bias in sequence reads because full-length transcripts are captured</li>
<li>Because DNA and RNA are physically separated and amplified independently, there is no need to mask coding sequences during analysis</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Physical separation of DNA and RNA can increase the risk of sample loss or contamination</li>
<li>Physical separation of DNA and RNA increases handling time</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25915121">G&amp;T-Seq: Macaulay I. C., Haerty W., Kumar P., Li Y. I., Hu T. X., et al. (2015) G&amp;T-seq: parallel sequencing of single-cell genomes and transcriptomes. Nat Methods 12: 519-522</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27212022" target="_blank">Bock C., Farlik M. and Sheffield N. C. Multi-Omics of Single Cells: Strategies and Applications. Trends Biotechnol. 2016;34:605-608</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27091476" target="_blank">Clark S. J., Lee H. J., Smallwood S. A., Kelsey G. and Reik W. Single-cell epigenomics: powerful new methods for understanding gene regulation and cell identity. Genome Biol. 2016;17:72</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26941284" target="_blank">Zhang X., Marjani S. L., Hu Z., Weissman S. M., Pan X., et al. Single-Cell Sequencing for Precise Cancer Research: Progress and Prospects. Cancer Res. 2016;76:1305-1312</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27412011" target="_blank">Vieira Braga F. A., Teichmann S. A. and Chen X. Genetics and immunity in the era of single-cell genomics. Hum Mol Genet. 2016;25:R141-R148</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27272212" target="_blank">Lu L., Lv B., Huang K., Xue Z., Zhu X. and Fan G. Recent advances in preimplantation genetic diagnosis and screening. J Assist Reprod Genet. 2016;33:1129-1134</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26752769" target="_blank">Angermueller C., Clark S. J., Lee H. J., et al. Parallel single-cell sequencing links transcriptional and epigenetic heterogeneity. Nat Methods. 2016;13:229-232</a></li>
</ol>

<h5>Hi-SCL</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/hi-scl.png"></p>

<p>Hi-SCL generates transcriptome profiles for thousands of single cells using a custom microfluidics system, similar to Drop-Seq and inDrop.  
</p><p>Single cells from cell suspension are isolated into droplets containing lysis buffer. After cell lysis, cell droplets are fused with a droplet containing cell-specific barcodes and another droplet with enzymes for RT. The droplets from all the wells are pooled and subjected to isothermal reactions for RT. The barcodes anneal to poly(A)+ mRNAs and act as primers for reverse transcriptase. Now that each mRNA strand has cell-specific barcodes, the droplets are broken, and the cDNA is purified. The 3' ends of the cDNA strands are ligated to adapters, amplified, annealed to indexed primers, and amplified further before sequencing.
</p><p>Similar methods: CEL-Seq, Drop-seq, MARS-Seq, CytoSeq, inDrop, Quartz-Seq.</p>
<h6>Pros:</h6>
<ul>
<li>High throughput single-cell transcriptome profiling using a microfluidics system</li>
<li>Low cost - $0.1 per cell (for experiment with 100 cells)</li>
<li>Highly scalable to larger cell quantities</li>
<li>No fragmentation step</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Lack of Unique Molecular Identifier (UMI) in oligonucleotides may create amplification noise</li>
<li>Droplets may contain 2 cells or 2 different types of barcodes</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000628" target="_blank">Hi-SCL: Rotem A., Ram O., Shoresh N., Sperling R. A., Schnall-Levin M., et al. (2015) High-Throughput Single-Cell Labeling (Hi-SCL) for RNA-Seq Using Drop-Based Microfluidics. PLoS One 10: e0116328</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26594792" target="_blank">Mato Prado M., Frampton A. E., Stebbing J. and Krell J. Single-cell sequencing in cancer research. Expert Rev Mol Diagn. 2016;16:1-5</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
Rotem A., Ram O., Shoresh N., Sperling R. A., Schnall-Levin M., et al. (2015) High-Throughput Single-Cell Labeling (Hi-SCL) for RNA-Seq Using Drop-Based Microfluidics. PLoS One 10: e0116328</ol>

<h5>inDrop</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/indrop.png"></p>

<p>inDrop is used for high-throughput single-cell labeling.  This approach is similar to Drop-seq, but it uses hydrogel microspheres to introduce the oligonucleotides.
</p><p>Single cells from a cell suspension are isolated into droplets containing lysis buffer. After cell lysis, cell droplets are fused with a hydrogel microsphere containing cell-specific barcodes and another droplet with enzymes for RT. Droplets from all the wells are pooled and subjected to isothermal reactions for RT. The barcodes anneal to poly(A)+ mRNAs and act as primers for reverse transcriptase. Now that each mRNA strand has cell-specific barcodes, the droplets are pooled and broken, and the cDNA is purified. The 3' ends of the cDNA strands are ligated to adapters, amplified, annealed to indexed primers, and amplified further before sequencing.
</p><p>Similar methods: CEL-Seq, Drop-seq, MARS-Seq, CytoSeq, Quartz-Seq, Hi-SCL.</p>
<h6>Pros:</h6>
<ul>
<li>High throughput single-cell transcriptome profiling using microfluidics system</li>
<li>Highly scalable to larger cell quantities</li>
<li>No fragmentation step</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Low mRNA capture efficiency of ~7%</li>
<li>Droplets may contain two cells or two different types of barcodes</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26000487">inDrop: Klein A. M., Mazutis L., Akartuna I., Tallapragada N., Veres A., et al. (2015) Droplet barcoding for single-cell transcriptomics applied to embryonic stem cells. Cell 161: 1187-1201</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27318512" target="_blank">Bian Q. and Cahan P. Computational Tools for Stem Cell Biology. Trends Biotechnol. 2016;</a></li>
<li><a href="link.springer.com/article/10.1007/s40484-016-0060-7" target="_blank">Zhao Q.-Y., Gratten J., Restuadi R. and Li X. Mapping and differential expression analysis from short-read RNA-Seq data in model organisms. Quantitative Biology. 2016;4:22-35</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26544934" target="_blank">Grun D. and van Oudenaarden A. Design and Analysis of Single-Cell Sequencing Experiments. Cell. 2015;163:799-810</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26450340" target="_blank">Saadatpour A., Lai S., Guo G. and Yuan G. C. Single-Cell Analysis in Cancer Genomics. Trends Genet. 2015;31:576-586</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27470110" target="_blank">Derr A., Yang C., Zilionis R., et al. End Sequence Analysis Toolkit (ESAT) expands the extractable information from single-cell RNA-seq data. Genome Res. 2016;26:1397-1410</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000487" target="_blank">Klein A. M., Mazutis L., Akartuna I., Tallapragada N., Veres A., et al. Droplet barcoding for single-cell transcriptomics applied to embryonic stem cells. Cell. 2015;161:1187-1201</a></li>
</ol>

<h5>MARS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mars-seq.png"></p>

<p>MARS-Seq profiles the transcriptional dynamics of single cells in an automated and massively parallel workflow with high resolution. MARS-Seq can be used with in vivo samples containing a wide variety of different cell subpopulations. Single cells are first isolated into individual wells using FACS. Each cell is lysed, and the 3' ends of mRNAs are annealed to unique molecular identifiers containing a T7 promoter. The mRNA is reverse-transcribed to generate the first cDNA strand and treated with exonuclease I to remove leftover RT primers. Next, the cellular lysates are pooled together and converted to double-stranded cDNA. The DNA strands are transcribed to RNA and treated with DNase to remove leftover DNA templates in the mixture. The RNA strands are fragmented and annealed to sequencing adapters, followed by RT to generate barcoded cDNA libraries that are ready for sequencing.</p>
<p>Similar methods: CEL-Seq, Quartz-Seq, Drop-seq, CytoSeq, inDrop.</p>
<h6>Pros:</h6>
<ul>
<li>High-throughput transcriptional profiling of single cells</li>
<li>In vivo sampling of thousands of cells</li>
<li>Three barcode levels (molecular, cellular, and plate-level tags) facilitate robust multiplexing capabilities</li>
<li>Processes 100 to 1000 single cells </li>
<li>Pooling all single cells into 1 flow cell reduces the cost to less than 50 cents per cell<sup>1</sup> </li>
</ul>
<h6>Cons:</h6>
<ul>
<li>3' bias can occur during the purification step</li>
<li>Fragmentation step eliminates strand-specific information<sup>2</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24531970" target="_blank">MARS-Seq: Jaitin D. A., Kenigsberg E., Keren-Shaul H., et al. Massively parallel single-cell RNA-seq for marker-free decomposition of tissues into cell types. Science. 2014;343:776-779</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25727184" target="_blank">1. Jaitin D. A., Keren-Shaul H., Elefant N. and Amit I. Each cell counts: Hematopoiesis and immunity research in the era of single cell genomics. Semin Immunol. 2015;27:67-71</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27198714" target="_blank">2. Hrdlickova R., Toloue M. and Tian B. RNA-Seq methods for transcriptome analysis. Wiley Interdiscip Rev RNA. 2016; </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27198714" target="_blank">Hrdlickova R., Toloue M. and Tian B. RNA-Seq methods for transcriptome analysis. Wiley Interdiscip Rev RNA. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27083874" target="_blank">Wen L. and Tang F. Single-cell sequencing in stem cell biology. Genome Biol. 2016;17:71</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25727184" target="_blank">Jaitin D. A., Keren-Shaul H., Elefant N. and Amit I. Each cell counts: Hematopoiesis and immunity research in the era of single cell genomics. Semin Immunol. 2015;27:67-71</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26627738" target="_blank">Paul F., Arkin Y., Giladi A., et al. Transcriptional Heterogeneity and Lineage Commitment in Myeloid Progenitors. Cell. 2015;163:1663-1677</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26779813" target="_blank">Baruch K., Deczkowska A., Rosenzweig N., et al. PD-1 immune checkpoint blockade reduces pathology and improves memory in mouse models of Alzheimer's disease. Nat Med. 2016;22:135-137</a></li>
</ol>

<h5>Nuc-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/nuc-seq.png"></p>

<p>Nuc-Seq is an RNA sequencing technique optimized for isolating and sequencing nuclear RNA from frozen tissue samples.  Nuc-Seq avoids proteolytic treatment during nuclei dissociation from cells, minimizing gene expression changes resulting from common protease dissociation procedures; this step is similar to the one used in snRNA-seq. Next, Smart-seq2 is used for cDNA synthesis, increasing the full-length cDNA yield due to its template-switching mechanism. Finally, the sequencing library is prepared using Tn5 transposase tagmentation. 
</p><p>Similar methods: snRNA-seq, Div-Seq.</p>
<h6>Pros:</h6>
<ul>
<li>Nonproteolytic nuclear dissociation minimizes gene expression changes during isolation of nuclei </li>
<li>Template-switching mechanism of Smart-seq2 during cDNA synthesis increases the yield of full-length cDNA strands</li>
<li>FACS isolation increases throughput</li>
<li>RNA from frozen nuclei gives better cDNA quality than cytoplasmic RNA</li>
<li>Can be used on frozen tissues</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Excludes any information from cytoplasmic RNA</li>
<li>Low-copy transcripts are hard to detect due to low amounts of isolated nucleolar RNA</li>
<li>ncRNAs and other short non-poly(A) RNA species are challenging to detect</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26890679" target="_blank">Nuc-Seq: Krishnaswami S. R., Grindberg R. V., Novotny M., et al. Using single nuclei for RNA-seq to capture the transcriptome of postmortem neurons. Nat Protoc. 2016;11:499-524</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27571191" target="_blank">Jennings C. G., Landman R., Zhou Y., et al. Opportunities and challenges in modeling human brain disorders in transgenic primates. Nat Neurosci. 2016;19:1123-1130</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26890679" target="_blank">Krishnaswami S. R., Grindberg R. V., Novotny M., Venepally P., Lacar B., et al. Using single nuclei for RNA-seq to capture the transcriptome of postmortem neurons. Nat Protoc. 2016;11:499-524</a></li>
</ol>

<h5>PAIR</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pair.png"></p>

<p>PAIR uses PNAs to capture RBPs in vivo. ,  The PNAs are coupled to a cell membrane-penetrating peptide (CPP) to deliver PNAs efficiently into living cells, as well as a photoactivatable compound, p-benzoylphenylalanine (Bpa). The cells are illuminated with UV light, activating the Bpa on the PNA to form covalent bonds with the RBP. Next, the cells are lysed, and the RNA complexes are captured on magnetic beads. The proteins can be reverse-crosslinked and visualized by denaturing gel electrophoresis, while the RNA strands are sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies RNA-protein interactions in vivo</li>
<li>	Commercial PNAs can be purchased, eliminating the need for PNA design</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Custom PNA design can cause problems with low protein yield</li>
<li>Not yet adopted widely by the scientific community</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/16432185" target="_blank">PAIR: Zielinski J., Kilk K., Peritz T., et al. In vivo identification of ribonucleoprotein-RNA interactions. Proc Natl Acad Sci U S A. 2006;103:1557-1562</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/17406325" target="_blank">PAIR Protocol: Zeng F., Peritz T., Kannanayakal T. J., et al. A protocol for PAIR: PNA-assisted identification of RNA binding proteins in living cells. Nat Protoc. 2006;1:920-927</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27625393" target="_blank">Jazurek M., Ciesiolka A., Starega-Roslan J., Bilinska K. and Krzyzosiak W. J. Identifying proteins that bind to specific RNAs - focus on simple repeat expansion diseases. Nucleic Acids Res. 2016;44:9050-9070</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24467948" target="_blank">McHugh C. A., Russell P. and Guttman M. Methods for comprehensive experimental identification of RNA-protein interactions. Genome Biol. 2014;15:203</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/16432185" target="_blank">Zielinski J., Kilk K., Peritz T., et al. In vivo identification of ribonucleoprotein-RNA interactions. Proc Natl Acad Sci U S A. 2006;103:1557-1562</a></li>
</ol>

<h5>Quartz-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/quartz-seq.png"></p>

<p>The Quartz-Seq method optimizes whole-transcript amplification (WTA) of single cells.  In this method, an RT  primer with a T7 promoter and PCR target is first added to the extracted mRNA. RT synthesizes first-strand cDNA, after which the RT primer is digested by exonuclease I. Next, a poly(A) tail is added to the 3' ends of first-strand cDNA, along with a poly(dT) primer containing a PCR target. After second-strand generation, a blocking primer is added to ensure PCR enrichment in sufficient quantity for sequencing. Deep sequencing allows for accurate, high-resolution representation of the whole transcriptome of a single cell.
</p><p>
Similar methods: CEL-Seq, Drop-seq, MARS-Seq, CytoSeq, inDrop, Hi-SCL.</p>
<h6>Pros:</h6>
<ul>
<li>Single-tube reaction suitable for automation</li>
<li>Digestion of RT primers by exonuclease I eliminates amplification of byproducts</li>
<li>Short fragments and byproducts are suppressed during enrichment</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>PCR biases can underrepresent GC-rich templates</li>
<li>Amplification errors caused by polymerases will be represented and sequenced incorrectly</li>
<li>Targets smaller than 500 bp are preferentially amplified by polymerases during PCR</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23594475" target="_blank">Quartz-Seq: Sasagawa Y., Nikaido I., Hayashi T., Danno H., Uno K. D., et al. (2013) Quartz-Seq: a highly reproducible and sensitive single-cell RNA sequencing method, reveals non-genetic gene-expression heterogeneity. Genome Biol 14: R31</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26941284" target="_blank">Zhang X., Marjani S. L., Hu Z., Weissman S. M., Pan X. and Wu S. Single-Cell Sequencing for Precise Cancer Research: Progress and Prospects. Cancer Res. 2016;76:1305-1312</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27571192" target="_blank">Poulin J. F., Tasic B., Hjerling-Leffler J., Trimarchi J. M. and Awatramani R. Disentangling neural cell diversity using single-cell transcriptomics. Nat Neurosci. 2016;19:1131-1141</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26003306" target="_blank">Sun H. J., Chen J., Ni B., Yang X. and Wu Y. Z. Recent advances and current issues in single-cell sequencing of tumors. Cancer Lett. 2015;365:1-10</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26544934" target="_blank">Grun D. and van Oudenaarden A. Design and Analysis of Single-Cell Sequencing Experiments. Cell. 2015;163:799-810</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25222669" target="_blank">Navin N. E. Cancer genomics: one cell at a time. Genome Biol. 2014;15:452</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25438696" target="_blank">Liang J., Cai W. and Sun Z. Single-Cell Sequencing Technologies: Current and Future. J Genet Genomics. 2014;41:513-528</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27615194" target="_blank">Takeuchi M., Yamaguchi S., Sakakibara Y., Hayashi T., Matsuda K., et al. (2016) Gene expression profiling of granule cells and Purkinje cells in the zebrafish cerebellum. J Comp Neurol;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27840077" target="_blank">Archer N., Walsh M. D., Shahrezaei V. and Hebenstreit D. Modeling Enzyme Processivity Reveals that RNA-Seq Libraries Are Biased in Characteristic and Correctable Ways. Cell Syst. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26142758" target="_blank">Scialdone A., Natarajan K. N., Saraiva L. R., et al. Computational assignment of cell-cycle stage from single-cell transcriptome data. Methods. 2015;</a></li>
</ol>

<h5>scM&amp;T-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scm-t-seq.png"></p>

<p>scM&amp;T-Seq allows parallel analysis of both epigenetic and gene expression patterns from single cells using Smart-seq2 and scBS-seq. scM&amp;T-Seq is built upon G&amp;T-seq, but instead of using MDA for DNA sequencing, it uses scBS-Seq to determine DNA methylation patterns.</p>
<p>Single cells are isolated and individually lysed. The mRNAs are captured with streptavidin-coupled mRNA capture primers to separate them physically from the DNA strands. Smart-seq2 uses RT with template switching and tagmentation to generate cDNA libraries from the mRNA. DNA libraries are prepared via scBS-seq, which involves bisulfite conversion of DNA strands to identify methylated cytosines. Both libraries are ready for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Investigates links between epigenetic and transcriptional heterogeneity in single cells</li>
<li>Because DNA and RNA are physically separated and amplified independently, there is no need to mask coding sequences during analysis</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Smart-seq2 is not strand-specific and applicable to only poly(A)+ RNA</li>
<li>Does not distinguish between 5mC and 5hmC</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26752769">scM&amp;T-Seq: Angermueller C., Clark S. J., Lee H. J., Macaulay I. C., Teng M. J., et al. (2016) Parallel single-cell sequencing links transcriptional and epigenetic heterogeneity. Nat Methods 13: 229-232</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27091476" target="_blank">Clark S. J., Lee H. J., Smallwood S. A., Kelsey G. and Reik W. Single-cell epigenomics: powerful new methods for understanding gene regulation and cell identity. Genome Biol. 2016;17:72</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27083874" target="_blank">Wen L. and Tang F. Single-cell sequencing in stem cell biology. Genome Biol. 2016;17:71</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27150361" target="_blank">Hu Y., Huang K., An Q., et al. Simultaneous profiling of transcriptome and DNA methylome from a single cell. Genome Biol. 2016;17:88</a></li>
</ol>

<h5>SCRB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scrb-seq.png"></p>

<p>SCRB-Seq is a cost-efficient, multiplexed, single-cell mRNA sequencing technique. 
</p><p>SCRB-Seq isolates single cells into wells using FACS. After cell lysis, poly(A)+ mRNAs are annealed to a custom primer containing a poly(T) tract, UMI, well barcode, and biotin. Template-switching RT and PCR amplification reactions are carried out on the mRNA, generating barcoded, full-length cDNA. cDNA strands from all wells are pooled together to be purified. They are PCR-amplified and purified further. The cDNA libraries are prepared using the Nextera XT library preparation protocol, with modified i5 primers. The resultant cDNA fragments are size-selected for 300–800 bp and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Cost-efficient, high-throughput, single-cell transcriptome profiling</li>
<li>Highly sensitive gene-detection results compared to popular scRNA-Seq techniques<sup>1</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Template-switching RT is heavily biased to full-length mRNA<sup>2</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://biorxiv.org/content/early/2014/03/05/003236" target="_blank">SCRB-Seq: Soumillon M., Cacchiarelli D., Semrau S., van Oudenaarden A. and Mikkelsen T. S. (2014). Characterization of directed differentiation by high-throughput single-cell RNA-Seq. bioRxiv</a></li>
<li><a href="http://biorxiv.org/content/early/2016/01/05/035758" target="_blank">1. Ziegenhain C., Parekh S., Vieth B., Smets M., Leonhardt H., et al. (2016) Comparative analysis of single-cell RNA-sequencing methods. bioRxiv </a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23897237" target="_blank">2. Shapiro E., Biezuner T. and Linnarsson S. (2013) Single-cell sequencing-based technologies will revolutionize whole-organism science. Nat Rev Genet 14: 618-630</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://biorxiv.org/content/biorxiv/early/2016/01/05/035758.full.pdf" target="_blank">Ziegenhain C., Parekh S., Vieth B., Smets M., Leonhardt H., et al. Comparative analysis of single-cell RNA-sequencing methods. bioRxiv. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23897237" target="_blank">Shapiro E., Biezuner T. and Linnarsson S. Single-cell sequencing-based technologies will revolutionize whole-organism science. Nat Rev Genet. 2013;14:618-630</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26186193" target="_blank">Cacchiarelli D., Trapnell C., Ziller M. J., et al. Integrative Analyses of Human Reprogramming Reveal Dynamic Nature of Induced Pluripotency. Cell. 2015;162:412-424</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25992865" target="_blank">Anahtar M. N., Byrne E. H., Doherty K. E., et al. Cervicovaginal bacteria are a major modulator of host inflammatory responses in the female genital tract. Immunity. 2015;42:965-976</a></li>
</ol>

<h5>scRNA-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/scrna-seq.png"></p>

<p>scRNA-Seq provides deeper insight to the multi-tiered complexity of different cells within the same tissue type.  scRNA-Seq has now been adapted widely into other methods in the single-cell RNA sequencing field.
In this method, single cells are isolated manually under a microscope and lysed. Next, mRNAs are purified and primed with a poly(T) primer for reverse transcription. Unreactive primers are removed by exonuclease I digestion. Poly(A) tails are added to the first strand cDNA at the 3' end and annealed to poly(T) primers for second-strand cDNA generation. Finally, the cDNAs are PCR-amplified, sheared, and prepared into sequencing libraries.
</p>
<h6>Pros:</h6>
<ul>
<li>Single-cell–resolution transcriptomic analysis</li>
<li>Able to detect unknown splice junctions </li>
<li>Various RNAPII-specific antibodies can be used to increase targeting accuracy</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Very low throughput </li>
<li>No molecular barcodes used</li>
<li>Can be expensive to scale up</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25910207" target="_blank">mNET-Seq: Nojima T., Gomes T., Grosso A. R., et al. Mammalian NET-Seq Reveals Genome-wide Nascent Transcription Coupled to RNA Processing. Cell. 2015;161:526-540</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26844429" target="_blank">1. Nojima T., Gomes T., Carmo-Fonseca M. and Proudfoot N. J. Mammalian NET-seq analysis defines nascent RNA profiles and associated RNA processing genome-wide. Nat Protoc. 2016;11:413-428</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27665068" target="_blank">Moignard V. and Gottgens B. Dissecting stem cell differentiation using single cell expression profiling. Curr Opin Cell Biol. 2016;43:78-86</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26577213" target="_blank">Woodhouse S., Moignard V., Gottgens B. and Fisher J. Processing, visualising and reconstructing network models from single-cell data. Immunol Cell Biol. 2016;94:256-265</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27824854" target="_blank">Wagner A., Regev A. and Yosef N. Revealing the vectors of cellular identity with single-cell genomics. Nat Biotechnol. 2016;34:1145-1160</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25628217" target="_blank">Stegle O., Teichmann S. A. and Marioni J. C. Computational and analytical challenges in single-cell transcriptomics. Nat Rev Genet. 2015;16:133-145</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000846" target="_blank">Kolodziejczyk A. A., Kim J. K., Svensson V., Marioni J. C. and Teichmann S. A. The Technology and Biology of Single-Cell RNA Sequencing. Mol Cell. 2015;58:610-620</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25675209" target="_blank">Lee J. H., Daugharthy E. R., Scheiman J., et al. Fluorescent in situ sequencing (FISSEQ) of RNA for gene expression profiling in intact cells and tissues. Nat Protoc. 2015;10:442-458</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25866248" target="_blank">Padovan-Merhar O., Nair G. P., Biaesch A. G., et al. Single Mammalian Cells Compensate for Differences in Cellular Volume and DNA Copy Number through Independent Global Transcriptional Mechanisms. Mol Cell. 2015;58:339-352</a></li>
</ol>

<h5>Smart-Seq/NanoCAGE/CAGEscan</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/smart-seq-nanocage-cagescan.png"></p>

<p>Smart-Seq and Smart-Seq2: Switch Mechanism at the 5' End of RNA Templates Smart-Seq was developed as a single-cell sequencing protocol with improved read coverage across transcripts. Complete coverage across the genome allows the detection of alternative transcript isoforms and SNPs. There are 2 versions of Smart-Seq: Smart-Seq and Smart-seq2. Smart-seq2 includes several improvements over the original Smart-Seq protocol. The new protocol includes a locked nucleic acid (LNA), an increased MgCl2 concentration, betaine, and elimination of the purification step to improve the yield significantly.</p>
<p>Smart-Seq: Cells are lysed, and the RNA is hybridized to an oligo(dT)-containing primer. The first strand of the cDNA is synthesized with the addition of a few untemplated C nucleotides. This poly(C) overhang is added exclusively to full-length transcripts. An oligonucleotide primer is hybridized to the poly(C) overhang and used to synthesize the second strand. Full-length cDNAs are PCR-amplified to obtain nanogram amounts of DNA. The PCR products are purified for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>mRNA sequence does not have to be known</li>
<li>As little as 50 pg of starting material can be used</li>
<li>Improved coverage across transcripts</li>
<li>High level of mappable reads</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not strand-specific</li>
<li>No early multiplexing</li>
<li>Applicable only to poly(A)+ RNA</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22820318" target="_blank">Smart-Seq: Ramskold D., Luo S., Wang Y. C., et al. Full-length mRNA-Seq from single-cell levels of RNA and individual circulating tumor cells. Nat Biotechnol. 2012;30:777-782</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Sample Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25607527" target="_blank">Agarwal S., Macfarlan T. S., Sartor M. A. and Iwase S. (2015) Sequencing of first-strand cDNA library reveals full-length transcriptomes. Nat Commun 6: 6002</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25575081" target="_blank">Kim D. H., Marinov G. K., Pepke S., Singer Z. S., He P., et al. (2015) Single-cell transcriptome analysis reveals dynamic changes in lncRNA expression during reprogramming. Cell Stem Cell 16: 88-101</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26004630" target="_blank">Tanaka Y., Hysolli E., Su J., Xiang Y., Kim K. Y., et al. (2015) Transcriptome Signature and Regulation in Human Somatic Cell Reprogramming. Stem Cell Reports 4: 1125-1139</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24419370" target="_blank">Bhargava V., Head S. R., Ordoukhanian P., Mercola M. and Subramaniam S. (2014) Technical variations in low-input RNA-seq methodologies. Sci Rep 4: 3678</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25096407" target="_blank">Biase F. H., Cao X. and Zhong S. (2014) Cell fate inclination within 2-cell and 4-cell mouse embryos revealed by single-cell RNA sequencing. Genome Res 24: 1787-1796</a></li>
</ol>

<h5>Smart-Seq2</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/smart-seq2.png"></p>

<p>Smart-Seq2 includes several improvements over the original Smart-Seq protocol. The new protocol includes a locked nucleic acid (LNA), an increased MgCl2 concentration, betaine, and elimination of the purification step to significantly improve the yield. In this protocol, single cells are lysed in a buffer that contains free dNTPs and oligo(dT)-tailed oligonucleotides with a universal 5′-anchor sequence. Reverse transcription is performed, which adds 2–5 untemplated nucleotides to the cDNA 3′ end. A template-switching oligo (TSO) is added, carrying two riboguanosines and a modified guanosine to produce a LNA as the last base at the 3′ end.&nbsp; After the first-strand reaction, the cDNA is amplified using a limited number of cycles. Tagmentation is then used to quickly and efficiently construct sequencing libraries from the amplified cDNA.</p>
<h6>Pros:</h6>
<ul>
<li>The sequence of the mRNA does not have to be known</li>
<li>As little as 50 pg of starting material can be used</li>
<li>Improves coverage across transcripts</li>
<li>High level of mappable reads</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not strand-specific</li>
<li>No early multiplexing</li>
<li>Applicable only to poly(A)+ RNA</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24056875" target="_blank">Smart-Seq2: Picelli S., Bjorklund A. K., Faridani O. R., Sagasser S., Winberg G., et al. (2013) Smart-seq2 for sensitive full-length transcriptome profiling in single cells. Nat Methods 10: 1096-1098</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24385147" target="_blank">Smart-Seq2: Picelli S., Faridani O. R., Björklund Å. K., Winberg G., Sagasser S., et al. (2014) Full-length RNA-Seq from single cells using Smart-seq2. Nat. Protocols 9: 171-181</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GBR/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25915121" target="_blank">Macaulay I. C., Haerty W., Kumar P., Li Y. I., Hu T. X., et al. (2015) G&amp;T-seq: parallel sequencing of single-cell genomes and transcriptomes. Nat Methods 12: 519-522</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25664528" target="_blank">Moignard V., Woodhouse S., Haghverdi L., Lilly A. J., Tanaka Y., et al. (2015) Decoding the regulatory network of early blood development from single-cell gene expression measurements. Nat Biotechnol 33: 269-276</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25326897" target="_blank">Swiech L., Heidenreich M., Banerjee A., Habib N., Li Y., et al. (2015) In vivo interrogation of gene function in the mammalian brain using CRISPR-Cas9. Nat Biotechnol 33: 102-106</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24408435" target="_blank">Deng Q., Ramskold D., Reinius B. and Sandberg R. (2014) Single-cell RNA-seq reveals dynamic, random monoallelic gene expression in mammalian cells. Science 343: 193-196</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24385147" target="_blank">Picelli S., Faridani O. R., Bjorklund A. K., Winberg G., Sagasser S., et al. (2014) Full-length RNA-seq from single cells using Smart-seq2. Nat Protoc 9: 171-181</a></li>
</ol>

<h5>snRNA-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/snrna-seq.png"></p>

<p>snRNA-Seq uses a mild and quick nuclear dissociation protocol to isolate and sequence RNA within the nucleus. The method minimizes technical issues that can arise from common dissociation protocols, especially in studying immediate early gene (IEG) behavior.  
</p><p>In this method, the cell suspension is lysed gently and the nuclei are separated from cytoplasmic lysates by centrifugation. Single cells/nuclei are sorted into individual wells using FACS. Individual nuclei are amplified using a microfluidics-assisted machinery that performs cell capture and reaction chemistry. The nuclear RNA contents are processed into cDNA libraries using a Nextera XT DNA Library Prep Kit. Pools of 40 samples are collected and purified using magnetic beads. The cDNA library is ready for sequencing.
</p><p>Similar methods: Div-Seq, Nuc-seq.</p>
<h6>Pros:</h6>
<ul>
<li>Rapid dissociation protocol prevents technical issues arising from protease digestion, heating, and spurious gene expression by cytoplasmic ribosomes</li>
<li>Prevents dendritic loss that commonly occurs during protease dissociation step</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported yet</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27090946" target="_blank">snRNA-Seq: Lacar B., Linker S. B., Jaeger B. N., Krishnaswami S., Barron J., et al. (2016) Nuclear RNA-Seq of single neurons reveals molecular signatures of activation. Nat Commun 7: 11022</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27571192" target="_blank">Poulin J. F., Tasic B., Hjerling-Leffler J., Trimarchi J. M. and Awatramani R. Disentangling neural cell diversity using single-cell transcriptomics. Nat Neurosci. 2016;19:1131-1141</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27788914" target="_blank">Gagliano S. A. It's All in the Brain: A Review of Available Functional Genomic Annotations. Biol Psychiatry. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27814520" target="_blank">Goncalves J. T., Schafer S. T. and Gage F. H. Adult Neurogenesis in the Hippocampus: From Stem Cells to Behavior. Cell. 2016;167:897-914</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27090946" target="_blank">Lacar B., Linker S. B., Jaeger B. N., et al. Nuclear RNA-seq of single neurons reveals molecular signatures of activation. Nat Commun. 2016;7:11022</a></li>
</ol>

<h5>STRT</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/strt.png"></p>

<p>STRT-Seq is a method similar to CEL-Seq that involves unique barcoding and sample pooling to overcome the challenges of samples with limited material. ,  In this method, single cells are first picked in individual tubes, where first-strand cDNA synthesis occurs using an oligo(dT) primer with the addition of 3–6 cytosines. A helper oligonucleotide promotes template switching, which introduces the barcode into the cDNA. The barcoded cDNA is amplified by single-primer PCR. Deep sequencing allows for accurate transcriptome determination of individual cells.</p>
<h6>Pros:</h6>
<ul>
<li>Barcoding and pooling allows for multiplexing and studying many different single cells at a time</li>
<li>Sample handling and the potential for cross-contamination are greatly reduced due to using a single tube per cell</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>PCR biases can underrepresent GC-rich templates</li>
<li>Nonlinear PCR amplification can lead to biases affecting reproducibility</li>
<li>Amplification errors caused by polymerases will be represented and sequenced incorrectly</li>
<li>Loss of accuracy due to PCR bias</li>
<li>Targets smaller than 500 bp are amplified preferentially by polymerases during PCR</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21543516">STRT: Islam S., Kjallquist U., Moliner A., Zajac P., Fan J. B., et al. (2011) Characterization of the single-cell transcriptional landscape by highly multiplex RNA-seq. Genome Res 21: 1160-1167</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24497842" target="_blank">Macaulay I. C. and Voet T. Single cell genomics: advances and future perspectives. PLoS Genet. 2014;10:e1004126</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000846" target="_blank">Kolodziejczyk A. A., Kim J. K., Svensson V., Marioni J. C. and Teichmann S. A. The Technology and Biology of Single-Cell RNA Sequencing. Mol Cell. 2015;58:610-620</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26003306" target="_blank">Sun H. J., Chen J., Ni B., Yang X. and Wu Y. Z. Recent advances and current issues in single-cell sequencing of tumors. Cancer Lett. 2015;365:1-10</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26544934" target="_blank">Grun D. and van Oudenaarden A. Design and Analysis of Single-Cell Sequencing Experiments. Cell. 2015;163:799-810</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26941284" target="_blank">Zhang X., Marjani S. L., Hu Z., Weissman S. M., Pan X., et al. Single-Cell Sequencing for Precise Cancer Research: Progress and Prospects. Cancer Res. 2016;76:1305-1312</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25222669" target="_blank">Navin N. E. Cancer genomics: one cell at a time. Genome Biol. 2014;15:452</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27355630" target="_blank">Korber I., Katayama S., Einarsdottir E., et al. Gene-Expression Profiling Suggests Impaired Signaling via the Interferon Pathway in Cstb-/- Microglia. PLoS One. 2016;11:e0158195</a></li> 
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26360614" target="_blank">Tohonen V., Katayama S., Vesterlund L., et al. Novel PRD-like homeodomain transcription factors and retrotransposon elements in early human development. Nat Commun. 2015;6:8207</a></li> 
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26108968" target="_blank">Katayama S., Skoog T., Jouhilahti E. M., et al. Gene expression analysis of skin grafts and cultured keratinocytes using synthetic RNA normalization reveals insights into differentiation and growth control. BMC Genomics. 2015;16:476</a></li>
</ol>

<h5>SUPeR-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/super-seq.png"></p>

<p>SinSUPeR-Seq sequences non-poly(A) and poly(A) RNAs from single cells. It is designed particularly for mapping circular RNA (circRNA) species. 
</p><p>RNA samples from lysed single cells are annealed to random primers with universal anchor sequences (AnchorX-T15N6) and reverse-transcribed to generate the first strand of cDNA. Unreacted primers are digested, to avoid primer-dimers. Next, a poly(A) tract is added to the 3' end of the cDNA by introducing dATP and ddATP in a 100:1 ratio, respectively. A second set of random primers, also with a universal anchor sequence (AnchorY-T24), anneals to the newly synthesized poly(A) tract. A second cDNA strand is generated by RT, and the cDNA is purified by gel electrophoresis. The purified cDNA molecules are PCR-amplified using 5'-amine-terminated primers, prepared by the TruSeq DNA library preparation protocol, and sequenced. circRNAs are identified from the dataset by finding 2 exonic reads that are distal in the reference genome, but adjacent to each other in the dataset with 1 inverted, signifying the circularization of the RNA.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies circRNAs from single cells</li>
<li>Avoids 3' bias by using random primers with anchor sequences</li>
<li>Able to identify novel circRNAs due to random primers</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Relies on dataset analysis to identify circRNAs</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26201400" target="_blank">SUPeR-Seq: Fan X., Zhang X., Wu X., Guo H., Hu Y., et al. (2015) Single-cell RNA-seq transcriptome analysis of linear and circular RNAs in mouse preimplantation embryos. Genome Biol 16: 148</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27315811" target="_blank">Dang Y., Yan L., Hu B., et al. Tracing the expression of circular RNAs in human pre-implantation embryos. Genome Biol. 2016;17:130</a></li>
</ol>

<h5>TCR Chain Pairing</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tcr-chain-pairing.png"></p>

<p>This method identifies TCR-alpha and -beta chain pairing in single cells using cell-based emulsion technology for isolation, followed by NGS. TCR chain pairing resolves one of the biggest challenges of identifying coexpressed gene pairs—random, nonspecific overlap extension of nonfused molecules—by introducing a unique PCR suppression technique during post–emulsion amplification reactions. First, single T cells are isolated into oil emulsion droplets containing RT primers for alpha and beta chain mRNA strands. The resultant cDNA is amplified, and the RT primer extensions overlapped to connect TCR-alpha and TCR-beta strands, which are now called fused molecules. The cDNA products are extracted from the emulsion and introduced to blocking primers. These primers anneal to the 3' end of nonfused cDNA strands, preventing them from being amplified; the authors name this technique “PCR suppression.” Finally, the fused molecules are PCR-amplified and sequenced.</p><p>Similar methods: TCR-LA-MC PCR</p>
<h6>Pros:</h6>
<ul>
<li>Identifies TCR chain pairing using NGS</li>
<li>PCR suppression of nonfused molecules significantly reduces random, nonspecific overlap extension during post–emulsion amplification reactions</li>
<li>Simple and straightforward protocol</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Heat-shock during cell lysis may reduce enzymatic activity during RT<sup>1</sup> </li>
<li>Amplification product is not suitable for cloning<sup>2</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23696157" target="_blank">TCR Chain Pairing: Turchaninova M. A., Britanova O. V., Bolotin D. A., et al. Pairing of T-cell receptor chains via emulsion PCR. Eur J Immunol. 2013;43:2507-2515</a></li>
<li><a href="http://www.cell.com/trends/biotechnology/fulltext/S0167-7799(16)30162-7" target="_blank">1. Friedensohn S., Khan T. A. and Reddy S. T. Advanced Methodologies in High-Throughput Sequencing of Immune Repertoires. Trends in Biotechnology. 2017;35:203-214</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27589924" target="_blank">2. Sprouse M. L., Blahnik G., Lee T., et al. Rapid identification and expression of human TCRs in retrogenic mice. J Immunol Methods. 2016; </a></li>
</ul>
<p><a href="http://www.ncbi.nlm.nih.gov/pubmed/27589924" target="_blank">&nbsp;</a></p>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.cell.com/trends/biotechnology/fulltext/S0167-7799(16)30162-7" target="_blank">Friedensohn S., Khan T. A. and Reddy S. T. Advanced Methodologies in High-Throughput Sequencing of Immune Repertoires. Trends in Biotechnology. 2017;35:203-214</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27307436" target="_blank">Munson D. J., Egelston C. A., Chiotti K. E., et al. Identification of shared TCR sequences from T cells in human breast cancer using emulsion RT-PCR. Proc Natl Acad Sci U S A. 2016;113:8272-8277</a></li>
</ol>

<h5>TCR-LA-MC PCR</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tcr-la-mc-pcr.png"></p>

<p>TCR-LA-MC PCR identifies TCR-alpha and -beta chains from T cells and uses sequencing to analyze the catalog of clonal TCR in vivo or in vitro from blood or tissue samples.  This technique can be performed with as little as 10 ng of cDNA, while providing great sensitivity and accuracy for analyzing the diversity and mechanisms that affect TCR clonality.
First-strand cDNA is generated using biotinylated primers that anneal to the constant gene of the TCR chains. RNA strands are removed by RNA digestion, and the single-stranded cDNA is captured magnetically using streptavidin beads. Single-stranded linker cassettes (ssLCs) containing primer sequences are ligated to the cDNA, and the samples are PCR-amplified. The double-stranded cDNAs are flanked with sequencing adapters and are ready for sequencing.
</p><p>Similar methods: TCR chain pairing.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies TCR diversity without sequence-associated or quantitative restrictions</li>
<li>Can be used to study the diversity and mechanism of TCRs that influences clonality</li>
<li>As little as 10 ng of cDNA can be used as input</li>
<li>Identifies T-cells with 1:10,000 resolution capacity, or even single cells</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported yet</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26324409" target="_blank">TCR-LA-MC PCR: Ruggiero E., Nicolay J. P., Fronza R., et al. High-resolution analysis of the human T-cell receptor repertoire. Nat Commun. 2015;6:8081</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27630639" target="_blank">Hou D., Chen C., Seely E. J., Chen S. and Song Y. High-Throughput Sequencing-Based Immune Repertoire Study during Infectious Disease. Front Immunol. 2016;7:336</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26659572" target="_blank">Oliveira G., Ruggiero E., Stanghellini M. T., et al. Tracking genetically engineered lymphocytes long-term reveals the dynamics of T cell immunological memory. Sci Transl Med. 2015;7:317ra198</a></li>
</ol>

<h5>TIVA</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tiva.png"></p>

<p>TIVA is a protocol that captures mRNA from live cells.  
In this method, a photoactivatable TIVA tag is loaded into cells. Selective photoactivation exposes the mRNA-capturing portion of the tag, allowing it to hybridize to the poly(A) tails of mRNA. The biotin-bound mRNA is captured using streptavidin-coated magnetic beads and transcribed into cDNA. Sequencing the cDNA provides transcriptome analysis of RNA from single cells in complex tissues.</p>
<h6>Pros:</h6>
<ul>
<li>In vivo transcriptome analysis using photoactivation in neuronal cells</li>
<li>Noninvasive method for capturing mRNAs in their natural microenvironment</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to a small number of cells</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24412976">TIVA: Lovatt D., Ruble B. K., Lee J., Dueck H., Kim T. K., et al. (2014) Transcriptome in vivo analysis (TIVA) of spatially defined single cells in live tissue. Nat Methods 11: 190-196</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26941284" target="_blank">Zhang X., Marjani S. L., Hu Z., Weissman S. M., Pan X., et al. Single-Cell Sequencing for Precise Cancer Research: Progress and Prospects. Cancer Res. 2016;76:1305-1312</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27198043" target="_blank">Binan L., Mazzaferri J., Choquet K., et al. Live single-cell laser tag. Nat Commun. 2016;7:11636</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27318512" target="_blank">Bian Q. and Cahan P. Computational Tools for Stem Cell Biology. Trends Biotechnol. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26949524" target="_blank">Liu S. and Trapnell C. Single-cell transcriptome sequencing: recent advances and remaining challenges. F1000Res. 2016;5:</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25867922" target="_blank">Achim K., Pettit J. B., Saraiva L. R., et al. High-throughput spatial mapping of single-cell RNA-seq data to tissue of origin. Nat Biotechnol. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000846" target="_blank">Kolodziejczyk A. A., Kim J. K., Svensson V., Marioni J. C. and Teichmann S. A. The Technology and Biology of Single-Cell RNA Sequencing. Mol Cell. 2015;58:610-620</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25016438" target="_blank">Baslan T. and Hicks J. Single cell sequencing approaches for complex biological systems. Curr Opin Genet Dev. 2014;26C:59-65</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24412976" target="_blank">Lovatt D., Ruble B. K., Lee J., Dueck H., Kim T. K., et al. (2014) Transcriptome in vivo analysis (TIVA) of spatially defined single cells in live tissue. Nat Methods 11: 190-196</a></li>
</ol>

<h5>UMI</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/umi.png"></p>

<p>Unique molecular identifiers (UMI) are molecular tags that are used to detect and quantify unique mRNA transcripts.  
In this method, mRNA libraries are generated by fragmentation and reverse-transcribed to cDNA. Oligo(dT) primers with specific sequencing linkers are added to the cDNA. Another sequencing linker with a 10 bp random label and an index sequence is added to the 5' end of the template, which is amplified and sequenced. Sequencing allows for high-resolution reads, enabling accurate detection of true variants.</p>
<h6>Pros:</h6>
<ul>
<li>Can sequence unique mRNA transcripts</li>
<li>Can detect transcripts occurring at low frequencies</li>
<li>Transcripts can be quantified based on sequencing reads specific to each barcode</li>
<li>Can be applied to multiple platforms to karyotype chromosomes</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Targets smaller than 500 bp are preferentially amplified by polymerases during PCR</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22101854" target="_blank">Kivioja T., Vaharautio A., Karlsson K., Bonke M., Enge M., et al. (2012) Counting absolute numbers of molecules using unique molecular identifiers. Nat Methods 9: 72-74</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/26000488" target="_blank">Macosko E. Z., Basu A., Satija R., Nemesh J., Shekhar K., et al. (2015) Highly Parallel Genome-wide Expression Profiling of Individual Cells Using Nanoliter Droplets. Cell 161: 1202-1214</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24793455" target="_blank">Shugay M., Britanova O. V., Merzlyak E. M., Turchaninova M. A., Mamedov I. Z., et al. (2014) Towards error-free profiling of immune repertoires. Nat Methods 11: 653-655</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24363023" target="_blank">Islam S., Zeisel A., Joost S., La Manno G., Zajac P., et al. (2014) Quantitative single-cell RNA-seq with unique molecular identifiers. Nat Methods 11: 163-166</a></li>
</ol>

#### RNA modification

<h5>ICE</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ice.png"></p>

<p>ICE followed by NGS identifies adenosine-to-inosine editing. 
In this method, RNA is treated with acrylonitrile, while control RNA is untreated. Control and treated RNAs are reverse-transcribed and PCR-amplified. Inosines in RNA fragments treated with acrylonitrile cannot be reverse-transcribed. Deep sequencing of the cDNA prepared from control and treated RNA provides high-resolution reads of inosines in RNA fragments.</p>
<h6>Pros:</h6>
<ul>
<li>Provides mapping of adenosine-to-inosine editing</li>
<li>Can be performed with limited material</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Nonlinear PCR amplification can lead to biases, affecting reproducibility</li>
<li>Amplification errors caused by polymerases will be represented and sequenced incorrectly</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/20835228" target="_blank">ICE: Sakurai M., Yano T., Kawabata H., Ueda H. and Suzuki T. (2010) Inosine cyanoethylation identifies A-to-I RNA editing sites in the human transcriptome. Nat Chem Biol 6: 733-740</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html" target="_blank">TruSeq Nano DNA Library Prep kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html" target="_blank">TruSeq Stranded total RNA library prep kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html" target="_blank">TruSeq DNA PCR-free library prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27208508" target="_blank">Ramaswami G. and Li J. B. Identification of human RNA editing sites: A historical perspective. Methods. 2016;107:42-47</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27140282" target="_blank">Frye M., Jaffrey S. R., Pan T., Rechavi G. and Suzuki T. RNA modifications: what have we learned and where are we headed? Nat Rev Genet. 2016;17:365-372</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26333314" target="_blank">Ishida K., Miyauchi K., Kimura Y., et al. Regulation of gene expression via retrotransposon insertions and the noncoding RNA 4.5S RNA. Genes Cells. 2015;</a></li>
</ol>

<h5>MeRIP-Seq/m6A-seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/merip-seq-m6a-seq.png"></p>

<p>MeRIP-Seq maps m6A-methylated RNA. In this method, m6A-specific antibodies are used to immunoprecipitate RNA. RNA is reverse-transcribed to cDNA and sequenced. Deep sequencing provides high-resolution reads of m6A-methylated RNA.
</p><p>Similar methods: miCLIP, m6A-LAIC-Seq.</p>
<h6>Pros:</h6>
<ul>
<li>Maps m6A methylated RNA</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Antibodies not specific to target will precipitate nonspecific RNA modifications<br>
</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22608085">MeRIP-Seq: Meyer K. D., Saletore Y., Zumbo P., Elemento O., Mason C. E., et al. (2012) Comprehensive analysis of mRNA methylation reveals enrichment in 3' UTRs and near stop codons. Cell 149: 1635-1646</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22575960">m6A-Seq:Dominissini D. et al. (2012) Topology of the human and mouse m6A RNA methylomes revealed by m6A-seq. Nature 485: 201-206</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html" target="_blank">TruSeq Small RNA Library Prep kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html" target="_blank">TruSeq Stranded total RNA library prep kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html" target="_blank">TruSeq DNA PCR-Free library prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27318512" target="_blank">Bian Q. and Cahan P. Computational Tools for Stem Cell Biology. Trends Biotechnol. 2016;</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27773535" target="_blank">Gokhale N. S., McIntyre A. B., McFadden M. J., et al. N6-Methyladenosine in Flaviviridae Viral RNA Genomes Regulates Infection. Cell Host Microbe. 2016;</a></li> 
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27117702" target="_blank">Lin S., Choe J., Du P., Triboulet R. and Gregory R. I. The m(6)A Methyltransferase METTL3 Promotes Translation in Human Cancer Cells. Mol Cell. 2016;62:335-345</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24979058" target="_blank">Meng J., Lu Z., Liu H., et al. A protocol for RNA methylation differential analysis with MeRIP-Seq data and exomePeak R/Bioconductor package. Methods. 2014;69:274-281</a></li>
</ol>

<h5>miCLIP-m6A*</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/miclip-m6a.png"></p>

<p>miCLIP-m6A maps m6A locations in the transcriptome with single-nucleotide resolution.  In this method, anti-m6A antibodies are crosslinked to mRNA sequences, and a cDNA library is prepared and sequenced. The cDNA library preparation in miCLIP follows the iCLIP protocol closely.
</p><p>Starting with total RNA, mRNA strands are isolated and fragmented. Anti-m6A antibodies are introduced and UV-crosslinked. The RNA-antibody complexes are immunoprecipitated and purified. Following the iCLIP cDNA library preparation protocol, the 3' ends of the RNA are dephosphorylated and ligated to 3' adapters. The RNA complexes are purified again before digesting the bound anti-m6A antibodies with proteinase K. The freed RNA strands are reverse-transcribed, and the resulting cDNA strands are circularized, relinearized, and PCR-amplified before sequencing. The m6A residues are identified accurately by analyzing the cDNA truncation and cytosine-to-thymine substitution patterns from the peptide residues on the RNA</p>
<h6>Pros:</h6>
<ul>
<li>Maps m6A locations transcriptome-wide with single-nucleotide resolution</li>
<li>Identifies m6A in small-RNA species</li>
<li>Able to identify m6Am in addition to m6A</li>
<li>Does not involve pretreating cells with 4-SU, as in PAR-CLIP</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Dependent on the consistency of antibodies used in producing C-to-T substitution patterns</li>
<li>cDNA library preparation uses radioactive labeling</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26121403">miCLIP-m6A: Linder B., Grozhik A. V., Olarerin-George A. O., Meydan C., Mason C. E., et al. (2015) Single-nucleotide-resolution mapping of m6A and m6Am throughout the transcriptome. Nat Methods </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23871666">*Note: The miCLIP method published by Linder et al. (2015) is distinctly different from the miCLIP method published by Hussain et al. (2013). We use the m6A designation to distinguish the two methods.</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26645578" target="_blank">Maity A. and Das B. N6-methyladenosine modification in mRNA: machinery, function and implications for health and diseases. FEBS J. 2016;283:1607-1630</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26593424" target="_blank">Meyer K. D., Patil D. P., Zhou J., et al. 5' UTR m(6)A Promotes Cap-Independent Translation. Cell. 2015;163:999-1010</a></li>
</ol>

<h5>Pseudo-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pseudo-seq.png"></p>

<p>mNPseudo-Seq detects pseudouridylation sites in ncRNAs with single-nucleotide resolution using high-throughput sequencing. Pseudo-Seq is very similar to PSI-seq, in that both methods use CMC to modify pseudouridines selectively and halt reverse transcription. However, Pseudo-Seq circularizes cDNA strands before PCR amplification and purification, instead of using ARTseq. Briefly, poly(A)-selected RNA is fragmented and treated with CMC. The RNA is dephosphorylated with CIP and PNK, and size-selected. Next, 3' adapters are ligated to RNA strands and reverse transcription is initiated. The truncated cDNAs resulting from CMC-modified pseudouridines are purified, circularized, and PCR-amplified. The purified cDNA libraries are sequenced by an NGS method.</p>
<p>Similar methods: PSI-seq, Ψ-Seq, CeU-Seq.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies pseudouridylation sites in ncRNAs</li>
<li>Provides single-nucleotide resolution</li>
<li>Identifies peaks by computationally calculating the ratio of reads at the initial mapped position to the total number of reads covering that position<sup>1</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Circularization step may introduce additional bias</li>
<li>Not yet adopted widely by the scientific community</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25192136" target="_blank">Pseudo-Seq: Carlile T. M., Rojas-Duran M. F., Zinshteyn B., Shin H., Bartoli K. M. and Gilbert W. V. Pseudouridine profiling reveals regulated mRNA pseudouridylation in yeast and human cells. Nature. 2014;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26968262" target="_blank">1. Zaringhalam M. and Papavasiliou F. N. Pseudouridylation meets next-generation sequencing. Methods. 2016;107:63-72</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26968262" target="_blank">Zaringhalam M. and Papavasiliou F. N. Pseudouridylation meets next-generation sequencing. Methods. 2016;107:63-72</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25192136" target="_blank">Carlile T. M., Rojas-Duran M. F., Zinshteyn B., Shin H., Bartoli K. M. and Gilbert W. V. Pseudouridine profiling reveals regulated mRNA pseudouridylation in yeast and human cells. Nature. 2014;</a></li>
</ol>

<h5>PSI-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/psi-seq.png"></p>

<p>PSI-Seq identifies RNA sequences containing pseudouridine sites using high-throughput sequencing.  PSI-Seq uses N-Cyclohexyl-N′-(2-morpholinoethyl)carbodiimide (CMC) to modify pseudouridines selectively, effectively halting reverse transcription. The cDNA libraries are prepared by the ARTseq method.
Briefly, samples are poly(A)-selected, treated with DNase, and fragmented. CMC is added to modify existing pseudouridines, and the 3′ ends of the RNA are ligated to linker-adapters. Next, the RNA fragments are reverse-transcribed to cDNA; however, upon encountering CMC-modified pseudouridines, reverse transcription is halted. cDNA strands of 20–80 nt are isolated and processed into cDNA libraries using the Ribo-Seq/ARTseq method before high-throughput sequencing.
</p><p>Similar methods: Pseudo-seq, Ψ-Seq, CeU-Seq.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies pseudouridylation sites in ncRNAs</li>
<li>Single-base resolution</li>
<li>Uses a regression analysis to compare reads in a specific location between treated and mock-treated libraries<sup>1</sup> </li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported yet	</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25353621" target="_blank">PSI-Seq: Lovejoy A. F., Riordan D. P. and Brown P. O. Transcriptome-Wide Mapping of Pseudouridines: Pseudouridine Synthases Modify Specific mRNAs in S. cerevisiae. PLoS One. 2014;9:e110799</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26968262" target="_blank">1. Zaringhalam M. and Papavasiliou F. N. Pseudouridylation meets next-generation sequencing. Methods. 2016;107:63-72</a></li>
</ul>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26968262" target="_blank">Zaringhalam M. and Papavasiliou F. N. Pseudouridylation meets next-generation sequencing. Methods. 2016;107:63-72</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25353621" target="_blank">Lovejoy A. F., Riordan D. P. and Brown P. O. Transcriptome-Wide Mapping of Pseudouridines: Pseudouridine Synthases Modify Specific mRNAs in S. cerevisiae. PLoS One. 2014;9:e110799</a></li>
</ol>

#### RNA-protein-interactions

<h5>AGO-CLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ago-clip.png"></p>

<p>Argonaute-crosslinking and immunoprecipitation (AGO-CLIP) is a protocol that maps miRNA binding to AGO sites in C. elegans.  In this method, the photoreactive nucleoside 4-SU is first incorporated into C. elegans RNA in vivo. The 4-SU–labeled RNA is crosslinked to bound protein, and the extracted lysate is treated with RNase T1, which shortens some miRNAs. After immunoprecipitation and washing, crosslinked RNA is treated with PNK, T4 RNA ligase, and finally proteinase K. The RNA is extracted, reverse-transcribed to cDNA, and sequenced. Deep sequencing provides single base-pair resolution of miRNA and AGO binding sites.</p>
<h6>Pros:</h6>
<ul>
<li>Maps miRNA binding to AGO sites using CLIP</li>
<li>Provides single base-pair resolution of the binding sites</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Low efficiency in hybrid capture</li>
<li>Unable to provide quantitative analysis of the strength of miRNA-target interactions<sup>1</sup> </li>
</ul>
<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24857550">AGO-CLIP: Grosswendt S., Filipchyk A., Manzano M., Klironomos F., Schilling M., et al. (2014) Unambiguous identification of miRNA:target site interactions by different types of ligation reactions. Mol Cell 54: 1042-1054</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25531890" target="_blank">1. Imig J., Brunschweiger A., Brummer A., et al. miR-CLIP capture of a miRNA targetome uncovers a lincRNA H19-miR-106a interaction. Nat Chem Biol. 2014;advance online publication:
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25359968" target="_blank">Schirle N. T., Sheu-Gruttadauria J. and MacRae I. J. Structural basis for microRNA targeting. Science. 2014;346:608-613</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27292025" target="_blank">Hamilton M. P., Rajapakshe K. I., Bader D. A., et al. The Landscape of microRNA Targeting in Prostate Cancer Defined by AGO-PAR-CLIP. Neoplasia. 2016;18:356-370</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25531890" target="_blank">Imig J., Brunschweiger A., Brummer A., et al. miR-CLIP capture of a miRNA targetome uncovers a lincRNA H19-miR-106a interaction. Nat Chem Biol. 2015;11:107-114</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25768906" target="_blank">Luna J. M., Scheel T. K., Danino T., et al. Hepatitis C Virus RNA Functionally Sequesters miR-122. Cell. 2015;160:1099-1110</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25800746" target="_blank">Wang P., Ning S., Zhang Y., et al. Identification of lncRNA-associated competing triplets reveals global patterns and prognostic markers for cancer. Nucleic Acids Res. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24857550" target="_blank">Grosswendt S., Filipchyk A., Manzano M., et al. Unambiguous identification of miRNA:target site interactions by different types of ligation reactions. Mol Cell. 2014;54:1042-1054</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24828673" target="_blank">Newie I., Sokilde R., Persson H., et al. The HER2-encoded miR-4728-3p regulates ESR1 through a non-canonical internal seed interaction. PLoS One. 2014;9:e97200</a></li>
</ol>

<h5>BrdU-CLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/brdu-clip.png"></p>

<p>BrdU-CLIP sequences the binding sites of RBPs with single-nucleotide resolution. BrdU-CLIP fixes a major problem in HITS-CLIP where 5' adapters are not attached to the cDNA due to premature termination of reverse transcription.  BrdU-CLIP uses BrdUTPs and primers with 3' and 5' adapters during reverse transcription. This method enables greater cDNA yield and attaches both 5' and 3' adapters in a single step.</p>
<p>First, RNA-protein complexes are UV-crosslinked, digested with RNase, and immunoprecipitated. 3' adapters are ligated to the RNA and reverse-crosslinked by proteinase K digestion. Some peptides from the crosslink remain bonded with the RNA strands, even after reverse-crosslinkage. RT is carried out using BrdUTPs and primers containing 3' and 5' adapters separated by an apurinic/apyrimidinic endonuclease (APE) cleavage site. The resultant cDNA is purified, circularized, and further purified by BrdU pull-down. Next, the cDNA is linearized by cleaving at the APE site, PCR-amplified, and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Sequences RNA-binding sites of RBPs with single-nucleotide resolution</li>
<li>Captures both truncated and nontruncated cDNAs, unlike HITS-CLIP</li>
<li>Provides higher cDNA yield due to BrdUTP</li>
<li>Attaches 3' and 5' adapters in one RT step</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Tube-column transfers can result in major loss of material<sup>1</sup> </li>
<li>Not yet adopted widely by the scientific community</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24613350">BrdU-CLIP: Weyn-Vanhentenryck S. M., Mele A., Yan Q., Sun S., Farny N., et al. (2014) HITS-CLIP and integrative modeling define the Rbfox splicing-regulatory network linked to brain development and autism. Cell Rep 6: 1139-1152</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27111506">1. Zarnegar B. J., Flynn R. A., Shen Y., Do B. T., Chang H. Y., et al. (2016) irCLIP platform for efficient characterization of protein-RNA interactions. Nat Methods 13: 489-492</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26593421" target="_blank">Scotti M. M. and Swanson M. S. RNA mis-splicing in disease. Nat Rev Genet. 2016;17:19-32</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27094079" target="_blank">Vuong C. K., Black D. L. and Zheng S. The neurogenetics of alternative splicing. Nat Rev Neurosci. 2016;17:265-281</a></li>
<li><a href="http://dx.doi.org/10.1007/978-94-017-7450-5_2" target="_blank">Hsiao Y.-H. E., Cass A. A., Bahn J. H., Lin X. and Xiao X. Global Approaches to Alternative Splicing and Its Regulation—Recent Advances and Open Questions. Transcriptomics and Gene Regulation. 2016;37-71</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25411354" target="_blank">Flynn R. A., Martin L., Spitale R. C., Do B. T., Sagan S. M., et al. Dissecting noncoding and pathogen RNA-protein interactomes. RNA. 2015;21:135-143</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24613350">Weyn-Vanhentenryck S. M., Mele A., Yan Q., Sun S., Farny N., et al. (2014) HITS-CLIP and integrative modeling define the Rbfox splicing-regulatory network linked to brain development and autism. Cell Rep 6: 1139-1152</a></li>
</ol>

<h5>CLASH-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/clash-seq.png"></p>

<p>CLASH maps RNA-RNA interactions.
In this method, RNA-protein complexes are UV-crosslinked and affinity-purified. RNA-RNA hybrids are ligated, isolated, and reverse-transcribed into cDNA. Deep sequencing of the cDNA provides high-resolution chimeric reads of RNA-RNA interactions.
</p><p>Similar methods: miTRAP, SPLASH, hiCLIP, RAP, RPL</p>
<h6>Pros:</h6>
<ul>
<li>Maps RNA-RNA interactions in vivo</li>
<li>Provides binding site–level resolution<sup>1</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Hybrid ligation may be difficult between short RNA fragments</li>
<li>Relatively low efficiency<sup>2</sup> </li>
<li>Requires known bait protein<sup>3</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21610164">CLASH-Seq: Kudla G., Granneman S., Hahn D., Beggs J. D. and Tollervey D. (2011) Cross-linking, ligation, and sequencing of hybrids reveals RNA-RNA interactions in yeast. Proc Natl Acad Sci U S A 108: 10010-10015</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25531890" target="_blank">1. Imig J., Brunschweiger A., Brummer A., et al. miR-CLIP capture of a miRNA targetome uncovers a lincRNA H19-miR-106a interaction. Nat Chem Biol. 2015;11:107-114</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25022902" target="_blank">2. Hausser J. and Zavolan M. Identification and consequences of miRNA-target interactions--beyond repression of gene expression. Nat Rev Genet. 2014;15:599-612</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27180905" target="_blank">3. Lu Z., Zhang Q. C., Lee B., et al. RNA Duplex Map in Living Cells Reveals Higher-Order Transcriptome Structure. Cell. 2016;165:1267-1279</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26590260" target="_blank">Chou C. H., Chang N. W., Shrestha S., et al. miRTarBase 2016: updates to the experimentally validated miRNA-target interactions database. Nucleic Acids Res. 2016;44:D239-247</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25022902" target="_blank">Hausser J. and Zavolan M. Identification and consequences of miRNA-target interactions--beyond repression of gene expression. Nat Rev Genet. 2014;15:599-612</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25531890" target="_blank">Imig J., Brunschweiger A., Brummer A., Guennewig B., Mittal N., et al. miR-CLIP capture of a miRNA targetome uncovers a lincRNA H19-miR-106a interaction. Nat Chem Biol. 2014;advance online publication:</a></li>
</ol>

<h5>DLAF</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/dlaf.png"></p>

<p>DLAF is a strand-specific RNA sequencing method that avoids second-strand cDNA synthesis by directly attaching unique double-stranded adapters to the first-strand cDNA. 
</p><p>First, mRNA is isolated and depleted of rRNA. Next, RNA fragments are partially hydrolyzed and annealed to random primers before RT. The resulting first-strand cDNA is purified and flanked with double-stranded adapters. One strand of each adapter, the annealing strand, contains uracils and an overhang with 5 or 6 random nucleotides that anneal to the cDNA. The other strand, the ligating strand, directly ligates to the last nucleotide of the cDNA strand. 3'-hexanediol is attached to the 3' ends of each adapter to reduce concatenation with other strands. The adapter-ligated cDNAs are purified and exposed to uracil-specific excision enzyme, to remove the annealing strands from the cDNA. This process results in single-stranded cDNA strands flanked by the ligated adapters. The cDNA is PCR-amplified, purified, and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Reads mRNA sequences solely from the first strand of cDNA</li>
<li>Sequences the 5' and 3' ends of mRNAs</li>
<li>Fewer steps ensure a high yield of cDNA library product</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Unable to differentiate between 5' capped and uncapped mRNA</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25607527" target="_blank">DLAF: Agarwal S., Macfarlan T. S., Sartor M. A. and Iwase S. (2015) Sequencing of first-strand cDNA library reveals full-length transcriptomes. Nat Commun 6: 6002</a></li>
</ul>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26804915" target="_blank">Iwase S., Brookes E., Agarwal S., Badeaux A. I., Ito H., et al. (2016) A Mouse Model of X-linked Intellectual Disability Associated with Impaired Removal of Histone Methylation. Cell Rep </a></li>
</ol>

<h5>eCLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/eclip.png"></p>

<p>eCLIP maps the binding sites of RBPs on their target RNAs using a modified individual nucleotide resolution CLIP (iCLIP) protocol, improving efficiency and decreasing execution complexity.  The hallmark of this method is the ligation of barcoded single-stranded DNA adapters, which reduce amplification bias significantly.
</p><p>First, RNA and the protein of interest are UV-crosslinked, followed by cell lysis and RNase I digestion. Next, the protein-RNA complexes are immunoprecipitated and ligated to an RNA adapter on the 3' end of the target RNA. The bound protein is removed by proteinase K digestion, and the RNA is reverse-transcribed. The resulting cDNA is ligated to single-stranded DNA adapters on the 3' end that contain either an N5 or N10 sequence to serve as unique identifiers against PCR duplicates. Finally, the paired-end cDNA fragments are amplified and sequenced.
</p><p>Similar methods: iCLIP, irCLIP, HITS-CLIP.</p>
<h6>Pros:</h6>
<ul>
<li>High-throughput mapping of protein-RNA binding sites</li>
<li>Barcoded adapters significantly reduce PCR duplicate reads and improves throughput</li>
<li>Improved ligation efficiency by ~1000 fold</li>
<li>Avoids usage of radioactive markers</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Antibodies not specific to target will precipitate nonspecific complexes</li>
<li>Cross-linking does not cover all RNA-binding domains<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27018577">eCLIP: Van Nostrand E. L., Pratt G. A., Shishkin A. A., Gelboin-Burkhart C., Fang M. Y., et al. (2016) Robust transcriptome-wide discovery of RNA-binding protein binding sites with enhanced CLIP (eCLIP). Nat Methods</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27243472">1. Martin G. and Zavolan M. (2016) Redesigning CLIP for efficiency, accuracy and speed. Nat Methods 13: 482-483</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-ribo-profile.html">ARTseq/TruSeq Ribo Profile</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27503141" target="_blank">Marchese D., de Groot N. S., Lorenzo Gotor N., Livi C. M. and Tartaglia G. G. Advances in the characterization of RNA-binding proteins. Wiley Interdiscip Rev RNA. 2016;7:793-810</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27847391" target="_blank">Manning K. S. and Cooper T. A. The roles of RNA processing in translating genotype to phenotype. Nat Rev Mol Cell Biol. 2017;18:102-114</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26990993" target="_blank">Sundararaman B., Zhan L., Blue S. M., et al. Resources for the Comprehensive Discovery of Functional RNA Elements. Mol Cell. 2016;61:903-913</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27068461">Conway Anne E., Van Nostrand Eric L., Pratt Gabriel A., Aigner S., Wilbert Melissa L., et al. (2016) Enhanced CLIP Uncovers IMP Protein-RNA Targets in Human Pluripotent Stem Cells Important for Cell Adhesion and Survival. Cell Reports</a></li>
</ol>

<h5>hiCLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/hiclip.png"></p>

<p>hiCLIP sequences RNA duplexes bound to RBPs in vivo.  The unique cloning and linker-adapter system in hiCLIP identifies whether the RBP-bound duplex originates from the same RNA or different RNAs.
</p><p>Similar to CLIP library preparation techniques, RNA and RBPs are UV-crosslinked, partially digested, and immunoprecipitated. The signature hiCLIP cloning and linker-adapters are ligated to both strands of the duplex. The 3' end of the linker-adapter is dephosphorylated and ligated to the 5' end of the other strand. The bound proteins are removed with proteinase K. The cDNA library is prepared in a similar dashion to iCLIP for high-throughput sequencing. The cloning and linker-adapters enable the mapping of the hybrid reads to the transcriptome and distinguish whether the duplex is formed by the same RNAs or different RNAs.</p>
<h6>Pros:</h6>
<ul>
<li>Maps RBP-bound RNA duplexes in vivo</li>
<li>Linker-adapter remediates physical and computational challenges seen in crosslinking, ligation, and sequencing of hybrids (CLASH)</li>
<li>Detects long-range RNA duplex interactions <sup>1</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Does not identify non-RBP-bound RNA duplexes</li>
<li>Technically complex procedure</li>
<li>Uses radioactive labeling</li>
<li>Artifacts may be introduced in the circularization step</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25799984">hiCLIP: HiClip: Sugimoto Y., Vigilante A., Darbo E., Zirra A., Militti C., et al. (2015) hiCLIP reveals the in vivo atlas of mRNA secondary structures recognized by Staufen 1. Nature 519: 491-494</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26923056">1. Lu Z. and Chang H. Y. (2016) Decoding the RNA structurome. Curr Opin Struct Biol 36: 142-148</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26923056" target="_blank">Lu Z. and Chang H. Y. Decoding the RNA structurome. Curr Opin Struct Biol. 2016;36:142-148</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27427309" target="_blank">Weidmann C. A., Mustoe A. M. and Weeks K. M. Direct Duplex Detection: An Emerging Tool in the RNA Structure Analysis Toolbox. Trends Biochem Sci. 2016;41:734-736</a></li>
<li><a href="http://www.nature.com/nmeth/journal/v12/n5/full/nmeth.3385.html" target="_blank">Nawy T. Structural biology: RNA structure served in vivo. Nature Methods. 2015;12:383-383</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25854184" target="_blank">Burgess D. J. RNA. Detailed probing of RNA structure in vivo. Nat Rev Genet. 2015;16:255</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25799984" target="_blank">Sugimoto Y., Vigilante A., Darbo E., et al. hiCLIP reveals the in vivo atlas of mRNA secondary structures recognized by Staufen 1. Nature. 2015;519:491-494</a></li>
</ol>

<h5>HITS-CLIP/CLIP-Seq/PTB-Seq <small>RNA</small></h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/hits-clip-clip-seq-ptb-seq.png"></p>

<p>Crosslinking and immunoprecipitation (CLIP), with the use of RNase T1 trimming, was first described by Ule et al. <sup>1</sup> and later applied to high-throughput sequencing to map protein-RNA binding sites in vivo.<sup>2</sup> This approach is similar to RIP-Seq but uses crosslinking to stabilize the protein-RNA complexes.</p>
<p>In HITS-CLIP, RNA-protein complexes are UV-crosslinked and immunoprecipitated. The protein-RNA complexes are treated with RNase T1, followed by proteinase K. RNA is extracted and reverse-transcribed to cDNA. Deep sequencing of the cDNA provides single-base resolution mapping of protein binding sites on RNA.</p>
<p>An improvement on the HITS-CLIP protocol was published by Gillen et al., which reduces artifacts from mispriming occurences.<sup>3</sup></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>Other versions: iCLIP, irCLIP, eCLIP, miCLIP</p>
<h6>Pros:</h6>
<ul>
<li>Crosslinking stabilizes the protein-target binding</li>
<li>UV crosslinking can be carried out in vivo</li>
<li>Provides low background and higher resolution of binding site, due to RNase digestion</li>
<li>No prior knowledge of the RNA is required</li>
<li>Genome-wide RNA screen</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Over-representation of the RT complement due to mispriming<sup>4</sup></li>
<li>Antibodies not specific to the target may precipitate nonspecific complexes.</li>
<li>UV crosslinking is not efficient and requires close protein-RNA interactions</li>
<li>Artifacts may be introduced during the crosslinking process</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19536157">HITS-CLIP: Chi SW, Zang JB, Mele A, Darnell RB; (2009) Argonaute HITS-CLIP decodes microRNA-mRNA interaction maps. Nature 460: 479-86</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/17540862">CLIP-Seq: Johnson D. S., Mortazavi A., Myers R. M. and Wold B. (2007) Genome-wide mapping of in vivo protein-DNA interactions. Science 316: 1497-1502</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20064465">PTB-Seq: Xue Y., Zhou Y., Wu T., Zhu T., Ji X., et al. (2009) Genome-wide analysis of PTB-RNA interactions reveals a strategy used by the general splicing repressor to modulate exon inclusion or skipping. Mol Cell 36: 996-1006</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/16314267" target="_blank">1. Ule J., Jensen K., Mele A. and Darnell R. B. CLIP: a method for identifying protein-RNA interaction sites in living cells. Methods. 2005;37:376-386</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18978773" target="_blank">2. Licatalosi D. D., Mele A., Fak J. J., et al. HITS-CLIP yields genome-wide insights into brain alternative RNA processing. Nature. 2008;456:464-469</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27150721" target="_blank">3. Gillen A. E., Yamamoto T. M., Kline E., Hesselberth J. R. and Kabos P. Improvements to the HITS-CLIP protocol eliminate widespread mispriming artifacts. BMC Genomics. 2016;17:338</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27150721" target="_blank">4. Gillen A. E., Yamamoto T. M., Kline E., Hesselberth J. R. and Kabos P. Improvements to the HITS-CLIP protocol eliminate widespread mispriming artifacts. BMC Genomics. 2016;17:338</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25504152" target="_blank">Cook K. B., Hughes T. R. and Morris Q. D. High-throughput characterization of protein-RNA interactions. Brief Funct Genomics. 2015;14:74-89</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27356879" target="_blank">Van Haute L., Dietmann S., Kremer L., et al. Deficient methylation and formylation of mt-tRNA(Met) wobble cytosine in a patient carrying mutations in NSUN3. Nat Commun. 2016;7:12039</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26950602" target="_blank">Vourekas A., Alexiou P., Vrettos N., Maragkakis M. and Mourelatos Z. Sequence-dependent but not sequence-specific piRNA adhesion traps mRNAs to the germ plasm. Nature. 2016;531:390-394</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26900662" target="_blank">Ji Z., Song R., Huang H., Regev A. and Struhl K. Transcriptome-scale RNase-footprinting of RNA-protein complexes. Nat Biotechnol. 2016;34:410-413</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26748710" target="_blank">Gosline S. J., Gurtan A. M., JnBaptiste C. K., et al. Elucidating MicroRNA Regulatory Networks Using Transcriptional, Post-transcriptional, and Histone Modification Measurements. Cell Rep. 2016;14:310-319</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27239029" target="_blank">Nutter C. A., Jaworski E. A., Verma S. K., et al. Dysregulation of RBFOX2 Is an Early Event in Cardiac Pathogenesis of Diabetes. Cell Rep. 2016;15:2200-2213</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27418678" target="_blank">Spengler R. M., Zhang X., Cheng C., et al. Elucidation of transcriptome-wide microRNA binding sites in human cardiac tissues by Ago2 HITS-CLIP. Nucleic Acids Res. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27150721" target="_blank">Gillen A. E., Yamamoto T. M., Kline E., Hesselberth J. R. and Kabos P. Improvements to the HITS-CLIP protocol eliminate widespread mispriming artifacts. BMC Genomics. 2016;17:338</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26914319" target="_blank">Moore M. J., Zhang C., Gantman E. C., Mele A., Darnell J. C. and Darnell R. B. Erratum: Mapping Argonaute and conventional RNA-binding protein interactions with RNA at single-nucleotide resolution using HITS-CLIP and CIMS analysis. Nat Protoc. 2016;11:616</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27034466" target="_blank">Bennett C. G., Riemondy K., Chapnick D. A., Bunker E., Liu X., et al. Genome-wide analysis of Musashi-2 targets reveals novel functions in governing epithelial cell migration. Nucleic Acids Res. 2016;44:3788-3800</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26950602" target="_blank">Vourekas A., Alexiou P., Vrettos N., Maragkakis M. and Mourelatos Z. Sequence-dependent but not sequence-specific piRNA adhesion traps mRNAs to the germ plasm. Nature. 2016;531:390-394</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27050392" target="_blank">Zheng Q., Bao C., Guo W., et al. Circular RNA profiling reveals an abundant circHIPK3 that regulates cell growth by sponging multiple miRNAs. Nat Commun. 2016;7:11215</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26998997" target="_blank">Preusse M., Theis F. J. and Mueller N. S. miTALOS v2: Analyzing Tissue Specific microRNA Function. PLoS One. 2016;11:e0151771</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27378374" target="_blank">Kapeli K., Pratt G. A., Vu A. Q., et al. Distinct and shared functions of ALS-associated proteins TDP-43, FUS and TAF15 revealed by multisystem analyses. Nat Commun. 2016;7:12143</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27180681" target="_blank">Valentin-Vega Y. A., Wang Y. D., Parker M., et al. Cancer-associated DDX3X mutations drive stress granule assembly and impair global translation. Sci Rep. 2016;6:25996</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26867678" target="_blank">Chen S., Blank M. F., Iyer A., et al. SIRT7-dependent deacetylation of the U3-55k protein controls pre-rRNA processing. Nat Commun. 2016;7:10734</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27003248" target="_blank">Zhao H., Chen M., Lind S. B. and Pettersson U. Distinct temporal changes in host cell lncRNA expression during the course of an adenovirus infection. Virology. 2016;492:242-250</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26907613" target="_blank">Taliaferro J. M., Vidaki M., Oliveira R., et al. Distal Alternative Last Exons Localize mRNAs to Neural Projections. Mol Cell. 2016;61:821-833</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27271479" target="_blank">Gaudreau M. C., Grapton D., Helness A., et al. Heterogeneous Nuclear Ribonucleoprotein L is required for the survival and functional integrity of murine hematopoietic stem cells. Sci Rep. 2016;6:27379</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27229370" target="_blank">Dugar G., Svensson S. L., Bischler T., Waldchen S., Reinhardt R., et al. The CsrA-FliW network controls polar localization of the dual-function flagellin mRNA in Campylobacter jejuni. Nat Commun. 2016;7:11667</a></li>
</ol>

<h5>HiTS-RAP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/hits-rap.png"></p>

<p>HiTS-RAP is a quantitative method to evaluate binding interactions of RNA aptamers with their proteins at a massive scale. ,  HiTS-RAP transcribes DNA directly on the flow cell and measures the binding affinity of RNA aptamers with fluorescently labeled proteins.
</p><p>First, sequencing libraries are prepared and sequenced on the Illumina flow cell. Next, the second strand of the DNA is removed and the single-stranded DNA attached to the flow cell is annealed to primers containing a 32 bp Ter sequence. An Escherichia coli replication terminator protein (Tus) is introduced into the system and binds to the Ter sequence. RNA transcription by T7 RNA polymerase begins and halts upstream of the Tus-bound Ter site. Because the RNA polymerase activity was halted abruptly due to the Tus bound to the DNA, the RNA strand is still linked to the RNA polymerase complex. Fluorescently labeled proteins are introduced and bind to the exposed RNA aptamers, producing a fluorescent signal that can be read by the sequencer.
</p><p>Similar methods: RBNS, RNA-MaP.</p>
<h6>Pros:</h6>
<ul>
<li>Quantitatively evaluates binding affinity of RNA aptamers on a massively parallel scale.</li>
<li>Can be adapted easily to nonprotein molecules</li>
<li>	Able to determine de novo binding specificity of RBPs</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to analysis of RNA fragments 150 nt or shorter, unless paired-end sequencing protocols are used, which increases the limit to 500 nt</li>
<li>Unable to measure binding kinetics, such as on and off rates</li>
<li>Susceptible to steric hindrance effects usually present in large proteins</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24809628">HiTS-RAP: Tome J. M., Ozer A., Pagano J. M., Gheba D., Schroth G. P., et al. (2014) Comprehensive analysis of RNA-protein interactions by high-throughput sequencing-RNA affinity profiling. Nat Methods 11: 683-688</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26182240">HiTS-RAP Protocol: Ozer A., Tome J. M., Friedman R. C., Gheba D., Schroth G. P., et al. (2015) Quantitative assessment of RNA-protein interactions with high-throughput sequencing-RNA affinity profiling. Nat Protoc 10: 1212-1233</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27503141" target="_blank">Marchese D., de Groot N. S., Lorenzo Gotor N., Livi C. M. and Tartaglia G. G. Advances in the characterization of RNA-binding proteins. Wiley Interdiscip Rev RNA. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25636997" target="_blank">Campbell Z. T. and Wickens M. Probing RNA-protein networks: biochemistry meets genomics. Trends Biochem Sci. 2015;40:157-164</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24809628" target="_blank">Tome J. M., Ozer A., Pagano J. M., Gheba D., Schroth G. P. and Lis J. T. Comprehensive analysis of RNA-protein interactions by high-throughput sequencing-RNA affinity profiling. Nat Methods. 2014;11:683-688</a></li>
</ol>

<h5>iCLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/iclip.png"></p>

<p>iCLIP maps protein-RNA interactions, in a process similar to HITS-CLIP and PAR-CLIP.  This approach includes additional steps to digest the proteins after crosslinking and to map the crosslink sites with reverse transcriptase. 
</p><p>In iCLIP, specific crosslinked RNA-protein complexes are immunoprecipitated. The complexes are treated with proteinase K, as the protein crosslinked at the binding site remains undigested. Upon RT, cDNA truncates at the binding site and is circularized. These circularized fragments are linearized and PCR-amplified. Deep sequencing of these amplified fragments provides nucleotide resolution of the protein-binding site  eCLIP is an improvement over iCLIP that avoids circularizing the cDNA to reduce artifacts. 
</p><p>Other versions: HITS-CLIP, PAR-CLIP, eCLIP, irCLIP.</p>
<h6>Pros:</h6>
<ul>
<li>Nucleotide resolution of protein-binding sites</li>
<li>Avoids the use of nucleases</li>
<li>Amplification allows the detection of rare events</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Antibodies not specific to target will precipitate nonspecific complexes</li>
<li>Nonlinear PCR amplification can lead to biases affecting reproducibility</li>
<li>Artifacts may be introduced in the circularization step</li>
<li>Radioisotopes required for visualization of UV-crosslinked protein-RNA complexes only label 5' ends </li>
<li>Circular ligation can be inefficient </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/20601959" target="_blank">iCLIP: Konig J., Zarnack K., Rot G., Curk T., Kayikci M., et al. (2010) iCLIP reveals the function of hnRNP particles in splicing at individual nucleotide resolution. Nat Struct Mol Biol 17: 909-915</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25504152" target="_blank">Cook K. B., Hughes T. R. and Morris Q. D. High-throughput characterization of protein-RNA interactions. Brief Funct Genomics. 2015;14:74-89</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26463384" target="_blank">Sutandy F. X., Hildebrandt A. and Konig J. Profiling the Binding Sites of RNA-Binding Proteins with Nucleotide Resolution Using iCLIP. Methods Mol Biol. 2016;1358:175-195</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27210763" target="_blank">Ennajdaoui H., Howard J. M., Sterne-Weiler T., Jahanbani F., Coyne D. J., et al. IGF2BP3 Modulates the Interaction of Invasion-Associated Transcripts with RISC. Cell Rep. 2016;15:1876-1883</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26697379" target="_blank">Misra A., Ou J., Zhu L. J. and Green M. R. Global analysis of CPSF2-mediated alternative splicing: Integration of global iCLIP and transcriptome profiling data. Genom Data. 2015;6:217-221</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27114556" target="_blank">Wang Q., Taliaferro J. M., Klibaite U., Hilgers V., Shaevitz J. W., et al. The PSI-U1 snRNP interaction regulates male mating behavior in Drosophila. Proc Natl Acad Sci U S A. 2016;113:5269-5274</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26748710" target="_blank">Gosline S. J., Gurtan A. M., JnBaptiste C. K., Bosson A., Milani P., et al. Elucidating MicroRNA Regulatory Networks Using Transcriptional, Post-transcriptional, and Histone Modification Measurements. Cell Rep. 2016;14:310-319</a></li>
</ol>

<h5>irCLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/irclip.png"></p>

<p>irCLIP maps protein-RNA interaction sites using less sample material, time, and increased cDNA library quality compared to previous CLIP methods.  irCLIP was designed to tackle the issues in both iCLIP and HITS-CLIP, such as reverse-transcriptase halting and short cDNA library fragments, by using on-bead nuclease digestion.
</p><p>First, RNA-protein complexes are UV-crosslinked and immunoprecipitated. Next, they are digested using RNase A and RNase I to excise both ends of the protein-bound RNA strand. An IR800-biotin adapter is ligated to the 3' end of the RNA fragment. After size selection, nitrocellulose blotting, and proteinase K digestion, the RNA strands of interest are purified. They are reverse-transcribed and immunopurified once again. The cDNA strands are circularized and PCR-amplified to produce cDNA libraries for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Nonisotopic detection of protein-RNA interactions with minimal starting material</li>
<li>On-bead nuclease digestion improves the length of RNA fragments for cDNA library prep</li>
<li>Able to accommodate small cell samples and reveal novel RBP binding sites</li>
<li>Uses thermostable reverse transcriptase at 60°C, reducing biases by melting secondary RNA structures<sup>1</sup> </li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not widely adapted by the scientific community yet</li>
<li>Circularization step may introduce artifacts</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27111506">irCLIP: Zarnegar B. J., Flynn R. A., Shen Y., Do B. T., Chang H. Y., et al. (2016) irCLIP platform for efficient characterization of protein-RNA interactions. Nat Methods 13: 489-492</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27243472">1. Martin G. and Zavolan M. (2016) Redesigning CLIP for efficiency, accuracy and speed. Nat Meth 13: 482-483</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27243472" target="_blank">Martin G. and Zavolan M. Redesigning CLIP for efficiency, accuracy and speed. Nat Methods. 2016;13:482-483</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27259196" target="_blank">Haque N. and Hogg J. R. Easier, Better, Faster, Stronger: Improved Methods for RNA-Protein Interaction Studies. Mol Cell. 2016;62:650-651</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27111506" target="_blank">Zarnegar B. J., Flynn R. A., Shen Y., Do B. T., Chang H. Y. and Khavari P. A. irCLIP platform for efficient characterization of protein-RNA interactions. Nat Methods. 2016;13:489-492</a></li>
</ol>

<h5>MiR-CLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mir-clip.png"></p>

<p>miR-CLIP was developed to identify mRNA targets of miRNA, using synthetic miRNAs.  The capture probes in miR-CLIP are pre-miRNAs conjugated to psoralen and biotin that can be crosslinked with mRNA to isolate their targets from total RNA.
</p><p>First, a miR-CLIP capture probe needs to be designed and tested for functionality and strong binding affinity. Next, they are transfected into cells and UV-crosslinked at 254 nm and 365 nm, followed by immunoprecipitation of the crosslinked complex. The RNA is extracted and further purified by streptavidin pull-down. The isolated RNA targets can now be reverse-transcribed and processed into cDNA libraries for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies targets of miRNAs genome-wide</li>
<li>Capture probe miRNA sequence can be easily modified to investigate different miRNA species</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not yet widely adapted by the scientific community </li>
<li>Requires careful design of miRNA capture probes</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25531890">MiR-CLIP: Imig J., Brunschweiger A., Brummer A., Guennewig B., Mittal N., et al. (2014) miR-CLIP capture of a miRNA targetome uncovers a lincRNA H19-miR-106a interaction. Nat Chem Biol advance online publication: </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/molecular-biology-reagents/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit (Human/Mouse/Rat)</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://dx.doi.org/10.1007/978-94-017-7417-8_7" target="_blank">Sandhu G. K., Milevskiy M. J. G., Wilson W., Shewan A. M. and Brown M. A. Non-coding RNAs in Mammary Gland Development and Disease. Non-coding RNA and the Reproductive System. 2016;121-153</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27105038" target="_blank">Yu B. and Shan G. Functions of long noncoding RNAs in the nucleus. Nucleus. 2016;7:155-166</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26021286" target="_blank">Jeker L. T. and Marone R. Targeting microRNAs for immunomodulation. Curr Opin Pharmacol. 2015;23:25-31</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25792595" target="_blank">Tycowski K. T., Guo Y. E., Lee N., et al. Viral noncoding RNAs: more surprises. Genes Dev. 2015;29:567-584</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25531890" target="_blank">Imig J., Brunschweiger A., Brummer A., et al. miR-CLIP capture of a miRNA targetome uncovers a lincRNA H19-miR-106a interaction. Nat Chem Biol. 2014;advance online publication:</a></li>
</ol>

<h5>miTRAP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mitrap.png"></p>

<p>miTRAP identifies the target RNA sequences of miRNA species in vitro utilizing MS2 stem loops attached to the target RNA sequence as bait for the miRNA.  MS2 is a 19 nt bacteriophage RNA sequence present at the ribosomal binding site of the MS2 replicase mRNA that folds into a hairpin loop structure.
</p><p>First, MS2 bait transcripts are transcribed in vitro. The miRNA-protein-RNA complexes are captured by immobilization on amylose resin. The RNA-protein complexes are incubated with cellular extracts, and the extracted RNA-protein complexes are eluted using maltose solution. miRNAs are purified from the maltose solution by a phenol-chloroform extraction, while protein analysis is carried out after incubating the resin with SDS-sample buffer containing 10% beta-mercaptoethanol. miRNA eluates are prepared into cDNA libraries, using standard small-RNA Library Prep Kit, and sequenced.
</p><p>Similar methods: CLASH.</p>
<h6>Pros:</h6>
<ul>
<li>Enables in vitro identification of miRNA targets</li>
<li>Also identifies novel and noncanonical miRNA target sequences involved in gene regulation</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not yet validated for analyzing trans-acting RBPs or lncRNAs that affect miRNA targeting</li>
<li>Unable to incorporate UV or chemical-based protein-RNA crosslinking prior to cell lysis</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24510096">miTRAP: Braun J., Misiak D., Busch B., Krohn K., Huttelmaier S. (2014) Rapid identification of regulatory microRNAs by miTRAP (miRNA trapping by RNA in vitro affinity purification). Nucleic Acids Res 42:e66</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27142884" target="_blank">Seliger B. Role of microRNAs on HLA-G expression in human tumors. Hum Immunol. 2016;77:760-763</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27047316" target="_blank">Elton T. S. and Yalowich J. C. Experimental procedures to identify and validate specific mRNA targets of miRNAs. EXCLI J. 2015;14:758-790</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27057628" target="_blank">Jasinski-Bergner S., Reches A., Stoehr C., et al. Identification of novel microRNAs regulating HLA-G expression and investigating their clinical relevance in renal cell carcinoma. Oncotarget. 2016;7:26866-26878</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25228695" target="_blank">Jasinski-Bergner S., Stehle F., Gonschorek E., et al. Identification of 14-3-3beta gene as a novel miR-152 target using a proteome-based approach. J Biol Chem. 2014;289:31121-31135</a></li>
</ol>

<h5>Par-CLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/par-clip.png"></p>

<p>PAR-CLIP maps RBP sites on the target RNAs.  This approach is similar to HITS-CLIP and CLIP-Seq, but it uses much more efficient crosslinking to stabilize the protein-RNA complexes. The requirement to introduce a photoactivatable ribonucleoside limits this approach to cell culture and in vitro systems. 
</p><p>In this method, 4-SU and 6-thioguanosine (6-SG) are incorporated into transcripts of cultured cells. UV irradiation crosslinks 4-SU/6-SG–labeled transcripts to interacting RBPs. The targeted complexes are immunoprecipitated and digested with RNase T1, followed by proteinase K, before RNA extraction. The RNA is reverse-transcribed to cDNA and sequenced. Deep sequencing of cDNA accurately maps RBPs interacting with labeled transcripts.</p>
<h6>Pros:</h6>
<ul>
<li>Highly accurate mapping of RNA-protein interactions</li>
<li>Labeling with 4-SU/6-SG improves crosslinking efficiency</li>
<li>Legitimately crosslinked sequences can be identified based on the presence of mutated bases, and mispriming can be filtered bioinformatically<sup>1</sup> </li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Antibodies not specific to the target may precipitate nonspecific complexes</li>
<li>Limited to cell culture and in vitro systems</li>
<li>Photoreactive nucleosides can be cytotoxic<sup>2</sup> </li>
<li>High concentrations of 4-SU can inhibit rRNA synthesis and induce a nucleolar stress response<sup>3</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/18158127" target="_blank">Par-CLIP: Hafner M., Landgraf P., Ludwig J., Rice A., Ojo T., et al. (2008) Identification of microRNAs and other small regulatory RNAs using cDNA library sequencing. Methods 44: 3-12</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27150721" target="_blank">1. Gillen A. E., Yamamoto T. M., Kline E., Hesselberth J. R. and Kabos P. Improvements to the HITS-CLIP protocol eliminate widespread mispriming artifacts. BMC Genomics. 2016;17:338</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24951655" target="_blank">2. Kloetgen A., Munch P. C., Borkhardt A., Hoell J. I. and McHardy A. C. Biochemical and bioinformatic methods for elucidating the role of RNA-protein interactions in posttranscriptional regulation. Brief Funct Genomics. 2015;14:102-114</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24025460" target="_blank">3. Burger K., Muhl B., Kellner M., et al. 4-thiouridine inhibits rRNA synthesis and causes a nucleolar stress response. RNA Biol. 2013;10:1623-1630</a></li>
</ul>

<h6>Associated kits:</h6>
<ul class="kits solutions">
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/rrna-globin-mrna-removal-kit-selection-guide.html" target="_blank">Ribo-Zero Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Sample Prep Kit</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html" target="_blank">TruSeq Stranded RNA</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free library prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep kit</a></li>
</ul>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25504152" target="_blank">Cook K. B., Hughes T. R. and Morris Q. D. High-throughput characterization of protein-RNA interactions. Brief Funct Genomics. 2015;14:74-89</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27406171" target="_blank">Tichon A., Gil N., Lubelsky Y., Havkin Solomon T., Lemze D., et al. A conserved abundant cytoplasmic long noncoding RNA modulates repression by Pumilio proteins in human cells. Nat Commun. 2016;7:12209</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26226348" target="_blank">Vongrad V., Imig J., Mohammadi P., et al. HIV-1 RNAs are Not Part of the Argonaute 2 Associated RNA Interference Pathway in Macrophages. PLoS One. 2015;10:e0132127</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25719671" target="_blank">Liu N., Dai Q., Zheng G., He C., Parisien M. and Pan T. N(6)-methyladenosine-dependent RNA structural switches regulate RNA-protein interactions. Nature. 2015;518:560-564</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26170170" target="_blank">Murakawa Y., Hinz M., Mothes J., et al. RC3H1 post-transcriptionally regulates A20 mRNA and modulates the activity of the IKK/NF-kappaB pathway. Nat Commun. 2015;6:7367</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26070070" target="_blank">Kang D., Skalsky R. L. and Cullen B. R. EBV BART MicroRNAs Target Multiple Pro-apoptotic Cellular Genes to Promote Epithelial Cell Survival. PLoS Pathog. 2015;11:e1004979</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27462443" target="_blank">Matveeva E., Maiorano J., Zhang Q., et al. Involvement of PARP1 in the regulation of alternative splicing. Cell Discov. 2016;2:15046</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26668354" target="_blank">Porter D. F., Koh Y. Y., VanVeller B., Raines R. T. and Wickens M. Target selection by natural and redesigned PUF proteins. Proc Natl Acad Sci U S A. 2015;112:15868-15873</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27114556" target="_blank">Wang Q., Taliaferro J. M., Klibaite U., Hilgers V., Shaevitz J. W. and Rio D. C. The PSI-U1 snRNP interaction regulates male mating behavior in Drosophila. Proc Natl Acad Sci U S A. 2016;113:5269-5274</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25849773" target="_blank">Lee A. S., Kranzusch P. J. and Cate J. H. eIF3 targets cell-proliferation messenger RNAs for translational activation or repression. Nature. 2015;522:111-114</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25813040" target="_blank">Chu Y., Wang T., Dodd D., Xie Y., Janowski B. A. and Corey D. R. Intramolecular circularization increases efficiency of RNA sequencing and enables CLIP-Seq of nuclear RNA from human cells. Nucleic Acids Res. 2015;43:e75</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25156441" target="_blank">Xie H., Lee L., Scicluna P., et al. Novel functions and targets of miR-944 in human cervical cancer cells. Int J Cancer. 2015;136:E230-241</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26308709" target="_blank">Xiong X. P., Vogler G., Kurthkoti K., Samsonova A. and Zhou R. SmD1 Modulates the miRNA Pathway Independently of Its Pre-mRNA Splicing Function. PLoS Genet. 2015;11:e1005475</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25683224" target="_blank">Chen T., Hao Y. J., Zhang Y., et al. m(6)A RNA Methylation Is Regulated by MicroRNAs and Promotes Reprogramming to Pluripotency. Cell Stem Cell. 2015;16:289-301</a></li>
</ol>

<h5>PIP-Seq<br>
</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pip-seq.png"></p>

<p>PIP-Seq sequences RBP interaction sites on both unprocessed and mature RNA species in crosslinked or noncrosslinked cells. In PIP-seq, both RNase-sensitive and RNase-insensitive fragments are isolated and processed separately to differentiate which sequences are actually bound to RBPs and which are just insensitive to RNases.</p>
<p>First, crosslinked (through UV or formaldehyde) or noncrosslinked cells are lysed. The lysates are split into 2 batches: experimental and RNase-insensitivity control. The experimental/footprint samples are digested with double-stranded RNase (dsRNase) or single-stranded RNase (ssRNase) and subsequently treated with proteinase K to remove the RBPs. However, to screen for regions insensitive to RNases, the controls are first treated with proteinase K and then with ssRNase or dsRNase. Both sets of fragments are reverse-crosslinked and used to prepare strand-specific libraries. Each library is normalized using rehybridization and a thermostable duplex-specific nuclease, and then sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Sequences RNA regions bound to RBPs in unprocessed or mature RNAs</li>
<li>Identifies regions that are insensitive to RNases</li>
<li>Can be used on tissues and whole organisms</li>
<li>Strand-specific</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited resolution of small nucleotide bulges and loops<sup>1</sup></li>
<li>Formaldehyde crosslinking presents a risk of protein-protein linking, in addition to protein-RNA linking<sup>1</sup></li>
<li>Nucleases have limited diffusability into plant cells; an advantage of chemical probes, such as dimethyl sulfate (DMS)<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24393486">PIP-Seq: Silverman I. M., Li F., Alexander A., Goff L., Trapnell C., et al. (2014) RNase-mediated protein footprint sequencing reveals protein-binding sites throughout the human transcriptome. Genome Biology 15: R3</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25448484">PIP-Seq: Silverman I. M. and Gregory B. D. (2014) Transcriptome-wide ribonuclease-mediated protein footprinting to identify RNA-protein interaction sites. Methods </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26119389">1. Foley S. W., Vandivier L. E., Kuksa P. P. and Gregory B. D. (2015) Transcriptome-wide measurement of plant RNA secondary structure. Curr Opin Plant Biol 27: 36-43</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-stranded-total-rna.html">TruSeq Stranded Total RNA</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/molecular-biology-reagents/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit (Human/Mouse/Rat)</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://onlinelibrary.wiley.com/doi/10.1002/cppb.20001/abstract" target="_blank">Anderson S. J., Willmann M. R. and Gregory B. D. Protein Interaction Profile Sequencing (PIP-seq) in Plants. Current Protocols in Plant Biology. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26119389" target="_blank">Foley S. W., Vandivier L. E., Kuksa P. P. and Gregory B. D. Transcriptome-wide measurement of plant RNA secondary structure. Curr Opin Plant Biol. 2015;27:36-43</a></li>	
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26107901" target="_blank">Popova V. V., Kurshakova M. M. and Kopytova D. V. [Methods to study the RNA-protein interactions]. Mol Biol (Mosk). 2015;49:472-481</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25557549" target="_blank">Gosai S. J., Foley S. W., Wang D., et al. Global analysis of the RNA-protein interaction and RNA secondary structure landscapes of the Arabidopsis nucleus. Mol Cell. 2015;57:376-388</a></li>
</ol>

<h5>Pol II CLIP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/poliiclip.png"></p>

<p>Pol II CLIP was developed to isolate and sequence noncoding RNAs involved in transcriptional regulation, particularly RNAPII-mediated transcription.  
Briefly, cells are UV-crosslinked at 254 nm and lysed. Anti-RNAPII antibodies are used to immunoprecipitate the RNAPII complexes. Next, the RNAPII complexes are separated via proteinase K reverse-crosslinking. The released RNA released is isolated, reverse-transcribed, and prepared into sequencing libraries. The CLIP RNA samples are ready for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies ncRNA sequences involved in transcriptional regulation</li>
<li>Simple procedure</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>None reported yet</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25664725">Pol II CLIP: Li Z., Huang C., Bao C., Chen L., Lin M., et al. (2015) Exon-intron circular RNAs regulate transcription in the nucleus. Nat Struct Mol Biol </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26052092" target="_blank">Qu S., Yang X., Li X., Wang J., Gao Y., et al. Circular RNA: A new star of noncoding RNAs. Cancer Lett. 2015;365:141-148</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25664725" target="_blank">Li Z., Huang C., Bao C., et al. Exon-intron circular RNAs regulate transcription in the nucleus. Nat Struct Mol Biol. 2015;</a></li>
</ol>

<h5>RBNS</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rbns.png"></p>

<p>RBNS characterizes RBPs by high-throughput quantification of their binding affinity, dissociation constants, and the effects of secondary RNA structures on binding.  RBNS performs deep sequencing on random short RNA oligonucleotides bound to pools of fluorescently labeled RBPs of different concentrations.
</p><p>
First, RBPs with streptavidin tags are separated into different concentrations pools. Next, they are added to a pool of random RNA fragments. Each RNA oligonucleotide is made up of high- and low-affinity binding sites that are flanked by sequencing adapters at both ends. After the RBPs bind to their target RNAs, the complexes are purified by streptavidin pull-down and the bound RNAs are eluted out. Standard cDNA library preparation procedures are carried out to produce the sequencing library.
</p><p>
Similar methods: HiTS-RAP.</p>
<h6>Pros:</h6>
<ul>
<li>Characterizes sequence and specificity of RBPs</li>
<li>Complements crosslinking-based methods</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Only uses a single round of selection, yielding shorter core RBP sites<sup>1</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24837674">RBNS: Lambert N., Robertson A., Jangi M., McGeary S., Sharp PA., et al. (2014) RNA Bind-n-Seq: quantitative assessment of the sequence and structural binding specificity of RNA binding proteins.Mol Cell 54:887-900</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25636997" target="_blank">1. Campbell Z. T. and Wickens M. Probing RNA-protein networks: biochemistry meets genomics. Trends Biochem Sci. 2015;40:157-164</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25636997" target="_blank">Campbell Z. T. and Wickens M. Probing RNA-protein networks: biochemistry meets genomics. Trends Biochem Sci. 2015;40:157-164</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27720642" target="_blank">Taliaferro J. M., Lambert N. J., Sudmant P. H., et al. RNA Sequence Context Effects Measured In Vitro Predict In Vivo Protein Binding and Regulation. Mol Cell. 2016;64:294-306</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27378374" target="_blank">Kapeli K., Pratt G. A., Vu A. Q., Hutt K. R., Martinez F. J., et al. Distinct and shared functions of ALS-associated proteins TDP-43, FUS and TAF15 revealed by multisystem analyses. Nat Commun. 2016;7:12143</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27068461" target="_blank">Conway Anne E., Van Nostrand Eric L., Pratt Gabriel A., Aigner S., Wilbert Melissa L., et al. Enhanced CLIP Uncovers IMP Protein-RNA Targets in Human Pluripotent Stem Cells Important for Cell Adhesion and Survival. Cell Reports. 2016;</a></li>
</ol>

<h5>Ribo-Seq/ART-Seq/GTI-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/ribo-seq-art-seq-gti-seq.png"></p>

<p>Ribosome profiling (Ribo-Seq), also called active mRNA translation sequencing (ARTseq), isolates RNA that is being processed by the ribosome in order to monitor the translation process.  
</p><p>In this method, ribosome-bound RNA first undergoes digestion. The RNA is extracted, and the rRNA is depleted. The extracted RNA is reverse-transcribed to cDNA. Deep sequencing of the cDNA provides the sequences of RNAs bound by ribosomes during translation. This method has been refined to improve both the qualitative and quantitative nature of the results. Careful attention should be paid to: 1) generation of cell extracts in which ribosomes have been faithfully halted along the mRNA they are translating in vivo; 2) nuclease digestion of RNAs that are not protected by the ribosome, followed by recovery of the ribosome-protected mRNA fragments; and 3) quantitative conversion of the protected RNA fragments into a DNA library that can be analyzed by deep sequencing.  The addition of harringtonine (an alkaloid that inhibits protein biosynthesis) causes ribosomes to accumulate precisely at initiation codons and assists in their detection.</p>
<h6>Pros:</h6>
<ul>
<li>Reveals a snapshot with the precise location of ribosomes on the RNA</li>
<li>More closely reflects the rate of protein synthesis than mRNA levels </li>
<li>No prior knowledge of the RNA or open-reading frames (ORFs) is required</li>
<li>Surveys the whole genome</li>
<li>Can identify protein-coding regions</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Initiation from multiple sites within a single transcript makes it challenging to define all ORFs</li>
<li>	Does not provide the kinetics of translational elongation</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19213877">ART-Seq/Ribo-Seq: Ingolia N. T., Ghaemmaghami S., Newman J. R. and Weissman J. S. (2009) Genome-wide analysis in vivo of translation with nucleotide resolution using ribosome profiling. Science 324: 218-223</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24203712">GTI-Seq: Wan J. and Qian S. B. (2014) TISdb: a database for alternative translation initiation in mammalian cells. Nucleic Acids Res 42: D845-850</a></li>
</ul>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26898226" target="_blank">Zur H., Aviner R. and Tuller T. Complementary Post Transcriptional Regulatory Information is Detected by PUNCH-P and Ribosome Profiling. Sci Rep. 2016;6:21635</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27281202" target="_blank">Arribere J. A., Cenik E. S., Jain N., et al. Translation readthrough mitigation. Nature. 2016;534:719-723</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27251447" target="_blank">Jeong Y., Kim J. N., Kim M. W., et al. The dynamic transcriptional and translational landscape of the model antibiotic producer Streptomyces coelicolor A3(2). Nat Commun. 2016;7:11605</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26887592" target="_blank">Nissley D. A., Sharma A. K., Ahmed N., et al. Accurate prediction of cellular co-translational folding indicates proteins can switch from post- to co-translational folding. Nat Commun. 2016;7:10341</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27034466" target="_blank">Bennett C. G., Riemondy K., Chapnick D. A., Bunker E., Liu X., et al. Genome-wide analysis of Musashi-2 targets reveals novel functions in governing epithelial cell migration. Nucleic Acids Res. 2016;44:3788-3800</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27120414" target="_blank">Dar D., Shamir M., Mellin J. R., et al. Term-seq reveals abundant ribo-regulation of antibiotics resistance in bacteria. Science. 2016;352:aad9822</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26893308" target="_blank">Gawron D., Ndah E., Gevaert K. and Van Damme P. Positional proteomics reveals differences in N-terminal proteoform stability. Mol Syst Biol. 2016;12:858</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26821878" target="_blank">Lin L., Jiang P., Park J. W., et al. The contribution of Alu exons to the human proteome. Genome Biol. 2016;17:15</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26527729" target="_blank">Olexiouk V., Crappe J., Verbruggen S., Verhegen K., Martens L. and Menschaert G. sORFs.org: a repository of small ORFs identified by ribosome profiling. Nucleic Acids Res. 2016;44:D324-329</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26935582" target="_blank">Sin C., Chiarugi D. and Valleriani A. Quantitative assessment of ribosome drop-off in E. coli. Nucleic Acids Res. 2016;44:2528-2537</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26815362" target="_blank">Singh A. R., Sivadas A., Sabharwal A., et al. Chamber Specific Gene Expression Landscape of the Zebrafish Heart. PLoS One. 2016;11:e0147823</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27406171" target="_blank">Tichon A., Gil N., Lubelsky Y., et al. A conserved abundant cytoplasmic long noncoding RNA modulates repression by Pumilio proteins in human cells. Nat Commun. 2016;7:12209</a></li>
</ol>

<h5>RIP-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rip-seq.png"></p>

<p>RIP-Seq maps the sites at which proteins are bound to the RNA within RNA-protein complexes.  
In this method, RNA-protein complexes are immunoprecipitated with antibodies targeted to the protein of interest. After RNase digestion, RNA protected by protein binding is extracted and reverse-transcribed to cDNA. The locations can then be mapped back to the genome. Deep sequencing of cDNA provides single-base resolution of protein-bound RNA.</p>
<h6>Pros:</h6>
<ul>
<li>Maps specific protein-RNA complexes, such as polycomb-associated RNAs</li>
<li>Low background and higher resolution of binding site due to RNase digestion</li>
<li>No prior knowledge of the RNA is required</li>
<li>Genome-wide RNA screen</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires antibodies to the targeted proteins</li>
<li>Nonspecific antibodies will precipitate nonspecific complexes</li>
<li>Lack of crosslinking or stabilization of the complexes may lead to false negatives</li>
<li>RNase digestion must be controlled carefully </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21172659" target="_blank">RIP-Seq: Zhao J., Ohsumi T. K., Kung J. T., Ogawa Y., Grau D. J., et al. (2010) Genome-wide identification of polycomb-associated RNAs by RIP-seq. Mol Cell 40: 939-953</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html" target="_blank">TruSeq Stranded total RNA library prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26859437" target="_blank">McFadden E. J. and Hargrove A. E. Biochemical Methods To Investigate lncRNA and the Influence of lncRNA:Protein Complexes on Chromatin. Biochemistry. 2016;55:1615-1630</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26883671" target="_blank">Fang Y. and Fullwood M. J. Roles, Functions, and Mechanisms of Long Non-coding RNAs in Cancer. Genomics Proteomics Bioinformatics. 2016;14:42-54</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27151434" target="_blank">Kim T. K. and Shiekhattar R. Diverse regulatory interactions of long noncoding RNAs. Curr Opin Genet Dev. 2016;36:73-82</a></li>
<li><a href="http://dx.doi.org/10.1007/978-1-4939-3191-0_4" target="_blank">Goeman F. and Fanciulli M. Application of RNA-Seq Technology in Cancer Chemoprevention. Cancer Chemoprevention: Methods and Protocols. 2016;31-43</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26967018" target="_blank">Carrier M. C., Lalaouna D. and Masse E. A game of tag: MAPS catches up on RNA interactomes. RNA Biol. 2016;13:473-476</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26752519" target="_blank">Cloonan S. M., Glass K., Laucho-Contreras M. E., et al. Mitochondrial iron chelation ameliorates cigarette smoke-induced bronchitis and emphysema in mice. Nat Med. 2016;22:163-174</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27220277" target="_blank">Yabe-Wada T., Matsuba S., Takeda K., et al. TLR signals posttranscriptionally regulate the cytokine trafficking mediator sortilin. Sci Rep. 2016;6:26566</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27229370" target="_blank">Dugar G., Svensson S. L., Bischler T., et al. The CsrA-FliW network controls polar localization of the dual-function flagellin mRNA in Campylobacter jejuni. Nat Commun. 2016;7:11667</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27210763" target="_blank">Ennajdaoui H., Howard J. M., Sterne-Weiler T., et al. IGF2BP3 Modulates the Interaction of Invasion-Associated Transcripts with RISC. Cell Rep. 2016;15:1876-1883</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26807845" target="_blank">Faraji F., Hu Y., Yang H. H., et al. Post-transcriptional Control of Tumor Cell Autonomous Metastatic Potential by CCR4-NOT Deadenylase CNOT7. PLoS Genet. 2016;12:e1005820</a></li>
</ol>

<h5>TRAP-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/trap-seq.png"></p>

<p>Targeted purification of polysomal mRNA (TRAP-Seq) maps translating mRNAs under various conditions.  In this method, tagged ribosomal proteins are expressed in cells. The tagged ribosomal proteins are purified and the RNA isolated. The RNA is reverse-transcribed to cDNA. Deep sequencing of the cDNA provides single-base resolution of translating RNAs.</p>
<h6>Pros:</h6>
<ul>
<li>Allows detection of translating RNAs</li>
<li>RNAs translated by specific targeted ribosomes can be assessed</li>
<li>No prior knowledge of the RNA is required</li>
<li>Provides a genome-wide RNA screen</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not as specific as more recently developed methods, such as Ribo-Seq</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20924354">TRAP-Seq: Jiao Y. and Meyerowitz E. M. (2010) Cell-type specific analysis of translating RNAs in developing flowers reveals new levels of control. Mol Syst Biol 6: 419</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-targeted-rna-expression-kits.html">TruSeq Targeted RNA Expression Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25349914" target="_blank">Maze I., Shen L., Zhang B., et al. Analytical tools and current challenges in the modern era of neuroepigenomics. Nat Neurosci. 2014;17:1476-1490</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25757773" target="_blank">Reynoso M. A., Juntawong P., Lancia M., Blanco F. A., Bailey-Serres J. and Zanetti M. E. Translating Ribosome Affinity Purification (TRAP) followed by RNA sequencing technology (TRAP-SEQ) for quantitative assessment of plant translatomes. Methods Mol Biol. 2015;1284:185-207</a></li>
</ol>

<h5>TRIBE</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tribe.png"></p>

<p>TRIBE identifies the target RNA sequences of RBPs in vivo by modifying the RNA sequence using fusion proteins.  The fusion protein consists of the RBP of interest, which binds to the target RNA, and the catalytic domain of adenosine deaminase acting on RNA (ADAR), which irreversibly modifies the proximal adenosine to inosine to serve as a marker during sequence analysis.
</p><p>First, fusion proteins with the RBP of interest are cloned into the animal model and expressed along with fluorescent marker proteins. After activating the expression of the fusion proteins, mRNA from the cells of interest are isolated using oligo(dT) beads. mRNAs are reverse-transcribed using poly(dT)-T7 primers and random-T7 primers to reduce 3' bias. The nascent cDNA strands are input into the TruSeq RNA Library Prep Kit to generate the cDNA library for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>In vivo identification of RNA targets of RBPs in specific cell types</li>
<li>Not restricted to the specificity of antibodies</li>
<li>Can be performed in a small number of specific cells</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires assembly of fusion proteins</li>
<li>Requires an adenosine proximal to the RBP binding site</li>
<li>Catalytic domain of ADAR has a strong preference for double-stranded RNA</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/27040499">TRIBE: McMahon A. C., Rahman R., Jin H., Shen J. L., Fieldsend A., et al. (2016) TRIBE: Hijacking an RNA-Editing Enzyme to Identify Cell-Specific Targets of RNA-Binding Proteins. Cell 165: 742-753</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-rrna-removal-human-mouse-rat.html">Ribo-Zero rRNA Removal Kit </a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27040499" target="_blank">McMahon A. C., Rahman R., Jin H., et al. TRIBE: Hijacking an RNA-Editing Enzyme to Identify Cell-Specific Targets of RNA-Binding Proteins. Cell. 2016;165:742-753</a></li>
</ol>

#### RNA structure
<h5>CapSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/capseq.png"></p>

<p>CapSeq maps potential transcription start sites . In this method, total RNA is treated with terminator 5′-phosphate-dependent exonuclease to degrade rRNAs, calf intestinal phosphatase (CIP) to remove 5′ phosphates, and tobacco acid pyrophosphatase (TAP) to remove 5′ caps. The resulting long-capped RNAs are ligated to a 5′ adaptor. The first-strand cDNA is primed using a pool of random octamers and sequenced after size selection. Sequencing helps determine potential transcription start sites for PolII loci.</p>
<h6>Pros:</h6>
<ul>
<li>Maps RNAs anchored to RNA polymerase II</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Multiple steps and treatments can lead to loss of material<br>
</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23260138" target="_blank">CapSeq: Gu W., Lee H. C., Chaves D., Youngman E. M., Pazour G. J., et al. (2012) CapSeq and CIP-TAP identify Pol II start sites and reveal capped small RNAs as C. elegans piRNA precursors. Cell 151: 1488-1500</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA library prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
<div class="col-sm-6"><ul class="enzymes solutions">
<li>Tobacco Acid Pyrophosphatase (TAP)</li>
<li>Calf Intestinal Phosphatase (CIP)</li>
<li><a target="_blank" href="http://www.epibio.com/enzymes/ligases-kinases-phosphatases/phosphatases/apex-heat-labile-alkaline-phosphatase?details">APex Heat-Labile Alkaline Phosphatase</a></li>
</ul>
</div>
</div>

<ol class="dynamic reviews">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25691467" target="_blank">Hainer S. J., Gu W., Carone B. R., Landry B. D., Rando O. J., et al. (2015) Suppression of pervasive noncoding transcription in embryonic stem cells by esBAF. Genes Dev 29: 362-378</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/25635455" target="_blank">Tsai H. Y., Chen C. C., Conte D., Jr., Moresco J. J., Chaves D. A., et al. (2015) A ribonuclease coordinates siRNA amplification and mRNA cleavage during RNAi. Cell 160: 407-419</a></li>
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/24906153" target="_blank">Mohn F., Sienski G., Handler D. and Brennecke J. (2014) The rhino-deadlock-cutoff complex licenses noncanonical transcription of dual-strand piRNA clusters in Drosophila. Cell 157: 1364-1379</a></li>
</ol>

<h5>CIP-TAP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cip-tap.png"></p>

<p>CIP-TAP maps capped small RNAs.  
In this method, RNA is treated with CIP followed by 3'-end linker ligation. Next, the RNA is treated with TAP, followed by 5'-end linker ligation. The fragments are reverse-transcribed to cDNA, PCR-amplified, and sequenced. Deep sequencing provides single-nucleotide resolution reads of the capped small RNAs.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies capped small RNAs missed by CAP-Seq</li>
<li>High throughput</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Non-linear PCR amplification can lead to biases affecting reproducibility</li>
<li>Amplification errors caused by polymerases</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23260138" target="_blank">CIP-TAP: Gu W., Lee H. C., Chaves D., Youngman E. M., Pazour G. J., et al. (2012) CapSeq and CIP-TAP identify Pol II start sites and reveal capped small RNAs as C. elegans piRNA precursors. Cell 151: 1488-1500</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA library prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
<div class="col-sm-6"><ul class="enzymes solutions">
<li>Tobacco Acid Pyrophosphatase (TAP)</li>
<li>Calf Intestinal Phosphatase (CIP)</li>
<li><a href="http://www.epibio.com/enzymes/ligases-kinases-phosphatases/phosphatases/apex-heat-labile-alkaline-phosphatase?details" target="_blank">APex Heat-Labile Alkaline Phosphatase</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23260138" target="_blank">Gu W., Lee H. C., Chaves D., et al. CapSeq and CIP-TAP identify Pol II start sites and reveal capped small RNAs as C. elegans piRNA precursors. Cell. 2012;151:1488-1500</a></li>
</ol>

<h5>CIRS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cirs-seq.png"></p>

<p>CIRS-Seq was developed to investigate the complexity of secondary RNA structures in the mammalian transcriptome.  CIRS-Seq uses DMS to methylate the N1 of adenosine and N3 of cytosine residues, and CMC to modify pseudouridines selectively, but only when they are in single-stranded conformation. Modifications on these nucleotide residues halt the RT process, effectively producing a truncated cDNA as a marker for the location of secondary RNA structures.
Briefly, cells are lysed and treated with proteinase K to dissociate protein-bound RNAs while leaving RNA secondary structures intact. The lysates are separated into 3 different treatment lines—DMS, CMC, and no treatment. In all 3 treatment lines, total RNA is extracted and reverse-transcribed using random primers. The resulting cDNA is isolated, ligated to sequencing adapters, and subjected to high-throughput sequencing. Reads from the DMS and CMC lines are used to identify the locations of secondary RNA structures, while the control is used to reduce background noise.</p>
<h6>Pros:</h6>
<ul>
<li>Accurately predicts secondary RNA structures, and reveals features of mRNAs and ncRNAs</li>
<li>Provides single-base resolution</li>
<li>Can identify structural requirements for RBPs</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>CMC and DMS may react with non–secondary RNA structures</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25323333" target="_blank">CIRS-Seq: Incarnato D., Neri F., Anselmi F. and Oliviero S. Genome-wide profiling of mouse RNA secondary structures reveals key features of the mammalian transcriptome. Genome Biol. 2014;15:491</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27872686" target="_blank">Zucchelli S., Patrucco L., Persichetti F., Gustincich S. and Cotella D. Engineering Translation in Mammalian Cell Factories to Increase Protein Yield: The Unexpected Use of Long Non-Coding SINEUP RNAs. Comput Struct Biotechnol J. 2016;14:404-410</a></li> 
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25797096" target="_blank">Kwok C. K., Tang Y., Assmann S. M. and Bevilacqua P. C. The RNA structurome: transcriptome-wide structure probing with next-generation sequencing. Trends Biochem Sci. 2015;40:221-232</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27132125" target="_blank">Strobel E. J., Watters K. E., Loughrey D. and Lucks J. B. RNA systems biology: uniting functional discoveries and structural tools to understand global roles of RNAs. Curr Opin Biotechnol. 2016;39:182-191</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27614074" target="_blank">Incarnato D., Anselmi F., Morandi E., et al. High-throughput single-base resolution mapping of RNA 2'-O-methylated residues. Nucleic Acids Res. 2016;</a></li>
</ol>

<h5>FRAG-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/frag-seq.png"></p>

<p>Fragmentation sequencing (FRAG-Seq) is a method for probing RNA structure. In this method, RNA is digested using nuclease P1, followed by reverse transcription. Deep sequencing of the cDNA provides high-resolution single-stranded reads, which can be used to determine the structure of RNA by mapping P1 endonuclease digestion sites.</p>
<h6>Pros:</h6>
<ul>
<li>Simple and fast protocol compared to PARS-Seq</li>
<li>High throughput</li>
<li>Alternative to mass spectrometry, NMR, and crystallography</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Need endogenous controls</li>
<li>Potential for contamination between samples and controls</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21057495">FRAG-Seq: Underwood J. G., Uzilov A. V., Katzman S., Onodera C. S., Mainzer J. E., et al. (2010) FragSeq: transcriptome-wide RNA structure probing using high-throughput sequencing. Nat Methods 7: 995-1001</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded Total RNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25531890" target="_blank">Imig J., Brunschweiger A., Brummer A., Guennewig B., Mittal N., et al. (2015) miR-CLIP capture of a miRNA targetome uncovers a lincRNA H19-miR-106a interaction. Nat Chem Biol 11: 107-114</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25768906" target="_blank">Luna J. M., Scheel T. K., Danino T., Shaw K. S., Mele A., et al. (2015) Hepatitis C virus RNA functionally sequesters miR-122. Cell 160: 1099-1110</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25800746" target="_blank">Wang P., Ning S., Zhang Y., Li R., Ye J., et al. (2015) Identification of lncRNA-associated competing triplets reveals global patterns and prognostic markers for cancer. Nucleic Acids Res 43: 3478-3489</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24857550" target="_blank">Grosswendt S., Filipchyk A., Manzano M., Klironomos F., Schilling M., et al. (2014) Unambiguous identification of miRNA:target site interactions by different types of ligation reactions. Mol Cell 54: 1042-1054</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24828673" target="_blank">Newie I., Sokilde R., Persson H., Grabau D., Rego N., et al. (2014) The HER2-encoded miR-4728-3p regulates ESR1 through a non-canonical internal seed interaction. PLoS One 9: e97200</a></li>
</ol>

<h5>icSHAPE</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/icshape.png"></p>

<p>icSHAPE provides accurate predictions of RNA-protein interactions and m6A modification in vivo by combining SHAPE-Seq with click chemistry for enhanced isolation. ,  Secondary RNA structures are modified by the addition of a custom 2-methylnicotinic acid imidazolide (NAI) probe, termed NAI-N3. The modifed RNA is marked selectively with dibenzocyclooxtyne (DIBO)-biotin through copper-free click chemistry, enabling purification by streptavidin pull-down.
Briefly, NAI-N3 is added to RNA in vivo to mark it selectively for DIBO-biotin tagging. The cells are lysed, the RNA is poly(A)-selected, tagged with DIBO-biotin, and fragmented. The RNA strands are 3'-end-repaired with T4 PNK and ligated to 3' adapters. After size-selection, the RNA strands are reverse-transcribed, and both the RNA and first-strand cDNA are captured on streptavidin beads. Another cDNA size-selection step is carried out before circularization and PCR amplification. The samples are ready for NGS.
</p><p>Similar methods: SHAPE-Seq</p>
<h6>Pros:</h6>
<ul>
<li>Provides accurate predictions of RNA-protein interactions and m6A modifications in vivo</li>
<li>Can be applied to ex vivo applications with slight modifications</li>
<li>Chemical modification is applicable to all nucleotides, unlike DMS which only modifies adenines and cytosines</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Circularization may introduce additional bias</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25799993" target="_blank">icSHAPE: Spitale R. C., Flynn R. A., Zhang Q. C., et al. Structural imprints in vivo decode RNA regulatory mechanisms. Nature. 2015;519:486-490</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26766114" target="_blank">icSHAPE Protocol: Flynn R. A., Zhang Q. C., Spitale R. C., Lee B., Mumbach M. R. and Chang H. Y. Transcriptome-wide interrogation of RNA secondary structure in living cells with icSHAPE. Nat Protoc. 2016;11:273-290</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26878240" target="_blank">Flynn R. A., Do B. T., Rubin A. J., et al. 7SK-BAF axis controls pervasive transcription at enhancers. Nat Struct Mol Biol. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27180905" target="_blank">Lu Z., Zhang Q. C., Lee B., et al. RNA Duplex Map in Living Cells Reveals Higher-Order Transcriptome Structure. Cell. 2016;165:1267-1279</a></li>
</ol>

<h5>PARS/dsRNA-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pars-dsrna-seq.png"></p>

<p>PARS-Seq  mapping provides information about the secondary and tertiary structure of RNA. In this method, RNA is digested with RNases that are specific for double-stranded and single-stranded RNA, respectively. The resulting fragments are reverse-transcribed to cDNA. Deep sequencing of the cDNA provides high-resolution sequences of the RNA. The RNA structure can be deduced by comparing the digestion patterns of the various RNases.</p>
<h6>Pros:</h6>
<ul>
<li>Provides RNA structural information</li>
<li>Distinguishes between paired and unpaired bases</li>
<li>Alternative to mass spectrometry, NMR, and crystallography</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Enzyme digestion can be nonspecific</li>
<li>Digestion conditions must be carefully controlled</li>
<li>RNA can be overdigested</li>
<li>Limited to in vitro applications</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23558785">PARS-Seq/dsRNA-Seq: Wan Y., Qu K., Ouyang Z. and Chang H. Y. (2013) Genome-wide mapping of RNA structure using nuclease digestion and high-throughput sequencing. Nat Protoc 8: 849-869</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA library prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27298343" target="_blank">Righetti F., Nuss A. M., Twittenhoff C., et al. Temperature-responsive in vitro RNA structurome of Yersinia pseudotuberculosis. Proc Natl Acad Sci U S A. 2016;113:7237-7242</a></li>
</ol>

<h5>SHAPE-MaP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/shape-map.png"></p>

<p>SHAPE-MaP sequences secondary RNA structures at various levels on a massively parallel scale. The method can be customized to interrogate small RNAs, amplicons, or rare RNA species accurately in a mixture of RNAs. As implied in the name, SHAPE-Map uses the SHAPE-Seq 1M7 reaction to mark RNA ribose 2’-OH groups to identify secondary RNA structures. This reaction is followed by mutational profiling (MaP) to induce noncomplementary nucleotide mutations on SHAPE adducts during RT. These MaP mutations are analyzed after sequencing using powerful informatics tools developed specifically for this method.
</p><p>Briefly, SHAPE electrophiles are added to the sample containing folded RNAs. The samples are divided into 3 different reaction lines: +reagent, –reagent, and a denaturing control, to correct against intrinsic background mutation rates from reverse transcription. After SHAPE mutations are introduced, RT primers are selected depending on the RNA type of interest (amplicon, small RNA, or specific RNA species profiling). The primers are added to the reaction and the RNA is reverse-transcribed. Subsequent library preparation steps differ according to the RNA of interest. The small RNA workflow involves standard PCR amplification with appropriate primers. The workflows for amplicons and specific RNA species follow the Nextera XT DNA Library Preparation Kit protocol. The barcoded samples are ready for sequencing.
</p><p>Similar methods: SHAPE-Seq, icSHAPe</p>
<h6>Pros:</h6>
<ul>
<li>Identifies RNA structures at single-nucleotide resolution using a combination of SHAPE-Seq and MaP techniques</li>
<li>Library preparation step is highly customizable for different applications: amplicon, small RNA, or rare RNA species profiling</li>
<li>Avoids common issues encountered with adapter-ligation methods</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Length of the RNA strand must be at least ~150 nt for the randomer and native workflow, and at least ~40 nt for the small-RNA workflow</li>
<li>Difficult to distinguish MaP mutations from background noise in samples with low levels of RNA</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25028896" target="_blank">SHAPE-MaP: Siegfried N. A., Busan S., Rice G. M., Nelson J. A. and Weeks K. M. RNA motif discovery by SHAPE and mutational profiling (SHAPE-MaP). Nat Methods. 2014;11:959-965</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26426499" target="_blank">SHAPE-MaP Protocol: Smola M. J., Rice G. M., Busan S., Siegfried N. A. and Weeks K. M. Selective 2'-hydroxyl acylation analyzed by primer extension and mutational profiling (SHAPE-MaP) for direct, versatile and accurate RNA structure analysis. Nat Protoc. 2015;10:1643-1669</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/nextera_xt_dna_library_prep_kit.html">Nextera XT DNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27007508" target="_blank">Schmitz S. U., Grote P. and Herrmann B. G. Mechanisms of long noncoding RNA function in development and disease. Cell Mol Life Sci. 2016;73:2491-2509</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27911722" target="_blank">Kwok C. K. Dawn of the in vivo RNA structurome and interactome. Biochem Soc Trans. 2016;44:1395-1410</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26544910" target="_blank">Smola M. J., Calabrese J. M. and Weeks K. M. Detection of RNA-Protein Interactions in Living Cells with SHAPE. Biochemistry. 2015;54:6867-6875</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25775547" target="_blank">Mauger D. M., Golden M., Yamane D., et al. Functionally conserved architecture of hepatitis C virus RNA genomes. Proc Natl Acad Sci U S A. 2015;112:3692-3697</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26531896" target="_blank">Lu Y. F., Mauger D. M., Goldstein D. B., Urban T. J., Weeks K. M. and Bradrick S. S. IFNL3 mRNA structure is remodeled by a functional non-coding polymorphism associated with hepatitis C virus clearance. Sci Rep. 2015;5:16037</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25470036" target="_blank">Taylor A. I., Pinheiro V. B., Smola M. J., et al. Catalysts from synthetic genetic polymers. Nature. 2014;</a></li> 
</ol>

<h5>SHAPE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/shape-seq.png"></p>

<p>SHAPE-Seq provides structural information about RNA. 
In this method, a unique barcode is first added to the 3' end of RNA, and the RNA is allowed to fold under pre-established in vitro conditions. The barcoded and folded RNA is treated with a SHAPE reagent, 1-methyl-7-nitroisatoic anhydride (1M7), which blocks RT. The RNA is reverse-transcribed to cDNA. Deep sequencing of the cDNA provides single-nucleotide sequence information for the positions occupied by 1M7. The structural information of the RNA can then be deduced.</p>
<h6>Pros:</h6>
<ul>
<li>Provides RNA structural information</li>
<li>Multiplexed analysis of barcoded RNAs provides information for multiple RNAs</li>
<li>Effect of point mutations on RNA structure can be assessed</li>
<li>Alternative to mass spectrometry, nuclear magnetic resonance (NMR), and crystallography</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires positive and negative controls to account for transcriptase drop-off</li>
<li>Requires pre-established conditions for RNA folding</li>
<li>Folding in vitro may not reflect actual folding in vivo </li>
</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/21642531" target="_blank">SHAPE-Seq: Lucks J. B., Mortimer S. A., Trapnell C., Luo S., Aviran S., et al. (2011) Multiplexed RNA structure characterization with selective 2'-hydroxyl acylation analyzed by primer extension sequencing (SHAPE-Seq). Proc Natl Acad Sci U S A 108: 11063-11068</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26883671" target="_blank">Fang Y. and Fullwood M. J. Roles, Functions, and Mechanisms of Long Non-coding RNAs in Cancer. Genomics Proteomics Bioinformatics. 2016;14:42-54</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27720642" target="_blank">Taliaferro J. M., Lambert N. J., Sudmant P. H., Dominguez D., Merkin J. J., et al. RNA Sequence Context Effects Measured In Vitro Predict In Vivo Protein Binding and Regulation. Mol Cell. 2016;64:294-306</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26350218" target="_blank">Watters K. E., Abbott T. R. and Lucks J. B. Simultaneous characterization of cellular RNA structure and function with in-cell SHAPE-Seq. Nucleic Acids Res. 2015;</a></li>
</ol>

<h5>SPARE</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/spare.png"></p>

<p>SPARE identifies genome-wide miRNA processing intermediates in plants.  SPARE infers the directionality of miRNA processing (base-to-loop or loop-to-base) by analyzing the resultant cDNA sequences. If only the first cleavage position is detected, the miRNA was processed in a base-to-loop fashion; however, if all cleavage intermediates are detected, it was processed in a loop-to-base fashion.
Briefly, total RNA is depleted of rRNA, and RNA adapters are ligated to the 5' ends of uncapped RNAs. These ligated RNAs are used as the template in reverse transcription using miRNA precursor–specific primers with generic adapter tails as RT primers. The resultant cDNAs are PCR-amplified, size-selected, and sequenced.
</p><p>Similar methods: PARE, 5' RACE</p>
<h6>Pros:</h6>
<ul>
<li>Enables genome-wide identification of miRNA intermediates</li>
<li>Able to infer processing directionality through sequence analysis</li>
<li>Less time-consuming than existing methods</li>
<li>Optimized for plant genomes</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not yet adopted widely by the scientific community</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24018204" target="_blank">SPARE: Schapire A. L., Bologna N. G., Moro B., Zhai J., Meyers B. C. and Palatnik J. F. Construction of Specific Parallel Amplification of RNA Ends (SPARE) libraries for the systematic identification of plant microRNA processing intermediates. Methods. 2013;64:283-291</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26016494" target="_blank">Ma X., Tang Z., Qin J. and Meng Y. The use of high-throughput sequencing methods for plant microRNA research. RNA Biol. 2015;12:709-719</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25429978" target="_blank">Schmidt S. A., Foley P. L., Jeong D. H., et al. Identification of SMG6 cleavage sites and a preferred RNA cleavage motif by global analysis of endogenous NMD targets in human cells. Nucleic Acids Res. 2015;43:309-323</a></li>
</ol>

<h5>Structure-Seq/DMS-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/structure-seq.png"></p>

<p>Structure-Seq profiles RNA structures for in vivo or in vitro applications with single-nucleotide resolution. This method identifies secondary RNA structures by using the chemical modification induced by DMS on unpaired adenines and cytosines.</p>
<p>Briefly, samples are treated with DMS to mark secondary RNA structures in vivo. The RNA is extracted, poly(A)-selected, and treated with DNase. Using random hexamers as primers, reverse transcription is initiated. The resulting single-stranded DNA is ligated to single-stranded DNA linkers and self-circularized using CircLigase enzyme. Next, the DNA is PCR-amplified, size-selected, and sequenced.</p>
<p>Similar methods: icSHAPE, Mod-Seq, DMS-seq, PARS, Frag-seq, dsRNA-Seq</p>
<h6>Pros:</h6>
<ul>
<li>Provides genome-wide profiling of RNA structures at single-nucleotide resolution</li>
<li>Can be used for in vivo and in vitro applications</li>
<li>DMS is cell-permeable and can be used for in vivo applications</li>
<li>One RT primer synthesis retrieves information for tens of thousands of RNA structures</li>
<li>Random-hexamer primers minimize 3' end bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>RBPs can block DMS modification in vivo</li>
<li>Circularization may introduce additional bias	</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24270811" target="_blank">Structure-Seq: Ding Y., Tang Y., Kwok C. K., Zhang Y., Bevilacqua P. C. and Assmann S. M. In vivo genome-wide profiling of RNA secondary structure reveals novel regulatory features. Nature. 2014;505:696-700</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26086407" target="_blank">Protocol: Ding Y., Kwok C. K., Tang Y., Bevilacqua P. C. and Assmann S. M. Genome-wide profiling of in vivo RNA structure at single-nucleotide resolution using structure-seq. Nat Protoc. 2015;10:1050-1066</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26883671" target="_blank">Fang Y. and Fullwood M. J. Roles, Functions, and Mechanisms of Long Non-coding RNAs in Cancer. Genomics Proteomics Bioinformatics. 2016;14:42-54</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000844" target="_blank">Reuter J. A., Spacek D. V. and Snyder M. P. High-Throughput Sequencing Technologies. Mol Cell. 2015;58:586-597</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26646615" target="_blank">Fang R., Moss W. N., Rutenberg-Schoenberg M. and Simon M. D. Probing Xist RNA Structure in Cells Using Targeted Structure-Seq. PLoS Genet. 2015;11:e1005668</a></li>
</ol>

#### RNA transcription
<h5>2P-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/2p-seq.png"></p>

<p>Poly(A)-tail-primed sequencing (2P-Seq) is designed to quantify mRNA stability and translational efficiency by characterizing 3'UTR isoforms. 
First, poly(A)+ mRNAs are isolated from total RNA and partially digested by RNase T1 to cleave the non-UTR regions. Poly (A)+ mRNA fragments are reverse-transcribed with a 20T-VN primer, which contains a stretch of 20 Ts and a VN anchor (N represents a fully degenerate base, and V is any base except for T). The resultant cDNAs are circularized and PCR-amplified using barcoded primers. The cDNA is sequenced with a custom primer ending with 20 Ts. To avoid 2P tags enriched for adenosine, analyses should be restricted to 2P tags mapping to within 20 bases of 3P-Seq–annotated poly(A) sites.</p>
<h6>Pros:</h6>
<ul>
<li>Quantifies mRNA stability and translational efficiency<br>
</li>
<li>Accurately measures half-lives and length of each UTR isoforms</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>3P-Seq datasets are needed to limit results specifically to Poly(A) sites<br>
</li>
<li>Poly(A) primer can mis-prime with A-rich regions elsewhere in the mRNA<br>
</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24072873" target="_blank">2P-Seq: Spies N., Burge C. B. and Bartel D. P. (2013) 3' UTR-isoform choice has limited influence on the stability and translational efficiency of most mRNAs in mouse fibroblasts. Genome Res 23: 2078-2090</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25899044" target="_blank">Kim M., You B. H. and Nam J. W. Global estimation of the 3' untranslated region landscape using RNA sequencing. Methods. 2015;83:111-117</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24072873" target="_blank">Spies N., Burge C. B. and Bartel D. P. 3' UTR-isoform choice has limited influence on the stability and translational efficiency of most mRNAs in mouse fibroblasts. Genome Res. 2013;23:2078-2090</a></li>
</ol>

<h5>3'-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/3prime-seq.png"></p>

<p>3'Seq was designed to quantitatively measure the abundance of 3' untranslated regions (UTR) isoforms in a wide-array of human tissue samples types. The first cDNA strand is generated by reverse transcribing total RNA using an oligo (dT) primer containing a VN-anchor (where V is dA, dC, or dG), P5 adapter sequence, a uridine, and biotin that is bound to a streptavidin-coated magnetic bead. The second cDNA strand is synthesized using DNA polymerase I. To initiate nick translation with DNA polymerase I, RNase HII was used to introduce a nick at the uridine. This creates another nick that is 50-75 bases away from the 3' end. A blunt end is created at the position of the new nick and double-stranded P7 adapters are ligated at this position. The double-stranded cDNA is PCR amplified, purified, and ready to be sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Measures 3' UTR isoform abundance to detect protein expression differences in multiple tissue types</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Technically challenging and nick translation requires precise conditions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24145798" target="_blank">3'-Seq: Lianoglou S., Garg V., Yang J. L., Leslie C. S. and Mayr C. (2013) Ubiquitously transcribed genes use alternative polyadenylation to achieve tissue-specific expression. Genes Dev 27: 2380-2396</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24903459" target="_blank">Miura P., Sanfilippo P., Shenker S. and Lai E. C. Alternative polyadenylation in the nervous system: to what lengths will 3' UTR extensions take us? Bioessays. 2014;36:766-777</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25779042" target="_blank">Kralovicova J., Knut M., Cross N. C. and Vorechovsky I. (2015) Identification of U2AF(35)-dependent exons by RNA-Seq reveals a link between 3' splice-site organization and activity of U2AF-related proteins. Nucleic Acids Res</a></li>
</ol>

<h5>3'NT Method</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/3-nt-method.png"></p>

<p>3' End of Nascent Transcripts (3'NT Method) sequences nascent RNA transcripts to map the positions of elongating and arrested RNA polymerase II (RNAPII) at nucleotide resolution . This method effectively isolates RNAPII-chromatin complex by capitalizing on its ability to remain bound to the DNA strand in the presence of high salt, urea, detergents and polyanions.</p>
<p>Transcription was arrested in the sample while both the cells and nucleus were lysed. Nascent RNA strands are isolated from the purified RNAPII-chromatin complex and are enriched for mRNA by selecting for strands with 5' 7-methylguanosine caps. cDNA libraries are prepared from nascent mRNA strands by following NET-Seq protocols with slight modifications. Resulting cDNA libraries are then sequenced to determine precise locations of RNAPII during each experimental conditions.</p>
<h6>Pros:</h6>
<ul>
<li>Tracks position of elongating and arrested RNAPII throughout the whole genome</li>
<li>Does not require transgenes, solubilization, or immunopurification</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Unable to interrogate relationship between RNAPII C-terminal domain modifications and nascent RNA strands<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24606920">3'NT Method: Weber C. M., Ramachandran S. and Henikoff S. (2014) Nucleosomes are context-specific, H2A.Z-modulated barriers to RNA polymerase. Mol Cell 53: 819-830</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25910207">1. Nojima T., Gomes T., Grosso A. R., Kimura H., Dye M. J., et al. (2015) Mammalian NET-Seq Reveals Genome-wide Nascent Transcription Coupled to RNA Processing. Cell 161: 526-540</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/by-type/sequencing-kits/library-prep-kits/truseq-chip.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25297728" target="_blank">Zentner G. E. and Henikoff S. High-resolution digital profiling of the epigenome. Nat Rev Genet. 2014;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25455758" target="_blank">Teves S. S., Weber C. M. and Henikoff S. Transcribing through the nucleosome. Trends Biochem Sci. 2014;39:577-586</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24606920">Weber C. M., Ramachandran S. and Henikoff S. (2014) Nucleosomes are context-specific, H2A.Z-modulated barriers to RNA polymerase. Mol Cell 53: 819-830</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25297728">Zentner G. E. and Henikoff S. (2014) High-resolution digital profiling of the epigenome. Nat Rev Genet </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25455758">Teves S. S., Weber C. M. and Henikoff S. (2014) Transcribing through the nucleosome. Trends Biochem Sci 39: 577-586</a></li>
</ol>

<h5>3P-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/3p-seq.png"></p>

<p>Poly(A)-position profiling by sequencing (3P-Seq) is used to identify 3'-UTRs in mRNA.  
Poly(A) selection is used to isolate mRNA from total RNA, and biotinylated-splint primers are annealed and splint-ligated to the end of the mRNA poly(A) tail. The RNA-primer complex is partially digested by RNase T1, bound to streptavidin, and washed to purify the 3' fragments. Primers corresponding to the 3'end of the poly(A) tail are annealed and reverse-transcribed with deoxythymidine triphosphate (dTTP) as the only dNTP to generate a cDNA strand complementary to the poly(A) tail. The biotin-bound poly(A) RNA fragments are released by RNase H digestion and purified. Next, P7 and P5 adapters are attached to the RNA fragments, and they are reverse-transcribed to generate cDNA fragments.</p>
<h6>Pros:</h6>
<ul>
<li>Reliable for UTR isoform discoveries</li>
<li>Prevents polymerase slippage by using splint-ligation primer in poly(A) capture</li>
<li>Prevents internal priming and is specific to 3' ends of poly(A) RNAs</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Needs large amounts of RNA</li>
<li>Technically challenging to perform</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21085120">3P-Seq: Jan C. H., Friedman R. C., Ruby J. G. and Bartel D. P. (2011) Formation, regulation and evolution of Caenorhabditis elegans 3'UTRs. Nature 469: 97-101</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27489207" target="_blank">Lakshmanan V., Bansal D., Kulkarni J., et al. Genome-Wide Analysis of Polyadenylation Events in Schmidtea mediterranea. G3 (Bethesda). 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25959816" target="_blank">Hezroni H., Koppstein D., Schwartz M. G., Avrutin A., Bartel D. P. and Ulitsky I. Principles of long noncoding RNA evolution derived from direct comparison of transcriptomes in 17 species. Cell Rep. 2015;11:1110-1122</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25838129" target="_blank">Jambor H., Surendranath V., Kalinka A. T., Mejstrik P., Saalfeld S. and Tomancak P. Systematic imaging reveals features and changing localization of mRNAs in Drosophila development. Elife. 2015;4:</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24072873" target="_blank">Spies N., Burge C. B. and Bartel D. P. 3' UTR-isoform choice has limited influence on the stability and translational efficiency of most mRNAs in mouse fibroblasts. Genome Res. 2013;23:2078-2090</a></li>
</ol>

<h5>3'-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/3prime-seq.png"></p>

<p>3'-Seq was designed to measure the abundance of 3'-UTR isoforms quantitatively in a wide array of human tissue types. 
The first cDNA strand is generated by reverse-transcribing total RNA using an oligo(dT) primer containing a VN-anchor (where V is dA, dC, or dG), P5 adapter sequence, a uridine, and biotin that is bound to a streptavidin-coated magnetic bead. The second cDNA strand is synthesized using DNA polymerase I. To initiate nick translation with DNA polymerase I, RNase HII is used to introduce a nick at the uridine. This creates another nick that is 50–75 bases away from the 3' end. A blunt end is created at the position of the new nick, and double-stranded P7 adapters are ligated at this position. The double-stranded cDNA is PCR-amplified, purified, and ready for sequencing.
</p>
<h6>Pros:</h6>
<ul>
<li>Measures 3' UTR isoform abundance to detect protein expression differences in multiple tissue types</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Technically challenging; nick translation requires precise conditions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24145798" target="_blank">3'-Seq: Lianoglou S., Garg V., Yang J. L., Leslie C. S. and Mayr C. (2013) Ubiquitously transcribed genes use alternative polyadenylation to achieve tissue-specific expression. Genes Dev 27: 2380-2396</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24903459" target="_blank">Miura P., Sanfilippo P., Shenker S. and Lai E. C. Alternative polyadenylation in the nervous system: to what lengths will 3' UTR extensions take us? Bioessays. 2014;36:766-777</a></li>
</ol><h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25779042" target="_blank">Kralovicova J., Knut M., Cross N. C. and Vorechovsky I. (2015) Identification of U2AF(35)-dependent exons by RNA-Seq reveals a link between 3' splice-site organization and activity of U2AF-related proteins. Nucleic Acids Res</a></li>
</ol>

<h5>3Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/3seq.png"></p>

<p>3'-end Sequencing for Expression Quantification (3Seq) is able to isolate highly degraded mRNA from formalin-fixed paraffin-embedded (FFPE) tissue samples for quantitative genome-wide expression analysis. 
First, mRNA is isolated from total RNA by poly(A) selection. Next, an oligo(dT)-P7 RT primer is annealed to the 3' end of the mRNA fragment to synthesize the first cDNA strand via reverse transcription (RT). A second cDNA strand is generated from the first strand, and P5 adapters are ligated on the opposite end from the P7 adapters. The fragments containing the adapters are amplified by PCR and are ready for sequencing. 3Seq can also be used for fresh-frozen tissue samples.
</p>
<h6>Pros:</h6>
<ul>
<li>Sequences highly degraded mRNA from FFPE or fresh-frozen tissue samples</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>High internal priming rate</li>
<li>Homopolymeric nature of poly(A) tail often causes polymerase slippage</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a adhocenable="false" href="http://www.ncbi.nlm.nih.gov/pubmed/20098735" target="_blank"> 3SEQ: Beck AH, Weng Z, Witten DM, Zhu S, Foley JW, et al. (2010) 3′-End Sequencing for Expression Quantification (3SEQ) from Archival Tumor Samples. PLoS ONE 5(1): e8768.</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-rna-access-kit.html">TruSeq RNA Access Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26240788" adhocenable="false">Guo X., Forgo E. and van de Rijn M. (2015) Molecular subtyping of leiomyosarcoma with 3' end RNA sequencing. Genom Data 5: 366-367</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26158411" adhocenable="false">Wei G., Luo H., Sun Y., Li J., Tian L., et al. (2015) Transcriptome profiling of esophageal squamous cell carcinoma reveals a long noncoding RNA acting as a tumor suppressor. Oncotarget 6: 17065-17080</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21343387" adhocenable="false">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. (2015) RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci 38: 226-236</a></li>
</ol>

<h5>4sUDRB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/4sudrb-seq.png"></p>

<p>4sUDRB-Seq investigates initiation frequencies and RNA elongation rates throughout the genome using 4-thiouridine (4-SU) and DRB. 
Cells are first treated with DRB to inhibit RNA elongation and arrest RNAPII at TSS. The cells are lysed, cleansed of DRB, and immediately incubated with 4-SU to label newly transcribed RNA molecules. Biotin is added to bind with 4-SU, and the tagged RNA is subsequently captured using streptavidin beads. The biotinylated RNA fragments are eluted and prepared for sequencing according to the protocol in the TruSeq RNA Library Preparation Kit.</p>
<h6>Pros:</h6>
<ul>
<li>Measures RNA elongation rate and transcription initiation rate simultaneously</li>
<li>Sequencing reads behave dynamically throughout the transcription wave – useful in accurately determining transcription initiation rate<sup>1</sup></li>
<li>No previous knowledge of the sequence is needed</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>High toxicity of 4sU can debilitate experiments with slow elongation rates<sup>1</sup></li>
<li>Measuring genome-wide transition of RNA pol II into active elongation can be cost-inefficient due to the high sequencing depth needed<sup>1</sup></li>
<li>Dynamic sequence reads makes identification of transcripts ends challenging<sup>1</sup></li>
<li>Limited to cultured cells</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24887486">4sUDRB-Seq: Fuchs G., Voichek Y., Benjamin S., Gilad S., Amit I., et al. (2014) 4sUDRB-seq: measuring genomewide transcriptional elongation rates and initiation frequencies within cells. Genome Biol 15: R69</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25811895">1. Fuchs G., Voichek Y., Rabani M., Benjamin S., Gilad S., et al. (2015) Simultaneous measurement of genome-wide transcription elongation speeds and rates of RNA polymerase II transition into active elongation with 4sUDRB-seq. Nat Protoc 10: 605-618</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25497548" target="_blank">Rabani M., Raychowdhury R., Jovanovic M., et al. High-Resolution Sequencing and Modeling Identifies Distinct Dynamic RNA Regulatory Strategies. Cell. 159:1698-1710</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26340425" target="_blank">Duffy E. E., Rutenberg-Schoenberg M., Stark C. D., Kitchen R. R., Gerstein M. B. and Simon M. D. Tracking Distinct RNA Populations Using Efficient and Reversible Covalent Chemistry. Mol Cell. 2015;59:858-866</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25693130" target="_blank">Jonkers I. and Lis J. T. Getting up to speed with transcription elongation by RNA polymerase II. Nat Rev Mol Cell Biol. 2015;16:167-177</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27068474" target="_blank">Zhang Y., Xue W., Li X., et al. The Biogenesis of Nascent Circular RNAs. Cell Rep. 2016;15:611-624</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26687678" target="_blank">Jaenicke L. A., von Eyss B., Carstensen A., et al. Ubiquitin-Dependent Turnover of MYC Antagonizes MYC/PAF1C Complex Accumulation to Drive Transcriptional Elongation. Mol Cell. 2016;61:54-67</a></li>
<li><a href="http://www.biorxiv.org/biorxiv/early/2015/12/25/035386.full.pdf" target="_blank">Fuchs G., Rosenthal E., Bublik D.-R., Kaplan T. and Oren M. Gene body H2B monoubiquitylation regulates gene-selective RNA Polymerase II pause release and is not rate limiting for transcription elongation. bioRxiv. 2015;</a></li>
</ol>

<h5>5'-GRO-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/5--gro-seq.png"></p>

<p>5'-GRO-Seq maps the sequences of nascent RNA with a 7-methylguanylate (m7G) cap at any given time using labeled nucleotides.  This method was originally developed to map and detect instabilities in TSS due to the presence of enhancer RNA. 
</p><p>Much like GRO-seq, 5'-GRO-Seq starts with the addition of Br-UTP and sarkosyl to the lysed nuclear material. The Br-UTP acts as a marker for isolating the RNA, while sarkosyl inhibits binding of additional RNAPII to the DNA. After the reaction is stopped, DNase I is added and the RNA products fragmented. The 3' ends of RNA are dephosphorylated with T4 PNK and fragments containing bromouridine are captured with anti-BrdU antibodies. The isolated RNAs are dephosphorylated with CIP, and the 5' caps are removed using TAP. Next, 3' and 5' adapters are ligated using RNA ligase 2 and RNA ligase, respectively. The fragments are reverse-transcribed, the resultant cDNA is isolated and amplified, and the cDNA is size-selected for 60–110 bp fragments. The fragments are isolated from the gel and sequenced.
</p>
<h6>Pros:</h6>
<ul>
<li>Maps nascent capped 5' RNA sequence at any given time</li>
<li>Determines activity of transcription sites</li>
<li>No prior knowledge of transcription sites needed</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to cell cultures and other artificial systems due to incubation with labelled nucleotides</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23728303" target="_blank">5'-GRO-Seq: Lam M. T., Cho H., Lesch H. P., Gosselin D., Heinz S., et al. (2013) Rev-Erbs repress macrophage gene expression by inhibiting enhancer-directed transcription. Nature 498: 511-515</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded total RNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24674738" target="_blank">Lam M. T., Li W., Rosenfeld M. G. and Glass C. K. Enhancer RNAs and regulated transcriptional programs. Trends Biochem Sci. 2014;39:170-182</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25639469">Duttke S. H., Lacadie S. A., Ibrahim M. M., Glass C. K., Corcoran D. L., et al. (2015) Human promoters are intrinsically directional. Mol Cell 57: 674-684</a></li>
</ol>

<h5>Bru-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bru-seq.png"></p>

<p>Bru-Seq maps nascent RNA transcripts using bromouridine tagging.  Active RNAPII synthesizes RNA in the presence of Br-UTP. Tagged RNA transcripts are immunoseparated from total RNA using magnetic beads coated with anti-BrdU antibodies. The captured RNA transcripts are eluted and fragmented before synthesis of cDNA strands via RT and PCR amplification. The resultant cDNA strands are prepared for sequencing using an Illumina TruSeq RNA Library Prep Kit.</p>
<h6>Pros:</h6>
<ul>
<li>Maps sequences of nascent RNA transcripts and determines relative transcription rate</li>
<li>Detects lncRNAs<sup>1</sup> </li>
<li>Detects transcription anywhere on the genome</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to cell cultures and other artificial systems, due to the requirement for incubation in the presence of labeled nucleotides</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23345452">Bru-Seq: Paulsen M. T., Veloso A., Prasad J., Bedi K., Ljungman E. A., et al. (2013) Coordinated regulation of synthesis and stability of RNA during the acute TNF-induced proinflammatory response. Proc Natl Acad Sci U S A 110: 2240-2245</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23973811">1. Paulsen M. T., Veloso A., Prasad J., Bedi K., Ljungman E. A., et al. (2014) Use of Bru-Seq and BruChase-Seq for genome-wide assessment of the synthesis and stability of RNA. Methods 67: 45-54</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26197343" target="_blank">Andrade-Lima L., Veloso A. and Ljungman M. Transcription Blockage Leads to New Beginnings. Biomolecules. 2015;5:1600</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26255935" target="_blank">Lefkofsky H. B., Veloso A. and Ljungman M. Transcriptional and post-transcriptional regulation of nucleotide excision repair genes in human cells. Mutat Res. 2015;776:9-15</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25659587" target="_blank">Kocab A. J., Veloso A., Paulsen M. T., Ljungman M. and Duckett C. S. Effects of physiological and synthetic IAP antagonism on c-IAP-dependent signaling. Oncogene. 2015;</a></li>
</ol>

<h5>BruChase-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/bruchase-seq.png"></p>

<p>BruChase-Seq uses bromouridine tagging to map and quantify the relative stability of nascent RNA transcripts. RNAPII synthesizes RNA in the presence of Br-UTP. Untagged uridine is added to chase out bromouridine from RNAs with high turnover. Long-lived RNA transcripts will remain tagged. The tagged RNA transcripts are immunoseparated from total RNA using magnetic beads coated with anti-BrdU antibodies. The captured RNA transcripts are eluted and fragmented before synthesis of cDNA strands via RT and PCR amplification. The resultant cDNA strands are prepared for sequencing using an Illumina TruSeq RNA Library Prep Kit.</p>
<h6>Pros:</h6>
<ul>
<li>Determines RNA stability through pulse-chase with bromouridine</li>
<li>Predicts nonsense and frameshift mutations<sup>1</sup></li>
<li>Detects transcription anywhere on the genome</li>
<li>No prior knowledge of transcription sites is needed</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to cell cultures and other artificial systems, due to the requirement for incubation in the presence of labeled nucleotides</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23345452" target="_blank">BruChase-Seq: Paulsen M. T., Veloso A., Prasad J., Bedi K., Ljungman E. A., et al. (2013) Coordinated regulation of synthesis and stability of RNA during the acute TNF-induced proinflammatory response. Proc Natl Acad Sci U S A 110: 2240-2245</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23973811" target="_blank">1. Paulsen M. T., Veloso A., Prasad J., et al. Use of Bru-Seq and BruChase-Seq for genome-wide assessment of the synthesis and stability of RNA. Methods. 2014;67:45-54</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26197343" target="_blank">Andrade-Lima L., Veloso A. and Ljungman M. Transcription Blockage Leads to New Beginnings. Biomolecules. 2015;5:1600</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26255935" target="_blank">Lefkofsky H. B., Veloso A. and Ljungman M. (2015) Transcriptional and post-transcriptional regulation of nucleotide excision repair genes in human cells. Mutat Res 776: 9-15</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25659587" target="_blank">Kocab A. J., Veloso A., Paulsen M. T., Ljungman M. and Duckett C. S. (2015) Effects of physiological and synthetic IAP antagonism on c-IAP-dependent signaling. Oncogene </a></li>
</ol>

<h5>BruDRB-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/brudrb-seq.png"></p>

<p>BruDRB-Seq reports the elongation rate of RNAPII. 
5,6-dichlorobenzimidazole 1-beta-D-ribofuranoside (DRB) is added to cells before elongation to inhibit RNAPII transiently, allowing synchronized transcriptional initiation throughout the genome. Upon removal of DRB, Br-UTP is added instead of UTP, along with other nucleotides. After cell lysis, RNA is isolated and fragmented. Next, bromouridine-tagged RNA is immunoseparated from total RNA using magnetic beads coated with anti-BrdU antibodies. cDNA libraries are generated, using the TruSeq RNA library preparation protocol, and then sequenced..</p>
<h6>Pros:</h6>
<ul>
<li>Quantifies RNA elongation rate throughout the whole genome</li>
<li>Newly transcribed RNA molecules are tagged through their entire length</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to cell cultures and other artificial systems, due to the requirement for incubation in the presence of labeled nucleotides</li>
<li>Bru-Seq must be performed in conjunction with Bru-DRB-Seq for accurate data analysis</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24714810">BruDRB-Seq: Veloso A., Kirkconnell K. S., Magnuson B., Biewen B., Paulsen M. T., et al. (2014) Rate of elongation by RNA polymerase II is associated with specific gene features and epigenetic modifications. Genome Res 24: 896-905</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit V2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25693130" target="_blank">Jonkers I. and Lis J. T. Getting up to speed with transcription elongation by RNA polymerase II. Nat Rev Mol Cell Biol. 2015;16:167-177</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25811895" target="_blank">Fuchs G., Voichek Y., Rabani M., Benjamin S., Gilad S., et al. (2015) Simultaneous measurement of genome-wide transcription elongation speeds and rates of RNA polymerase II transition into active elongation with 4sUDRB-seq. Nat Protoc 10: 605-618</a></li>
</ol>

<h5>CAGE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cage-seq.png"></p>

<p>CAGE measures RNA expression and maps TSS in promoters.  
In this method, RNA is first reverse-transcribed using random primers. The RNA cap and 3' ends are biotinylated. Nonhybridized, single-stranded RNAs are digested with RNase, leaving 5' complete cDNAs that are captured using streptavidin beads. The cDNA is processed for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Measures RNA expression levels and maps TSS in promoter regions</li>
<li>Provides precise mapping of TSS with single-nucleotide resolution</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Only works on total mature RNA<sup>1</sup> </li>
<li>Detection is biased toward TSS of long-lived transcripts </li>
</ul>
<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22362160">CAGE-Seq: Takahashi H., Lassmann T., Murata M. and Carninci P. (2012) 5' end-centered expression profiling using cap-analysis gene expression and next-generation sequencing. Nat Protoc 7: 542-561</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26783721" target="_blank">1. Haberle V. and Lenhard B. Promoter architectures and developmental gene regulation. Semin Cell Dev Biol. 2016;57:11-23</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27645561" target="_blank">Horie M., Yamaguchi Y., Saito A., et al. Transcriptome analysis of periodontitis-associated fibroblasts by CAGE sequencing identified DLX5 and RUNX2 long variant as novel regulators involved in periodontitis. Sci Rep. 2016;6:33666</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25978676" target="_blank">Poletti V., Delli Carri A., Malagoli Tagliazucchi G., et al. Genome-Wide Definition of Promoter and Enhancer Usage during Neural Induction of Human Embryonic Stem Cells. PLoS One. 2015;10:e0126590</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24670763" target="_blank">Andersson R., Gebhard C., Miguel-Escalada I., et al. An atlas of active enhancers across human cell types and tissues. Nature. 2014;507:455-461</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24670639" target="_blank">Brown J. B., Boley N., Eisman R., et al. Diversity and dynamics of the Drosophila transcriptome. Nature. 2014;512:393-399</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24985915" target="_blank">Chen Z. X., Sturgill D., Qu J., et al. Comparative validation of the D. melanogaster modENCODE transcriptome annotation. Genome Res. 2014;24:1209-1223</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24777452" target="_blank">Fort A., Hashimoto K., Yamada D., et al. Deep transcriptome profiling of mammalian stem cells supports a regulatory role for retrotransposons in pluripotency maintenance. Nat Genet. 2014;46:558-566</a></li>
</ol>

<h5>CaptureSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/captureseq.png"></p>

<p>CaptureSeq is a targeted RNA sequencing method that is able to provide higher sequencing coverage for selected regions of the genome.
This method follows the TruSeq RNA sample preparation protocol, in which mRNA is first isolated from total RNA by poly(A) selection and then fragmented. Double-stranded cDNA copies of the fragments are generated using reverse transcriptase and then ligated to p5 and p7 adapters. Next, these cDNA library fragments are amplified by the polymerase chain reaction (PCR). To increase specificity, custom capture probes are hybridized to the cDNA and bound to an array while other transcripts are washed away prior to PCR amplification. This process leaves the targeted fragments that are ready for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Highly suitable for discovering novel exons, genes, and splice isoforms</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires large amount of total RNA (5 µg) to yield 250 ng of amplified cDNA for capture</li>
<li>Coverage accuracy drops for transcripts with repetitive sequences</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22081020" target="_blank">CaptureSeq: Mercer T. R., Gerhardt D. J., Dinger M. E., Crawford J., Trapnell C., et al. (2012) Targeted RNA sequencing reveals the deep complexity of the human transcriptome. Nat Biotechnol 30: 99-104</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-exome.html">TruSeq Exome Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26803287" target="_blank">Marbaniang C. N. and Vogel J. Emerging roles of RNA modifications in bacteria. Curr Opin Microbiol. 2016;30:50-57</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26297315" target="_blank">Gloss B. S. and Dinger M. E. The specificity of long noncoding RNA expression. Biochim Biophys Acta. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25801053" target="_blank">Luciano D. J. and Belasco J. G. NAD in RNA: unconventional headgear. Trends Biochem Sci. 2015;40:245-247</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27197243" target="_blank">Bussotti G., Leonardi T., Clark M. B., et al. Improved definition of the mouse transcriptome via targeted RNA sequencing. Genome Res. 2016;26:705-716</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25751143" target="_blank">Clark M. B., Mercer T. R., Bussotti G., et al. Quantitative gene profiling of long noncoding RNAs with targeted RNA sequencing. Nat Methods. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22081020" target="_blank">Mercer T. R., Gerhardt D. J., Dinger M. E., et al. Targeted RNA sequencing reveals the deep complexity of the human transcriptome. Nat Biotechnol. 2012;30:99-104</a></li>
</ol>

<h5>CHART</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/chart.png"></p>

<p>CHART maps genomic binding sites of ncRNAs by isolating and sequencing the DNA regions where the crosslinked RNA-DNA-protein complexes are bound.  CHART differs from other crosslinked-complex purification techniques, such as ChIRP, due to the use of biotinylated 24 nt oligonucleotides (C-oligos) that are highly sensitive and unique to the ncRNA of interest.  
</p><p>An RNase H mapping assay is used to design the 24 nt sequence of the C-oligos. First, nuclei samples are crosslinked and fragmented. Next, C-oligos are hybridized to the complex and bound to streptavidin beads. The mixture is washed and the complex eluted. The DNA is isolated and sequenced, and the proteins involved in the complex are isolated and analyzed by Western blots.</p>
<h6>Pros:</h6>
<ul>
<li>Maps genomic binding sites of lncRNAs</li>
<li>Simultaneously identify proteins associated with the lncRNA complex</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Needs large amount of nuclei (1x10<sup>9</sup> cells)</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22143764" target="_blank">CHART: Simon M. D., Wang C. I., Kharchenko P. V., West J. A., Chapman B. A., et al. (2011) The genomic binding sites of a noncoding RNA. Proc Natl Acad Sci U S A 108: 20497-20502</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded Total RNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26039869" target="_blank">Hassan M. Q., Tye C. E., Stein G. S. and Lian J. B. Non-coding RNAs: Epigenetic regulators of bone development and homeostasis. Bone. 2015;81:746-756</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25662012" target="_blank">Lee N., Moss W. N., Yario T. A. and Steitz J. A. EBV noncoding RNA binds nascent RNA to drive host PAX5 to viral DNA. Cell. 2015;160:607-618</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27441387" target="_blank">Torres M., Becquet D., Blanchard M. P., et al. Circadian RNA expression elicited by 3'-UTR IRAlu-paraspeckle associated elements. Elife. 2016;5:</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24488179" target="_blank">Vance K. W., Sansom S. N., Lee S., et al. The long non-coding RNA Paupar regulates the expression of both local and distal genes. EMBO J. 2014;33:296-311</a></li>
</ol>

<h5>ChIRP-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/chirp-seq.png"></p>

<p>ChIRP, also commonly referred to as ChIRP-seq, is a protocol to detect the locations on the genome where ncRNAs, such as lncRNAs, and their proteins are bound.  
In this method, samples are first crosslinked and sonicated. Biotinylated tiling oligos are hybridized to the RNAs of interest, and the complexes are captured with streptavidin magnetic beads. After treatment with RNase H, the DNA is extracted and sequenced. Deep sequencing can determine the lncRNA/protein interaction site at single-base resolution.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies binding sites anywhere on the genome</li>
<li>Enables discovery of new binding sites</li>
<li>Allows selection of specific RNAs of interest</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Nonspecific oligonucleotide interactions can lead to misinterpretation of binding sites</li>
<li>Chromatin can be disrupted during the preparation stage</li>
<li>The sequence of the RNA of interest must be known</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21963238">ChIRP-Seq: Chu C., Qu K., Zhong F. L., Artandi S. E. and Chang H. Y. (2011) Genomic maps of long noncoding RNA occupancy reveal principles of RNA-chromatin interactions. Mol Cell 44: 667-678</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-rrna-removal-human-mouse-rat.html">Ribo-Zero rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27489248" target="_blank">Tomita S., Abdalla M. O., Fujiwara S., et al. Roles of long noncoding RNAs in chromosome domains. Wiley Interdiscip Rev RNA. 2017;8:n/a-n/a</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27070700" target="_blank">Schmitt A. M. and Chang H. Y. Long Noncoding RNAs in Cancer Pathways. Cancer Cell. 2016;29:452-463</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26381323" target="_blank">Simon M. D. Insight into lncRNA biology using hybridization capture analyses. Biochim Biophys Acta. 2016;1859:121-127</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26500759" target="_blank">Yang Y., Wen L. and Zhu H. Unveiling the hidden function of long non-coding RNA by identifying its major partner-protein. Cell Biosci. 2015;5:59</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25565030" target="_blank">Chu C., Spitale R. C. and Chang H. Y. Technologies to probe functions and mechanisms of long noncoding RNAs. Nat Struct Mol Biol. 2015;22:29-35</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25813522" target="_blank">Leveille N., Melo C. A., Rooijers K., Diaz-Lagares A., Melo S. A., et al. (2015) Genome-wide profiling of p53-regulated enhancer RNAs uncovers a subset of enhancers controlled by a lncRNA. Nat Commun 6: 6520</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25664725" target="_blank">Li Z., Huang C., Bao C., Chen L., Lin M., et al. (2015) Exon-intron circular RNAs regulate transcription in the nucleus. Nat Struct Mol Biol 22: 256-264</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25772072" target="_blank">Luo M., Jeong M., Sun D., Park H. J., Rodriguez B. A., et al. (2015) Long Non-Coding RNAs Control Hematopoietic Stem Cell Function. Cell Stem Cell 16: 426-438</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25908244" target="_blank">Montes M., Nielsen M. M., Maglieri G., Jacobsen A., Hojfeldt J., et al. (2015) The lncRNA MIR31HG regulates p16(INK4A) expression to modulate senescence. Nat Commun 6: 6967</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25891907" target="_blank">Yin Y., Yan P., Lu J., Song G., Zhu Y., et al. (2015) Opposing Roles for the lncRNA Haunt and Its Genomic Locus in Regulating HOXA Gene Activation during Embryonic Stem Cell Differentiation. Cell Stem Cell 16: 504-516</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24997788" target="_blank">Quinn J. J., Ilik I. A., Qu K., Georgiev P., Chu C., et al. (2014) Revealing long noncoding RNA architecture and functions using domain-specific chromatin isolation by RNA purification. Nat Biotechnol 32: 933-940</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24371310" target="_blank">Li Z., Chao T. C., Chang K. Y., Lin N., Patil V. S., et al. (2014) The long noncoding RNA THRIL regulates TNFalpha expression through its interaction with hnRNPL. Proc Natl Acad Sci U S A 111: 1002-1007</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25083870" target="_blank">Trimarchi T., Bilal E., Ntziachristos P., Fabbri G., Dalla-Favera R., et al. (2014) Genome-wide mapping and characterization of Notch-regulated long noncoding RNAs in acute leukemia. Cell 158: 593-606</a></li>
</ol>

<h5>ClickSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/clickseq.png"></p>

<p>ClickSeq is an RNA sequencing technique that uses bioconjugation as an alternative to fragmentation in the library preparation step, to produce lower error rates than standard sequencing methods. 
</p><p>First, RNA is reverse-transcribed into cDNA, in a process similar to Sanger sequencing, with 3'-azido-2',3'dideoxynucleotides (AzNTPs). This process induces chain termination and semirandom primers (6 random nucleotides followed by an Illumina 3' P7 adapter) to sequence random positions on the RNA template. Single-stranded cDNA is purified, and the 3'-ends are click-ligated with alkyne-modified (5'hexynyl) P5 adapters. After PCR amplification, the cDNA library is ready to be sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Significantly reduced artifactual recombination rate due to elimination of the fragmentation step</li>
<li>Highly suitable for detecting rare recombination events</li>
<li>No fragmentation step</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>3'-azido blocked cDNA fragments are converted into double-stranded DNA with low efficiency</li>
<li>Read-through of AzNTP is still highly inefficient</li>
<li>Further optimization required for single-cell or single-molecule studies</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26116762">ClickSeq: Routh A., Head S. R., Ordoukhanian P. and Johnson J. E. (2015) ClickSeq: Fragmentation-Free Next-Generation Sequencing via Click Ligation of Adaptors to Stochastically Terminated 3'-Azido cDNAs. J Mol Biol 427: 2610-2616</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26408523" target="_blank">Routh A., Chang M. W., Okulicz J. F., Johnson J. E. and Torbett B. E. (2015) CoVaMa: Co-Variation Mapper for disequilibrium analysis of mutant loci in viral populations using next-generation sequence data. Methods 91: 40-47</a></li>
</ol>

<h5>cP-RNA-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cp-rna-seq.png"></p>

<p>2',3'-cyclic phosphate (cP) RNA sequencing (cP-RNA-Seq) is a method to isolate and sequence RNA species protected by cP at their 3' terminus, which usually prevents adapter ligation.  The researchers originally developed this technique to identify transfer RNA (tRNA) species that generate sex hormone–dependent tRNA-derived RNAs (SHOT-RNAs) in human breast cancer cells, but it can be used for other RNA species protected by cP at the 3' end.<sup>1</sup>
</p><p>Total RNA from samples is isolated and gel-purified to the desired length. This mixture contains RNA species with 3' hydroxy, 3'phosphate, and 3'-cP. Phosphatase treatment removes phosphates from the 5' and 3' ends. The RNA is treated subsequently with periodate to cleave the 3'-hydroxyl ends into 2'3'-dialdehydes, while leaving the 3'-cP ends intact. RNA strands with 2'3'-dialdehydes at their 3' terminus are inert to adapter ligation. Strands with 3'-cP are cleaved with T4 polynucleotide kinase (PNK) and ligated to sequencing adapters. After flanking both ends with adapters, the RNA strands are reverse-transcribed, amplified, purified, and sequenced.
</p>
<h6>Pros:</h6>
<ul>
<li>Selective isolation, amplification, and sequencing of RNA species protected by cP</li>
<li>Considerable improvement in efficiency and specificity compared to an earlier method using recombinant tRNA ligase and multiple gel purifications<sup>2</sup> </li>
</ul>
<h6>Cons:</h6>
<ul>
<li>False positives will arise when sequencing RNA species with 2'-O-methylribose modifications—such as plant miRNAs, plant and animal short interfering RNAs (siRNAs), and animal PIWI-interacting RNAs (piRNAs)—due to periodate cleavage specificity<sup>3</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26866791">cP-RNA-Seq: Honda S., Morichika K. and Kirino Y. (2016) Selective amplification and sequencing of cyclic phosphate-containing RNAs by the cP-RNA-seq method. Nat Protoc 11: 476-489</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26124144">1. Honda S., Loher P., Shigematsu M., Palazzo J. P., Suzuki R., et al. (2015) Sex hormone-dependent tRNA halves enhance cell proliferation in breast and prostate cancers. Proc Natl Acad Sci U S A 112: E3816-3825</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26866791" target="_blank">2. Honda S., Morichika K. and Kirino Y. Selective amplification and sequencing of cyclic phosphate-containing RNAs by the cP-RNA-seq method. Nat Protoc. 2016;11:476-489</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26866791" target="_blank">3. Honda S., Morichika K. and Kirino Y. Selective amplification and sequencing of cyclic phosphate-containing RNAs by the cP-RNA-seq method. Nat Protoc. 2016;11:476-489</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-rrna-removal-human-mouse-rat.html">Ribo-Zero rRNA Removal Kit (Human/Mouse/Rat)</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26124144">Honda S., Loher P., Shigematsu M., Palazzo J. P., Suzuki R., et al. (2015) Sex hormone-dependent tRNA halves enhance cell proliferation in breast and prostate cancers. Proc Natl Acad Sci U S A 112: E3816-3825</a></li>
</ol>

<h5>FRT-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/frt-seq.png"></p>

<p>Flow-cell surface reverse transcription sequencing (FRT-Seq) is an transcriptome sequencing technique developed in 2010 by Mamanova et al.  The method is strand-specific, free of amplification, and compatible with paired-end sequencing. 
</p><p>To begin with, poly(A) RNA samples are fragmented by metal-ion hydrolysis and dephosphorylated. Next, P7 primer/adapters are ligated to the 3' end of the fragments. The 3' adapter sequence starts at the 5' terminus with 20 nt of RNA followed by DNA nucleotides. The adapters are also 5' phosphorylated and blocked with dideoxycytosine (ddC) at the 3' end. After 3' adapter ligation, the fragments are size-selected for nucleotide fragments longer than the adapter. The 5' ends of the fragments are phosphorylated and ligated to P5 adapters. These adapters are blocked with an amino-C6 linker at the 5' end. Now that the fragments are flanked by adapters, they are hybridized to the flow cell and reverse-transcribed before cluster generation and sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Strand-specific poly(A) mRNA sequencing for transcriptome analysis</li>
<li>No amplification step - gives more accurate representation of the total mRNA population, preventing amplification bias</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires a large amount of input RNA material (250 ng)</li>
<li>Selects only poly(A) mRNA samples</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/20081834" target="_blank">FRT-Seq: Mamanova L., Andrews R. M., James K. D., Sheridan E. M., Ellis P. D., et al. (2010) FRT-seq: amplification-free, strand-specific transcriptome sequencing. Nat Methods 7: 130-132</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Preparation Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24440557" target="_blank">van Dijk E. L., Jaszczyszyn Y. and Thermes C. Library preparation methods for next-generation sequencing: tone down the bias. Exp Cell Res. 2014;322:12-20</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23290152" target="_blank">McGettigan P. A. Transcriptomics in the RNA-seq era. Curr Opin Chem Biol. 2013;17:4-11</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24907032" adhocenable="false">Vergara-Irigaray M., Fookes M. C., Thomson N. R. and Tang C. M. (2014) RNA-seq analysis of the influence of anaerobiosis and FNR on Shigella flexneri. BMC Genomics 15: 438</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24179440" adhocenable="false">Mills J. D., Kawahara Y. and Janitz M. (2013) Strand-Specific RNA-Seq Provides Greater Resolution of Transcriptome Profiling. Curr Genomics 14: 173-181</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22538806" adhocenable="false">Kroger C., Dillon S. C., Cameron A. D., Papenfort K., Sivasankaran S. K., et al. (2012) The transcriptional landscape and small RNAs of Salmonella enterica serovar Typhimurium. Proc Natl Acad Sci U S A 109: E1277-1286</a></li>
</ol>

<h5>GMUCT 1.0</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/gmuct11.png"></p>

<p>GMUCT is a method for constructing sequencing libraries made up of decapped or cleaved mRNAs.  There are 2 versions of GMUCT: version 1.0 was developed in 2008, while a more streamlined and efficient version 2.0 was designed in 2013. GMUCT 2.0 significantly decreases library preparation time by 3 days (it takes 2–3 days instead of 5–6 days) and requires 10 times less starting total RNA (5 µg instead of 50 µg. 
</p><p>GMUCT 1.0: Starting with total RNA, mRNA is isolated by poly(A) selection. Next, 5' RNA adapters are ligated and the RNA is reverse-transcribed. The resultant first strand of cDNA is amplified using oligo(dT) and 5'-adapter primers. The double-stranded cDNA is fragmented, ligated to 3'- and 5'-sequencing adapters, PCR-amplified, and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Sequences RNA degradation intermediates and uncapped RNAs</li>
<li>GMUCT 2.0 only takes 2-3 days and 5 µg of total RNA</li>
<li>Can be modified to study cleavage of miRNA or siRNA targets</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Minimum size of 135 bp</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/18486559">GMUCT 1.0: Gregory B. D., O'Malley R. C., Lister R., Urich M. A., Tonti-Filippini J., et al. (2008) A link between RNA metabolism and silencing affecting Arabidopsis development. Dev Cell 14: 854-866</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26016494" target="_blank">Ma X., Tang Z., Qin J. and Meng Y. The use of high-throughput sequencing methods for plant microRNA research. RNA Biol. 2015;12:709-719</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26561561" target="_blank">Vandivier L. E., Campos R., Kuksa P. P., Silverman I. M., Wang L. S. and Gregory B. D. Chemical Modifications Mark Alternatively Spliced and Uncapped Messenger RNAs in Arabidopsis. Plant Cell. 2015;27:3024-3037</a></li>
</ol>

<h5>GMUCT 2.0</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/gmuct1.png"></p>

<p>GMUCT is a method for constructing sequencing libraries made up of decapped or cleaved mRNAs.  There are 2 versions of GMUCT: version 1.0 was developed in 2008, while a more streamlined and efficient version 2.0 was designed in 2013. GMUCT 2.0 significantly decreases library preparation time by 3 days (it takes 2–3 days instead of 5–6 days) and requires 10 times less starting total RNA (5 µg instead of 50 µg. 
</p><p>GMUCT 2.0: This version starts out similar to GMUCT 1.0, but deviates after the ligation of 5' RNA adapters to poly(A) RNAs. Another round of poly(A) selection is performed to further purify the desired mRNA away from any unligated RNA. RT is performed using primers with 3' adapters on their 5' terminus and a random hexamer on the 3' end. This modification adds 3' adapters during RT, resulting in cDNA strands flanked with adapters at both ends. The cDNA is PCR-amplified, to add sequencing indexes, and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Sequences RNA degradation intermediates and uncapped RNAs</li>
<li>GMUCT 2.0 only takes 2-3 days and 5 µg of total RNA</li>
<li>Can be modified to study cleavage of miRNA or siRNA targets</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Minimum size of 135 bp</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23867340">GMUCT 2.0: Willmann M. R., Berkowitz N. D. and Gregory B. D. (2014) Improved genome-wide mapping of uncapped and cleaved transcripts in eukaryotes--GMUCT 2.0. Methods 67: 64-73</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26016494" target="_blank">Ma X., Tang Z., Qin J. and Meng Y. The use of high-throughput sequencing methods for plant microRNA research. RNA Biol. 2015;12:709-719</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26561561" target="_blank">Vandivier L. E., Campos R., Kuksa P. P., Silverman I. M., Wang L. S. and Gregory B. D. Chemical Modifications Mark Alternatively Spliced and Uncapped Messenger RNAs in Arabidopsis. Plant Cell. 2015;27:3024-3037</a></li>
</ol>

<h5>GRO-Seq/BRIC-Seq/Bru-Seq/BruChase-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/gro-seq-bric-seq-bru-seq-bruchase-seq.png"></p>

<p>GRO-Seq maps the binding sites of transcriptionally active RNA polymerase II (RNAPII). In this method, active RNAPII is allowed to run on in the presence of 5-bromouridine 5'-triphosphate (Br-UTP). RNAs are hydrolyzed and purified using beads coated with antibodies to 5-bromo-2-deoxyuridine (BrdU). After cap removal and end repair, the eluted RNA is reverse-transcribed to cDNA. Deep sequencing of the cDNA identifies RNAs that are actively transcribed by RNAPII.</p>
<h6>Pros:</h6>
<ul>
<li>Maps position of transcriptionally engaged RNA polymerases</li>
<li>Determines relative activity of transcription sites</li>
<li>Detects sense and antisense transcription</li>
<li>Detects transcription anywhere on the genome</li>
<li>No prior knowledge of transcription sites is needed</li>
<li>Provides robust coverage of enhancer- and promoter-associated RNAs<sup>1</sup></li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Limited to cell cultures and other artificial systems, due to the requirement for incubation in the presence of labeled nucleotides</li>
<li>Artifacts may be introduced during the preparation of the nucle<sup>2</sup>i .</li>
<li>New initiation events may occur during the run-on step</li>
<li>Physical impediments may block the polymerases</li>
<li>Resolution is only 30–100 nt<sup>3</sup></li>
<li>Requires nascent RNAs of at least 18 nt<sup>4</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/19056941">GRO-Seq: Core L. J., Waterfall J. J. and Lis J. T. (2008) Nascent RNA sequencing reveals widespread pausing and divergent initiation at human promoters. Science 322: 1845-1848</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/22369889">BRIC-Seq: Tani H., Mizutani R., Salam K. A., Tano K., Ijiri K., et al. (2012) Genome-wide determination of RNA stability reveals hundreds of short-lived noncoding transcripts in mammals. Genome Res 22: 947-956&nbsp;</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23345452">Bru-Seq / BruChase-Seq: Paulsen M. T., Veloso A., Prasad J., Bedi K., Ljungman E. A., et al. (2013) Coordinated regulation of synthesis and stability of RNA during the acute TNF-induced proinflammatory response. Proc Natl Acad Sci U S A 110: 2240-2245</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26914315" target="_blank">1. Melnik S., Caudron-Herger M., Brant L., et al. Isolation of the protein and RNA content of active sites of transcription from mammalian cells. Nat Protoc. 2016;11:553-565</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22986266" target="_blank">2. Adelman K. and Lis J. T. Promoter-proximal pausing of RNA polymerase II: emerging roles in metazoans. Nat Rev Genet. 2012;13:720-731</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26844429" target="_blank">3. Nojima T., Gomes T., Carmo-Fonseca M. and Proudfoot N. J. Mammalian NET-seq analysis defines nascent RNA profiles and associated RNA processing genome-wide. Nat Protoc. 2016;11:413-428</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27010758" target="_blank">4. Mayer A. and Churchman L. S. Genome-wide profiling of RNA polymerase transcription at nucleotide resolution in human cells with native elongating transcript sequencing. Nat Protoc. 2016;11:813-833</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html" adhocenable="false">TruSeq Small RNA Library Preparation Kits</a></li>
<li><a adhocenable="false" href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html" target="_blank">TruSeq Stranded total RNA Library prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26780995" target="_blank">Murakawa Y., Yoshihara M., Kawaji H., Nishikawa M., Zayed H., et al. Enhanced Identification of Transcriptional Enhancers Provides Mechanistic Insights into Diseases. Trends Genet. 2016;32:76-88</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26499213" target="_blank">Li Y., Chen C. Y., Kaye A. M. and Wasserman W. W. The identification of cis-regulatory elements: A review from a machine learning perspective. Biosystems. 2015;138:6-17</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25693130" target="_blank">Jonkers I. and Lis J. T. Getting up to speed with transcription elongation by RNA polymerase II. Nat Rev Mol Cell Biol. 2015;16:167-177</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26873106" target="_blank">Schwer B., Wei P. C., Chang A. N., et al. Transcription-associated processes cause DNA double-strand breaks and translocations in neural stem/progenitor cells. Proc Natl Acad Sci U S A. 2016;113:2258-2263</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27292797" target="_blank">Chen Y. C., Stuwe E., Luo Y., et al. Cutoff Suppresses RNA Polymerase II Termination to Ensure Expression of piRNA Precursors. Mol Cell. 2016;63:97-109</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27245778" target="_blank">Czimmerer Z., Varga T., Kiss M., et al. The IL-4/STAT6 signaling axis establishes a conserved microRNA signature in human and mouse macrophages regulating cell survival via miR-342-3p. Genome Med. 2016;8:63</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27259512" target="_blank">Day D. S., Zhang B., Stevens S. M., et al. Comprehensive analysis of promoter-proximal RNA polymerase II pausing across mammalian cell types. Genome Biol. 2016;17:120</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26814966" target="_blank">de Dieuleveult M., Yen K., Hmitou I., et al. Genome-wide nucleosome specificity and function of chromatin remodellers in ES cells. Nature. 2016;530:113-116</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26878240" target="_blank">Flynn R. A., Do B. T., Rubin A. J., Calo E., Lee B., et al. 7SK-BAF axis controls pervasive transcription at enhancers. Nat Struct Mol Biol. 2016;23:231-238</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26751173" target="_blank">Korkmaz G., Lopes R., Ugalde A. P., et al. Functional genetic screens for enhancer elements in the human genome using CRISPR-Cas9. Nat Biotechnol. 2016;34:192-198</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26914315" target="_blank">Melnik S., Caudron-Herger M., Brant L., et al. Isolation of the protein and RNA content of active sites of transcription from mammalian cells. Nat Protoc. 2016;11:553-565</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26844429" target="_blank">Nojima T., Gomes T., Carmo-Fonseca M. and Proudfoot N. J. Mammalian NET-seq analysis defines nascent RNA profiles and associated RNA processing genome-wide. Nat Protoc. 2016;11:413-428</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26751768" target="_blank">Petryk N., Kahli M., d'Aubenton-Carafa Y., et al. Replication landscape of the human genome. Nat Commun. 2016;7:10208</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27299313" target="_blank">Woolnough J. L., Atwood B. L., Liu Z., Zhao R. and Giles K. E. The Regulation of rRNA Gene Transcription during Directed Differentiation of Human Embryonic Stem Cells. PLoS One. 2016;11:e0157276</a></li>
</ol>

<h5>mNET-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/mnet-seq.png"></p>

<p>mNET-Seq generates profiles of nascent RNA and cotranscriptional RNA processing associated with different C-terminal domain (CTD) phosphorylation states throughout the whole genome. mNET-Seq is able to provide precise sequence reads of RNAPII active sites during transcript elongation and also RNA processing intermediates. First, elongating RNAPII complexes are isolated through chromatin fractionation. They are digested with MNase, breaking down all exposed DNA while leaving RNA strands protected by RNAPII or spliceosomes intact. The RNAPII complexes are immunoprecipitated using RNAPII antibodies and 5' phosphorylated by T4 PNK. Next, 3' linkers are ligated to the 3' hydroxyl end of the RNA strand still embedded within RNAPII. They are also incubated with radioactive ATP to facilitate size selection. Nascent RNA strands are size-selected for 35–100 nt, processed into cDNA sequencing libraries, and sequenced. The use of various RNAPII antibodies during purification raises the versatility and specificity of the technique in targeting CTDs of RNAPII.</p>
<h6>Pros:</h6>
<ul>
<li>Maps nascent RNA strands and cotranscriptional RNA processing during RNAPII elongation with phosphorylated CTDs</li>
<li>Able to detect sense and antisense transcripts at TSS<sup>1</sup></li>
<li>No crosslinking—eliminates introduction of artifactual interactions</li>
<li>MNase digestion is specific and efficient</li>
<li>Various RNAPII-specific antibodies can be used to increase targeting accuracy</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Nascent RNAs shorter than 35 nt cannot be detected reliably</li>
<li>RNA can degrade during RNAPII immunoprecipitation</li>
<li>mNET-Seq peaks might be obscured by peaks from cotranscriptional RNA cleavage</li>
<li>PCR amplification may give rise to peaks from amplification bias.</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25910207" target="_blank">mNET-Seq: Nojima T., Gomes T., Grosso A. R., et al. Mammalian NET-Seq Reveals Genome-wide Nascent Transcription Coupled to RNA Processing. Cell. 2015;161:526-540</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26844429" target="_blank">1. Nojima T., Gomes T., Carmo-Fonseca M. and Proudfoot N. J. Mammalian NET-seq analysis defines nascent RNA profiles and associated RNA processing genome-wide. Nat Protoc. 2016;11:413-428</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26613890" target="_blank">Mellor J., Woloszczuk R. and Howe F. S. The Interleaved Genome. Trends Genet. 2016;32:57-71</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27605205" target="_blank">Zaborowska J., Egloff S. and Murphy S. The pol II CTD: new twists in the tail. Nat Struct Mol Biol. 2016;23:771-777</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25910207" target="_blank">Nojima T., Gomes T., Grosso A. R., et al. Mammalian NET-Seq Reveals Genome-wide Nascent Transcription Coupled to RNA Processing. Cell. 2015;161:526-540</a></li>
</ol>

<h5>NET-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/net-seq.png"></p>

<p>NET-Seq detects nascent, actively transcribed RNAPII RNAs, through the capture of 3' RNA.  
In this method, the RNAPII elongation complex is immunoprecipitated, and RNA is extracted and reverse-transcribed to cDNA. Deep sequencing of the cDNA allows for 3'-end sequencing of nascent RNA, providing nucleotide-resolution mapping of transcripts.</p>
<h6>Pros:</h6>
<ul>
<li>Mapping of nascent RNA-bound protein</li>
<li>Transcription is mapped at nucleotide resolution</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Antibodies not specific to the target will precipitate nonspecific complexes</li>
<li>Requires nascent RNAs of at least 18 nt<sup>1</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/21248844">NET-Seq: Churchman L. S. and Weissman J. S. (2011) Nascent transcript sequencing visualizes transcription at nucleotide resolution. Nature 469: 368-373</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-rrna-removal-human-mouse-rat.html">Ribo-Zero rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27198714" target="_blank">Hrdlickova R., Toloue M. and Tian B. RNA-Seq methods for transcriptome analysis. Wiley Interdiscip Rev RNA. 2017;8:n/a-n/a</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26780995" target="_blank">Murakawa Y., Yoshihara M., Kawaji H., Nishikawa M., Zayed H., et al. Enhanced Identification of Transcriptional Enhancers Provides Mechanistic Insights into Diseases. Trends Genet. 2016;32:76-88</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26822487" target="_blank">Zhang J. and Landick R. A Two-Way Street: Regulatory Interplay between RNA Polymerase and Nascent RNA Structure. Trends Biochem Sci. 2016;41:293-310</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26254229" target="_blank">Liu X., Kraus W. L. and Bai X. Ready, pause, go: regulation of RNA polymerase II pausing and release by cellular signaling pathways. Trends Biochem Sci. 2015;40:516-525</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26273910" target="_blank">Lemay J. F. and Bachand F. Fail-safe transcription termination: Because one is never enough. RNA Biol. 2015;12:927-932</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27239037" target="_blank">Harlen K. M., Trotta K. L., Smith E. E., Mosaheb M. M., Fuchs S. M. and Churchman L. S. Comprehensive RNA Polymerase II Interactomes Reveal Distinct and Varied Roles for Each Phospho-CTD Residue. Cell Rep. 2016;15:2147-2158</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27010758" target="_blank">Mayer A. and Churchman L. S. Genome-wide profiling of RNA polymerase transcription at nucleotide resolution in human cells with native elongating transcript sequencing. Nat Protoc. 2016;11:813-833</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25976475" target="_blank">Imashimizu M., Takahashi H., Oshima T., et al. Visualizing translocation dynamics and nascent transcript errors in paused RNA polymerases in vivo. Genome Biol. 2015;16:98</a></li>
</ol>

<h5>PAL-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pal-seq.png"></p>

<p>PAL-Seq measures poly(A)-tail length by incorporating fluorescent tags on biotinylated deoxyuridine triphosphate (dUTPs) and using signal intensity to quantify poly(A)-tail length.  Similar to 3P-Seq RNA library preparation, a splint oligonucleotide containing a 3'-adapter sequence is ligated to the 3' end of polyadenylated RNA and partially digested with RNase T1. 
</p><p>To separate mRNA from total RNA, the sample is size-selected by gel purification and bound to streptavidin beads before phosphorylating the 5' ends for adapter ligation. Before cluster generation, the mRNA fragments are reverse-transcribed into cDNA, released from the beads, and purified by size selection through a gel. Sequencing primers are attached to the 3' end of the poly(A) sequence and extended using deoxythymidine triphosphate (dTTP) and biotinylated dUTP. To map the fragments, regions near the 5' end of the poly(A) tails are sequenced. Fluorescent-labeled streptavidin molecules are attached to the biotin-dUTPs, and their signal intensity is measured to quantify the length of the adenine homopolymers in each cluster.</p>
<h6>Pros:</h6>
<ul>
<li>Accurate measurement of poly(A)-tail length, regardless of length</li>
<li>Avoids direct sequencing of the poly(A) tail</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Technically complex to perform</li>
<li>Efficiency-related issues may arise during the biotin-dUTP extension step</li>
<li>Only captures 3' ends that consist purely of adenines</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24476825" target="_blank">PAL-Seq: Subtelny A. O., Eichhorn S. W., Chen G. R., Sive H. and Bartel D. P. (2014) Poly(A)-tail profiling reveals an embryonic switch in translational control. Nature 508: 66-71</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit V2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27474798" target="_blank">Eichhorn S. W., Subtelny A. O., Kronja I., Kwasnieski J. C., Orr-Weaver T. L. and Bartel D. P. mRNA poly(A)-tail changes specified by deadenylation broadly reshape translation in Drosophila oocytes and early embryos. Elife. 2016;5:</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26092945" target="_blank">Harrison P. F., Powell D. R., Clancy J. L., et al. PAT-seq: a method to study the integration of 3'-UTR dynamics with gene expression in the eukaryotic transcriptome. RNA. 2015;21:1502-1510</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26305463" target="_blank">Kappel C., Trost G., Czesnick H., et al. Genome-Wide Analysis of PAPS1-Dependent Polyadenylation Identifies Novel Roles for Functionally Specialized Poly(A) Polymerases in Arabidopsis thaliana. PLoS Genet. 2015;11:e1005474</a></li>
</ol>

<h5>PARE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pare-seq.png"></p>

<p>Various RNA degradation processes impart characteristic sequence ends. By analyzing the cleavage sites, the degradation processes can be inferred.  
In PARE-Seq, the degraded uncapped mRNA is ligated to 5' adapters containing an MmeI restriction site and reverse-transcribed. The cDNA fragments are digested with Mmel, purified, ligated to 3' adapters, and PCR-amplified. Deep sequencing of the cDNA provides information about uncapped transcripts that undergo degradation.</p>
<h6>Pros:</h6>
<ul>
<li>Maps degrading RNA</li>
<li>miRNA cleavage sites are identified</li>
<li>No prior knowledge of the target RNA sequence is required</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Non-linear PCR amplification can lead to biases affecting reproducibility</li>
<li>Amplification errors caused by polymerases will be represented and sequenced incorrectly</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18542052" target="_blank">PARE-Seq: German M. A., Pillay M., Jeong D. H., Hetawal A., Luo S., et al. (2008) Global identification of microRNA-target RNA pairs by parallel analysis of RNA ends. Nat Biotechnol 26: 941-946</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-nano-dna-library-prep-kit.html">TruSeq Nano DNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq-dna-pcr-free-library-prep-kits.html">TruSeq DNA PCR-Free Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26000844" target="_blank">Reuter J. A., Spacek D. V. and Snyder M. P. High-Throughput Sequencing Technologies. Mol Cell. 2015;58:586-597</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26444665" target="_blank">Yi F., Chen J. and Yu J. Global analysis of uncapped mRNA changes under drought stress and microRNA-dependent endonucleolytic cleavages in foxtail millet. BMC Plant Biol. 2015;15:241</a></li>
</ol>

<h5>PEAT</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/peat.png"></p>

<p>PEAT characterizes transcription start sites (TSS) in mRNA using a technique similar to TIF-Seq.  
First, poly(A)+ RNAs are enriched from total RNA and the caps are removed with TAP. The 5' ends of uncapped mRNAs are ligated to chimeric linkers containing MmeI restriction endonuclease sites prior to RT. The RT primers  also contain an MmeI site, resulting in single-stranded cDNA flanked by MmeI sites. The fragments are PCR-amplified and circularized into circular single-stranded cDNA, which is amplified further by rolling-circle amplification. MmeI is used to cut circular cDNA at the 2 MmeI sites to create linear, double-stranded cDNA fragments that are 93–95 bp long. The fragments are ligated to paired-end adapters, amplified, and sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Maps transcription initiation patterns using paired-end sequencing</li>
<li>Improved accuracy and alignment yield compared to older, single-end TSS mapping strategies</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Does not distinguish between capped and noncapped RNA as in TIF-Seq</li>
<li>Not designed to sequence 3'-UTRs as in TIF-Seq</li>
<li>May produce chimeric fragments</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/20495556">PEAT: Ni T., Corcoran D. L., Rach E. A., Song S., Spana E. P., et al. (2010) A paired-end sequencing strategy to map the complex landscape of transcription initiation. Nat Methods 7: 521-527</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit V2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26869700" target="_blank">Megraw M., Cumbie J. S., Ivanchenko M. G. and Filichkin S. A. Small Genetic Circuits and MicroRNAs: Big Players in Polymerase II Transcriptional Control in Plants. Plant Cell. 2016;28:286-303</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26780995" target="_blank">Murakawa Y., Yoshihara M., Kawaji H., et al. Enhanced Identification of Transcriptional Enhancers Provides Mechanistic Insights into Diseases. Trends Genet. 2016;32:76-88</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25035402" target="_blank">Morton T., Petricka J., Corcoran D. L., et al. Paired-end analysis of transcription start sites in Arabidopsis reveals plant-specific promoter signatures. Plant Cell. 2014;26:2746-2760</a></li>
</ol>

<h5>PRO-cap</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pro-cap.png"></p>

<p>PRO-cap maps RNAPII initiation sites during RNA transcription with base-pair resolution. This approach is a variation of the PRO-Seq method, which maps RNAPII pause sites.  
A nuclear run-on reaction with biotin-NTP and sarkosyl is carried out on nuclear lysates. Incorporation of the first biotin-NTP halts further elongation of nascent RNA strands by RNAPII. The RNA strands are extracted and purified through streptavidin pull-down. Next, 3' adapters are ligated directly to the purified sample before another streptavidin purification step. The 5' ends are repaired using Antarctic phosphatase and TAP before ligating 5' adapters. The adapter-flanked RNA fragments are enriched through another streptavidin pull-down process before RT and PCR amplification. The resultant cDNA strands are sequenced from the 5' end, and RNAPII pause sites are mapped.</p>
<h6>Pros:</h6>
<ul>
<li>Maps RNAPII initiation sites with base-pair resolution</li>
<li>Multiple biotin enrichment steps before PCR</li>
<li>Pause sites mapped using PRO-seq</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>	Limited to in vitro reactions</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23430654" target="_blank">PRO-cap: Kwak H., Fuda N. J., Core L. J. and Lis J. T. (2013) Precise maps of RNA polymerase reveal how promoters direct initiation and pausing. Science 339: 950-953</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27720190" target="_blank">Brent M. R. Past Roadblocks and New Opportunities in Transcription Factor Network Mapping. Trends Genet. 2016;32:736-750</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27783602" target="_blank">Engreitz J. M., Haines J. E., Perez E. M., Munson G., Chen J., et al. Local regulation of gene expression by lncRNA promoters, transcription and splicing. Nature. 2016;539:452-455</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24561252" target="_blank">Wang I. X., Core L. J., Kwak H., Brady L., Bruzel A., et al. RNA-DNA differences are generated in human cells within seconds after RNA exits polymerase II. Cell Rep. 2014;6:906-915</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25799441" target="_blank">Danko C. G., Hyland S. L., Core L. J., Martins A. L., Waters C. T., et al. Identification of active transcriptional regulatory elements from GRO-seq data. Nat Methods. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25383968" target="_blank">Core L. J., Martins A. L., Danko C. G., Waters C. T., Siepel A., et al. Analysis of nascent RNA identifies a unified architecture of initiation regions at mammalian promoters and enhancers. Nat Genet. 2014;</a></li>
</ol>

<h5>PRO-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/pro-seq.png"></p>

<p>Precision nuclear run-on sequencing (PRO-Seq) maps RNAP active sites with base-pair resolution.  This approach is similar to GRO-Seq, but it provides the added benefit of single-base resolution. RNAPII initiation sites can be mapped using a modified protocol named PRO-cap.</p>
<p>In PRO-seq, a run-on reaction is carried out with biotin-NTPs (either all 4, or one with additional unlabeled NTPs to reduce cost) and sarkosyl, is carried out in isolated nuclei or permeabilized cells. Incorporation of the single biotin-NTP halts further elongation of nascent RNA strands by RNAPII. The RNA strands are extracted, fragmented, and purified through streptavidin pull-down. Next, 3' adapters are ligated directly to the purified sample before another streptavidin purification step. The 5' ends are repaired using TAP and PNK before ligating 5' adapters. The adapter-flanked RNA fragments are enriched through another streptavidin pull-down process before RT and PCR amplification. The resultant cDNA strands are sequenced from the 3' end.</p>
<h6>Pros:</h6>
<ul>
<li>Maps RNAPII pausing sites with base-pair resolution</li>
<li>Multiple biotin enrichment steps before PCR</li>
<li>Initiation sites can be mapped using a PRO-cap variant protocol</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Unable to detect arrested or backtracked RNAPII complexes<sup>1</sup></li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23430654" target="_blank">PRO-Seq: Kwak H., Fuda N. J., Core L. J. and Lis J. T. (2013) Precise maps of RNA polymerase reveal how promoters direct initiation and pausing. Science 339: 950-953</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24606920" target="_blank">1. Weber C. M., Ramachandran S. and Henikoff S. (2014) Nucleosomes are context-specific, H2A.Z-modulated barriers to RNA polymerase. Mol Cell 53: 819-830</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27720190" target="_blank">Brent M. R. Past Roadblocks and New Opportunities in Transcription Factor Network Mapping. Trends Genet. 2016;32:736-750</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27783602" target="_blank">Engreitz J. M., Haines J. E., Perez E. M., et al. Local regulation of gene expression by lncRNA promoters, transcription and splicing. Nature. 2016;539:452-455</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24561252" target="_blank">Wang I. X., Core L. J., Kwak H., et al. RNA-DNA differences are generated in human cells within seconds after RNA exits polymerase II. Cell Rep. 2014;6:906-915</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25799441" target="_blank">Danko C. G., Hyland S. L., Core L. J., et al. Identification of active transcriptional regulatory elements from GRO-seq data. Nat Methods. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25383968" target="_blank">Core L. J., Martins A. L., Danko C. G., Waters C. T., Siepel A. and Lis J. T. Analysis of nascent RNA identifies a unified architecture of initiation regions at mammalian promoters and enhancers. Nat Genet. 2014;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24453987" target="_blank">Pagano J. M., Kwak H., Waters C. T., et al. Defining NELF-E RNA binding in HIV-1 and promoter-proximal pause regions. PLoS Genet. 2014;10:e1004090</a></li>
</ol>

<h5>RAP</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rap.png"></p>

<p>RAP isolates lncRNAs and maps the sequence of their target DNA through a probe-capture mechanism.  
First, the cells are crosslinked and lysed before DNase I chromatin digestion to 100–300 bp DNA fragments. Biotinylated RNA probes, antisense to the lncRNA, are hybridized and captured with streptavidin. The biotin-RNA probes are 120 nt and are tiled every 15 nt over the span of the lncRNA. The captured complexes are eluted and prepared for sequencing. RNA library preparation is done through RAP-RNA, and DNA library preparation by standard chromatin immuniprecipitation (ChIP).</p>
<h6>Pros:</h6>
<ul>
<li>Genomic mapping of lncRNA targets</li>
<li>Possible to sequence RNA and DNA from the purification products</li>
<li>Long RNA probe length provides high binding affinity to the target lncRNA<sup>1</sup> </li>
<li>Minimal amplification steps during RNA sequencing after purification of the lncRNA complex</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires RNA sequence to be known</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23828888">RAP: Engreitz J. M., Pandya-Jones A., McDonel P., Shishkin A., Sirokman K., et al. (2013) The Xist lncRNA exploits three-dimensional genome architecture to spread across the X chromosome. Science 341: 1237973</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26477492">1. Kashi K., Henderson L., Bonetti A. and Carninci P. (2015) Discovery and functional analysis of lncRNAs: Methodologies to investigate an uncharacterized transcriptome. Biochim Biophys Acta </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded Total RNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_chip_sample_prep_kit.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26477492" target="_blank">Kashi K., Henderson L., Bonetti A. and Carninci P. Discovery and functional analysis of lncRNAs: Methodologies to investigate an uncharacterized transcriptome. Biochim Biophys Acta. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26381323" target="_blank">Simon M. D. Insight into lncRNA biology using hybridization capture analyses. Biochim Biophys Acta. 2016;1859:121-127</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27492478" target="_blank">Chen C. K., Blanco M., Jackson C., et al. Xist recruits the X chromosome to the nuclear lamina to enable chromosome-wide silencing. Science. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25902512" target="_blank">Boque-Sastre R., Soler M., Oliveira-Mateos C., et al. Head-to-head antisense transcription and R-loop formation promotes transcriptional activation. Proc Natl Acad Sci U S A. 2015;</a></li>
<li><a href="http://dx.doi.org/10.1038/nature14443" target="_blank">McHugh C. A., Chen C.-K., Chow A., et al. The Xist lncRNA interacts directly with SHARP to silence transcription through HDAC3. Nature. 2015;521:232-236</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25259926" target="_blank">Engreitz J. M., Sirokman K., McDonel P., et al. RNA-RNA interactions enable specific targeting of noncoding RNAs to nascent Pre-mRNAs and chromatin sites. Cell. 2014;159:188-199</a></li>
</ol>

<h5>RAP-RNA</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rap-rna.png"></p>

<p>RNA sequencing of RAP isolates is different from standard RNA-Seq due to the noise from antisense RNA probes that were added. The complex is initially reverse-crosslinked and treated with DNase. The RNA mixture is dephosphorylated and ligated with an adaptor before reverse transcription. While the RNA-cDNA complexes are still annealed, the RNA probes are pulled-down with streptavidin to separate the cDNA fragments of interest from the antisense probes. After purification of cDNA fragments, a second adaptor is ligated and amplified through PCR before sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Genomic mapping of lncRNA targets</li>
<li>Possible to sequence RNA and DNA from the purification products</li>
<li>Long RNA probe length provide high binding affinity to the target lncRNA<sup>1</sup></li>
<li>Minimal amplification steps during RNA sequencing post-purification of lncRNA complex</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires RNA sequence to be known beforehand</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23828888">RAP-RNA: Engreitz J. M., Pandya-Jones A., McDonel P., Shishkin A., Sirokman K., et al. (2013) The Xist lncRNA exploits three-dimensional genome architecture to spread across the X chromosome. Science 341: 1237973</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26477492">1. Kashi K., Henderson L., Bonetti A. and Carninci P. (2015) Discovery and functional analysis of lncRNAs: Methodologies to investigate an uncharacterized transcriptome. Biochim Biophys Acta </a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_total_rna_library_prep_kit.html">TruSeq Stranded Total RNA Library Preparation Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_chip_sample_prep_kit.html">TruSeq ChIP Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25902512">Boque-Sastre R., Soler M., Oliveira-Mateos C., Portela A., Moutinho C., et al. (2015) Head-to-head antisense transcription and R-loop formation promotes transcriptional activation. Proc Natl Acad Sci U S A 112: 5785-5790</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25915022">McHugh C. A., Chen C. K., Chow A., Surka C. F., Tran C., et al. (2015) The Xist lncRNA interacts directly with SHARP to silence transcription through HDAC3. Nature </a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25259926">Engreitz J. M., Sirokman K., McDonel P., Shishkin A. A., Surka C., et al. (2014) RNA-RNA interactions enable specific targeting of noncoding RNAs to nascent Pre-mRNAs and chromatin sites. Cell 159: 188-199</a></li>
</ol>

<h5>RARSeq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rarseq.png"></p>

<p>RARseq is a cDNA-based, genotype-by-sequencing method for identifying RNA SNPs and polymorphic loci for population genomics.  This method performs read alignment using sequencing data from single and dual restriction enzyme digestion libraries and aligns them using both de novo and reference-based genome assembly.
</p><p>In RARseq, total RNA is isolated from samples. Next, first- and second-strand cDNA are generated by RT. The double-stranded cDNA is digested with selected restriction enzymes (MseI and MseI-StyI-HF). The double-stranded cDNA fragments are ligated to sequencing adapters before purification and size-selection to 200 bp. The samples are PCR-amplified, purified, and sequenced. Reads from both single- and double-digestion libraries are used for de novo and reference-based genome assembly.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies RNA SNPs and polymorphic loci for population genomics studies</li>
<li>Reduces reads from nongenic regions arising from highly methylated genomes</li>
<li>Uses both de novo and reference-based genome assembly for read alignment</li>
<li>More accurate SNP and allele discovery than genotyping by sequencing methods</li>
<li>Restriction enzyme selection is flexible and can be customized, depending on the genome</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Not yet adopted widely by the scientific community </li>
<li>Has only been performed on plant genomes</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26241739">RARSeq: Alabady M. S., Rogers W. L. and Malmberg R. L. (2015) Development of Transcriptomic Markers for Population Analysis Using Restriction Site Associated RNA Sequencing (RARseq). PLoS One 10: e0134855</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/26241739">Alabady M. S., Rogers W. L. and Malmberg R. L. (2015) Development of Transcriptomic Markers for Population Analysis Using Restriction Site Associated RNA Sequencing (RARseq). PLoS One 10: e0134855</a></li>
</ol>

<h5>RASL-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rasl-seq.png"></p>

<p>RNA-mediated oligonucleotide annealing, selection, and ligation with next-generation sequencing (RASL-Seq) is a 2-dimensional RNA sequencing method to quantify expression profiles of several hundred genes, under thousands of different conditions.  
</p><p>Custom probe pairs are designed for each gene of interest. A pair of probes needs to contain: 1) One probe containing a common index primer on its 3' end and a 20 nt oligonucleotide corresponding to the targeted exon sequence with a phosphate on the 5' end; and 2) another probe with a P5 adapter on its 5' end with a 20 nt sequence complementary to the exon that is adjacent to the other probe. The probe pairs are hybridized to the mRNA and separated from total RNA using oligo(dT)-biotin beads. A ligation step joins the probe pairs into a single PCR amplicon probe. The biotinylated mRNA strands are subsequently attached to streptavidin magnetic beads to elute the probe fragments. Next, P7 adapters are attached to the 3' index primer, and the library undergoes PCR amplification before sequencing. The library is sequenced from the 40 nt ligated P5 primer, followed by sequencing from the P7 primer oligonucleotide.</p>
<h6>Pros:</h6>
<ul>
<li>Quantify genetic expression in large gene panels under thousands of different experimental conditions</li>
<li>Effective on low total RNA amounts (10 ng for about 1000 cells)</li>
<li>Can be performed on isolated RNA samples or cell lysates</li>
<li>Can be performed manually or automatically using a custom robot</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Sequencing is carried out on short 40 nt fragments, which can cause problems in repetitive regions</li>
<li>High rate of random ligations can occur at low RNA levels</li>
<li>Automated process produces less robust results, due to random ligations during probe removal </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22470064" target="_blank">RASL-Seq: Li H., Qiu J. and Fu X. D. (2012) RASL-seq for massively parallel and quantitative analysis of gene expression. Curr Protoc Mol Biol Chapter 4: Unit 4.13.11-19</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27492256" target="_blank">Qiu J., Zhou B., Thol F., et al. Distinct splicing signatures affect converged pathways in myelodysplastic syndrome patients carrying mutations in different splicing regulators. RNA. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25779042" target="_blank">Kralovicova J., Knut M., Cross N. C. and Vorechovsky I. Identification of U2AF(35)-dependent exons by RNA-Seq reveals a link between 3' splice-site organization and activity of U2AF-related proteins. Nucleic Acids Res. 2015;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25326705" target="_blank">Shao C., Yang B., Wu T., et al. Mechanisms for U2AF to define 3' splice sites and regulate alternative splicing in the human genome. Nat Struct Mol Biol. 2014;21:997-1005</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/22727668" target="_blank">Zhou Z., Qiu J., Liu W., et al. The Akt-SRPK-SR axis constitutes a major pathway in transducing EGF signaling to regulate alternative splicing in the nucleus. Mol Cell. 2012;47:422-433</a></li>
</ol>

<h5>RNA-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/rna-seq.png"></p>

<p>RNA-Seq describes the abundance and sequence of RNA transcripts. The method, first published by several groups in 2008<sup>1-5</sup> has effectively displaced older methods such as serial analysis of gene expression (SAGE)  and massively parallel signature sequencing (MPSS).  With over 8000 references in PubMed, RNA-Seq is by far the most abundantly cited NGS method.<sup>6</sup>  All RNA-Seq methods are based on the use of a reverse transcriptase to convert the RNA to cDNA. Two basic variations use either random primers or oligo(dT) primers for this reaction. Oligo(dT) primers are highly 3' biased and mostly suitable for mRNA abundance (expression) analysis. Random primers also result in some bias, which can be reduced by fragmentation of the input RNA.<sup>7</sup>
</p><p>
Additional refinements, such as the use of Moloney murine leukemia virus reverse transcriptase (MMLV-RT) and template-switching oligonucleotides produce a higher yield of full-length transcripts for gene annotation and splice-variant detection. These methods include those based on switch mechanism at the 5' end of RNA templates (Smart), such as Smart-Seq  and Smart-seq2 ; cap-analysis gene expression (CAGE), such as NanoCAGE  and CAGEscan ; RNA-Seq from single nuclei (snRNA-Seq) ; and sequencing of fixed and recovered intact single-cell RNA (FRISCR).
</p>
<h6>Pros:</h6>
<ul>
<li>Highly suitable for discovering novel exons, genes, and splice isoforms</li>
<li>High dynamic range in expression analysis, compared to microarrays</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Primer bias</li>
<li>Reverse transcriptase may introduce sequencing errors</li>
</ul>

<h6>References:</h6>
<ul class="references">
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18488015" target="_blank">1. Wilhelm B. T., Marguerat S., Watt S., et al. Dynamic repertoire of a eukaryotic transcriptome surveyed at single-nucleotide resolution. Nature. 2008;453:1239-1243</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18599741" target="_blank">2. Sultan M., Schulz M. H., Richard H., et al. A global view of gene activity and alternative splicing by deep sequencing of the human transcriptome. Science. 2008;321:956-960</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18550803" target="_blank">3. Marioni J. C., Mason C. E., Mane S. M., Stephens M. and Gilad Y. RNA-seq: an assessment of technical reproducibility and comparison with gene expression arrays. Genome Res. 2008;18:1509-1517</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18516045" target="_blank">4. Mortazavi A., Williams B. A., McCue K., Schaeffer L. and Wold B. Mapping and quantifying mammalian transcriptomes by RNA-Seq. Nat Methods. 2008;5:621-628</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18451266" target="_blank">5. Nagalakshmi U., Wang Z., Waern K., et al. The transcriptional landscape of the yeast genome defined by RNA sequencing. Science. 2008;320:1344-1349</a></li>
  <li>6. Based on a PubMed search for RNA-Seq on 11/11/2016</li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/18516045" target="_blank">7. Mortazavi A., Williams B. A., McCue K., Schaeffer L. and Wold B. Mapping and quantifying mammalian transcriptomes by RNA-Seq. Nat Methods. 2008;5:621-628</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26813401" target="_blank">Conesa A., Madrigal P., Tarazona S., Gomez-Cabrero D., Cervera A., et al. A survey of best practices for RNA-seq data analysis. Genome Biol. 2016;17:13</a></li>
</ol>
<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27606429" target="_blank">Pareek C. S., Smoczynski R., Kadarmideen H. N., et al. Single Nucleotide Polymorphism Discovery in Bovine Pituitary Gland Using RNA-Seq Technology. PLoS One. 2016;11:e0161370</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27034466" target="_blank">Bennett C. G., Riemondy K., Chapnick D. A., et al. Genome-wide analysis of Musashi-2 targets reveals novel functions in governing epithelial cell migration. Nucleic Acids Res. 2016;44:3788-3800</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27377755" target="_blank">Suarez-Vega A., Gutierrez-Gil B., Klopp C., Tosser-Klopp G. and Arranz J. J. Comprehensive RNA-Seq profiling to evaluate lactating sheep mammary gland transcriptome. Sci Data. 2016;3:160051</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27765019" target="_blank">Davila J. I., Fadra N. M., Wang X., et al. Impact of RNA degradation on fusion detection by RNA-seq. BMC Genomics. 2016;17:814</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26969372" target="_blank">Chen M. J., Chen L. K., Lai Y. S., et al. Integrating RNA-seq and ChIP-seq data to characterize long non-coding RNAs in Drosophila melanogaster. BMC Genomics. 2016;17:220</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27706236" target="_blank">Arnold W. K., Savage C. R., Brissette C. A., Seshu J., Livny J. and Stevenson B. RNA-Seq of Borrelia burgdorferi in Multiple Phases of Growth Reveals Insights into the Dynamics of Gene Expression, Transcriptome Architecture, and Noncoding RNAs. PLoS One. 2016;11:e0164165</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27265030" target="_blank">Joshi R. K., Megha S., Rahman M. H., Basu U. and Kav N. N. A global study of transcriptome dynamics in canola (Brassica napus L.) responsive to Sclerotinia sclerotiorum infection using RNA-Seq. Gene. 2016;590:57-67</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26818975" target="_blank">Seo M., Caetano-Anolles K., Rodriguez-Zas S., et al. Comprehensive identification of sexually dimorphic genes in diverse cattle tissues using RNA-seq. BMC Genomics. 2016;17:81</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27724872" target="_blank">Lukoszek R., Feist P. and Ignatova Z. Insights into the adaptive response of Arabidopsis thaliana to prolonged thermal stress by ribosomal profiling and RNA-Seq. BMC Plant Biol. 2016;16:221</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27623506" target="_blank">Zhang Q., Lai M. M., Lou Y. Y., Guo B. H., Wang H. Y. and Zheng X. Q. Transcriptome altered by latent human cytomegalovirus infection on THP-1 cells using RNA-seq. Gene. 2016;594:144-150</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27488818" target="_blank">Choi S. Y., Park B., Choi I. G., et al. Transcriptome landscape of Synechococcus elongatus PCC 7942 for nitrogen starvation responses using RNA-seq. Sci Rep. 2016;6:30584</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27756914" target="_blank">Zhang Z. X., Zhao S. N., Liu G. F., et al. Discovery of putative capsaicin biosynthetic genes by RNA-Seq and digital gene expression analysis of pepper. Sci Rep. 2016;6:34121</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27385103" target="_blank">Weissbein U., Schachter M., Egli D. and Benvenisty N. Analysis of chromosomal aberrations and recombination by allelic bias in RNA-Seq. Nat Commun. 2016;7:12144</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26883051" target="_blank">Chakraborty S., Britton M., Martinez-Garcia P. J. and Dandekar A. M. Deep RNA-Seq profile reveals biodiversity, plant-microbe interactions and a large family of NBS-LRR resistance genes in walnut (Juglans regia) tissues. AMB Express. 2016;6:12</a></li>
</ol>

<h5>SMORE-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/smore-seq.png"></p>

<p>Simultaneous mapping of RNA ends with sequencing (SMORE-Seq) is an RNA sequencing method to identify the transcription start sites (TSS) and polyadenylation sites (PAS) of RNA samples by sequencing the 5' and 3' ends simultaneously. Poly (A) RNA is first isolated from total RNA before adding tobacco acid pyrophosphatase (TAP) to remove the 5' mRNA cap. The de-capped 5' end of the mRNA is ligated to a P5 adapter and a fragmentation step occurs before ligating the P7 adapters to the 3' ends of the fragments. The mRNA fragments are reverse transcribed, PCR amplified, and size-selected to ~250 bp fragments. The selected fragments are PCR amplified and are ready to be sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies both TSS and PAS from the same RNA library dataset</li>
<li>More accurate in identifying TSS regions than RNA-Seq due to 5' de-capping with TAP</li>
<li>Mapping PAS using degradation intermediates is possible because a phosphatase treatment before TAP is omitted</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Full-length mRNA samples are preferable, which can be rare in highly degraded samples such as human tissue samples</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24413663" target="_blank">SMORE-Seq: Park D., Morris A. R., Battenhouse A. and Iyer V. R. (2014) Simultaneous mapping of transcript ends at single-nucleotide resolution and identification of widespread promoter-associated non-coding RNA governed by TATA elements. Nucleic Acids Res 42: 3736-3749</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GBR/products/truseq_small_rna_sample_prep_kit.html">TruSeq Small RNA Library Preparation Kits</a></li>
</ul>
</div>
</div>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24413663">Park D., Morris A. R., Battenhouse A. and Iyer V. R. (2014) Simultaneous mapping of transcript ends at single-nucleotide resolution and identification of widespread promoter-associated non-coding RNA governed by TATA elements. Nucleic Acids Res 42: 3736-3749</a></li>
</ol>

<h5>TAIL-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tail-seq.png"></p>

<p>TAIL-Seq focuses on sequencing the very ends of mRNA molecules (3'-UTRs and poly(A) tail regions) to explore their role in mRNA half-life, stability, their impact on translational efficiency, and to discover other aspects surrounding 3'-terminome function.  
</p><p>Ribosomal RNA (rRNA) is first removed from total RNA by affinity-based depletion. After purification, mRNAs are ligated to biotinylated 3' adapters prior to RNase T1 fragmentation and purified further by streptavidin pull-down. The 5' ends are phosphorylated and size-selected for 500–1000 nt fragments to prevent short noncoding RNA (ncRNA) fragments from contaminating the sequence data. The phosphorylated 5' ends are ligated to 5' adapters, reverse-transcribed, PCR-amplified, and sequenced. TAIL-Seq uses a unique paired-end run system to correlate the genes corresponding to the 3'-end sequence reads. By separating the paired-end reads, read 1 sequences 52 nt from the 5' end of the fragment to map the genome and identify transcripts, while read 2 sequences 251 nt from the 3' end specifically for sequence determination..</p>
<h6>Pros:</h6>
<ul>
<li>Quantifies poly(A) tail length on mRNA samples with high accuracy using a special fluorescence analysis method</li>
<li>Eliminates bias toward long poly(A) because it does not use oligo(dT) enrichment</li>
<li>Able to detect modified 3' ends, unlike poly(A)-tail length profiling by sequencing (PAL-Seq)<sup>1</sup> </li>
</ul>
<h6>Cons:</h6>
<ul>
<li>PCR amplification is unfavorable for homopolymeric sequences</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/24582499">TAIL-Seq: Chang H., Lim J., Ha M. and Kim V. N. (2014) TAIL-seq: genome-wide determination of poly(A) tail length and 3' end modifications. Mol Cell 53: 1044-1052</a></li>
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/25765321">1. Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. (2015) RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci 38: 226-236</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Prep Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/ribo-zero-gold-rrna-removal-human-mouse-rat.html">Ribo-Zero Gold rRNA Removal Kit</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/phix_control_v3.html">PhiX Sequencing Control V3</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25765321" target="_blank">Nussbacher J. K., Batra R., Lagier-Tourenne C. and Yeo G. W. RNA-binding proteins in neurodegeneration: Seq and you shall receive. Trends Neurosci. 2015;38:226-236</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27198714" target="_blank">Hrdlickova R., Toloue M. and Tian B. RNA-Seq methods for transcriptome analysis. Wiley Interdiscip Rev RNA. 2017;8:n/a-n/a</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26183531" target="_blank">Viegas S. C., Silva I. J., Apura P., Matos R. G. and Arraiano C. M. Surprises in the 3'-end: 'U' can decide too! FEBS J. 2015;282:3489-3499</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26972004" target="_blank">Zuber H., Scheer H., Ferrier E., et al. Uridylation and PABP Cooperate to Repair mRNA Deadenylated Ends in Arabidopsis. Cell Rep. 2016;14:2707-2717</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27153541" target="_blank">Park J. E., Yi H., Kim Y., Chang H. and Kim V. N. Regulation of Poly(A) Tail and Translation during the Somatic Cell Cycle. Mol Cell. 2016;62:462-471</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/26524240" target="_blank">Lapointe C. P., Wilinski D., Saunders H. A. and Wickens M. Protein-RNA networks revealed through covalent RNA marks. Nat Methods. 2015;12:1163-1170</a></li>
</ol>

<h5>TATL-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tatl-seq.png"></p>

<p>TATL-Seq works in conjunction with TL-Seq to target the sequence around the 5'-UTRs of mRNA attached to polysomes.  RNA from polysome gradient fractions is extracted, poly(A)-selected, and fragmented. Next, the TL-Seq protocol is followed to isolate and sequence the 5'-UTRs.</p>
<h6>Pros:</h6>
<ul>
<li>Sequences 5'-UTRs and identifies variants</li>
<li>TATL-Seq enables de novo transcript leader annotation while simultaneously testing their translational activity in a single experiment</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Selects short nucleotide fragments (50–80 nt)</li>
<li>Labor-intensive; requires large amounts of starting material</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a target="_blank" href="http://www.ncbi.nlm.nih.gov/pubmed/23580730">TATL-Seq: Arribere J. A. and Gilbert W. V. (2013) Roles for transcript leaders in translation and mRNA decay revealed by transcript leader sequencing. Genome Res 23: 977-987</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25820233" target="_blank">Smith J. E. and Baker K. E. Nonsense-mediated RNA decay--a switch and dial for regulating gene expression. Bioessays. 2015;37:612-623</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23580730" target="_blank">Arribere J. A. and Gilbert W. V. Roles for transcript leaders in translation and mRNA decay revealed by transcript leader sequencing. Genome Res. 2013;23:977-987</a></li>
</ol>

<h5>TIF-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tif-seq.png"></p>

<p>Transcript isoform sequencing (TIF-Seq) identifies transcript isoforms by selective sequencing of full-length mRNA molecules with 5'caps and poly(A) tails. 
Capped mRNA molecules are selected by substituting the 5'caps with oligonucleotides. To achieve this result, 5'-phosphate groups are removed from non-capped RNAs to differentiate them from their capped counterparts. The caps are removed by tobacco acid pyrophosphatase (TAP) treatment to expose the 5'-phosphate groups for ligation with oligonucleotides. mRNAs are separated into 2 different tubes and reverse-transcribed to generate full-length cDNA (flcDNA). flcDNA in each tube is annealed to barcoded 5'-biotinylated primers and 3' primers. The primers contain barcode sequences unique to each tube, as a control mechanism against chimeric fragments and intermolecular ligation. The 2 tubes are combined, digested with NotI enzyme to produce sticky ends, and ligated to form circular double-stranded cDNA, which is fragmented subsequently. Fragments containing the biotinylated 3' and 5' ends are isolated with streptavidin. Multiplexing barcodes are added to the 3' and 5' ends of the purified cDNA fragments to create a cDNA library for sequencing.</p>
<h6>Pros:</h6>
<ul>
<li>Identifies transcript isoforms by sequencing the 5' and 3' end of the same RNA strand</li>
<li>Chimera-control barcodes filter out intermolecular ligation of cDNA fragments</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Requires a large amount of full-length RNA in the sample</li>
<li>Use of NotI enzyme to introduce sticky ends is only viable for AT-rich genomes like yeast</li>
<li>Strong bias toward short RNA strands<sup>1</sup> </li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23615609" target="_blank">TIF-Seq: Pelechano V., Wei W. and Steinmetz L. M. (2013) Extensive transcriptional heterogeneity revealed by isoform profiling. Nature 497: 127-131</a></li>
  <li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24967623" target="_blank">1. Pelechano V., Wei W., Jakob P. and Steinmetz L. M. Genome-wide identification of transcript start and end sites by transcript isoform sequencing. Nat Protoc. 2014;9:1740-1759</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Prep Kit v2</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.intechopen.com/books/next-generation-sequencing-advances-applications-and-challenges/transcriptomic-profiling-using-next-generation-sequencing-advances-advantages-and-challenges" target="_blank">Anamika K., Verma S., Jere A. and Desai A. Transcriptomic Profiling Using Next Generation Sequencing - Advances, Advantages, and Challenges. 2016;</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27066865" target="_blank">Bagchi D. N. and Iyer V. R. The Determinants of Directionality in Transcriptional Initiation. Trends Genet. 2016;32:322-333</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25262381" target="_blank">Sole C., Nadal-Ribelles M., de Nadal E. and Posas F. A novel role for lncRNAs in cell cycle control during stress adaptation. Curr Genet. 2015;61:299-308</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23615609" target="_blank">Pelechano V., Wei W. and Steinmetz L. M. Extensive transcriptional heterogeneity revealed by isoform profiling. Nature. 2013;497:127-131</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/24967623" target="_blank">Pelechano V., Wei W., Jakob P. and Steinmetz L. M. Genome-wide identification of transcript start and end sites by transcript isoform sequencing. Nat Protoc. 2014;9:1740-1759</a></li>
</ol>

<h5>TL-Seq</h5>

<p class="seq-method-image"><img  src="https://emea.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/tl-seq.png"></p>

<p>TL-Seq targets and enriches for the sequence around the 5'-UTRs of 5'-capped mRNA molecules before sequencing. 
Poly(A)+ RNA is fragmented and selected for 50–80 nt fragments. RNA fragments with phosphorylated 5' ends are dephosphorylated, using calf intestinal phosphatase (CIP), to distinguish them from capped mRNA fragments. Next, TAP strips the capped mRNAs and exposes the phosphate on the 5' end for P5 adapter ligation. The adapter-ligated fragments are gel-purified by molecular weight before ligation of P7 adapters. The 3'-end adapters can be attached by poly(A) tailing and ligation, or directly if using preadenylated adapters. After RT and PCR amplification, the RNA library is sequenced.</p>
<h6>Pros:</h6>
<ul>
<li>Sequences 5' UTRs and identifies variants</li>
<li>Able to associate transcript leader function in translation when combined with translation-associated TL-Seq (TATL-Seq)</li>
</ul>
<h6>Cons:</h6>
<ul>
<li>Selects short nucleotide fragments (50–80 nt)</li>
<li>Labor-intensive; requires large amounts of starting material</li>
</ul>

<h6>References:</h6>
<ul class="references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23580730" target="_blank">TL-Seq: Arribere J. A. and Gilbert W. V. (2013) Roles for transcript leaders in translation and mRNA decay revealed by transcript leader sequencing. Genome Res 23: 977-987</a></li>
</ul>

<h6>Associated kits:</h6>
<div class="row"><div class="col-sm-6"><ul class="kits solutions">
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_rna_library_prep_kit_v2.html">TruSeq RNA Library Preparation Kit v2</a></li>
<li><a href="/content/illumina-marketing/emea/en_GB/products/truseq_stranded_mrna_library_prep_kit.html">TruSeq Stranded mRNA Library Preparation Kit</a></li>
</ul>
</div>
</div>

<h6>Most recent reviews</h6>
<ol class="dynamic reviews"><li><a href="http://www.ncbi.nlm.nih.gov/pubmed/27909578" target="_blank">Bangru S. and Kalsotra A. Advances in analyzing RNA diversity in eukaryotic transcriptomes: peering through the Omics lens. F1000Research. 2016;5:2668</a></li>
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/25820233" target="_blank">Smith J. E. and Baker K. E. Nonsense-mediated RNA decay--a switch and dial for regulating gene expression. Bioessays. 2015;37:612-623</a></li>
</ol>

<h6>Most recent references</h6>
<ol class="dynamic references">
<li><a href="http://www.ncbi.nlm.nih.gov/pubmed/23580730" target="_blank">Arribere J. A. and Gilbert W. V. Roles for transcript leaders in translation and mRNA decay revealed by transcript leader sequencing. Genome Res. 2013;23:977-987</a></li>
</ol>
