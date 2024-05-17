# Импорт данных из Yandex Managed Service for PostgreSQL в Yandex Data Proc с помощью Sqoop

Утилита [Sqoop](https://yandex.cloud/ru/docs/data-proc/operations/sqoop-usage) позволяет импортировать данные из [Managed Service for PostgreSQL](https://yandex.cloud/ru/docs/managed-postgresql) в кластер [Yandex Data Proc](https://yandex.cloud/ru/docs/data-proc). В зависимости от конфигурации кластера Yandex Data Proc вы можете выполнить импорт в:

* бакет [Yandex Object Storage](https://yandex.cloud/ru/docs/storage);
* директорию HDFS;
* Apache Hive;
* Apache HBase.

Подготовка инфраструктуры для виртуальной машины, Object Storage, Yandex Data Proc и Managed Service for PostgreSQL через Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/dataplatform/sqoop-mpg), необходимый для настройки конфигурационный файл [clusters-postgresql-data-proc-and-vm.tf](clusters-postgresql-data-proc-and-vm.tf) расположен в этом репозитории.
