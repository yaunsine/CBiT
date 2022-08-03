# CBiT
Implementation of the paper "Contrastive Learning with Bidirectional Transformers for Sequential Recommendation".

## Run beauty
```
python main.py --template train_bert --dataset_code beauty
```

## Run toys
```
python main.py --template train_bert --dataset_code toys
```

## Run ml-1m
```
python main.py --template train_bert --dataset_code ml-1m
```

## Test a pretrained checkpoint on beauty
```
python test.py --template test_bert
```

## Acknowledgements
Training pipeline is implemented based on this repo https://github.com/jaywonchung/BERT4Rec-VAE-Pytorch . We would like to thank the contributors for their work.
