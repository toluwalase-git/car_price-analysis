# ((Car Price Prediction DataSet))
## by (Toluwalase Abikehin)


## Dataset

> The Car Price Prediction DataSet was gotten from [here](https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge/discussion/335871)
> The dataset presents the pricing of cars with some car features including the following columns
* Levy
* Manufacturer
* Model
* Production year
* Category
* Leather interior
* Fuel type 
* Engine volume 
* Mileage
* Cylinders 
* Gear box type 
* Drive wheels 
* Doors Wheel 
* Color
* Airbags
> The main feature of intrest is **Price**
> Numeric features of interest: `Production year`, `Mileage`, `Cylinders`, `Air bags`
> Categorical features of interest: `Fuel type`, `gear box type`, `Color`

### Data Wrangling

> Upon reading the `.csv dataset`:
* `Mileage` was converted from `object` to `int`
* `Production year`, `Mileage`, `Cylinders`, `Air bags` coverted into ordered `categorical data`

### Univariate Exploration
* Price distribution plotted using histogram on log scale
* Mileage distribution plotted on histogram
* Barchart showing the categorical features of interest: `Fuel type`, `gear box type`, `Color`
* Histogram plot for the Numeric features of interest: `Production year`, `Mileage`, `Cylinders`, `Air bags`

### Bivariate Exploration
* Numeric variable correlation checked using `heat map` and `correlation matrix`
* Show `Price` relationship with the categorical features of interest using `boxplot`
* Relationship of categorical features of interest: `Fuel type`, `gear box type`, `Color` was shown using multiple `barchart`

### Multivariate Exploration
* 3 variable plot drawn to show relationship of `Production year` and `Gear box type` with `Price` using faceted `scatter plot`
* 3 variable plot drawn to show relationship of `Fuel type` and `Gear box type` with `Price` using faceted `box plot`

## Summary of Findings
> The `Price` distribution shows some tail distribution to the left showing more levels on low `Price` region. 

> The `Mileage` distribution shows some minimal tail distribution to the left.

> The bivariate plots shows that the most sold car types are `Petrol` and `Diesel` fuel types, however LPG seems to be on a promising level. It is shown that there seem to be a lot of preference for black colored cars followed by white. Automatic `Gear box type` seem to be the top sold car followed by `Tiptronic` before `Manual`. This suggests some transition from `Manual` to `Automatic` in recent years. 

> The `heat map` and the `correlation matrix` shows that the `Price` of the car doesn't have a strong direct correlation with the `Mileage`, `Airbags`, but a rather weak coorelation with number of `Cylinders` and the `Production year`. Black and white colors seem to be the sales drivers for the cars with Tiptronic and Automatic Gear types and Petrol fueled cars.

> The multivariate faceted scatter plot informs that the Tiptronic gearbox type makes the highest car Price. And it is obviously a design that gained market force around 2010. The Manual Cars are densely compacted in the 10k - 50k price region.

> The multivariate faceted box plot showed the relationship `fuel type` and `gear box type` has to determine `Price` levels. The box plot emphasize that higher priced cars are Tiptronic Black Diesel Fueled Cars, followed by automatic Grey diesel fueled cars. The first boxplot shows that Automatic Gearbox with Diesel Fueled Cars drives the higher prices for cars. The Second box plot shows Tiptronic  gear box  Disel fuel cars as the highest priced cars. The Third box plot shows that the varitor gear box type is highly priced on hybrid fuel types. And the last box plot shows diesel fueled manual cars as most highly priced among other Manual gear box type. 

## Key Insights for Presentation

> Petrol fuel types, black colored cars, Automatic bear box type makes the highest car Counts.
> The Diesel Fueled Cars are higher in price than other Fuel types 
> Black and Grey Cars are higher in price than other Color types
> Tiptronic Cars are higher in price than other Gear box types
> Conclusively, the features that makes the high priced cars include _Tiptronic Black Diesel Fueled Cars_,followed by _Automatic Grey diesel fueled cars_
# car_price-analysis
