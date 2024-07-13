## 1. Download dataset:Download and process the data in the same format as in `data/`.

- [GENIA](http://www.geniaproject.org/genia-corpus)
- [CADEC](https://pubmed.ncbi.nlm.nih.gov/25817970/)
- [Conll 2003](https://www.clips.uantwerpen.be/conll2003/ner/)
- [Resume](https://github.com/jiesutd/LatticeLSTM)


## 2. Download the appropriate version of bert into the `bert/`.

## 3. Environments
```
- python (3.8)
- transformers (4.13.0)
- torch (1.10.0)
- numpy (1.21.4)
- scikit-learn (1.0.1)
```

## 4. Training

```bash
>> CUDA_VISIBLE_DEVICES=0  python main.py --config ./config/genia.json
```



