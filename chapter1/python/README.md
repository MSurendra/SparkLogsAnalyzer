# Chapter 1: Introduction to Apache Spark in Python.

This directory contains all the sample code for Chapter 1 in Python. For
more explanation of this code, see (Chapter 1)[../README.md].  Streaming
examples are currently omitted, as streaming support is not available 
in Python when these examples are written.

To run an example, such as LogAnalyzer, you can use spark-submit program
```
%  ${YOUR_SPARK_HOME}/bin/spark-submit databricks/apps/logs/log_analyzer.py
#    --py-files databricks/apps/logs/apache_access_log.py
#    ../../data/apache.access.log
```
