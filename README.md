# LongRepeatFinder
This script is used for long repeat identification and result information statistics in chloroplast and mitochondrial genomes. Please ensure that mkvtree and vmatch are installed and have been run to obtain preliminary results before using the script.
# The recommended commands for mkvtree and vmatch are:
mkvtree -db input.fa -dna -pl -v -allout
vmatch -v -l 30 -seedlength 8 -h 3 -d -p  input.fa
