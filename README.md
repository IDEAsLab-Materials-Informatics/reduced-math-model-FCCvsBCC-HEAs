# reduced-math-model-FCCvsBCC-HEAs
A reduced mathematical (RM) model for prediction of probability of occurence of FCC and BCC phases in high-entropy alloys (HEAs). Publication details are as below:

#### Title : [FCC vs. BCC phase selection in high-entropy alloys via simplified and interpretable reduction of machine learning models](https://www.sciencedirect.com/science/article/pii/S2589152922003131)
- **Authors** : Dishant Beniwal[^1], Pratik K. Ray[^1]
- **Journal** : Materialia

[^1]: Department of Metallurgical and Materials Engineering, Indian Institute of Technology Ropar, Rupnagar 140001, Punjab, India

#### Files and database'
'**_database**' : directory with database files that contain feature values and probability of occurence of FCC and BCC phases as predicted by the neural network (NN) model. It contains following database files:
- '**df-hea-fit.xlsx**' : dataset used for fitting the RM Model; alloys with 5, 6, and 7 elements; absolute features values
- '**df-hea-fit-normFeats.xlsx**' : dataset used for fitting the RM Model; alloys with 5, 6, and 7 elements; normalized features values
- '**df-hea-val.xlsx**' : dataset used for validating the RM Model; alloys with 8 and 9 elements; absolute features values
- '**df-hea-val-normFeats.xlsx**' : dataset used for validating the RM Model; alloys with 8 and 9 elements; normalized features values

'**rm-mod-fcc.ipynb**' : jupyter notebook containing development of RM model for FCC phase

'**rm-mod-bcc.ipynb**' : jupyter notebook containing development of RM model for BCC phase
