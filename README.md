# knutsa lab1 in course: ID2223/FID3020 HT24 Scalable Machine Learning and Deep Learning

The dashboard is available [here](https://knutsa.github.io/scalable_lab1/air-quality/).

My model predicts pm25 values at [Utö, Länsi-Turunmaa](https://aqicn.org/city/finland/lansi-turunmaa/uto/), an island in the southern part of the Finish archipelago.

In addition to the weather features 'temperature_2m_mean', 'precipitation_sum', 'wind_speed_10m_max' and 'wind_direction_10m_dominant', my model also uses the pm25 value of the previous three days. When predicting multiple days into the future, the model predicts values sequentially since the value for each day is dependant on the predictions of earlier days.
