# Kaggle_Quora

kaggle project comparing the sentence
They give the data total 404290 sentence to comparing same sentence or not

## Preprocessing
- Using stop word & regular expression we did preprocessing

## Modeling
- LSTM & word2vector
- Tokenizing(split sentence to word) -> Padding(make the lengh of sentece same) -> Embedding(using GoogleNews-vectors-negative300.bin.gz)

## Limitation
- Need to use GPU(I used CPU so it takes very long time to dirve the model)
