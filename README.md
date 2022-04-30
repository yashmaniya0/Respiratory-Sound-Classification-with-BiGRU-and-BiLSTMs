# **Respiratory Sound Classification**

In this project, we construct a hybrid framework for the
classification task of respiratory sounds. The framework 
initially uses a wide range techniques to extract time-domain
and spectral features. Then it trains BiGRU and BiLSTM with 
Attention mechanism to extract more advanced features of 
respiratory sounds for XGBoost to classify.

In addition, we conduct feature selection to solve
the problem of data insufficiency and imbalance and select
effective feature combination for the models. The results show
that the model we propose has made latest developments in
four-category classification tasks of respiratory sounds.

> Access the Dataset from here : [download dataset](https://bhichallenge.med.auth.gr/sites/default/files/ICBHI_public_dataset.zip)
