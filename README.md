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
