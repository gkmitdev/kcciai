# Before Importing the data
ciPARTHENON is meant to connect to your data sources without you having to do the work. Depending on where your data is stored we have a connector for it. If your data is in Excel then Excel is fine, hopefully with your data in rows and the column headers on the first row since it makes it easier to load data that way. If your data is in text files then the same as Excel, data in rows (comma separated for example) and column header at the top. As an example of data structure, below are examples of a good and bad data structure:


**Pivoted data (Not Recommened)**

| Name        | Age | Country  |
|------------|----|---------|
| Alice       | 25  | USA     |
| Bob         | 30  | Canada  |
| Charlie     | 22  | UK      |


## Data Flow

Data Flow is a module that processes data from one or more input tables and outputs it to one or multiple tables.
It gives users power to create maps clearly showing the flow of data.

### Input Table

The Input table node is the first to be used in any new data flow.
This is the dataset you wish to transform in a data flow.

Input tables can also be used further downstream to feed into other nodes, such as Join or Lookup.
Multiple input tables can be used from the start of the Data flow.

#### Table Fusion

Table Fusion is an input node that allows to append multiple datasets of same type together. Columns with the same name and datatype will be mapped automatically. Columns with differences can be mapped manually, or ignored.

## Data Scripts


The Data Scripts module empowers you to write and execute custom Python Scripts for advanced data processing. Seamlessly integrate your scripts across the platform to unlock powerful custom transformations, analyses, and visualizations.

