## Baseline with Hyperparamter Tuning 

python mainXwandb.py --mode train --lang en

python mainXwandb.py --mode eval --lang en


### POS Tagger with mBERT Word Embedding

python mainXbert.py --mode train --lang en

python mainXbert.py --mode eval --lang en


### POS Tagger with mBERT Contextualized Embedding

python main.py --lang en --batch_size 32
