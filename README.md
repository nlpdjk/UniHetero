## 1. Download and process the data in the same format as in `data/`.

- [GENIA](https://drive.google.com/file/d/1DkqYm3mjcL8w_2Nd3YX-tOT-r2PeOrJZ/view?usp=sharing)
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



