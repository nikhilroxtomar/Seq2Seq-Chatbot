# Seq2Seq-Chatbot
Using seq2seq model to train a simple greeting chatbot.

### Training

```
python train.py --batch-size 128 --num-epochs 30 -lr 0.001
```

### Inference

```
python test.py
```

### Inference (Web)

```
cd mysite/
python manage.py runserver *.*.*.*:*
```

*192.168.\*.\*:\** is your IP address and port which can be queried with instruction 'ifconfig'.



## Corpus

* Cornell Movie Dataset
* Twitter Dialog Dataset
* Mixed Dataset (including cornell, twitter, greeting) maybe will be updated in the future.



