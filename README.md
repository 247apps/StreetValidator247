# StreetValidator247 API
StreetValidator247 is API to validate streets and zipcodes in US and Canada. 
Languages supported: 
- Java
- PHP
- NodeJS
- Python
- C#
Method supported:
- POST
- GET: /api/v1/streetvalidator/isStreetValid?street=4855%20Adelphian%20Wy.&postalcode=94502&apikey=Kh8mrYfoppzD26AFD3yid4WanQ

#### /api/v1/streetvalidator/isStreetValid

header: 
Content-Type:application/json

request:
{
    "street" : "Adelphian Wy.",
    "postalcode" : "94502",
    "apikey" : "Kh8mrYfoppzD26AFD3yid4WanQ"
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
