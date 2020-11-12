# Kill corona

### 📖 Story

I recently came up with the idea to 'reverse engineer' corona as I read articles done by George Hotz giving me some inspirations on it (he gave analogies between computer terminology & biology). 
Now realising the fact that it is too hard for me only to do all research, I found @Caliton-Universe, who is very good at science, to do some research for me, and is currently my partner. 

**Now to the topic**

----

### 📌  The First Analogy

Biological systems are fundamentally information processing systems. Whilst not a perfect analogy, software provides a useful framework for thinking about biology. 

### 📑 Info

- This is currently written in Python. Currently I merely have some dictionaries made in order to decode the corona DNA series, Proteins, RNAs, and such. However, more investigations & thoughts (that I have no idea at all on) will be done in order to have me some ideas. 
- I am not at all expecting a success. Nevertheless, it will be happy to me if I can contribute even a tiny bit to the human healthcare. 
- I will upload all codes via [GitHub](https://www.github.com/KnowsCount/corona) in no longer than a month. Taking the suggestions given by @Caliton-Universe (that we shall not make it open-sourced) & Mrs Reed (that we shall at least leave our names), I give it a MIT license. 
- This Project, along with [MIT licensing](https://zh.wikipedia.org/wiki/MIT許可證) for the code, also is licensed [CC BY-NC-SA 4.0 (Attribution-NonCommercial-ShareAlike 4.0 International)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh). 

As I have previously stated, we are making some progress now by making some dictionaries that decodes the biological series (not sure if named so). 

### 📈 Progress

- BP (Base Pairs);
- Genetic Translation; 
- Proteins; 
- Codons; 
- Maybe a conspiracy from NCBI (just kidding... It might be my own mistake writing the code); 

### 🎉 Wishes

- We obviously want one to give suggestions if one can; 
- To maybe join the development if can work well; 
- To like the project... and maybe give a star in future GitHub repository.   

### 🔗 Useful Links

[Base Pair](https://en.wikipedia.org/wiki/Base_pair)
[Genome](https://www.soe.ucsc.edu/news/ucsc-genome-browser-posts-coronavirus-genome) or [Genome2](https://www.eurekalert.org/pub_releases/2020-02/uoc--ugb020720.php)
[NCBI stuff](https://www.ncbi.nlm.nih.gov/nuccore/NC_045512)
#### you should read this [article](./masks.md) about why masks dont really work..

### Biology vs. software

Biological systems are fundamentally [information processing systems](https://en.wikipedia.org/wiki/Information_processor). While not a perfect analogy, software provides a useful framework for thinking about biology. The table below provides a rough outline of this analogy. 

| 🔬 Biology                                                    | 💻 Software                                                   | Notes                                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [nucleotide](https://en.wikipedia.org/wiki/Nucleotide)       | [byte](https://en.wikipedia.org/wiki/Byte)                   |                                                              |
| [genome](https://en.wikipedia.org/wiki/Genome)               | [bytecode](https://en.wikipedia.org/wiki/Bytecode)           |                                                              |
| [translation](https://en.wikipedia.org/wiki/Translation_(biology)) | [disassembly](https://en.wikipedia.org/wiki/Disassembler)    | 3 byte wide instruction set with arbitrary "[reading frames](https://en.wikipedia.org/wiki/Reading_frame)" |
| [protein](https://en.wikipedia.org/wiki/Protein)             | [function](https://en.wikipedia.org/wiki/Function_(computer_science)) | a polyprotein is a function with multiple pieces             |
| [protein secondary structure](https://en.wikipedia.org/wiki/Protein_secondary_structure) | [basic blocks](https://en.wikipedia.org/wiki/Basic_block)    | 80% accuracy in [prediction](https://en.wikipedia.org/wiki/Protein_structure_prediction#Secondary_structure) |
| [protein tertiary structure](https://en.wikipedia.org/wiki/Protein_tertiary_structure) |                                                              | This seems like the hard one to predict: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0205819 |
| [quaternary structure](https://en.wikipedia.org/wiki/Protein_quaternary_structure) | [compiled function with inlining](https://en.wikipedia.org/wiki/Inline_expansion) | [https://en.wikipedia.org/wiki/Protein%E2%80%93protein_interaction_prediction](https://en.wikipedia.org/wiki/Protein–protein_interaction_prediction) |
| [gene](https://en.wikipedia.org/wiki/Gene)                   | [library](https://en.wikipedia.org/wiki/Library_(computing)) | bacteria are statically linked, viruses are dynamically linked |
| [transcription](https://en.wikipedia.org/wiki/Transcription_(biology)) | [loading](https://en.wikipedia.org/wiki/Loader_(computing))  |                                                              |
| [protein structure prediction](https://en.wikipedia.org/wiki/Protein_structure_prediction) | [library identification](https://www.hex-rays.com/products/ida/tech/flirt/in_depth/) |                                                              |
| [genome analysis](https://en.wikipedia.org/wiki/Genomics#Genome_analysis) | [static analysis](https://en.wikipedia.org/wiki/Static_program_analysis) |                                                              |
| [molecular dynamics](https://en.wikipedia.org/wiki/Molecular_dynamics)simulations of [protein folding](https://en.wikipedia.org/wiki/Protein_folding) | [dynamic analysis](https://en.wikipedia.org/wiki/Dynamic_program_analysis) | Simulation doesn't seem to work yet. Constrained by tooling and compute. |
| no equivalent                                                | [execution](https://en.wikipedia.org/wiki/Execution_(computing)) | We are reverse engineering a CAD format. Runs more like FPGA code, all at once. No serial execution. (What are the FPGA reverse engineering tools?) |

---

Some links<br>
https://en.wikipedia.org/wiki/Base_pair<br>
https://www.soe.ucsc.edu/news/ucsc-genome-browser-posts-coronavirus-genome or https://www.eurekalert.org/pub_releases/2020-02/uoc--ugb020720.php<br>
https://www.ncbi.nlm.nih.gov/nuccore/NC_045512
