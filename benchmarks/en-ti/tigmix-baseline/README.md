# English to Tigrigna

Author: Alp Öktem

## Data
	
A mix of corpora is used: 
- JW300
- OPUS/Tatoeba
- [Parallel Corpora for Ethiopian Languages](https://github.com/AAUThematic4LT/Parallel-Corpora-for-Ethiopian-Languages)

## Model
	
- Masakhane Transformer model adapted for large dataset is trained for 70 epochs.
- Best model was selected by choosing the checkpoint (286000) with highest BLEU score on validation set. 
- [Model link on drive](https://drive.google.com/file/d/12dGHeKzwhJ4t0m13paA33ujqFPHrNUqx/view?usp=sharing)

## Results
	
- BLEU dev: 21.83
- BLEU test: 14.88
