# battle


To access the apis, need to generate the token. Api to generate-token

URL:https://battles-app.herokuapp.com/api/generate-token
Method: POST
Body:uname:


Pass the generated token in headers as 'x-access-token'

Please access the below apis for testing

https://battles-app.herokuapp.com/api/list
	This Api return distinct locations

https://battles-app.herokuapp.com/api/count
	This Api return total battles count

https://battles-app.herokuapp.com/api/stats
	This Api return stats

https://battles-app.herokuapp.com/api/search?king=Robb Stark&location=Riverrun&type=siege
https://battles-app.herokuapp.com/api/search?king=Robb Stark&location=Riverrun
https://battles-app.herokuapp.com/api/search?king=Robb Stark&type=siege
https://battles-app.herokuapp.com/api/search?king=Robb Stark
	This Api return stats as per the filter



