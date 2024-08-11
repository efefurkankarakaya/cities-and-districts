# Cities and Districts (in JSON)

The original data is obtained from the publicly available page at <a href="https://uetds.uab.gov.tr/teknik-dokuman">https://uetds.uab.gov.tr/teknik-dokuman</a>.

## What's Different?

- Original data was in excel format and is converted to JSON and added geolocation data for the cities.

- Sorted according to the city code, each index actually references to the city code.

- Each district sorted alphabetically according to the UTF-8.

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
