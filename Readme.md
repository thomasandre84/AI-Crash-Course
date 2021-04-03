#AI Crash Course
## start jupyter notebook
ˋˋˋ
docker run -d -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work --name=jupyter-ai jupyter/all-spark-notebook
ˋˋˋ
