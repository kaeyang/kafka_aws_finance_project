# Real time stock data pipeline and analysis

### Exploratory Data Analysis and Data augmentation

In this section, I conducted exploratory data analysis of the stock data and applied data augmentation to create daily average, min, and max price for the stock.

### Kafka streaming pipeline
I built a Kafka streaming pipeline to stream 13.8 million rows of data from my local machine into the EC2 S3 bucket

### AWS Services
I used EC2 to host a server to create a virtual machine to run the code, S3 Bucket to catch and store the JSON time series data from my local machine, AWS GLUE and Athena to convert the json data into SQL tables for querying.
