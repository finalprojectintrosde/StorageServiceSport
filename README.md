# STORAGE SERVICE SPORT (SOAP):

https://storageservicesport.herokuapp.com/ws/storageServiceSport?wsdl

*	**getSportsByWeather:** returns all the sports related to a particular condition (cloudy, sunny, rain, snow)

*	**getActivityBySport:** returns a random activity related to a sport present in the DB. Activities are the sports present in the Fitbit DB and their relative information for instance mets index. If the activity searched is still not in the local DB of the service, it will be searched through the Fitbit API and then saved in the DB.

*	**getSportsList:** returns all the sports stored in the DB
