
To access the apis, need to generate the token

URL:
	https://battles-app.herokuapp.com/api/generate-token
Method: 
	POST
Body:
	uname:


Please access the below apis for testing, pass token in headers as 'x-access-token'

Api return distinct locations
	https://battles-app.herokuapp.com/api/list

Api return total battles count
	https://battles-app.herokuapp.com/api/count

Api return stats
	https://battles-app.herokuapp.com/api/stats

Api return stats as per the filter
	https://battles-app.herokuapp.com/api/search?king=Robb Stark&location=Riverrun&type=siege
	https://battles-app.herokuapp.com/api/search?king=Robb Stark&location=Riverrun
	https://battles-app.herokuapp.com/api/search?king=Robb Stark&type=siege
	https://battles-app.herokuapp.com/api/search?king=Robb Stark


