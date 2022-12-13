# spark_windows_install

https://sparkbyexamples.com/pyspark/how-to-install-and-run-pyspark-on-windows/


```python
from pyspark import SparkContext
from pyspark.sql import SparkSession

spark = SparkSession.builder\
    .master("local")\
    .getOrCreate()
```
