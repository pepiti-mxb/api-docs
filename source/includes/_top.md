# Top

## mmr

```python
import requests

requests.get('https://pepiti.com/stats/api/v1/top/mmr').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/top/mmr"
```

> The above command returns JSON structured like this:

```json
{
	"riders": [{
		"_id": "FF0110000115D369F5",
		"MMR": 19290,
		"SR": 5909,
		"name": "Sauce Gardner",
		"contact": 2074,
		"banned": false,
		"banned_by": null,
		"avatar": "https://avatars.akamai.steamstatic.com/d5ff90ae073ba5e89555debf1f6db98c589e0371_full.jpg",
		"type": "user",
		"donation": 15,
		"online": false,
		"server": null,
		"seasons": [{
			"name": "First summer",
			"MMR": 19290,
			"position": 1
		}],
		"races": {
			"first": 510,
			"second": 143,
			"third": 50,
			"total_races": 792,
			"fastlap": 531,
			"holeshot": 24
		},
		"bikes": {
			"2022 Honda CRF250R OEM": {
				"laps": 22
			},
			"2022 Yamaha YZ450F OEM": {
				"laps": 4
			},
			"Husqvarna FC 250 2023": {
				"laps": 47
			},
			"KTM 250 SX-F 2023": {
				"laps": 962
			},
			"Yamaha YZ250F 2023": {
				"laps": 1752
			},
			"Yamaha YZ450F 2023": {
				"laps": 378
			},
			"Honda CRF250R 2023": {
				"laps": 887
			},
			"KTM 350 SX-F 2023": {
				"laps": 427
			},
			"Husqvarna FC 350 2023": {
				"laps": 285
			},
			"TM MX450Fi 2023": {
				"laps": 12
			},
			"Husqvarna TC 125 2023": {
				"laps": 91
			},
			"Husqvarna TC 250 2023": {
				"laps": 28
			},
			"Suzuki RM-Z250 2023": {
				"laps": 39
			},
			"Service Honda CR500AF": {
				"laps": 5
			},
			"Kawasaki KX250 2023": {
				"laps": 13
			},
			"TM MX 530 Fi 2023": {
				"laps": 5
			},
			"KTM Black Knight 2021": {
				"laps": 5
			},
			"KTM 125 SX 2023": {
				"laps": 19
			}
		}
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/top/mmr`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
limit | 10 | return more values


## sr

```python
import requests

requests.get('https://pepiti.com/stats/api/v1/top/sr').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/top/sr"
```

> The above command returns JSON structured like this:

```json
{
	"riders": [{
		"_id": "FF0110000115D369F5",
		"MMR": 19290,
		"SR": 5909,
		"name": "Sauce Gardner",
		"contact": 2074,
		"banned": false,
		"banned_by": null,
		"avatar": "https://avatars.akamai.steamstatic.com/d5ff90ae073ba5e89555debf1f6db98c589e0371_full.jpg",
		"type": "user",
		"donation": 15,
		"online": false,
		"server": null,
		"seasons": [{
			"name": "First summer",
			"MMR": 19290,
			"position": 1
		}],
		"races": {
			"first": 510,
			"second": 143,
			"third": 50,
			"total_races": 792,
			"fastlap": 531,
			"holeshot": 24
		},
		"bikes": {
			"2022 Honda CRF250R OEM": {
				"laps": 22
			},
			"2022 Yamaha YZ450F OEM": {
				"laps": 4
			},
			"Husqvarna FC 250 2023": {
				"laps": 47
			},
			"KTM 250 SX-F 2023": {
				"laps": 962
			},
			"Yamaha YZ250F 2023": {
				"laps": 1752
			},
			"Yamaha YZ450F 2023": {
				"laps": 378
			},
			"Honda CRF250R 2023": {
				"laps": 887
			},
			"KTM 350 SX-F 2023": {
				"laps": 427
			},
			"Husqvarna FC 350 2023": {
				"laps": 285
			},
			"TM MX450Fi 2023": {
				"laps": 12
			},
			"Husqvarna TC 125 2023": {
				"laps": 91
			},
			"Husqvarna TC 250 2023": {
				"laps": 28
			},
			"Suzuki RM-Z250 2023": {
				"laps": 39
			},
			"Service Honda CR500AF": {
				"laps": 5
			},
			"Kawasaki KX250 2023": {
				"laps": 13
			},
			"TM MX 530 Fi 2023": {
				"laps": 5
			},
			"KTM Black Knight 2021": {
				"laps": 5
			},
			"KTM 125 SX 2023": {
				"laps": 19
			}
		}
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/top/sr`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
limit | 10 | return more values

## contacts

```python
import requests

requests.get('https://pepiti.com/stats/api/v1/top/contacts').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/top/contacts"
```

> The above command returns JSON structured like this:

```json
{
	"riders": [{
		"_id": "FF0110000115D369F5",
		"MMR": 19290,
		"SR": 5909,
		"name": "Sauce Gardner",
		"contact": 2074,
		"banned": false,
		"banned_by": null,
		"avatar": "https://avatars.akamai.steamstatic.com/d5ff90ae073ba5e89555debf1f6db98c589e0371_full.jpg",
		"type": "user",
		"donation": 15,
		"online": false,
		"server": null,
		"seasons": [{
			"name": "First summer",
			"MMR": 19290,
			"position": 1
		}],
		"races": {
			"first": 510,
			"second": 143,
			"third": 50,
			"total_races": 792,
			"fastlap": 531,
			"holeshot": 24
		},
		"bikes": {
			"2022 Honda CRF250R OEM": {
				"laps": 22
			},
			"2022 Yamaha YZ450F OEM": {
				"laps": 4
			},
			"Husqvarna FC 250 2023": {
				"laps": 47
			},
			"KTM 250 SX-F 2023": {
				"laps": 962
			},
			"Yamaha YZ250F 2023": {
				"laps": 1752
			},
			"Yamaha YZ450F 2023": {
				"laps": 378
			},
			"Honda CRF250R 2023": {
				"laps": 887
			},
			"KTM 350 SX-F 2023": {
				"laps": 427
			},
			"Husqvarna FC 350 2023": {
				"laps": 285
			},
			"TM MX450Fi 2023": {
				"laps": 12
			},
			"Husqvarna TC 125 2023": {
				"laps": 91
			},
			"Husqvarna TC 250 2023": {
				"laps": 28
			},
			"Suzuki RM-Z250 2023": {
				"laps": 39
			},
			"Service Honda CR500AF": {
				"laps": 5
			},
			"Kawasaki KX250 2023": {
				"laps": 13
			},
			"TM MX 530 Fi 2023": {
				"laps": 5
			},
			"KTM Black Knight 2021": {
				"laps": 5
			},
			"KTM 125 SX 2023": {
				"laps": 19
			}
		}
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/top/contacts`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
limit | 10 | return more values

## donators

```python
import requests

requests.get('https://pepiti.com/stats/api/v1/top/donators').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/top/donators"
```

> The above command returns JSON structured like this:

```json
{
	"riders": [{
		"_id": "FF0110000115D369F5",
		"MMR": 19290,
		"SR": 5909,
		"name": "Sauce Gardner",
		"contact": 2074,
		"banned": false,
		"banned_by": null,
		"avatar": "https://avatars.akamai.steamstatic.com/d5ff90ae073ba5e89555debf1f6db98c589e0371_full.jpg",
		"type": "user",
		"donation": 15,
		"online": false,
		"server": null,
		"seasons": [{
			"name": "First summer",
			"MMR": 19290,
			"position": 1
		}],
		"races": {
			"first": 510,
			"second": 143,
			"third": 50,
			"total_races": 792,
			"fastlap": 531,
			"holeshot": 24
		},
		"bikes": {
			"2022 Honda CRF250R OEM": {
				"laps": 22
			},
			"2022 Yamaha YZ450F OEM": {
				"laps": 4
			},
			"Husqvarna FC 250 2023": {
				"laps": 47
			},
			"KTM 250 SX-F 2023": {
				"laps": 962
			},
			"Yamaha YZ250F 2023": {
				"laps": 1752
			},
			"Yamaha YZ450F 2023": {
				"laps": 378
			},
			"Honda CRF250R 2023": {
				"laps": 887
			},
			"KTM 350 SX-F 2023": {
				"laps": 427
			},
			"Husqvarna FC 350 2023": {
				"laps": 285
			},
			"TM MX450Fi 2023": {
				"laps": 12
			},
			"Husqvarna TC 125 2023": {
				"laps": 91
			},
			"Husqvarna TC 250 2023": {
				"laps": 28
			},
			"Suzuki RM-Z250 2023": {
				"laps": 39
			},
			"Service Honda CR500AF": {
				"laps": 5
			},
			"Kawasaki KX250 2023": {
				"laps": 13
			},
			"TM MX 530 Fi 2023": {
				"laps": 5
			},
			"KTM Black Knight 2021": {
				"laps": 5
			},
			"KTM 125 SX 2023": {
				"laps": 19
			}
		}
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/top/donators`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
limit | 10 | return more values


## Bikes

```python
import requests

requests.get('https://pepiti.com/stats/api/v1/top/bikes').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/top/bikes"
```

> The above command returns JSON structured like this:

```json
{
	"bikes": [{
		"name": "Honda CRF250R 2023",
		"laps": 751670
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/top/bikes`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
limit | 10 | return more values


## Riders

```python
import requests

requests.get('https://pepiti.com/stats/api/v1/top/riders').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/top/riders"
```

> The above command returns JSON structured like this:

```json
{
	"riders": {
		"FF011000013ED1C557": {
			"_id": "FF011000013ED1C557",
			"MMR": 7091,
			"SR": 1757,
			"contact": 1976,
			"name": "Moose | Oblivion",
			"banned": false,
			"banned_by": null,
			"avatar": "https://avatars.akamai.steamstatic.com/14d3b56a1b856730d1f2ec0e306c7ef1dd47b851_full.jpg",
			"type": "user",
			"donation": 0,
			"online": false,
			"server": null,
			"seasons": [{
				"name": "First summer",
				"MMR": 5273,
				"position": 24
			}],
			"races": {
				"first": 182,
				"second": 85,
				"third": 81,
				"total_races": 579,
				"fastlap": 215,
				"holeshot": 19
			},
			"bikes": {
				"2021 KTM Black Knight": {
					"laps": 7
				},
				"2022 Honda CRF450R OEM": {
					"laps": 3
				},
				"2021 KTM 450 SX-F OEM": {
					"laps": 1
				},
				"Kawasaki KX450 2023": {
					"laps": 11
				},
				"Honda CRF450R 2023": {
					"laps": 9
				},
				"Kawasaki KX250 2023": {
					"laps": 10
				},
				"KTM 450 SX-F 2023": {
					"laps": 3
				},
				"Honda CRF250R 2023": {
					"laps": 2677
				},
				"KTM 250 SX-F 2023": {
					"laps": 25
				},
				"Suzuki RM-Z250 2023": {
					"laps": 49
				},
				"Yamaha YZ250F 2023": {
					"laps": 58
				},
				"TM MX 144 2023": {
					"laps": 6
				},
				"Suzuki RM-Z450 2023": {
					"laps": 18
				},
				"Yamaha YZ250 2023": {
					"laps": 8
				},
				"Husqvarna TC 250 2023": {
					"laps": 5
				},
				"KTM 250 SX 2023": {
					"laps": 2
				},
				"Yamaha YZ450F 2023": {
					"laps": 13
				},
				"Husqvarna FC 250 2023": {
					"laps": 1
				}
			},
			"MX1 OEM": 0,
			"MX1-2T OEM": 0,
			"MX2 OEM": 9,
			"MX2-2T OEM": 0,
			"total": 9
		}
	}
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/top/riders`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
limit | 10 | return more values
