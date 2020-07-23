## Predicting number of people in a place at a current time
Taking a stroll in the park will never be the same as it was before COVID. Neither will be shopping or eating at your favorite restaurant. The fear of contracting the virus will always keep one on the edge, making the "new normal" not so normal.
Through Vatika, we aim to provides with the live count of people at any given place to help people make an informed decision about choosing whether to go there, look for some alternative or reschedule your visit.
Through our application, they can search for the place they want to visit or choose any listed category. 
We also use time series prediction to predict the number of people to be present at a current place on a current time slot based on previous trends. The best thing about this, is that it can be deployed with no additional cost and maintains complete user privacy.

## __To run the count model__

1. ```Clone the repository```
2.  install requirements from requirement.txt ```pip install -r requirements.txt ```
3. ```cd ML-model```
4. ```python people_counter.py``` 

> Main requirements are 
> 1. python
> 2. flask
> 3. openCV
> 4. imutils
> 5. dlib
> 6. numpy

The default UID for the test surveillance video is 1, you can change that when replicating for multiple real time camera ids

## __api.py__
It is the api file which runs on localhost server and can serve get request for the current count of people at a particular location by camera unique id (UID)
