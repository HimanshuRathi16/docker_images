# Kafka Cluster with Spark

Kafka Cluster with Zookeeper and PySpark Jupyter Notebook.

### Download or clone the repository in local system
1. Open Command Prompt (cmd)
2. Go to the directory where you downloaded or cloned the Docker files.
3. Execute the following command.
   
### To start the cluster and create containers
    docker compose build

#### Once Build is complete
    docker compose up

### Run Jupyter notebook
1. Open Chrome or any web browser and access the Jupyter server at [localhost:8888](http://localhost:8888/)
2. If you're setting up for the first time, make sure to create a password or token. Remember it because you'll need it every time you want to use Jupyter Notebook
3. To get the token, open Docker Desktop and go to the 'pyspark-jupyter-lab' image. Check the logs, and you'll find the token there. Just copy and paste it.
4. Setup the password
5. After completing these steps, you'll be able to access Jupyter Notebook
