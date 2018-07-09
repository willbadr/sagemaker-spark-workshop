# sagemaker-spark-workshop


## Setup Juypter Notebook within Amazon SageMaker

#### 1- Create a Sagemaker Configuration Lifecycle and place the below commands in the `create notebook` tab:

```shell
#!/bin/bash
set -e
cd SageMaker
sudo pip install plotly
git clone https://github.com/willbadr/sagemaker-spark-workshop.git
```

## References:

A tool to create BYO containers: https://github.com/aws/sagemaker-containers
Sagemaker Spark SDK (Scala): https://github.com/aws/sagemaker-spark/tree/master/sagemaker-spark-sdk
