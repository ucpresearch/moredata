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
	
	    Uriel Cohen Priva and Emily Gleason. Accepted with minor revisions. [The causal structure of lenition: A case for the causal precedence of durational
shortening](http://urielcpublic.s3.amazonaws.com/CohenPriva_Gleason-Lenition-Submitted.pdf). *Language*.

	- The formant and pitch calculations were discussed in. Uriel Cohen Priva and Emily Strand. Under Review. "Schwa's duration and acoustic position in American English."  
	  Chelsea Sanker contributed to the creation of this resource.

* [**buckeye-fave-stressed-vowels.tsv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/buckeye-fave-stressed-vowels.tsv.bz2)

    Only the vowels provided in Cohen Priva and Strand, Under
    Review. The formants in this case were extracted using
    FAVE-extract, and containing only information that relates to
    vowel normalization studies.


* [**aligned-buckeye-counts.python.txt.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/aligned-buckeye-counts.python.txt.bz2)

	This file is a python dictionary which represents the final alignment counts between CMU underlying representations and Buckeye annotations. These can serve as weights for future alignments. The process is described in:
	
    Uriel Cohen Priva and Emily Gleason. 2020. [The causal structure of lenition: A case for the causal precedence of durational
shortening](http://urielcpublic.s3.amazonaws.com/CohenPriva_Gleason-Lenition-Submitted.pdf). *Language*.

	
* [**swbd.obstr.monov.obstr.props.csv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/swbd.obstr.monov.obstr.props.csv.bz2)

    Word formant and pitch modes for Switchboard words that have only one monophthong and no other sonorants. The data is meant to be aligned with the MS State annotations. Chelsea Sanker contributed to the creation of this resource. The method is described in:
	
	Cohen Priva, Uriel and Emily Strand. Under Review. "Schwa's duration and acoustic position in American English." Preprint available at [psyarxiv.com/gwkvh/](https://psyarxiv.com/gwkvh/)

* [**swbd-convergence-alldf.tsv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/swbd-convergence-alldf.tsv.bz2)

    Summary data per conversation side for multipls characteristics in Switchboard. The data is described in:
	
	Cohen Priva, Uriel and Chelsea Sanker, Under review. "Natural Leaders: Some interlocutors elicit greater convergence across conversations and across characteristics"

