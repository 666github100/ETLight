## ETLight Code Implementation
The code for project 'ETLight: An Evolution Transformer for Efficient Traffic Signal Control'.

## Introduction

- We adopt the idea of sequence modeling to solve the problem of traffic signal control. 
- Since residual connections simply add the input directly to the transformed output, their processing of information is relatively single and rough, lacking the ability to adaptively filter and control different information. Therefore, we design a feature evolution module (FEM) in place of residual connect.
- Extensive experiments are conducted on real-world datasets in Jinan, Hangzhou, and New York city, including average queue length, stability, convergence, robustness, etc.

## Install Dependencies
pip install -r requirements.txt

## Main Environment
cityflow0.1, numpy, pandas, torch1.8.0, transformers=4.11.0, etc.

## Experiments
- run_etlight.py: Run the script of the ETLight model under different traffic environments, 
pay attention to different parameter settings.
- summary.py: 
Analyze and summarize the results of model operation to generate corresponding evaluation reports. 
