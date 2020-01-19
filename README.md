1. Import and convert the data contained in data_DD_MN008.csv to the following target JSON (individual readings):
[
  {
    timestamp: <unix-epoch>,
    direction: <degrees>
  },
  ...
]



2. Import and convert the data contained in data_DD_MN008.csv to the following target JSON (aggregated per day):
[
  {
    day: <YYYY-MM-DD>,
    direction: <mean of all degrees during the day>
  },
  ...
]
