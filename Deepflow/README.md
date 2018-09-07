# Reconstructing cell cycle and disease progression using deep learning
This code contains the neural network implementation from the nature communication publication https://doi.org/10.1038/s41467-017-00623-3 .

## Access the data
You can download the data here: https://www.dropbox.com/s/tzbhp1skpjsmfsn/CellCycle.zip?dl=0

## Running the code.
Run the following commands in the terminal:python /home/dj/anaconda3/lib/python3.5/site-packages/mxnet/tools/im2rec.py ./records/test_fold_1 ./records/
（If the file is placed in different locations, the above path will change.）
Then Run the following commands in the terminal: python run.py
Then Run the following commands in the terminal: python tsne.py



