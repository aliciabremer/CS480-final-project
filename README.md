# CS 480 Final Project

* Models are trained with training_code.py.
* The two models I use for the final ensemble can be trained with script.sh
* The data/ folder is assumed to exist (from unzipping the kaggle dataset .zip file)
* The file averaging.ipynb loads the best models from training (lowest validation score during training) and generates the .csv file from averaging the models
* The file testing_r2_score_avg.ipynb loads the best models from training (lowest validation score during training) and calculates the R2 score for each individual trait, as well as the R2 for each individual trait from averaging the outputs of the two trained models
* The best model from training (lowest validation score during training) is obtained by loading the csv/model file corresponding to the outputted best epoch (which is printed at the end of training)
* The saved output files are logs_vit_dino.txt and logs_swin_batchnorm.txt
