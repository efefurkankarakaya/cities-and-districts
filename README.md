# Cities and Districts (in JSON)

This data is acquired from <a href="https://uetds.uab.gov.tr/teknik-dokuman">https://uetds.uab.gov.tr/teknik-dokuman</a> page which is publicly available.

- Original data was in excel format and is converted to JSON and added geolocation data for the cities.

- Sorted according to the city code, each index actually references to the city code.

- Each city has their geolocation data with latitude and longitude.

## Data Structure

```
data: [
  {
    "cityName": string,
    "cityCode": number,
    "location": {
      "latitude": string,
      "longitude": string
    },
    districts: string[]
  }
]
```
