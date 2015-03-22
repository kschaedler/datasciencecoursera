Datasets Characteristics
Multivariate, Time-Series
	
based on: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
, see also
Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

Number of Instances:
180
	

Area:
Computer

Attribute Characteristics:
N/A
	
Number of Attributes:
81
	
Missing Values?
N/A

Attributes:

- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope.
- A 79-feature vector with time and frequency domain variables means and standard deviations of the above.
- Its activity label (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING or LAYING).
- An identifier (number 1..20) of the subject who carried out the experiment.


Files:

assign_data.txt : Dataset see above
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.

run_analysis.R: 
- Script converting the original dataset using following steps:

reads test / train data and combines both
produces reduced data set mergedred containing only means and stds
adds label and subject attributes to the new dataset
produces new dataset containing the average of each variable for each activity and each subject.

