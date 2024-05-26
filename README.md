## Property Tax Analysis using Pandas and Seaborn
This project aims to analyze property tax payments using Python libraries such as Pandas and Seaborn. By exploring and visualizing property tax data, we seek to gain insights into payment patterns, trends, and variations across different geographic locations or demographic groups.

### Project Overview
Property tax payments are crucial sources of revenue for local governments, and analyzing payment data can provide valuable insights for policymakers, tax administrators, and researchers. This project utilizes Python for data analysis and visualization, with a focus on the following tasks:

> Data loading and preprocessing using Pandas.
> Exploratory data analysis (EDA) to understand the distribution and characteristics of property tax payments.
> Visualization of payment patterns using Seaborn, including time series analysis, geographic analysis, and comparison across different demographic groups or property types.

### Data Source
The property tax dataset used in this project contains the following columns:

> YR: Year of the tax payment.
> BILL_TYPE: Type of bill.
> BILL_NUM: Bill number.
> PARCEL_ID: Parcel identifier.
> TXPR_NAME: Taxpayer name.
> CO_NAME: County name.
> MAIL_ADDR: Mailing address.
> MAIL_ADDR2: Additional mailing address (if any).
> CITY: City name.
> STATE: State abbreviation.
> ZIP1: ZIP code part 1.
> ZIP2: ZIP code part 2.
> PROP_LOC_NUM: Property location number.
> PROP_LOC_NAME: Property location name.
> LIEN_SOLD: Indicator for lien sold.
> BILLED: Billed amount.
> PAID: Amount paid.
> TAX_DUE: Tax due amount.

### Analysis Steps
The property tax analysis is conducted in the following steps:

> Data Loading and Preprocessing: The dataset is loaded into a Pandas DataFrame and cleaned to handle missing values, data types, and inconsistencies.

> Exploratory Data Analysis (EDA): Descriptive statistics, distributions, and correlations are explored to understand the structure and characteristics of property tax payments.

> Visualization using Seaborn: Seaborn is used to visualize property tax payments over time, across different geographic locations, and by various demographic groups or property types.

### Libraries Used
> Pandas: For data manipulation, preprocessing, and analysis.
> Seaborn: For statistical data visualization and exploration.
