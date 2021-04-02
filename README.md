# jupyter-notebook-storage
ML 공부용 쥬피터 노트북 저장소 :)

### Docker Jupyter Notebook
```shell
docker run -p 8888:8888 --name jupyter-notebook -v [jupyter-notebook-storage path]:/home/jovyan/ jupyter/tensorflow-notebook
```
