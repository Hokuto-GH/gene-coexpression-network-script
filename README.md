# gene-coexpression-network-script

Generate gene coexpression network for RNA-Seq data.

Welcome! This is repository for gene coexpression network script.
This R script was used in the published project: [Lignin-based resistance to Cuscuta campestris parasitism in Heinz resistant tomato cultivars](https://doi.org/10.1101/706861)

## Usage

The input file should be a CSV file with normalized RNA-Seq expression data or read counts with gene names by row and experiment samples by column.
Please see the sample data CSV file `t_only_all_4.csv` for examples of formatting. 

```{r}
counts=read.csv ("t_only_all_4.csv", row.names=1)
```

Please replace "t_only_all_4.csv" with the RNA-Seq expression data that you are using.

## Author Contact Info

- Package Author:
[Hokuto Nakayama](mailto:hokuto@bs.s.u-tokyo.ac.jp)

Feel free to contact Hokuto if you have any questions about the script.

- README.md Author:
[Min-Yao Jhu](mailto:minjhu@ucdavis.edu)