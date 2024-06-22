# Masked Language Modeling with Mosaic BERT model on Sagemaker Pipeline 
This project combines the BERT training process (including pre-training and fine-tuning) with 
SageMaker's Pipeline framework. 

## Features
- MLM pre-training on the C4 dataset
- Fine-tuning on GLUE benchmark tasks
- Dynamic creation of SageMaker Pipeline DAGs based on configuration files
- Support for both single-model and multi-model training scenarios
- Flexible step sequencing and dependencies
