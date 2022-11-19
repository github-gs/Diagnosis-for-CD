![](https://img.shields.io/badge/Python-3.8-brightgreen) ![](https://img.shields.io/badge/Version-dev-yellowgreen) ![](https://img.shields.io/badge/lisense-MIT-orange) [![](https://img.shields.io/badge/Website-CADD-blue)](https://cadd.tongji.edu.cn/)

# Diagnosis-for-CD
Microbial genes outperform species and SNVs as diagnostic markers for Crohn’s disease according to artificial intelligence analyses of multicohort fecal metagenomes

## 1.Raw_data_process  

Metagenomic sequencing data:  

	(1) Quality control  

	(2) Taxonomic annotation and abundance estimation  

	(3) Gene prediction and abundance estimation  


## 2.Differential_analysis_MMUPHin  

Identifying differential signatures from multi-cohorts by correcting batch effects.

## 3.Alpha diversity  

Calculating alpha diversity of microbiome in CD patients and controls.

## 4.Beta diversity  

Calculating beta diversity of microbiome in CD patients and controls.

## 5.SNV Calling  

MIDAS was used to perform microbial SNV annotation.  
The WMS reads were mapped to the database for SNV calling.   

## 6.Model contruction with FNN  

Feedforward neural network (FNN) was employed to construct the diagnostic model:  
	
	(1) Neuron network construction  

	(2) Ten fold cross-validation  

	(3) Model trainning   

	(4) Model testing  

## 7.Feature evaluation with SHAP  

The feature importance was evaluated with SHapley Additive exPlanations (SHAP) to explain the output of machine learning model.