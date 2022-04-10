# CS5228 Final Project - Group DCS

## Folder and File

```shell
Group_DCS_Final_Report.pdf
Readme.md
Code
｜--1feat_process_eng.ipynb # Feature preprocessing and engineering implementation
｜--2norm_enc_model.ipynb # Data encoding, normalization and model instruction implementation
｜--add_aux.ipynb # Processing auxiliary data.
｜--auxiliary-data.zip # Directory contains auxiliary data.
		｜---sg-xxx.csv
｜--input_test_before_EncNorm.csv # 1feat_process_eng.ipynb output csv file(test)
｜--input_train_features_before_EncNorm.csv # 1feat_process_eng.ipynb output csv file(train) 
｜--model_input_train_prices.csv # csv file for Price 
｜--models.zip # Directory contains our trained models
			|--- xxx.model
｜--predict # Directory contains our prediction results
			|--- xxx.csv
｜--test_add_aux.csv # add_aux.ipynb output csv file(test)
｜--test.csv # Original test dataset
｜--train_add_aux.csv# add_aux.ipynb output csv file(train) 
｜--train.csv # Original train dataset
```



## Usage

First, process auxiliary data:

- add_aux.ipynb : processing auxiliary data

Second, add auxiliary data to the main dataset and do feature preprocessing and engineering:

- 1feat_process_eng.ipynb 

Next, do data encoding and normalization. Use models to fit data for prediction.

- 2norm_enc_model.ipynb

