# smart-applications-project

## About 

This project was build during Smart Application class at my university. In this project the Naive Bayes algorithm is used for classifying iris species

## Structure

- *iris.csv* file is used as a data source for *Lab07_08_Irises* notebook
- *sample_libsvm_data.txt* file is used as a data source for *Lab07_08_Example* notebook
- *Lab07_08_Example* is an [exemplary notebook from Spark documentation](https://spark.apache.org/docs/latest/ml-classification-regression.html#naive-bayes)
- *Lab07_08_Irises* is classification project using Naive Bayes algorithm from Spark MLlib
- *Dockerfile* contains instructions used to build a docker image

## Running the notebooks

These notebooks can be run in a dedicated docker container with this command
```sh
docker run -it --rm -p 8888:8888 -v "$(pwd)":/home/jovyan/work kklejbor/pyspark-notebook-with-findspark:latest
```
