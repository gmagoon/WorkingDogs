e# WorkingDogs
The home repo for the Working Dogs bioinformatics tools: Blue, Pup, Kelpie and other members of the pack. These tools are all kMer-based and make use of the very useful almost-always-unique properties of moderate-length kMers (k=20+).

Blue is a DNA read error corrector based on kMers and their context. It was published as "Blue: correcting sequencing errors using consensus and context" in Bioinformatics. 2014; 30(19), 2723-2732. Release 2.0 will appear here around the middle of 2018.

Pup is a kMer-based gene/genome comparator uses techniques from error correction to get better-than-BLAST similarity numbers for sequences ranging from genes to whole genomes. It will be published later in 2019 (after Kelpie).

Kelpie is a specialised assembler for between-primer regions, taking WGS reads and producing the equivalent of amplicons. It was published
in PeerJ in January 2019. https://peerj.com/articles/6174/

FilterReads is a boringly-named kMer filter than can rapidly find reads of interest in very large datasets. Given a 16S filter, it produces results very similar to HMM-based tools, but runs at close to IO speed.

Other kMer-based bioiformatics tool will join the pack from time to time.
