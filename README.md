# pyspark-native-function
Simple guide on how to use native function to further optimize your spark jobs.


# Requirements
* Spark 3.0 +

# How to Install on pyspark
1. Build project and upload jar to spark cluster
2. Register function by executing:
> sc._jvm.com.spark.native.functions.Registration.registerFunctions(spark._jsparkSession)
3. Use expr("") function to execute the function
