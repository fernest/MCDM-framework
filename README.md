# *MCDM-ConSel* – a Framework for Blockchain Consensus Protocol Selection using MCDM


## Goal of this repository

Selecting the most suitable consensus protocol for a particular DLT system is essential. At the same time, a challenging step, as developers need to make a trade-off between conflicting requirements of a blockchain system.

This repository provides an Multi-Criteria Decision-Making (MCDM) framework for researchers and practitioners to select the most suitable consensus protocols (or other DLT system components) for specific blockchain systems or applications.

## The steps of the *MCDM-ConSel* framework

- Problem definition

- Selection of the alternatives

- Selection of the evaluation criteria

- Data processing

- Criteria weighting

- Ranking alternatives

The more detailed description of the framework and each step will be published soon

## The framework‘s tools

- [Tool to determine criteria importance weights](Tools/Pairwise-Comparison-2levels-blank.xlsx)

It is MS Excel based tool to determine criteria importance weights for criteria groups and criteria. The tool is based on Analytic Hierarchy Process (AHP) (Saaty, 2008) and pairwise comparisons (Odu, 2019). This tool is build on the basis of excel [AHP Spreadsheet](https://www.pyzdekinstitute.com/blog/six-sigma/ahp-spreadsheet.html).

- **Tool with MCDM methods**

It is a freely available (on-demand) MS Excel-based MCDM tool (Wang and Rangaiah,2017; Wang et al., 2020). The tool implements 14 different MCDM methods (SAW, TOPSIS, VIKOR, etc.) in total, and it could be used for extensive performed analysis. To get the tool, please contact Prof. GP Rangaiah [gprangaiah@nus.edu.sg](mailto:gprangaiah@nus.edu.sg).

## The data sets for the framework

- [Raw data set](Data/Consensus-data-raw.md)

  The raw data set was developed with the aim of identifying the preferable consensus protocols for the blockchain system according to its requirements. 

  Currently, the data set consists of categorized quantitative and qualitative data reflecting 18 state-of-the-art consensus protocols aggregated from various sources.

  The consensus protocols are grouped by families, and the most popular platform utilizing the protocol is indicated. We also identify the criteria corresponding to the collected features and metrics. 

- [Processed data set](Data/Consensus-data-processed.md)

Together with the collected raw data, we provide the processed data set ready to use by various MCDM methods. Then the collected data was processed following these rules:

1. Qualitative units are converted to quantitative ones;
2. Values represented by intervals are replaced by the mean values (by averaging each interval’s limit values);
3. Values bounded from above are replaced by the exact bound values;
4. Zero values are replaced with relatively small values  to  avoid  division  by  zero  error  in  some  MCDM  methods. 



## Contribution to the *MCDM-ConSel*

We welcome contributions and corrections to this resource either way:

- **common way** - send us your comments, corrections or suggestions by email: [ernestas.filatovas@mif.vu.lt](mailto:ernestas.filatovas@mif.vu.lt), [marco.marcozzi@unicam.it](mailto:marco.marcozzi@unicam.it), [remigijus.paulavicius@mif.vu.lt](mailto:remigijus.paulavicius@imperial.ac.uk)
- **modern way** - [fork](https://help.github.com/articles/fork-a-repo/) github repository, add new information & correct existing, then create a [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) and  we gratefully incorporate your contribution!

## References

- Saaty, T.L., 2008. Decision making with the analytic hierarchy process. *International Journal of Services Sciences* 1, 83–98. https://doi.org/10.1504/IJSSCI.2008.017590 
- Wang, Z., Parhi, S.S., Rangaiah, G.P., Jana, A.K., (2020). Analysis of weighting and selection methods for pareto-optimal solutions of multiobjective optimization in chemical engineering applications. *Industrial & Engineering Chemistry Research* 59, 14850–14867. https://doi.org/10.1021/acs.iecr.0c00969
- Wang, Z., Rangaiah, G.P., (2017). Application and analysis of methods for selecting an optimal solution from thepareto-optimal front obtained by multiobjective optimization. *Industrial & Engineering Chemistry Research* 56, 560–574. https://doi.org/10.1021/acs.iecr.6b03453

## Acknowledgment

- This research has been supported by a Grant (No. S-MIP-21-53) from the Research Council of Lithuania.
