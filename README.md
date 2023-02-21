# Drosophilid transposon libraries

Semi-curated de-novo transposon libraries for 119 Drosophilid species.

## Content
A list of all species is provided in [species_list.txt](https://github.com/susbo/Drosophila_TE_libraries/tree/main/species_list.txt). The `FASTA` folder contains transposon consensus sequences for each species and the `info` folder contains the following information about each transposon:

1. Name
2. Class/Family
3. Predicted subfamily (95/80/98)
4. Predicted subfamily (90/80/90)
5. Predicted subfamily (80/80/80)
6. *env* ORF present
7. *gag* ORF present
8. *pol* ORF present
9. Count (buildSummary.pl)
10. Hits (blastn hits covering at least 80 nt and 50% of query length)
11. Coverage (buildSummary.pl)
12. Coverage (calcDivergenceFromAlign.pl)
13. Kimura divergence (calcDivergenceFromAlign.pl)
14. Length

## Generation of transposon libraries

Description of how the transposon libraries were generated is available at [https://github.com/susbo/Uni-strand_clusters](https://github.com/susbo/Uni-strand_clusters).

## Version

The current version is 0.1. For other the versions, see the [releases on this repository](https://github.com/susbo/Uni-stand_clusters/releases).

## Authors

* **Susanne Bornelöv** - [susbo](https://github.com/susbo)
* **Jasper van Lopik** - [Jvanlopik](https://github.com/JvanLopik)

## License

This project is licensed under the  GNU GPLv3 License - see the [LICENSE](LICENSE) file for details.

## Citation

If you use these scripts and pipelines, please cite our preprint:

