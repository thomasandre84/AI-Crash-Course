#AI Crash Course
## setup jupyter notebook
1. `git clone <git-repo>`
2. Go to the Repository folder `cd <cloned-folder>`
3. Start docker: ˋdocker run -d -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work --name=jupyter-ai jupyter/all-spark-notebookˋ
4. The token can be found in the logs: `docker logs jupyter-ai` - Copy the token
5. Open the browser: http://localhost:10000   and enter token as well as choose a new password

## start Jupyter Notebook
`docker start jupyter-ai`
