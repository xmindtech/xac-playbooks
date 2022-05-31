

# eXtendable Automation for Cloud <!-- omit in toc -->
This project manages Airflow DAGs and Jupyter Notebooks to run in [xac-service](https://github.com/xmindtech/xac-service)

## Directed Acyclic Graphs
The [DAGs](https://airflow.apache.org/docs/apache-airflow/stable/concepts/dags.html) are specific to Airflow, but you can also call then worflows.

You can find some examples under [airflow/example_dags](https://github.com/apache/airflow/tree/main/airflow/example_dags) in Airflow project.

## Jupyter Notebooks
To interact with the exposed services by `xac-service`, we propose to use JNBs. The notebooks are under `notebooks/` folder.
Where to run them? Either locally, in AWS SageMaker Lab, or your own JupyterHub server.
