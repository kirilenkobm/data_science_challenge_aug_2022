I did this data science challenge for company X during the recruiting process.
The challenge description (company name excluded) is provided below.
As I was informed, clarifying each step is more important than the overall model performance.


### CHALLENGE SENIOR DATA SCIENTIST

With this challenge you received a dataset in csv format (input.csv).
The dataset consists of spectroscopic measurements (readings of NIR and UVVis sensors) (feature columns prefixed with nir_ or uv_, the number after the prefix is the measuring wavelength in nm) identified by a unique measurement ID (measurement_ID). Sensor readings were performed directly in the soil on three different fields (see column location) in the US. Coordinate pairs (see columns lat and lng; WGS84) specify the location where the soil readings were performed. Column soc_percent_labval contains soil organic carbon content in % determined by soil sampling of the soil layer of 0-30 cm depth close to the position of a FarmLab device reading.

Please fulfill the following tasks. Which tools you use to do so, is up to you. Make sure the reasoning and results of all steps are documented.

1. Familiarize with the dataset. Are there any issues, that could disturb further analyses? Find appropiate ways to remedy the issues.
2. Use the sensor readings and lab values to build models for prediction of soil organic carbon (SOC) content of the fields covered by measurements.

    - a. Make sure to apply adequate preprocessing to the data before model building.
    - b. Perform model building. Aim should be to create models that are likely to also give good estimates of soil organic carbon for closeby fields.
    - c. Evaluate the performance of your models.
