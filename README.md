# Intro-To-Scala
A repository for the material used during my Intro To Scala demonstration

I ran the jupyter docker container with this command. If the notebook from this repository is stored under ~/workspace/jupyter/

This command below will give you a running instance of jupyter with the correct kernels installed.
```
docker run -it --rm -v ~/workspace/jupyter/:/home/jovyan/ -p 8888:8888 jupyter/all-spark-notebook
```
