RJMapper package version 0.1

A Tool to Improving Genome Assemblies with Repeat Junction Markers

Authors: Hao Wang
Address: Department of Genetics, University of Georgia, GA U.S.A.
Email: ynwh.km@gmail.com

Requirement:
        - Linux system
        - Perl 5.8 or higher
        - Python 2.6 (to run Easyfig)
        - NCBI Blastall program installed
        - Easyfig program installed (http://mjsull.github.io/Easyfig/)

How to use:
1. Prepare sequences:
        - Query data set: FASTA format. Unanchored sequences 
          that need to be mapped.
        - Reference data set: FASTA format.

3. Install program:
        - Download RJMapper-vXX.tar.gz
        - Untar RJMapper-v0.1.tar.gz and copy the package of 
          "RJMapper-vXX" to a folder.
        
4. Run program:
        - Type "perl RJMapper.pl", and provide pathes for
          reqired programs according to instructions
        
5. Examples:
	
        - perl RJMapper.pl -b /RJMapper/path/ -B /blastall/path 
          -i query.fasta -j ref.fasta -t LTR.fasta -o Map 
          -E /easyfig/path/ 
