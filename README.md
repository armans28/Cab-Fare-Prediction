# Cab-Fare-Prediction

To view the user's portfolio blog on the Cab Fare Prediction, please visit [My Blog](https://danielrs.systeme.io/cab-price-prediction) to see the explanation of the notebook.

Due to the use of `plotly.express` and `plotly.graph_objects`, the visualizations in this code cannot be displayed on GitHub. To view the visualizations, please download the code and run it on your local machine.

## Data Description
This beginner-friendly dataset, spanning from November 26, 2018, to December 19, 2018, in Boston, MA, offers a great opportunity for hands-on data analysis. Despite containing numerous NA values, it provides valuable insights into the relationship between predictors like hour and price using Linear Regression Models. An exciting aspect is the inclusion of corresponding weather data, including factors such as temperature, wind, and sunset, along with brief weather summaries. With over 693,071 unique values, this dataset allows for robust exploration of cab pricing patterns and serves as a valuable resource for learning data cleaning, regression analysis, and incorporating external factors in predictive modeling. There are 57 columns in this dataset but mainly it contains with :

### Main Feature
`hour`, `day`, `month`
  , `source`
  , `destination`
  , `cab_type`
  , `latitude`
  , `longitude`
  , `short_summary`
  , `long_summary`
  , `icon`
  , `name`
  , `price`
  , `distance`
  , `surge_multiplier`

### Temperature Feature
`temperature`
, `apparentTemperature`
, `temperatureHigh`
, `temperatureLow`
, `apparentTemperatureHigh`
, `apparentTemperatureLow`
, `temperatureMin`
, `temperatureHighTime`
, `temperatureMax`
, `apparentTemperatureMin`
, `apparentTemperatureMax`
, `apparentTemperatureMaxTime`
, `apparentTemperatureMinTime`
, `temperatureMaxTime`
, `temperatureMinTime`
, `temperatureLowTime`
, `apparentTemperatureLowTime`
, `apparentTemperatureHighTime`

### Climate Feature
`precipIntensity`
, `precipProbability`
, `humidity`
, `windSpeed`
, `windGust`
, `visibility`
, `dewPoint`
, `pressure`
, `windBearing`
, `cloudCover`
, `uvIndex`
, `ozone`
, `moonPhase`
, `precipIntensityMax`
, `uvIndexTime`
, `sunsetTime`
, `sunriseTime`
, `windGustTime`

## Dataset Source

You can get the data from [Uber and Lyft Dataset Boston](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma).
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

