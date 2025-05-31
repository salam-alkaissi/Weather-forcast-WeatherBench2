## Input
Dataset (era5_data_6hours.nc):
Loaded using xarray, this is a NetCDF file containing environmental data, typically used in weather forecasting or climate studies.
Variables Extracted:
t2m, sp, skt, u10, v10, tp, ssr, str, etc., which represent temperature, pressure, wind speed, soil moisture, etc.
These variables were chosen because they are commonly used in weather models, and are relevant for understanding atmospheric and surface conditions.

## Output
Filtered Dataset:

Created by selecting only relevant variables from the dataset to limit processing to only the necessary information for the specific analysis.
Outputted in the form of a dataframe (df_filtered).
Visualizations:

Heatmaps for each variable showing spatial distribution over a grid (latitude x longitude).
Temporal visualizations to show variable progression over time, such as predictions.
Scatter plots, residual distributions for understanding the performance of the linear regression model.
Model Training Output:

Predictions (y_pred_train, y_pred_val) from the linear regression model.
Performance metrics like Root Mean Square Error (RMSE) and R² score were computed to evaluate the model’s effectiveness.

### Extracted Variables:
The variables like t2m, sp, skt and the rest, were chosen because they play a significant role in forecasting weather and analyzing environmental conditions.

t2m (2m temperature) is key for understanding surface temperature conditions.

Wind components (u10, v10) are essential for wind analysis.

tp (total precipitation) helps in analyzing rainfall patterns.

These are typically used as both inputs to forecast weather and as features to study relationships with target variables in climate models.

he 2m temperature (t2m) is a critical variable in weather analysis as it represents the temperature close to the earth's surface, which is important for forecasting and understanding climate conditions.
Your goal in this analysis was to predict t2m based on the other available variables (features) that describe atmospheric and surface conditions. the target because it is a key variable for surface weather analysis.


![image](https://github.com/user-attachments/assets/dfb76daa-0070-40ec-ba35-a68f90d7e29e)


![image](https://github.com/user-attachments/assets/9e2bf19e-b92a-4957-b519-ca086f1faad6)

![image](https://github.com/user-attachments/assets/53ea3402-510a-4957-ab33-2ce2f4f649fd)

![image](https://github.com/user-attachments/assets/3df18886-009c-4be3-84dc-92ee64031b77)

![image](https://github.com/user-attachments/assets/5be424b2-441f-42fc-96c1-122f478d7510)

