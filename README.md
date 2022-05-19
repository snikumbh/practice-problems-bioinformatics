# practice-problems-bioinformatics
Beginner level practice problems for aspiring bioinformaticians

These are some practice problems which can help make yourself more comfortable with doing routine data wrangling or manoeuvring in R. I believe this will be useful for you to think/imagine in R. In general this can speed things up for you to go from the imagination stage to prototyping some task. Some problems here can help you gain knowledge of some very popular Bioconductor packages. For instance, Biostrings, GenomicRanges/IRanges, etc. 

_Only if there is enough time_, I recommend also doing these problems without using the said Bioconductor packages to evaluate for yourself the benefit of having Bioconductor packages' ecosystem over the base R ecosystem.

Finally, please create a private repository on GitHub to maintain your code for these problems. Add me as a collaborator. My GitHub id is: snikumbh. 


## Problems:

1. Read an input text file (FASTA file with extension ".fa") containing genomic sequences. Try performing the following tasks:
  
	a. What all characters are present in the sequences? Are there any in addition to the DNA alphabet? [Hint: Biostrings]
    
	b. Report statistics on the base (single nucleotides) percentages over all sequences in the file.
    
	c. Can you separate out the positive and negative strand sequences into two separate files? Name these files "<input_filename>-positive-strand.fa" and "<input_filename>-negative-strand.fa". Here, replace the <input_filename> with the actual filename (without the extension). For example, if the input filename is: "input.fa", the output filenames will be "input-positive-strand.fa" and "input-negative-strand.fa".
    
    
2. Lookup what are the following file formats: Bed, Bedgraph, bigwig. Notice that these specify structured data -- for instance, data in a tabular format.
 
	  a. What functions are available to read such files into R? (Base R options)
		
    b. Given the example Bed file, can you read this file into R? 
	
    c. Read the second Bed file provided into R. Find the overlapping genomic regions between the two sets of regions obtained from the two files. [Hint: GenomicRanges]
	
3. Graphing/plotting: 

   a. For problem 1b, can you plot the base percentages? Use either of ggplot or base R plotting. If you can do both, great.

   b. For problem 2, the bed file has a score column. Can you show with a plot if the score is biased by the strand? 
	

## Additional notes:

1. Code reading: Reading (scientific) papers is very useful for scientists. 
In addition to getting to know current scientific research, this also helps you learn how (not) to write papers. 
Similarly, reading somebody else's code is also very useful, and in fact, encouraged. 
This speeds up learning a lot. 
And, as you cite somebody else's work/ideas in your papers, one must also cite and/or acknowledge anybody's code that you may have adapted (not necessary for rudimentary tasks). 
You don't have to overdo it.

