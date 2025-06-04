# Importing data from Yandex Managed Service for PostgreSQL to Yandex Data Processing through Sqoop

[Sqoop](https://yandex.cloud/en/docs/data-proc/operations/sqoop-usage) is a utility for importing data from [Managed Service for PostgreSQL](https://yandex.cloud/en/docs/managed-postgresql) to a [Yandex Data Processing](https://yandex.cloud/en/docs/data-proc) cluster. Depending on the Yandex Data Processing cluster configuration, you can import your data to one of the following storages:

* [Yandex Object Storage](https://yandex.cloud/en/docs/storage) bucket
* HDFS directory
* Apache Hive
* Apache HBase

See [this tutorial](https://yandex.cloud/en/docs/tutorials/dataplatform/sqoop-mpg) to learn how to set up the infrastructure for a VM, Object Storage, Yandex Data Processing, and Managed Service for PostgreSQL using Terraform. This repository contains the configuration file you will need: [clusters-postgresql-data-proc-and-vm.tf](clusters-postgresql-data-proc-and-vm.tf).
