# Миграция данных из Elasticsearch в Yandex Managed Service for OpenSearch

Вы можете настроить перенос данных из индексов Elasticsearch в индексы Managed Service for OpenSearch с помощью сервиса Data Transfer. Для этого:

1. Настройте кластер-источник.
2. Подготовьте тестовые данные.
3. Настройте кластер-приемник.
4. Подготовьте и активируйте трансфер.
5. Проверьте работу трансфера.

Подробное описание см. в [практическом руководстве](https://cloud.yandex.ru/docs/data-transfer/tutorials/mes-to-mos).
Сценарий может быть выполнен в [Консоли Управления Yandex Cloud](https://console.cloud.yandex.ru) или с помощью Terraform. Для выполнения сценария с помощью Terraform скачайте конфигурационный файл, [data-transfer-mes-mos.tf](data-transfer-mes-mos.tf). 

Дополнительные материалы о Yandex Data Transfer:
* [Доступные трансферы](https://cloud.yandex.ru/docs/data-transfer/transfer-matrix)
* [Практические руководства](https://cloud.yandex.ru/docs/data-transfer/tutorials/)
