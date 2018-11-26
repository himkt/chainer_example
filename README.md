# PyNER: Named Entity Recognizer

## Reference
- [Neural Architectures for Named Entity Recognition]
  - NAACL2016
  - Lample et al.

### QuickStart

- build container

```
make build
make build SUDO=  # if you are not administrator
```

- launch container

```
make start
make start SUDO=  # if you are not administrator
```

In Docker container

- run experiments

```
make install  # you have to run this command on docker container
python3 pyner/named_entity/train.py config/001.config --gpu 0
```

[Neural Architectures for Named Entity Recognition]: https://arxiv.org/abs/1603.01360