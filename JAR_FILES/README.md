please copy the requirements to the local spark folder :
like : C:\Utill\spark-3.1.1-bin-hadoop3.2\jars

and also please copy the runing folder as well
or share the folder in jupyter:

os.environ['PYSPARK_SUBMIT_ARGS'] = '--jars ./ojdbc7.jar pyspark-shell'
sc = spark.sparkContext.addPyFile("./ojdbc7.jar")


