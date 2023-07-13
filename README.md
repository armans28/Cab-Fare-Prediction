# Cab-Fare-Prediction

To view the user's portfolio blog on the Cab Fare Prediction, please visit [My Blog](https://danielrs.systeme.io/cab-price-prediction) to see the explanation of the notebook.

Due to the use of `plotly.express` and `plotly.graph_objects`, the visualizations in this code cannot be displayed on GitHub. To view the visualizations, please download the code and run it on your local machine.

## Data Description
This beginner-friendly dataset, spanning from November 26, 2018, to December 19, 2018, in Boston, MA, offers a great opportunity for hands-on data analysis. Despite containing numerous NA values, it provides valuable insights into the relationship between predictors like hour and price using Linear Regression Models. An exciting aspect is the inclusion of corresponding weather data, including factors such as temperature, wind, and sunset, along with brief weather summaries. With over 693,071 unique values, this dataset allows for robust exploration of cab pricing patterns and serves as a valuable resource for learning data cleaning, regression analysis, and incorporating external factors in predictive modeling. There are 57 columns in this dataset but mainly it contains with :

| Feature Name | Description |
| --- | --- |
| `hour` | The hour of the day when the ride was requested. |
| `day` | The day of the month when the ride was requested. |
| `month` | The month of the year when the ride was requested. |
| `source` | The starting point of the ride. |
| `destination` | The destination of the ride. |
| `cab_type` | The type of cab requested (e.g. Uber, Lyft). |
| `latitude` | The latitude of the ride's starting point. |
| `longitude` | The longitude of the ride's starting point. |
| `short_summary` | A short summary of the weather conditions at the time of the ride request. |
| `long_summary` | A longer summary of the weather conditions at the time of the ride request. |
| `icon` | An icon representing the weather conditions at the time of the ride request. |
| `name` | The name of the weather service used to obtain the weather data. |
| `price` | The price of the ride. |
| `distance` | The distance of the ride. |
| `surge_multiplier` | The surge multiplier applied to the ride price during peak hours. |
| `temperature` | The temperature at the time of the ride request. |
| `apparentTemperature` | The apparent temperature at the time of the ride request. |
| `temperatureHigh` | The highest temperature of the day. |
| `temperatureLow` | The lowest temperature of the day. |
| `apparentTemperatureHigh` | The highest apparent temperature of the day. |
| `apparentTemperatureLow` | The lowest apparent temperature of the day. |
| `temperatureMin` | The minimum temperature of the day. |
| `temperatureHighTime` | The time when the highest temperature of the day occurred. |
| `temperatureMax` | The maximum temperature of the day. |
| `apparentTemperatureMin` | The minimum apparent temperature of the day. |
| `apparentTemperatureMax` | The maximum apparent temperature of the day. |
| `apparentTemperatureMaxTime` | The time when the maximum apparent temperature of the day occurred. |
| `apparentTemperatureMinTime` | The time when the minimum apparent temperature of the day occurred. |
| `temperatureMaxTime` | The time when the maximum temperature of the day occurred. |
| `temperatureMinTime` | The time when the minimum temperature of the day occurred. |
| `temperatureLowTime` | The time when the lowest temperature of the day occurred. |
| `apparentTemperatureLowTime` | The time when the lowest apparent temperature of the day occurred. |
| `apparentTemperatureHighTime` | The time when the highest apparent temperature of the day occurred. |
| `precipIntensity` | The intensity of precipitation at the time of the ride request. |
| `precipProbability` | The probability of precipitation at the time of the ride request. |
| `humidity` | The humidity at the time of the ride request. |
| `windSpeed` | The wind speed at the time of the ride request. |
| `windGust` | The wind gust at the time of the ride request. |
| `visibility` | The visibility at the time of the ride request. |
| `dewPoint` | The dew point at the time of the ride request. |
| `pressure` | The air pressure at the time of the ride request. |
| `windBearing` | The wind bearing at the time of the ride request. |
| `cloudCover` | The cloud cover at the time of the ride request. |
| `uvIndex` | The UV index at the time of the ride request. |
| `ozone` | The ozone level at the time of the ride request. |
| `moonPhase` | The phase of the moon at the time of the ride request. |
| `precipIntensityMax` | The maximum intensity of precipitation for the day. |
| `uvIndexTime` | The time when the UV index was at its highest for the day. |
| `sunsetTime` | The time of sunset for the day. |
| `sunriseTime` | The time of sunrise for the day. |
| `windGustTime` | The time when the wind gust was at its highest for the day. |

## Dataset Source

You can get the data from [Uber and Lyft Dataset Boston](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma).
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

