#Replicating GPT2 nano model
It uses EthioNLP amharic dataset for training. This model however is build for generation purposes so it will train only on the 'instruction' lable of the dataset. Still working on it to fit the entire classification dataset. please feel free to pull and work on this repo.

###How to run

`cd [PROJECT_DIR]
pip install -r requirements.txt
python ethionlp.py
python train-gpt2.py`

If you have access to multiple GPU's be sure to change the variables 'B' and 'T' in train-gpt2.py file to 64 and 1024 respectively.  
