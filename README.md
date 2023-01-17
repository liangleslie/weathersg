# weathersg
Simple python module to simulate json response from data.gov.sg weather APIs using SG weather data from `www.nea.gov.sg` and `www.weather.gov.sg`

# Usage
`Weather().api.json` --> simulated json output in the same format as data.gov.sg. Dict keys map to endpoint pathinfo, i.e. simulated json output of `https://api.data.gov.sg/v1/environment/24-hour-weather-forecast` can be returned with weather.api.json['24-hour-weather-forecast']

Example
```
from weathersg import Weather

weather = Weather()
simulated_resp = weather.api.json['24-hour-weather-forecast']
```
