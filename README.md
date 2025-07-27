# stock-market-real-time-kafka-project

ARCHITECTURE
cvs -----> python(simulation) -----> producer -----> KAFKA -----> consumer ------> Amazon(s3) -----> crawler ------> aws glue data catalog ------> aws(athena-sql)

TECHNOLOGY USED
python
aws - s3,glue catalog,glue crawler,athena, ec2
apache kafka

DATASET 
https://www.alphavantage.co/query?function=TIME_SERIES_INTRADAY&symbol=IBM&interval=5min&apikey=demo&datatype=csv
