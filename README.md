# spark_windows_install

## installing

https://sparkbyexamples.com/pyspark/how-to-install-and-run-pyspark-on-windows/

## create spark session

```python
from pyspark import SparkContext
from pyspark.sql import SparkSession

spark = SparkSession.builder\
    .master("local")\
    .getOrCreate()
```

## check the jobs

http://localhost:4041/jobs/


# docker 

```bash
docker build -t jingyanwang1/spark_docker:1.0.1 .
```

```bash
docker run -it `
-p 0.0.0.0:3760:3760  `
-v `"C:\Users\jinyan.wang\Documents\proj_teamflow_230107`":/code/ `
-v `"C:\data\teamflow`":/data/ `
jingyanwang1/spark_docker:1.0.1
```
