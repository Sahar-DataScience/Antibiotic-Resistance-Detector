# Antibiotic-Resistance-Detector
The challenge is to build a classifier that can detect ARGs. Using genetic sequences as input, the classifier should be able to identify if a gene is antibiotic resistant or not.

1. EDA & preprocessing : tokenization, removing rare amino acids 
2. encoding gene sequences and preparing dataloaders
3. feature embeddings extratcion using pretrained prot bert
4. reducing embeddings vectors dimensions using pca tsne and other Manifold Learning methods from scikit learn 
5. visualize feature distribution
6. training on prot_fat_bert
