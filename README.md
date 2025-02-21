# Temperature Prediction Modelling Based on Air Quality in an Italian City


### Project Overview

The objective of this project is to build a model that can correctly predict air temperature and identify which feature has the most importance to the prediction.

### Data Source

[UCI Repository](https://archive.ics.uci.edu/dataset/360/air+quality)

### Tools

- Jupyter Notebook

### Data Preparation

Exploring the data, there were no missing values and the features were in the right datatype. The date and time columns were concatenated and made the dataframe index.

![carbon (13)](https://github.com/user-attachments/assets/a3d6b9fa-b690-454b-bfe4-746b89ed5507)

### Exploratory Data Analysis

A time series trend of all the features and the target was plotted.

![EDA](https://github.com/user-attachments/assets/37a649cf-7b1d-4b72-a841-5b7e215c33e5)

### Model Development


![model](https://github.com/user-attachments/assets/b213f88e-abd9-45eb-9543-5a165b81748c)

### Model Evaluation

![evaluation](https://github.com/user-attachments/assets/73754a79-2bb8-4a4e-8ba5-c03d4552ae93)

![Screenshot 2025-02-21 155522](https://github.com/user-attachments/assets/5bb45379-7d6d-4599-b1ba-5bb301c18d48)

![Screenshot 2025-02-21 155650](https://github.com/user-attachments/assets/fa41110b-c0af-4441-a15e-d90af9782382)

### Conclusion

In conclusion, monitoring air temperature is vital for predicting weather conditions, addressing climate change, supporting agriculture, safeguarding public health, and optimizing energy consumption. As technology advances, the integration of satellite data, remote sensors, and artificial intelligence in temperature monitoring will enhance our ability to respond effectively to environmental challenges. The need for accurate temperature monitoring will continue to grow, making it an indispensable tool in managing the world’s climate and resources effectively.

Benzene (C6H6) has a high correlation with temperature (0.97) and it is also the feature with the highest importance to the model development. To mitigate the concentration of benzene will likewise, have the same effect on temperature. Benzene is both a synthetically made and naturally occurring chemical from processes that include: volcanic eruptions, wildfires, synthesis of chemicals such as phenol, production of synthetic fibres, and fabrication of rubbers, lubricants, pesticides, medications, and dyes. The major sources of benzene exposure are tobacco smoke, automobile service stations, exhaust from motor vehicles, incomplete combustion of Polyaromatic hydrocarbons (PAHs) and industrial emissions. The recommended air standard for benzene is 975 - 9750 mg/m3. Hydroxyl radicals in the atmosphere are the most important means of degradation of benzene while oxidants (like ozone and nitrate radicals) lessen the extent of degradation of benzene.
