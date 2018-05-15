# SbtPlayData
Very small examples for testing Sequence Bloom Trees and similar data structures

The example1 directory contains five fastq files representing sequencing
experiments. These non-paired reads were simulated by sampling at 7X coverage
from five fake genomes. Simulated sequencing error was about 1% mismatches
with no indels.

The five genomes have lengths ranging from about 11K bp to 21K bp. These
contain a mix of random sequence data and some transcript-like sequences.  Some
"transcripts" are present in more than one genome, albeit with a 2% mutation
rate.
