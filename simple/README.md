see http://spark.apache.org/docs/latest/quick-start.html

### Package a jar containing your application
'''
$ sbt package
'''

### Use spark-submit to run your application
'''
$ YOUR_SPARK_HOME/bin/spark-submit \
  --class "SimpleApp" \
  --master local[4] \
  target/scala-2.10/simple-project_2.10-1.0.jar
'''
