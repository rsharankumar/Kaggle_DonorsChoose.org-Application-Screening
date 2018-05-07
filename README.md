Code used for the Kaggle Competition on the Super Heros Prediction.<br /> 
A Kaggle competition to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved,<br />
using the test of the project descriptions as well as additional metadata about the project, teacher, and school.<br /> 
<br /> 
Link to the Completition. <br /> 
https://www.kaggle.com/c/donorschoose-application-screening

The folder structures are as follows,

Root Folder<br />
|<br />
|<br />
|--- Code<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- script_benchmark_lgbm.ipynb<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- script_ultimateFeatureEngineering.ipynb<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- training_log.csv<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
|--- Input<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- resources.csv<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- sample_submission.csv<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- test.csv<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- train.csv<br />
|<br />
|<br />
|--- README.md<br />


The folder Input contains all the input files and a sample submission file to explain the format of the data to be submitted <br />
and the Code folder contains the python coding used for the submission and the file training_log.csv tracks the accuracy <br />
of the model for all the epochs and the folder Submission has the data that had been submited in the competition<br />

Ranking : 79/581 (in top 15 percentile) <br />
