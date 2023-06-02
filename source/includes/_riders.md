# Riders

## Details

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0"
```

> The above command returns JSON structured like this:

```json
{
	"_id": "FF01100001013A65F0",
	"MMR": 1148,
	"SR": 2299,
	"name": "Pepiti",
	"contact": 341,
	"banned": false,
	"banned_by": null,
	"avatar": "https://avatars.akamai.steamstatic.com/fec0d1643347a79a72441a0ce50631550bbd2fa2_full.jpg",
	"type": "admin",
	"online": false,
	"server": null,
	"donation": 0,
	"seasons": [{
		"name": "First summer",
		"MMR": 1148,
		"position": 4308
	}],
	"races": {
		"first": 9,
		"second": 7,
		"third": 12,
		"total_races": 142,
		"fastlap": 5,
		"holeshot": 1
	},
	"bikes": {
		"2021 KTM 450 SX-F OEM": {
			"laps": 25
		},
		"2020 Honda CRF250R SM OEM": {
			"laps": 14
		},
		"2021 KTM 250 SX-F SM OEM": {
			"laps": 8
		},
		"2022 Honda CRF250R OEM": {
			"laps": 72
		},
		"2021 KTM 250 SX-F OEM": {
			"laps": 26
		},
		"2021 KTM 125 SX OEM": {
			"laps": 52
		},
		"2022 Husqvarna TC 125 OEM": {
			"laps": 13
		},
		"2022 Yamaha YZ125 OEM": {
			"laps": 33
		},
		"2021 KTM 125 SX SM OEM": {
			"laps": 11
		},
		"2021 KTM 250 SX OEM": {
			"laps": 18
		},
		"2021 KTM Black Knight": {
			"laps": 6
		},
		"2022 Beta 300 RX OEM": {
			"laps": 1
		},
		"2022 Kawasaki KX250F OEM": {
			"laps": 45
		},
		"2022 Honda CRF450R OEM": {
			"laps": 4
		},
		"Kawasaki KX250 2023": {
			"laps": 34
		},
		"KTM 450 SX-F 2023": {
			"laps": 21
		},
		"Honda CRF250R 2023": {
			"laps": 43
		},
		"Kawasaki KX450 2023": {
			"laps": 4
		},
		"KTM 250 SX-F 2023": {
			"laps": 349
		},
		"Yamaha YZ450F 2023": {
			"laps": 24
		},
		"GASGAS MC 250F 2023": {
			"laps": 4
		},
		"Yamaha YZ250F 2023": {
			"laps": 119
		},
		"Suzuki RM-Z250 2023": {
			"laps": 3
		},
		"Fantic XXF 250 2023": {
			"laps": 32
		},
		"KTM 350 SX-F 2023": {
			"laps": 34
		},
		"GASGAS MC 350F 2023": {
			"laps": 5
		},
		"GASGAS MC 450F 2023": {
			"laps": 7
		},
		"TM MX300Fi 2023": {
			"laps": 5
		},
		"Fantic XXF 450 2023": {
			"laps": 4
		},
		"Husqvarna FC 250 2023": {
			"laps": 6
		}
	},
	"world_records": {
		"MX1 OEM": 0,
		"MX1-2T OEM": 0,
		"MX2 OEM": 0,
		"MX2-2T OEM": 0,
		"total": 0
	},
	"total_laps": 1022,
	"personal_records": 0,
	"average_speed": 14.078571428571427,
	"favorite_bike": {
		"name": "KTM 250 SX-F 2023",
		"laps": 349
	}
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0`


## MMR History

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/mmr_history').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/mmr_history"
```

> The above command returns JSON structured like this:

```json
{
	"_id": "FF01100001013A65F0",
	"MMR_updates": [{
		"timestamp": 1671805750,
		"mmr": 1000,
		"type": "initial"
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/mmr_history`

## Races

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/races').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/races"
```

> The above command returns JSON structured like this:

```json
{
	"races": [{
		"track": "Forest Raceway",
		"_id": "63d3cdc706bc08738be863e9",
		"wheater": {
			"air_temp": 20,
			"conditions": "Clear"
		},
		"FastestLap": 70023,
		"Classification": {
			"RaceNum": "33",
			"RaceTime": 301262,
			"Gap": 13103,
			"Penalty": 0,
			"Laps": 4,
			"Status": "-",
			"Pos": 3
		},
		"MMR": {
			"BPP": 24.502399999999998,
			"old_MMR": 1095,
			"PRB": 30,
			"NRB": -1.8,
			"FL": 0,
			"HS": 0,
			"total": 53
		}
	}],
	"total_races": 194
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/races`


## Personal records

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/records').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/records"
```

> The above command returns JSON structured like this:

```json
{
	"records": [{
		"_id": "6472af3dcc44366caf609fa2",
		"category": "MX2 OEM",
		"rider_guid": "FF01100001013A65F0",
		"track": "MXB Club",
		"air_temp": 20,
		"average_speed": 17.9,
		"bike": "Husqvarna FC 250 2023",
		"conditions": "Clear",
		"lap_time": 60440,
		"race_id": "6474e6458a75e65cac273442",
		"race_number": 31,
		"rider_name": "Pepiti",
		"session": "WARMUP",
		"split_1": 22832,
		"split_2": 42281,
		"timestamp": 1685382967.009213
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/records`

## Total laps

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/total_laps').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/total_laps"
```

> The above command returns JSON structured like this:

```json
{
    "total_laps": 1022
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/total_laps`

## Laps

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/laps').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/laps"
```

> The above command returns JSON structured like this:

```json
{
	"laps": [{
		"_id": "63d3d0d51d04747c97f14061",
		"race_number": 33,
		"rider_guid": "FF01100001013A65F0",
		"rider_name": "Pepiti",
		"bike": "Yamaha YZ250F 2023",
		"category": "MX2 OEM",
		"track": "Forest Raceway",
		"lap_time": 70023,
		"split_1": 23164,
		"split_2": 48592,
		"average_speed": 17.9,
		"conditions": "Clear",
		"air_temp": 20,
		"race_id": "63d3cdc706bc08738be863e9",
		"session": "RACE2",
		"timestamp": 1674825941.7969084
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/laps`

This endpoint returns only 10 results at the moment


## Laps per track

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/track/Forest%20Raceway').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/track/Forest%20Raceway"
```

> The above command returns JSON structured like this:

```json
{
	"laps": [{
		"_id": "63d3d0d51d04747c97f14061",
		"race_number": 33,
		"rider_guid": "FF01100001013A65F0",
		"rider_name": "Pepiti",
		"bike": "Yamaha YZ250F 2023",
		"category": "MX2 OEM",
		"track": "Forest Raceway",
		"lap_time": 70023,
		"split_1": 23164,
		"split_2": 48592,
		"average_speed": 17.9,
		"conditions": "Clear",
		"air_temp": 20,
		"race_id": "63d3cdc706bc08738be863e9",
		"session": "RACE2",
		"timestamp": 1674825941.7969084
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/track/Forest%20Raceway`

This endpoint returns ALL results


## search

```python
import requests
requests.get('https://pepiti.com/stats/api/v1/rider/search/Pepiti').json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/search/Pepiti"
```

> The above command returns JSON structured like this:

```json
{
	"results": [{
		"_id": "FF01100001013A65F0",
		"MMR": 1148,
		"SR": 2299,
		"name": "Pepiti",
		"contact": 341,
		"banned": false,
		"banned_by": null,
		"avatar": "https://avatars.akamai.steamstatic.com/fec0d1643347a79a72441a0ce50631550bbd2fa2_full.jpg",
		"type": "admin",
		"online": false,
		"server": null,
		"donation": 0,
		"seasons": [{
			"name": "First summer",
			"MMR": 1148,
			"position": 4308
		}],
		"races": {
			"first": 9,
			"second": 7,
			"third": 12,
			"total_races": 142,
			"fastlap": 5,
			"holeshot": 1
		},
		"bikes": {
			"2021 KTM 450 SX-F OEM": {
				"laps": 25
			},
			"2020 Honda CRF250R SM OEM": {
				"laps": 14
			},
			"2021 KTM 250 SX-F SM OEM": {
				"laps": 8
			},
			"2022 Honda CRF250R OEM": {
				"laps": 72
			},
			"2021 KTM 250 SX-F OEM": {
				"laps": 26
			},
			"2021 KTM 125 SX OEM": {
				"laps": 52
			},
			"2022 Husqvarna TC 125 OEM": {
				"laps": 13
			},
			"2022 Yamaha YZ125 OEM": {
				"laps": 33
			},
			"2021 KTM 125 SX SM OEM": {
				"laps": 11
			},
			"2021 KTM 250 SX OEM": {
				"laps": 18
			},
			"2021 KTM Black Knight": {
				"laps": 6
			},
			"2022 Beta 300 RX OEM": {
				"laps": 1
			},
			"2022 Kawasaki KX250F OEM": {
				"laps": 45
			},
			"2022 Honda CRF450R OEM": {
				"laps": 4
			},
			"Kawasaki KX250 2023": {
				"laps": 34
			},
			"KTM 450 SX-F 2023": {
				"laps": 21
			},
			"Honda CRF250R 2023": {
				"laps": 43
			},
			"Kawasaki KX450 2023": {
				"laps": 4
			},
			"KTM 250 SX-F 2023": {
				"laps": 349
			},
			"Yamaha YZ450F 2023": {
				"laps": 24
			},
			"GASGAS MC 250F 2023": {
				"laps": 4
			},
			"Yamaha YZ250F 2023": {
				"laps": 119
			},
			"Suzuki RM-Z250 2023": {
				"laps": 3
			},
			"Fantic XXF 250 2023": {
				"laps": 32
			},
			"KTM 350 SX-F 2023": {
				"laps": 34
			},
			"GASGAS MC 350F 2023": {
				"laps": 5
			},
			"GASGAS MC 450F 2023": {
				"laps": 7
			},
			"TM MX300Fi 2023": {
				"laps": 5
			},
			"Fantic XXF 450 2023": {
				"laps": 4
			},
			"Husqvarna FC 250 2023": {
				"laps": 6
			}
		}
	}]
}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/search/Pepiti`


## ban (admin)

```python
import requests
headers = {'Authorization': 'Bearer token'}
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/ban/<reason>', headers=headers).json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/ban/<reason>" -H "Authorization: Bearer {token}"
```

> The above command returns JSON structured like this:

```json
{"success": true}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/ban/<reason>`


## unban (admin)

```python
import requests
headers = {'Authorization': 'Bearer token'}
requests.get('https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/unban', headers=headers).json()
```

```shell
curl "https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/unban" -H "Authorization: Bearer {token}"
```

> The above command returns JSON structured like this:

```json
{"success": true}
```

### HTTP Request

`GET https://pepiti.com/stats/api/v1/rider/FF01100001013A65F0/unban`
