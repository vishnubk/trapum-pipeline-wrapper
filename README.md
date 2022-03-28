# trapum-pipeline-wrapper

PIKA and SQLAlchemy wrappers for TRAPUM pipelines

This is a forked repo.

Original Code: https://github.com/MPIfR-BDG/trapum-pipeline-wrapper

Changes to Original Repo: TRAPUM Search Pipeline Dockerfile Has been updated with the following changes.

* Ubuntu16.04 -> Ubuntu18.04
* python3.6 -> python3.8
* Concurrent Installation of Peasoup, Circular and Elliptical orbit template-bank peasoup
* Updated sigpyproc3
* Installed vim, pandas

The pipelines folder contain Docker and Kubernetes configurations and pipeline scripts for launching specific pipelines on the TRAPUM cluster. Every product from the processing chain is marked and tabulated in a centralised database which is done through SQLalchemy.



