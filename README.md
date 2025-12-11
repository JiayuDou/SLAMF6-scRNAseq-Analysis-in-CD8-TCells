# SLAMF6-scRNAseq-Analysis-in-CD8-TCells

**Single-cell RNA-seq analysis code** for the paper:  
**"SLAMF6 as a drug-targetable suppressor of T cell immunity against cancer"**

**Authors**  
Bin Li¹², Ming-Chao Zhong¹, Cristian Camilo Galindo¹³, Jiayu Dou¹³, Jin Qian¹, Zhenghai Tang¹⁴⁵, Dominique Davidson¹ and André Veillette¹²³*  

¹Laboratory of Molecular Oncology, Institut de recherches cliniques de Montréal (IRCM), Montréal, Québec H2W 1R7, Canada  
²Department of Medicine, University of Montréal, Montréal, Québec H3T 1J4, Canada  
³Department of Medicine, McGill University, Montréal, Québec H3G 1Y6, Canada  
⁴Cancer Center, Faculty of Health Sciences, University of Macau, Macau SAR, China  
⁵MoE Frontiers Science Center for Precision Oncology, University of Macau, Macau SAR, China  
*Correspondence: andre.veillette@ircm.qc.ca

This repository contains all code used for the single-cell RNA sequencing analysis in the paper.

Zenodo DOI
DOI: 10.5281/zenodo.17902239

## Data availability
The single-cell RNA-sequencing datasets analysed in this study are publicly available from the original publication:  
Chu, Y. et al. Pan-cancer T cell atlas links a cellular stress response state to immunotherapy resistance. *Nat. Med.* **29**, 1550–1562 (2023). https://doi.org/10.1038/s41591-023-02371-y  

Processed CD8 T-cell data were downloaded from the MD Anderson Single-Cell Research Portal (SCRP;https://singlecell.mdanderson.org/TCM/)

No new primary sequencing data were generated in this study.

The noise gene removal steps and batch effect correction closely follow the reference pipeline from TCM Github: https://github.com/Coolgenome/TCM  
We gratefully acknowledge their open-source contribution and refer users to their repository for detailed methodology.

## Software 
- R version 4.4.0

## Contact
- Email: Jiayu.Dou@ircm.qc.ca / Jiayu.Dou@mcgill.mail.ca
