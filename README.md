# Diabetic Retinopathy degradation stage Keras Classification Model

<img src="https://upload.wikimedia.org/wikipedia/commons/5/55/Blausen_0312_DiabeticRetinopathy.png" width="512" height="384">


<i>This repository contains Keras classification model based on APTOS 2019 Blindness Detection dataset.</i>

<i>Dataset is available here:</i> https://www.kaggle.com/c/aptos2019-blindness-detection

<b>Diabetic retinopathy definition:</b><i> also known as diabetic eye disease, is a medical condition in which damage occurs to the retina due to diabetes mellitus. It is a leading cause of blindness.</i>

<b><i>Model description:</i></b> 

<b><i>1. Libraries import, definition of required classes and methods.</i></b>

<b><i>2. Data download process, files unziping, image classes import, dataset histogram visualisation.</i></b>

<img src="https://i.ibb.co/WPhhTvY/histogram.png" width="608" height="306">

<b><i>3. Samples import, files relocation, dataset divide into training and validating set.</i></b>

<b><i>4. Training pictures visualisation</i></b>

<img src="https://i.ibb.co/19hNP1Y/wizualizacja.png" width="859" height="836">

<b><i>5. Creating of training and validation images datagens, output definition :</i></b>

Images size were set on 224x224 with 3 channels, batch_size was equal 32, five output classes called: 'NO_DR', 'Mild', 'Moderate', 'Severe' and 'Proliferative_DR' .
Model was trained on 50 epochs.

<b><i>5. Model Summary and training process: </i></b>

<img src="https://i.ibb.co/KqRzKzW/modelsummary.png" width="346" height="506">

<b><i>6. Training results visualisation: </i></b>

<img src="https://i.ibb.co/G9crLL8/wizualizacja-treningu.png">

If there is problem to render .ipynb file please check: https://nbviewer.jupyter.org/github/JMcsLk/APTOS_Diabetic_Retinopathy/blob/master/APTOS_Keras.ipynb

References:
https://en.wikipedia.org/wiki/Diabetic_retinopathy
https://www.kaggle.com/tanlikesmath/intro-aptos-diabetic-retinopathy-eda-starter
https://www.kaggle.com/xhlulu/aptos-2019-densenet-keras-starter
