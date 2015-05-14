Here are some useful software  tools for genome assembly:

"Overlap layout consensus" assemblers use read alignments to generate consensus sequence, best for longer read technologies. Examples include: 

[Celera wgs-asssembler] (http://wgs-assembler.sourceforge.net)

[Newbler (Roche)] (http://www.454.com/products/analysis-software) 

String Graph Assembler (SGA; Simpson and Durbin, 2012); https://github.com/jts/sga

“graph-based assemblers” split the sequence reads into kmers and derive consensus sequence from weighted graphs, best for highly accurate short read technologies. Examples include: 

Velvet (Zerbino and Birney, 2008); https://www.ebi.ac.uk/~zerbino/velvet/

ABySS (Simpson et al., 2009); http://www.bcgsc.ca/platform/bioinfo/software/abyss

SOAPdenovo (Li et al., 2010); http://soap.genomics.org.cn/soapdenovo.html

AllPaths (MacCallum et al., 2009); https://www.broadinstitute.org/software/allpaths-lg/blog/

##Notes:::
Available computational resources need to be considered (for example, ABySS was designed for distributed computing systems, while SOAPdenovo runs best on single servers with multiple processors).

In recent years, there has been increasing interaction between experimental design and the development of assembly approaches (for example the ALLPATHS-LG assembler is specifically designed for the assembly of a specific combination of fragment and mate-pair libraries; Gnerre et al., 2011). For an overview of performing assemblies see Nagarajan and Pop (2013).
