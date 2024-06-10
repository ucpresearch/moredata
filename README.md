# moredata

This repository contains metadata (and some associated code) that I
created for existing corpora, especially the [Buckeye
Corpus](https://buckeyecorpus.osu.edu/), and
[Switchboard](https://catalog.ldc.upenn.edu/LDC97S62) (usually relying
on the [MS State annotations](https://www.isip.piconepress.com/projects/switchboard/)). You
are welcome to use my metadata for academic and educational purposes,
but please cite the appropriate paper. Whenever citing my work, be
sure to cite the original corpora as well. If you find any errors,
please let me know.

Currently, you can find the following metadata collections under the `metadata` directory

* [**aligned-buckeye-intensity_pitch_formants.tsv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/aligned-buckeye-intensity_pitch_formants.tsv.bz2)

    This collections contains data from two distinct papers. 
	
	- The alignment between CMU underlying representations and the intensity measures were presented in:
	
	    Uriel Cohen Priva and Emily Gleason. [The causal structure of lenition: A case for the causal precedence of durational shortening](http://dx.doi.org/10.1353/lan.2020.0025). *Language*, 96 (2): 413--448. ([open access](https://urielcpublic.s3.amazonaws.com/CohenPriva_Gleason-2020-Language.html))

	- The formant and pitch calculations were discussed in. Uriel Cohen Priva and Emily Strand. Under Review. "Schwa's duration and acoustic position in American English."  
	  Chelsea Sanker contributed to the creation of this resource. **Notice: this file is not the dataset used for the final publication in Journal of Phonetics, following reviewers' requests**

* [**buckeye-fave-stressed-vowels.tsv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/buckeye-fave-stressed-vowels.tsv.bz2)

    Only the vowels provided in Cohen Priva and Strand 2023. [Schwa's duration and acoustic position in American 
    English](http://dx.doi.org/10.1016/j.wocn.2022.101198). The formants in this case were extracted using FAVE-extract.


* [**aligned-buckeye-counts.python.txt.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/aligned-buckeye-counts.python.txt.bz2)

	This file is a python dictionary which represents the final alignment counts between CMU underlying representations and Buckeye annotations. These can serve as weights for future alignments. The process is described in:
	
    Uriel Cohen Priva and Emily Gleason. [The causal structure of lenition: A case for the causal precedence of durational shortening](http://dx.doi.org/10.1353/lan.2020.0025). *Language*, 96 (2): 413--448. ([open access](https://urielcpublic.s3.amazonaws.com/CohenPriva_Gleason-2020-Language.html))

	
* [**swbd.obstr.monov.obstr.props.csv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/swbd.obstr.monov.obstr.props.csv.bz2)

    Word formant and pitch modes for Switchboard words that have only one monophthong and no other sonorants. The data is meant to be aligned with the MS State annotations. Chelsea Sanker contributed to the creation of this resource. The method is described in:
	
	Cohen Priva, Uriel and Emily Strand. Under Review. "Schwa's duration and acoustic position in American English." Preprint available at [psyarxiv.com/gwkvh/](https://psyarxiv.com/gwkvh/)

* [**swbd-convergence-alldf.tsv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/swbd-convergence-alldf.tsv.bz2)

    Summary data per conversation side for multipls characteristics in Switchboard. The data is described in:
	
	Uriel Cohen Priva and Chelsea Sanker. [Natural leaders: Some interlocutors elicit greater convergence across conversations and across characteristics](http://dx.doi.org/10.1111/cogs.12897). *Cognitive Science*, 44 (10): e12897. ([download published version](https://urielcpublic.s3.amazonaws.com/papers/CohenPriva_Sanker-Cognitive_Science-Natural_Leaders.pdf)

