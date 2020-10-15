# Pytorch implementation of SiamRPN

## Description
[Code](https://github.com/HonglinChu/SiamRPN)

## File tree
```
.
├── bin
├── got10k
└── siamrpn
```

## Dataset
First get VID dataset and youtube-bb dataset. 
```
python bin/create_dataset_ytbid.py 
```
The command above will get a dataset, you can download from 

- **YTB&VID**  [BaiduYun](https://pan.baidu.com/s/1gF8PSZDzw-7EAVrdYHQwsA) password: 6vkz 

Then use the data to create lmdb.
```
python bin/create_lmdb.py
```
## Train
```bash
python bin/train_siamrpn.py 
```
## Test
```bash
python bin/test_siamrpn.py 
```

## Model

[BaiduYun](https://pan.baidu.com/s/1tENmHYBzomQE31DO5PCmcQ)  password:myw6

## Reference
```

[1] Li B, Yan J, Wu W, et al. High performance visual tracking with siamese region proposal network.Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018: 8971-8980.

[2] https://github.com/HelloRicky123/Siamese-RPN

```

