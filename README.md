## Baseline with Hyperparamter Tuning 

Training:

``python mainXwandb.py --mode train --lang en``

Evaluation:

``python mainXwandb.py --mode eval --lang en``


### POS Tagger with mBERT Word Embedding

Training:

``python mainXbert.py --mode train --lang en``

Evaluation:

``python mainXbert.py --mode eval --lang en``


### POS Tagger with mBERT Contextualized Embedding


Training + Evaluation:

``python main.py --lang en --batch_size 32``
