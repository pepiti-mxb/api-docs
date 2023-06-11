# Subscriptions

## Types

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/subscription/types').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/subscription/types"
```

> The above command returns JSON structured like this:

```json
{
	"free": {
		"name": "free",
		"visible": true,
		"max_leagues": 1,
		"max_races": 1,
		"max_create_leagues": 0,
		"logo": "free.png",
		"price_month": 0,
		"price_year": 0
	},
	"regular": {
		"name": "regular",
		"visible": true,
		"max_leagues": 10,
		"max_races": 10,
		"max_create_leagues": 1,
		"logo": "regular.png",
		"price_month": 1,
		"price_year": 10
	},
	"premium": {
		"name": "premium",
		"visible": true,
		"max_leagues": 1000,
		"max_races": 1000,
		"max_create_leagues": 10,
		"logo": "premium.png",
		"price_month": 5,
		"price_year": 50
	},
	"admin": {
		"name": "admin",
		"visible": false,
		"max_leagues": -1,
		"max_races": -1,
		"max_create_leagues": -1,
		"logo": "admin.png",
		"price_month": 0,
		"price_year": 0
	}
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/subscription/types`

