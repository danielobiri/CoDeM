# CoDeM
Users have the option of using any of the four  neural layers (word vectors) used in the models for prediction.
1. GloVe
2. Skipgram
3. CBOW
4. FastText

# clone CoDem 
 https://github.com/danielobiri/CoDeM.git
# Navigate to the CoDeM directory
 cd CoDeM
 
# Run CoDeM using the command below
python3 CODeM.py -choice_wordvector [1,2,3, or 4] -in your_input_file.fasta  -out file_results

# Output
CoDeM outputs two files with each of the files containing separated fastq sequences. One file contains contaminated DNA nuclotides and the other file contains the uncotaminated nucleuotides 
