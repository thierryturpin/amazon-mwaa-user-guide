# Amazon MWAA Document History<a name="doc-history"></a>

The following table describes important additions to the Amazon MWAA service documentation, beginning in November 2020\. To receive notifications about updates to this documentation, subscribe to the RSS feed\.

| Change | Description | Date | 
| --- |--- |--- |
| [New topics and use cases](#doc-history) | Added the following changes:  Added Apache Hive use case to [Installing Python dependencies](working-dags-dependencies.md)\.   Clarified the docs that the required dependencies for an Apache Airflow package needs to be included in the `requirements.txt` file at [Installing Python dependencies](working-dags-dependencies.md)\.   Added *Updating requirements\.txt* troubleshooting topic to [Troubleshooting Amazon Managed Workflows for Apache Airflow \(MWAA\)](troubleshooting.md)\.   | February 25, 2021 | 
| [New tutorials](#doc-history) | Added the following changes:  Added private network tutorial to [Tutorial: Configuring private network access using a Linux Bastion Host](tutorials-private-network-bastion.md)\.   | February 22, 2021 | 
| [New topics and use cases](#doc-history) | Added the following changes:  Added private and public network configurations to [Amazon MWAA network access](configuring-networking.md)\.   Added development group use case and user scenarios to [Amazon MWAA Execution role](mwaa-create-role.md)\.   | February 22, 2021 | 
| [New sample code](#doc-history) | Added the following changes:  Added sample Python scripts for web login token and CLI token to [Accessing the Apache Airflow UI](access-airflow-ui.md)\.   Added sample code to trigger DAG in another environment to [Code examples](sample-code.md)\.   Added sample code to trigger DAG using a Lambda function to [Invoking DAGs with an AWS Lambda function](samples-lambda.md)\.   | February 22, 2021 | 
| [New commands and procedures](#doc-history) | Added the following changes:  Added step by step procedures to all scripts at [Accessing the Apache Airflow UI](access-airflow-ui.md)\.   | February 22, 2021 | 
| [New sample code](#doc-history) | Added the following changes:  Updated curl example for web login token at [Accessing the Apache Airflow UI](access-airflow-ui.md)\.   Added sample code to connect to an Amazon RDS Microsoft SQL Server to [Using Amazon MWAA with Amazon RDS Microsoft SQL Server](samples-sql-server.md)\.   | February 17, 2021 | 
| [New commands and procedures](#doc-history) | Added the following changes:  Added AWS CLI commands to [Working with DAGs on Amazon MWAA](working-dags.md) pages\.   Apache Airflow doesn't support serialized DAGs in CLI commands\. Since the CLI runs on the web server, which doesn't have plugins or requirements for security reasons, any MWAA environments with a plugins\.zip or requirements\.txt will not support these commands\. Moved Apache Airflow `list_dags` and `backfill` commands to unsupported commands at [Accessing the Apache Airflow UI](access-airflow-ui.md)\.   | February 17, 2021 | 
| [GitHub launch](#doc-history) | User guide docs are now open source on GitHub\. Choose "Edit this page on GitHub" on any page\. | February 17, 2021 | 
| [New topics and use cases](#doc-history) | Added the following changes:  Added frequently asked question for Step Functions v\. Amazon MWAA use case to [Troubleshooting Amazon Managed Workflows for Apache Airflow \(MWAA\)](troubleshooting.md)\.   Added CLI access policy to [Accessing an Amazon MWAA environment](access-policies.md)\.   Clarified the docs that any supported Apache Airflow configuration option can be specified at [Amazon MWAA Apache Airflow configuration options](configuring-env-variables.md)\.   Clarified the docs that if a Fargate container in one availability zone fails, MWAA switches to the other container in a different availability zone at [Create the VPC network](vpc-create.md)\.   | February 12, 2021 | 
| [New topics and use cases](#doc-history) | Added the following changes:  Added [Amazon MWAA environment class](environment-class.md)\.   | February 5, 2021 | 
| [Removed or moved topics](#doc-history) | Added the following changes:  Removed requirement for Amazon S3 bucket name to start with `airflow-` at [Get started with Amazon Managed Workflows for Apache Airflow \(MWAA\)](get-started.md)\.   Moved [Accessing an Amazon MWAA environment](access-policies.md) and [Amazon MWAA Execution role](mwaa-create-role.md) to [Managing access to an Amazon MWAA environment](manage-access.md)\.   | February 4, 2021 | 
| [Amazon MWAA CloudFormation](#doc-history) | Update the parameters to create an environment at [Amazon MWAA CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-mwaa-environment.html)\.  Remove SubnetList\.   Remove TagList\.   Add NetworkConfiguration\.   Add TagMap\.   Add create environment request examples\.   | February 4, 2021 | 
| [New topics and use cases](#doc-history) | Added the following changes:  Added example email configuration to [Amazon MWAA Apache Airflow configuration options](configuring-env-variables.md)\.   Added PostgresHook troubleshooting topic to [Troubleshooting Amazon Managed Workflows for Apache Airflow \(MWAA\)](troubleshooting.md)\.   Added AWS Secrets Manager troubleshooting topic to [Troubleshooting Amazon Managed Workflows for Apache Airflow \(MWAA\)](troubleshooting.md)\.   Added high performance use case to [Amazon MWAA automatic scaling](mwaa-autoscaling.md)\.   | January 29, 2021 | 
| [Amazon MWAA launch](#doc-history) | General availability launch of Amazon Managed Workflows for Apache Airflow \(MWAA\)\.  User guide documentation   AWS CloudFormation documentation   | November 24, 2020 | 