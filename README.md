# BERT-fine-tuning-sentence-classification-CoLA-dataset

BERT (Bidirectional Encoder Representations from Transformers) is a method of pretraining language representations that was used to create models that NLP practicioners can use. You can either use these models to extract high quality language features from your text data, or you can fine-tune these models on a specific task (classification, entity recognition, question answering, etc.) with your own data to produce state of the art predictions.
#
Usage of transfer learning has transformed learning and caused a huge shift in NLP. Rather than training a new network from scratch each time, the lower layers of a trained network could be copied and transfered for use in another network for a different task. This is vastly preferable to the expensive process of training a network from scratch.
Here, I’ll use BERT with the huggingface PyTorch library to quickly and efficiently fine-tune a model to get near state of the art performance in sentence classification creating  a high performance model with minimal effort.
