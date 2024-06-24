# Masked Language Modeling with MosaicML BERT model on Sagemaker Pipeline 
This project illustrates BERT pre-training and fine-tuning through 
SageMaker's Pipeline framework. Training is handled through MosaicML's composer framework. 

## Features
- MLM pre-training on the C4 dataset
- Fine-tuning on GLUE benchmark tasks
- Dynamic creation of SageMaker Pipeline DAGs based on configuration files
- Support for both single-model and multi-model training scenarios
- Flexible step sequencing and dependencies

## Resources 
- [Bert Training Code](https://github.com/mosaicml/examples/tree/main/examples/benchmarks/bert)
- [Sagemaker Pipeline Framework](https://github.com/aws-samples/dynamic-sagemaker-pipelines-framework)
