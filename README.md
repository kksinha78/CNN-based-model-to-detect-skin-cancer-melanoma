# CNN-based-model-to-detect-skin-cancer-melanoma
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
Tools used : pathlib,glob,prefetch(Autotune),
Modelling : CNN (Dense, Dropout, Flatten,activation='relu'
optimizer='adam'
loss=keras.losses.SparseCategoricalCrossentropy
metrics='accuracy'
epochs = 20
Data balacing : Augmentation
Finding : Here we have good training and validation accuracy post using drop outs,augumentation. Model does not seems to have overfit or underfit.however, other techniniques of regularization or more hyperparamerts need to tuned for better model performace.
