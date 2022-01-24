# Docker_learn
This session is used to take some important notes for education purposes.
## 1. Pyspark
```docker run -it --name <container-name> -p 8888:8888 -v ${PWD}:/home/jovyan/work jupyter/pyspark-notebook```
More information, check [here.](https://medium.com/@suci/running-pyspark-on-jupyter-notebook-with-docker-602b18ac4494)
## 2. Jupyter
```docker run -it --name <container-name> -p 8888:8888 -v ${PWD}:/home/jovyan/work -e JUPYTER_ENABLE_LAB=yes <image-name>```
image-name could be taken from [Jupyter Docker Stacks.](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html)
