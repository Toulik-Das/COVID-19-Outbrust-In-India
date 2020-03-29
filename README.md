# COVID-19-Outbrust-In-India
Predict remaining days before reaching peak COVID-19 effected in India
I used SIR model to predict the remaining days needed before reaching the peak of infections in a given country.
This value can be used as a feature to train your ML model.

![alt text](https://www.kaggleusercontent.com/kf/31068179/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..UK1_gWawxdSksfzZkXqA_A.dw1dkeQrPvvrYw-gWGhSg5FcqTUvJGkAJ2QCWu0tPC-i0sAPOXP8FHR7O1R0vSfxWSXcjrq2jNkI1D5VMhSxvcUZI5oLbd4Vczsoh2-6LHPC6-PPJK5_PLfmRLP5Sq2lY7Xj7OTkAM5ab18uQHDyYBhaRwSc7JvGRtJ50X67R4htCjiDoPBqsO8B2mFBsHn2w58P8JtsFWXtps1KIwFKOV73skDIfGbsKFs1dhRo69i7u-y-QSGPBHOe9XnGkfTeSSX9V0eVwXiAb2FDgMbUQhaROjkuJe3sPn3e95QAH5a4J9fhtiUZJ0O6X-gE_dhEw6K7jZD6TVkjQNpRdkDEORwTMv_Qm2CGZwhUaN0f9Xb6pXT-p1qR2s3EYOUPhkKQavmPUx77hLl8z8XobXoEIlguXmJaUqi_dGBG-Xq7huieY97iV1duM4nNpPKLc3ANZRim3iVXQKc523_MS3EqRZ4YAB-VJlWJSedGZgnHV5jBiHMYIUDuo1PfUZoJlaKQpw1EO6P0T4VaJKcVboRd9HMrxYQosNqhpireb4wHSMMM5i0heyrdTJEAt5zTzFmi78SonAIEl3qAC3fAs8bdrN5fntk8YDp2uAN52I-5U8FyCur2IJg7rGmZxefH7GGQRdLhI9nmp0TLZD8gyuGZ6i2OtjfVDwhTVqZjSwTF4lMM866C8UPFRrBZQHk2bfAq.vGM253LGyBjN6C-Niw2HHw/__results___files/__results___5_2.png "Description goes here")

Here, we can see that -sometimes- we get negative duration values for some simulations. This is due to a bad fit between real data and SIR model. We can remove the negative values from that list and calculate the mean of the list to get an idea about the remaining days before the peak.
On average, the peak of infected cases in  India  is coming in :  38.0 days
