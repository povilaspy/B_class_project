# B_class_project
## Questions 2019-12-21

### Train - Test features match

* train set has more features than test set

**train_labels df**

<img src='https://i.postimg.cc/6p4qBggn/train-labels-features.png'>

**test df**

<img src='https://i.postimg.cc/m2t2SKbJ/test-initial-features.png'>

**sample of prepared df**

<img src='https://i.postimg.cc/cHsyDknV/train-labels-features2.png'>


### CPU usage

* how to efficiently use 16 GB RAM in order not to crash the Kernel with 120 features (agg(sum) usually)

<img src = 'https://i.postimg.cc/ry4ftw4P/kaggle-cpu-usage.png'>
<img src = 'https://i.postimg.cc/8CjzZ3Bj/notebook-exceeded-allowed-compute.png'>

* if breaking down code into separate cells reduces the CPU load
* is there a way to process code slower, but use max 95% of CPU
* training locally, loading model to Kernel and making preds there (?)
* loading and processing parts of train df separately and then merging (?)

### Index

* Index installation_id or whatever index numbers are sufficient
<img src='https://i.postimg.cc/3Ndq6sJb/index.png'>
