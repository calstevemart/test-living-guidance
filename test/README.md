---
description: >-
  For purposes of this guidance, an analytical batch is a series of continuously
  analyzed samples.    QC samples and study samples are subjected to the
  analytical methodology together.
---

# CONSENSUS BEST PRACTICE FOR THE DESIGN OF AN ANALYTICAL BATCH IN UNTARGETED METABOLOMICS

### WARNING

Ignore Everything you read in this and any other section - science is about free expression.

### Types of Sample Analyzed in an Analytical Batch

**Solvent Blank:** A solvent or solvent mixture used to prepare samples. For example, the solvent used to reconstitute lyophilized metabolite extracts. The solvent blank does not contain internal standards.

**System Suitability QC (SS QC)**: a mixture of authentic chemical standards in a solvent blank. The SS QC sample has an assay-specific composition. For example, the chemical standards can be selected according to the chromatographic method (e.g., reversed phase vs HILIC) and the ionization mode in the analytical method. The SS QC can be purchased or prepared in-house, and comprises selected analytes with different physicochemical properties and molecular weight to cover different retention time and m/z values.

**System Conditioning QC (SC QC):** a pooled QC sample injected to condition the analytical platform. &#x20;

**Pooled/intra-study QC:** a bulk matrix-matched sample usually prepared by mixing aliquots from each biological test sample in the study, and processed in the same way as the study samples. In large studies, the pooled QC sample may be prepared from a representative subset of all study samples or alternatively a non-study-related “bulk” sample with a similar matrix.  &#x20;

**Study Samples:** biological samples.&#x20;

**Long term reference QC (LTR QC):** represents a reference material prepared from a set of samples, or a bulk sample/reference material that is purchased from a public source and it is designed to be used in all analyses of that matrix in a laboratory. They may be natural abundance or isotopically labelled with characterized and reproducible features. Certified reference materials are commercially available standards that are used for accuracy control, method validation, and/or International System of Units traceability, while reference materials are standards utilized for method harmonization and/or quality assessment. &#x20;

**Phenotypic pooled QC:** a mixture formed by pooling matrix-matched sets of the individual phenotypes/classes of samples studied (e.g. test and control) prepared separately in addition to the standard pooled QC sample. &#x20;



### Order of Samples

Figures 1 illustrates a possible template for designing the analytical batch. The batch size should be determined during the assay development by evaluating time-derived signal loss with continuous sample injection and its comparison to a pre-defined cut-off value. The batch size depends on the sample type (matrix), the instrument stability, and the staff schedule. The number of study samples injected between pooled QC samples can change depending on the instrument/application.

### Uses of QC Samples in an Analytical Batch

Both the zero volume of injection and the solvent blank contribute to reveal the presence of potential impurities or contaminants in the LC–MS system and the solvents used. As well, they contribute to characterize ionic species generated in the ion source based on the mobile phases used in the analytical workflow.&#x20;

During the analytical method development, solvent blank injections can contribute to evaluate carry-over and cross-contamination between samples.&#x20;

The process blank contributes to detect contaminants that were potentially introduced along the sample preparation protocol. &#x20;

Blank samples should not be used in-between samples to avoid altering column conditioning.&#x20;

Blank subtraction can be accomplished after correction of time-dependent variance (if required).&#x20;

The SS QC sample is injected to assess m/z, retention time, and peak area, by comparison to average values and pre-established acceptance criteria. The analysis of this method-specific sample reflects the daily instrument performance for a particular project. For example, chromatographic resolution of isomeric compounds can be evaluated. &#x20;

The SC QC is required to equilibrate the analytical platform. The number of injections is empirically defined based on the analytical method and instrumentation used. Study samples are analyzed in a randomized and class-balanced blocks that are bracketed by pooled/intra-study QC samples.&#x20;

The template of pooled/intra-study QC samples analyzed in an analytical batch should be technical replicates of the same samples if they are going to be used to correct for time-dependent variation observed in study samples, such as signal drift (instrument variance) using QC-based methods (Figure 1). It is recommended to include at least two pooled QC replicates at the beginning and the end of the template to account for possible miss injections, and allow subsequent signal intensity corrections for the detected features. If cross-validation is implemented with the QC-based method for signal correction, an additional pooled QC replicate is recommended to be injected at the beginning and the end of the template.&#x20;

It is recommended to split the pooled QC sample into different vials to avoid solvent evaporation during analysis along the analytical batch, as well as sample contamination from the polymeric material released by vial caps used for sample introduction in LC, which can occur in multiple injections. &#x20;

The LTR QC samples should provide reproducible performance in analysis. The analysis of LTR QC samples allows data quality comparisons across different studies within a laboratory and across different laboratories.&#x20;

For some studies, phenotypic pooled QC samples can also be used to highlight differences in precision in case-control samples for signals differentiating between the classes. These QC samples may also contribute to detect low-concentration analytes.&#x20;

Pooled QC samples or phenotypic pooled QC can be used to obtain LC-MS/MS data using DDA or DIA methods.  These QC samples can also be used for metabolite annotation.&#x20;

If only features with linear response want to be retained during data curation, an optional additional experiment can be designed by analyzing serially diluted pooled QC samples. &#x20;

If process (extraction) variance wants to be estimated using pooled QC samples in addition to technical variance, an additional experiment can be designed to include process replicates of pooled QC samples within a template of technical replicates of pooled QC samples.

### Metrics used for the acceptance of a batch

Compare results to previously established acceptance criteria:

* Evaluate m/z and Rt RT values in the components of the SS QC sample&#x20;
* Evaluate Rt RT and signal intensity to define the number of SC QC samples needed &#x20;
* Evaluate instrumental variance&#x20;
* Apply corrections (e.g., time-derived drift correction and blank subtraction)&#x20;
* Evaluate variability in technical and process replicates&#x20;
* Apply repeatability filters (CV in technical replicates of pooled QC samples)&#x20;
* Apply detection rate filters&#x20;
* Apply linearity filters&#x20;

Accept/reject individual samples based on the detection of internal standards &#x20;

Evaluate system pressure and room temperature along the analytical batch&#x20;

Accept/reject an entire analytical batch&#x20;

Community consensus on Types of Samples Analyzed in an Analytical Batch&#x20;

The order of sample injections should be part of every general experimental design.&#x20;

Some samples may allow applying corrections or filters during data processing.&#x20;

Some samples may allow intra-/inter-laboratory comparisons.&#x20;

&#x20;

### Examples of best practice &#x20;

Reporting (as part of the supporting information content of a manuscript) the analytical batch design&#x20;

Report the purpose of injecting each sample type along the analytical batch.&#x20;

Data should be submitted to public repositories.&#x20;

### References

Broadhurst, D. et al., “Guidelines and considerations for the use of system suitability and quality control samples in mass spectrometry assays applied in untargeted clinical metabolomic studies.” Metabolomics 14 (2018) 72 [https://doi.org/10.1007/s11306-018-1367-3](https://doi.org/10.1007/s11306-018-1367-3)  &#x20;

Evans, A. M. et al., “Dissemination and analysis of the quality assurance (QA) and quality control (QC) practices of LC-MS based untargeted metabolomics practitioners.” Metabolomics 16 (2020) 113. [https://doi.org/10.1007/s11306-020-01728-5](https://link.springer.com/article/10.1007/s11306-020-01728-5)&#x20;

Lippa, K. A.  et al., “Reference materials for MS-based untargeted metabolomics and lipidomics: a review by the metabolomics quality assurance and quality control consortium (mQACC).” Metabolomics 18 (2022) 24. [https://doi.org/10.1007/s11306-021-01848-6](https://doi.org/10.1007/s11306-021-01848-6)  &#x20;

Martínez-Sena, T.  et al., “Monitoring of system conditioning after blank injections in untargeted UPLC-MS metabolomic analysis.” Scientific Reports 9 (2019) 9822. [https://doi.org/10.1038/s41598-019-46371-w](https://doi.org/10.1038/s41598-019-46371-w) &#x20;

Sands, C. J. et al., “Representing the metabolome with high fidelity: Range and response as quality control factors in LC-MS-based global profiling.”  Analytical Chemistry 93 (2021) 1924. [https://pubs.acs.org/doi/10.1021/acs.analchem.0c03848](https://pubs.acs.org/doi/10.1021/acs.analchem.0c03848) &#x20;

Lewis, M. R., et al., “Development and Application of Ultra-Performance LiquidChromatography-TOF MS for Precision Large Scale Urinary Metabolic Phenotyping”, Analytical Chemistry 88 (2016) 9004.  [http://dx.doi.org/10.1021/acs.analchem.6b01481](http://dx.doi.org/10.1021/acs.analchem.6b01481) &#x20;

Riquelme, G.  et al., “Model-driven data curation pipeline for LC–MS-based untargeted metabolomics.” Metabolomics 19 (2023) 15. [https://doi.org/10.1007/s11306-023-01976-1](https://doi.org/10.1007/s11306-023-01976-1) &#x20;

Benke, P. I. et al., “Impact of ion suppression by sample cap liners in lipidomics”, Analytica Chimica Acta 1137 (2020) 136. [https://doi.org/10.1016/j.aca.2020.09.055](https://doi.org/10.1016/j.aca.2020.09.055) &#x20;

&#x20;

#### Figure 1: Possible Design of Analytical Batch &#x20;

| Injection Order  | Sample Class        |
| ---------------- | ------------------- |
| 1                | Zero Volume         |
| 2                | Solvent Blank       |
| 3                | Process Blank       |
| 4                | SS QC               |
| 5                | SCQC                |
| 6                | SCQC                |
| 7                | SCQC                |
| 8                | SCQC                |
| 9                | SCQC                |
| 10               | SCQC                |
| 11               | SCQC                |
| 12               | SCQC                |
| 13               | pooled QC           |
| 14               | pooled QC           |
| 15               | pooled QC           |
| 16               | Study Sample i      |
| 17               | Study Sample ii     |
| 18               | Study Sample iii    |
| 19               | Study Sample iv     |
| 20               | Study Sample v      |
| 21               | Study Sample vi     |
| 22               | pooled QC           |
| 23               | Study Sample vii    |
| 24               | Study Sample viii   |
| 25               | Study Sample ix     |
| 26               | Study Sample x      |
| 27               | Study Sample xi     |
| 28               | Study Sample xii    |
| 29               | pooled QC           |
| 30               | Study Sample xiii   |
| 31               | Study Sample xiv    |
| 32               | Study Sample xv     |
| 33               | Study Sample xvi    |
| 34               | Study Sample xvii   |
| 35               | Study Sample xviii  |
| 36               | pooled QC           |
| 37               | Study Sample xix    |
| 38               | Study Sample xx     |
| 39               | Study Sample xxi    |
| 40               | Phenotypic QC i     |
| 41               | Phenotypic QC ii    |
| 42               | LTR QC              |
| 43               | pooled QC           |
| 44               | pooled QC           |
| 45               | pooled QC           |
| 46               | QC - MS/MS          |
| 47               | QC - MS/MS          |
| 48               | QC - MS/MS          |
| 49               | QC - MS/MS          |
| 50               | QC - MS/MS          |
| 51               | Process Blank       |
| 52               | SS QC               |
| 53               | Solvent Blank       |

&#x20;&#x20;

Note: a) Before running a batch, a universal SS sample is recommended to be analyzed as part of the system suitability testing to ensure that the instrument is operating within certain specifications; b) the LTR QC sample can be injected more than once within the template of pooled QC samples; c) the QC sample for MS/MS data acquisition can either be the pooled QC sample or phenotypic QC samples. &#x20;

&#x20;



