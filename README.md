# RUN-OR-WALK-CLASSFICATION
This dataset complements https://github.com/vmalyi/run-or-walk project which aims to detect whether the person is running or walking based on deep neural network and sensor data collected from iOS device.

This dataset has been accumulated with help of "Data Collection" iOS app specially developed for this purpose: https://github.com/vmalyi/run-or-walk/tree/master/ios_app_data_collection.

Please note that this app is not available in the AppStore yet.

Content
Currently, the dataset contains a single file which represents 88588 sensor data samples collected from accelerometer and gyroscope from iPhone 5c in 10 seconds interval and ~5.4/second frequency. This data is represented by following columns (each column contains sensor data for one of the sensor's axes):

acceleration_x
acceleration_y
acceleration_z
gyro_x
gyro_y
gyro_z
There is an activity type represented by "activity" column which acts as label and reflects following activities:

"0": walking
"1": running
Apart of that, the dataset contains "wrist" column which represents the wrist where the device was placed to collect a sample on:

"0": left wrist
"1": right wrist
Additionally, the dataset contains "date", "time" and "username" columns which provide information about the exact date, time and user which collected these measurements.
