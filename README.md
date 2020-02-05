# StreetValidator247 API
StreetValidator247 is API to validate streets and zipcodes in US and Canada. 
Languages supported: 
- Java, 
- PHP, 
- NodeJS
- Python
- C#

#### /api/v1/streetvalidator/isStreetValid

header: 
Content-Type:application/json

request:
{
    "street" : "Adelphian Wy.",
    "postalcode" : "94502",
    "apikey" : "U8mrPoppzD26AFD3yid4WanQ"
}

response:
{
	"status": true,
	"code": 200,
	"message": "",
	"data": [{
		"street": "Adelphian Way",
		"side": null,
		"zipcode": "94502"
	}]
}

#### /api/v1/streetvalidator/getStreets

#### /api/v1/streetvalidator/getStreetsByZipcode
