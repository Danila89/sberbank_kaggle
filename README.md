# sberbank_kaggle
The 15th place solution of Sberbank Contest on Kaggle https://www.kaggle.com/c/sberbank-russian-housing-market
Kaggle Discussions thread: https://www.kaggle.com/c/sberbank-russian-housing-market/discussion/35700

Models:

1. model_1_price_per_meter.ipynb - the model fitting price_doc/full_sq
2. model_2_price.ipynb - the model fitting price_doc
3. model_3_price_kaggle.ipynb - my version of the public kernel https://www.kaggle.com/aharless/latest-iteration-in-this-silly-game/code
4. mixing_final_models.ipynb - final averaging of the models

Data:
I'm really sorry for that but I had to delete the data according to the competition rules. Here is the list of files needed for the models:

1. train_sber_corrected.csv - train data after correction from Sberbank https://www.kaggle.com/c/sberbank-russian-housing-market/discussion/34364
2. test_sber_corrected.csv - test data after correction from Sberbank https://www.kaggle.com/c/sberbank-russian-housing-market/discussion/34364
3. macro.csv - macroeconomic data from Sberbank
4. train_corr_clean.csv - train_sber_corrected.csv after cleaning with https://www.kaggle.com/keremt/very-extensive-cleaning-by-sberbank-discussions
5. test_corr_clean.csv - test_sber_corrected.csv after cleaning with https://www.kaggle.com/keremt/very-extensive-cleaning-by-sberbank-discussions

And the output of models will be:

6. model_1_output.csv - output of model_1_price_per_meter.ipynb
7. model_2_output.csv - output of model_2_price.ipynb
8. model_3_output.csv - output of model_3_price_kaggle.ipynb
9. model_entire.csv - the weighted average, output of mixing_final_models.ipynb
