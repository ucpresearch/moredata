# moredata

This repository contains metadata (and some associated code) that I created for existing corpora, especially the [Buckeye Corpus](https://buckeyecorpus.osu.edu/), and [Switchboard](https://catalog.ldc.upenn.edu/LDC97S62) (usually relying on the [MS State annotations](https://www.isip.piconepress.com/projects/switchboard/)). You are welcome to use my metadata for academic and educational purposes, but please cite the appropriate paper. Whenever citing my work, be sure to cite the original corpora as well. If you find any errors, please let me know. 

Currently, you can find the following metadata collections under the `metadata` directory

* [**aligned-buckeye-intensity_pitch_formants.tsv.bz2**](https://github.com/ucpresearch/moredata/blob/master/metadata/aligned-buckeye-intensity_pitch_formants.tsv.bz2)

    This collections contains data from two distinct papers. 
	
	- The alignment between CMU underlying representations and the intensity measures were presented in:
	
	    Uriel Cohen Priva and Emily Gleason. Accepted with minor revisions. [The causal structure of lenition: A case for the causal precedence of durational
shortening](http://urielcpublic.s3.amazonaws.com/CohenPriva_Gleason-Lenition-Submitted.pdf). *Language*.

	- The formant and pitch calculations were discussed in 
	
	    Uriel Cohen Priva and Emily Strand. In prep. Schwa has an articulatory target in American English.

* **aligned-buckeye-counts.python.txt.bz2**

	This file is a python dictionary which represents the final alignment counts between CMU underlying representations and Buckeye annotations. These can serve as weights for future alignments. The process is described in:
	
    Uriel Cohen Priva and Emily Gleason. Accepted with minor revisions. [The causal structure of lenition: A case for the causal precedence of durational
shortening](http://urielcpublic.s3.amazonaws.com/CohenPriva_Gleason-Lenition-Submitted.pdf). *Language*.

	
