# pacbio_oxford_nanopore_repeat_coverage
a long read repeat coverage calculator,given an long read file  before assembly either direct from the sequencing runs or after  the cleaning, it calculates the total amount of the repeat stretches present in the sequencing reads and you can plot them before assembly to see how much repetitive your sequencing is and how to set the 
long read assembly parameters. 

I implemented a totally different approach and it parses millions of long reads in few minutes for the estimation of the coverage. It reports where the stretch is located and what is the position and how much is the total coverage of that type in your each sequencing read.   

```
repeatlocatorLongRead("/Users/gauravsablok/Desktop/CodeCheck/test_sample_sample1.fasta", 
                                                             polyATGCstretch_type="A")
	ids	sequences	repeat_locator	fraction_length	fraction_length_coverage
0	>seq1	ATATATATATAAGACGAGATAATAAAATTTTATATATATATAAAAA...	[AAAA, AAAAA]	[(41, 46), (23, 27)]	5.777778
1	>seq2	ATATATATATAAGACGAGATAATAAAATTTTATATATATATAAAAA...	[AAAA, AAAAA]	[(41, 46), (23, 27)]	5.777778
```

Gaurav Sablok \
ORCID: https://orcid.org/0000-0002-4157-9405 \
WOS: https://www.webofscience.com/wos/author/record/C-5940-2014 \
RubyGems Published: https://rubygems.org/profiles/sablokgaurav \
Python Packages Published : https://pypi.org/user/sablokgaurav/
