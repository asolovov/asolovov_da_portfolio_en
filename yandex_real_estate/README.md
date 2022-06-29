# [Apartment sale advertisements research](https://github.com/asolovov/asolovov_da_portfolio_en/blob/main/yandex_real_estate/yandex_real_estate_en.ipynb)

We have at our disposal Yandex.Realty service data - an sale ads archive for the apartments in St. Petersburg and neighboring settlements for several years. We need to learn how to determine the real estate market value. Our task is to set the parameters. This will allow to build an automated system: it will track anomalies and fraudulent activity.

Two types of data are available for each apartment for sale. The first ones are entered by the user, the second ones are obtained automatically on the basis of cartographic data. For example, the distance to the center, airport, nearest park and pond.

### Tools:
- pandas
- pyplot
- seaborn

### Reserch Plan:
- 1  Introduction to data
- 2  Data preprocessing
  - 2.1  Deleting columns
  - 2.2  Gaps
  - 2.3  Changing the data types
  - 2.4  Duplicates
- 3  Adding data
- 4  Exploratory data analysis
  - 4.1  Statistical outliers processing
  - 4.2  Indicators research
    - 4.2.1  Price
    - 4.2.2  Area
    - 4.2.3  Rooms
    - 4.2.4  Ceiling height
  - 4.3  The study of price influencing factors
  - 4.4  Top-10 cities research
  - 4.5  St. Petersburg city center research
    - 4.5.1  Data Sample
    - 4.5.2  Parameters research
    - 4.5.3  Factors research
- 5  Research results

### Summary:
Values are defined for the following parameters:
- Price
- Total area
- Number of rooms
- Ceiling height
- Impact on price

For the top-10 cities research conclusions are made
