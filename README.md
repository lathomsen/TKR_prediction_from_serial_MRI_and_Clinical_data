# Medical_outcome_3D_serial_data
Code for project on predicting total knee replacement based on clinical data and MR-images.
Note that it needs to be adjusted fore each specific case. 

The files contain: 

LR_Clinical.ipynb
- Baseline models, correlation and t-statistics of clinical feature

LR_imagedata.ipynb
- Baseline models, correlation and t-statistics of MRI feature

Improved_LSTM_Img.ipynb
- LSTM, Shallow LSTM and modelling code for MRI features

Improved_LSTM_Clinical.ipynb
- LSTM, Shallow LSTM for clinical features

Combined_LSTM.ipynb
- Code for combining the two data sets and training combined models

Ensamble.ipynb
- Loading data, models from other notebooks and then combine to an ensamble method

Dialation_and_Erotion.ipynb:
- Perform dialation and erotion, then save the difference

Extract features.ipynb
- Extract featrues from MRI: Total amount of each kind of cartilage, Split Tibial and Femural compartments, Approx JSW, Miniscus, Intensities and Entropi, Opening and closing, 

Thicknesses.ipynb
- Extract thickness of compartments in two manners.

makedataset.ipynb
- Construct the data set, select which samples to use

Clinical information.ipynb
- Ro furter construct the clinical features as wanted. 

Statistics.ipynb
- make paired T-test and Delong test 
